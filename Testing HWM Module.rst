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

13. in submit hwm inspection report 
	add - Fourth Stage Treatment Details Of Effluent
	no data is comming in fourth stage list select dropdown

	Hence i was not able to submit the report

14. Even after setting approval right. Approval field is not shown to the officer.

15. There is no link to prepare SCN Certificate

16. There is no link to prepare approval/reject certificate

17. Waste application search - on clicking application no a view form gets open-> on clicking Hazardeous Waste 		

	Generation Details tab -> click view -> a popup window gets open and http 404 error is shown

18. SCN Certificate in HWM Module
	Adding link to prepare and view scn certificate

		File edited - grails-app/views/wasteManagementProcessingDetails/appProcessing.gsp

		search for - bhanu code start; date: 11-04-2017

	Functionality of SCN link

		File edited - WasteManagementProcessingDetailsController.groovy

		search for - bhanu code start; date: 11-04-2017

		actions added - scnCertificateHwm 




Note : further testing cannot be done due to point no. - 13, 14, 15, 16   