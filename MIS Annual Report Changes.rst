MIS Annual Report Changes
=========================

1. grails-app/views/userMaster/reportAdminMenuVerticalPage.gsp
	
	search for 

	bhanu code start; date: 31-03-2017

	added link to call the bmwAnnualReport action 

2. In AllReportController.gsp

	Search for 

	bhanu code start; date: 29-03-2017

	new action added - bmwAnnualReport, bmwAnnualReportSearch, popAnnualReportPrintPreview, popAnnualReportPendingList,
	popAnnualReportGrantList, popAnnualReportRejectedList, popAnnualReportPendingGrantRejectedList

3. grails-app/views/allReports/bmwAnnualReport.gsp
	
	It is new file added
	It is called when '4.BMW Annual Report' is clicked(MIS -> Waste Management)

4. grails-app/views/allReports/popAnnualReportPrintPreview.gsp
	
	It is new file added
	It is called when print preview is clicked on bmwAnnualReport.gsp

5. grails-app/views/allReports/popAnnualReportPendingList.gsp

	It is new file added
	It is called when no of Annual application is clicked on bmwAnnualReport.gsp
	It may be pending, granted, rejected or all(--)

6. grails-app/views/industryRegMaster/show.gsp

	search for bhanu code start; date: 06-04-2017


Adding Annual Report Management at Employee side
------------------------------------------------

1. grails-app/views/userMaster/reportEmployeeMenuVerticalPage.gsp

	Search for bhanu code start; date: 07-04-2017

	image:

	.. image:: images/MIS_Annual_Report_Changes/adding_annual_report_management_at_emp/001.JPG

Changes after test link
-----------------------

1. grails-app/views/allReports/bmwAnnualReport.gsp

	replace this file 

2. grails-app/views/allReports/popAnnualReportPrintPreview.gsp

	replace this file

	image before:

	.. image:: images/MIS_Annual_Report_Changes/changes_after_test_link/001.JPG

	image after:

	.. image:: images/MIS_Annual_Report_Changes/changes_after_test_link/002.JPG	

	after clicking print preview

	.. image:: images/MIS_Annual_Report_Changes/changes_after_test_link/003.JPG



