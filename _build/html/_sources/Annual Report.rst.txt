Annual Report
=============

Adding delete application
-------------------------

Adding functionality in which admin can delete application
Application get deleted from every table

changes:

1. grails-app/views/bmwRenew/bmwRenewAdminVertical.gsp

	Search for - bhanu code start date: 07-04-2017

	Added verical menu to delete application

2. BmwRenewController.groovy

	Search for - bhanu code start; date: 07-04-2017

	action added - deleteApplicationByAdmin, deleteApplicationByAdminActualWork

3. new file added
	
	grails-app/views/bmwRenew/deleteApplicationByAdmin.gsp

4. new file added - BmwRenewDeletedApplication.groovy

Images:

1. Click on BMW Annual Report

.. image:: images/Annual_Report/Adding_delete_application/001.JPG

2. Click on delete Application

.. image:: images/Annual_Report/Adding_delete_application/002.JPG

3. Enter Application id and click delete
	
.. image:: images/Annual_Report/Adding_delete_application/003.JPG

4. Message is shown when application is deleted

.. image:: images/Annual_Report/Adding_delete_application/004.JPG

Adding logo to BMW Annual Report Application Receipt
----------------------------------------------------

changes: 

1. 
