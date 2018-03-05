Testing HWM Module
==================

1. Attach district in HWM - ditrict are not in alphabetically sorted order [Fixed]

2. Delete application at industry and officer side is not working [Implemented] 
	
	Admin and Employee vertical menu was same as BMW [made the different gsp and fixed it]

	Implementation:

	In IndustryRegMasterController.groovy
	Search for - bhanu code start; date: 10-04-2017
	actions added - delAppWasteHwm, delAppWasteActualHwm

	new file created - grails-app/views/industryRegMaster/delAppWasteHwm.gsp

	In UserMasterController.groovy
	Search for - bhanu code start; date: 11-04-2017
	actions added - wasteManagementAdminHwmVertical, wasteManagementEmpHwmVertical

	New files added - grails-app/views/userMaster/wasteManagementAdminHwmVerticalPage.gsp
					  grails-app/views/userMaster/wasteManagementEmpHwmVerticalPage.gsp

  	Files edited 
  		a. grails-app/views/wasteManagementPendingDetails/hwmPendingList.gsp
			search for - bhanu code start; date: 11-04-2017
		b. grails-app/views/hazardeousWasteAuthApp/searchHWMApp.gsp
			search for - bhanu code start; date: 11-04-2017

3. Forwarding rights - tabs design -> on line commented [Fixed]

4. On clicking HWM -> Apply authorization -> Hazardeous waste new ==> body on load problem

5. On clicking HWM -> Apply authorization -> Hazardeous waste new [resolved by discussion with gajendra sir]

	if application is not saved in-progress, application instance is saved in inprogress list

6. Delete application is not showing in select at industry side [ignore it]

	grails-app/views/industryRegMaster/delAppWaste.gsp
	search for - bhanu code start; date: 07-04-2017 

	Fixed partially

7. HWM -> Apply Authorization -> Hazardeous waste
	Document upload no list of documnet is shown

8. In view clarification popup(Green C) - No link to download file attatched by officer when clarification is raised

9. On submitting clarification by officer we go to /HSPCB/wasteManagementPendingDetails/pendingList

	which is BMW Module page

10. on clicking - 'View form' at officer side server gets busy

11. on clicking orange i - no download link to download 'file attached when inspection is raised'

12. Name change - consent to hwm - on cliking submit hwm inspection report 

	point no 2. - Date of Receipt of Consent Application at regional office  

13. in submit hwm inspection report [Fixed]
	add - Fourth Stage Treatment Details Of Effluent
	no data is comming in fourth stage list select dropdown

	data is directly filled to the table

	Hence i was not able to submit the report

14. Even after setting approval right. Approval field is not shown to the officer. [Fixed]

15. There is no link to prepare SCN Certificate [Implemented]

16. There is no link to prepare approval/reject certificate [It is shown after the inspection is closed]

17. Waste application search - on clicking application no a view form gets open -> on clicking Hazardeous Waste 		

	Generation Details tab -> click view -> a popup window gets open and http 404 error is shown

18. SCN Certificate in HWM Module [Implemented]
	Adding link to prepare and view scn certificate

		File edited - grails-app/views/wasteManagementProcessingDetails/appProcessing.gsp

		search for - bhanu code start; date: 11-04-2017

	Functionality of SCN link

		File edited - WasteManagementProcessingDetailsController.groovy

		search for - bhanu code start; date: 11-04-2017

		actions added - scnCertificateHwm, popConditionsAddHwm, saveconditionsHwm, popConditionsViewHwm, popConditionsEditHwm, 

		File added - grails-app/views/wasteManagementProcessingDetails/popConditionsAddHwm.gsp

		File added - SaveConditionsHWM.groovy

		File added - grails-app/views/wasteManagementProcessingDetails/popConditionsViewHwm.gsp

		File added - grails-app/views/wasteManagementProcessingDetails/popConditionsEditHwm.gsp

19. Drop the table 
		hwmInspectionReport
		RecordCertificateHWM - and update category_qty size to 65000
		FourthStagePollutionControlDevicesMaster - add value to this table

20. Refusal Certificate in HWM Module [Implemented]
	
	Some other changes - 

	HazardeousWasteAuthAppController.groovy
	search for bhanu

21. Grant certificate for HWM

	grails-app/views/hazardeousWasteAuthApp/insrtCertDetailsForNew.gsp
	search for bhanu code start; date: 24-04-2017

22. View form link in appProcessing  page + download attached file in them

	grails-app/views/wasteManagementProcessingDetails/appProcessing.gsp

	search for bhanu code start; date: 18-04-2017

	work on date 20-04-2017:

	a. Provide copy of the Emergency - name="erpAttach" - file51.description = "ERP Attachment" - file51.typeOfFile = "ERP"
	b. Provide undertaking or declaration - name="undertakingOrDeclaration" - file51.description = "UndertakingOrDeclaration Attachment" - file51.typeOfFile = "undertakingOrDeclaration" 
	c. Process description including process - name="processDescription_new" - file51.description = "processDescription_new Attachment" - file51.typeOfFile = "processDescription_new"
	d. Hazardous and other wastes generated  - name="generatedWastesAttach" - file51.description = "generatedWastes Attachment" - file51.typeOfFile = "generatedWastesAttach"
	e. Copy of prior Environmental Clearance - name="priorEnv" - file51.description = "priorEnv Attachment" - 	file51.typeOfFile = "priorEnv"
	f. Installed capacity as per registration - name="furnishInstalledCapacity" - file51.description = "furnishInstalledCapacity Attachment" - file51.typeOfFile = "furnishInstalledCapacity" 


	it is still not working properly 
	
23. Forwarded by shows only new arrival in hwm pending list [Fixed]
	
	grails-app/views/wasteManagementPendingDetails/hwmPendingList.gsp

	search for bhanu code start; date: 19-04-2017
	search for bhanu code commented; date: 19-04-2017

	WasteManagementProcessingDetailsController.groovy

	search for bhanu code start; date: 19-04-2017

	New file added - grails-app/views/wasteManagementProcessingDetails/showNewFormatHwm.gsp






Note : further testing cannot be done due to point no. - 13, 14, 15, 16   




Deleted appplication in bmw module
----------------------------------

1. Add appDel column in BioMedicalWaste.groovy
2. wasteManagementAdminVerticalPage.gsp(userMaster) search satish
3. set appDel = false in BioMedicalWaste table (UPDATE bio_medical_waste SET app_del = FALSE ;)
4. file added - grails-app/views/industryRegMaster/deletedAppsBmw.gsp
5. grails-app/views/allReports/wasteDetailBmw.gsp
	search for satish
6. IndustryRegMasterController.groovy
	search satish 
7. update all queries (BIoMedicalWaste)
8. WasteManagementProcessingDetailsController.groovy
	search for satish
9. WasteManagementPendingDetailsController.groovy
	search for - bhanu code start; date: 20-04-2017
10. grails-app/views/userMaster/menuAdminHorizontal.gsp
	search for - bhanu code start; date: 20-04-2017
11. Fixed note history unavailable for previously deleted application
12. Fixed Application name
