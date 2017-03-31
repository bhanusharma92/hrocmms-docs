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

