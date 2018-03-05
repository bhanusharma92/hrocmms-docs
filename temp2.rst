Temporary work
==============

Date: 19-09-2017 
----------------

TEST Server
HWM application number - 141047 

Local 
CTE application no. 
143649 

CTE certificate details

Application for : Air
use case: grant certificate generated or refuse certificate generated
name: Certificate.pdf
type_of_file: Certificate
description: Certificate Generation Record

use case: upload generated certificate(grant or refuse)
name: CertiFicate1.pdf
type_of_file: Certificate1
description: Certificate Generation Record

Local 
CTE application no(water)
143695

Application for : Water
use case: grant certificate generated or refuse certificate generated
name: Certificate.pdf
type_of_file: Certificate
description: Certificate Generation Record

use case: upload generated certificate(grant or refuse)
name: CertiFicate1.pdf
type_of_file: Certificate1
description: Certificate Generation Record


Local
CTE Application(both)
143751

Application for: Both


Changes for scn certificate show in CTE
File: ApplicationProcessingDetailsController, pdfScn
else if (opt.equals("both") || opt.equals("Air/Water")) {
File: ApplicationProcessingDetails/appProcessing
else if(indApp.applicationFor == "both" || indApp.applicationFor == "Air/Water"){
File: ScnPdfGeneration.java
}else if(opt.equals("both") || opt.equals("Air/Water")){ // in pdfFunction and pdfFunctionArray


Application for : Air/Water
use case: grant certificate generated or refuse certificate generated
name: Certificate.pdf
type_of_file: Certificate
description: Certificate Generation Record

use case: upload generated certificate(grant or refuse)
name: CertiFicate1.pdf
type_of_file: Certificate1
description: Certificate Generation Record

local CTE application no. - 143796

Negi Washing Plant
COMPASS GROUP INDIA SUPPORT SERVICES PVT LTD

19-09-2017:
1. Single Window - Completed prepare and view SCN certificate for CTE.
2. Single Window - Completed download CTE certificate from single window, But hepc must add the link on there application.
3. Working on issue that is our data is not sent to hepc.


keytool -import -alias _alias_name_ -keystore "C:\Program Files\Java\jre1.8.0_131\lib\security\cacerts" -file "C:\Users\dshar\Desktop\hepc.cer"



keytool -import -alias investharyana.in -keystore "C:\Program Files\Java\jre1.8.0_131\lib\security\cacerts" -file "C:\Users\dshar\Desktop\hepcTwo.cer"

keytool -import -alias investharyana.in -keystore "C:\Program Files\Java\jre1.8.0_131\lib\security\cacerts" -file "C:\Users\dshar\Desktop\hepcThree.cer"

keytool -delete -alias investharyana.in -keystore "C:\Program Files\Java\jre1.8.0_131\lib\security\cacerts"

onlineMonitoringHomePage


test cte application no. - 141118


-----------------------------------------------------

Industry 1 - Negi Washing Plant
{
  "actionTaken": "OpenComment",
  "commentByUserLogin": "Negi Washing Plant",  
  "commentDate": "2017-09-14T01:09:54.625Z",
  "comments": "application submitted successfully",
  "projectid": "00a88555-ccfa-4abc-a8ef-ee7bf7fe69f3",
  "serviceid": "6bd18359-09f4-4c71-85d9-e4f313ccfb8d"
}

Industry 2 - Aaravi Enterprises
{
  "actionTaken": "OpenComment",
  "commentByUserLogin": "Aaravi Enterprises",  
  "commentDate": "2017-09-12T11:40:41.000Z",
  "comments": "application submitted successfully",
  "projectid": "d7dd7761-c552-4bf8-8aa0-207ec2e65eaa",
  "serviceid": "6bd18359-09f4-4c71-85d9-e4f313ccfb8d"
}


Industry 3 - COMPASS GROUP INDIA SUPPORT SERVICES PVT LTD
{
  "actionTaken": "OpenComment",
  "commentByUserLogin": "VARENDER SHARMA",  
  "commentDate": "2017-09-18T15:51:27.749Z",
  "comments": "application submitted successfully",
  "projectid": "49b201aa-e077-4381-bff9-999588ee8b2c",
  "serviceid": "6bd18359-09f4-4c71-85d9-e4f313ccfb8d"
}



Yarn / Textile processing involving any effluent/emission generating processes including bleaching, dyeing, printing and colouring


Yarn / Textile processing involving any effluent/emission generating processes including bleaching, dyeing, printing and colouring

-------------------------------------------------------------------------------------------------------

local CTE application no. - 143838

projectid: 0ed7ef2b-5e64-4126-a0a5-011300c26b22
serviceid: b27b79b9-a3ec-4eb1-9f70-3e275dd13cd6



TEST SERVER - CTE application no. - 141222

-------------------------------------------------------------------------------------------------------
TEST HWM reopened application
application no - 141320

Before reopen:
hazardeous_waste_auth_app
	id-141320 application_status-approved
waste_management_pending_details
	id-141322 application_status-approved
waste_management_processing_details
	id-141489 approval_status-Approved
	id-141490 approve-true
hwm_all_summary_report
	id-142127 application_status-approved

After reopen:
hazardeous_waste_auth_app
	id-141320 application_status-approved
waste_management_pending_details
	id-141322 application_status-approved
waste_management_processing_details
	id-141489 approval_status-Approved
	id-141490 approve-true
hwm_all_summary_report
	id-142127 application_status-approved

------------------------------------------------------------------------------------------

  http://localhost:8080/HSPCB/industryRegMaster/updateSingleWindowApplicationDetail?id=143867&indUser=17FAT142339&applicationId=108795&serviceId=123&projectServiceId=123

CTO application no. 143880 [local with test projectid]

-----------------------------------
HWM appliaction no. 142187

22-09-2017:

1. Single Window- Before when application is in-progress i am send serviceFormEdited through api, and when application is completed i sending opencomment - application submitted successfully. But now when in-progress then opencomment - form filling in-progress is sent and when completed, then serviceFormEdited is sent.
2. When user login - a new option 'Apply CTO New' is added and when it is clicked - user will be directed to investharyana.in
3. Rename the instruction as shown to user & 'Apply consent' to 'Apply CTO Renew'.
4. In HWM Verification report 
---------------------------------------------------------------------------

Bio-medical waste:
Before:
bio_medical_waste
  id-140106 application_status-approved
waste_management_pending_details
  id-140108 application_status-approved
waste_management_processing_details
  id-140129 approval_status-Approved
  id-140130 approve-true
bmw_all_summary_report
  id-141889 application_status-approved


  ALERE MEDICAL PRIVATE LIMITED - 4416777
regionalofficer@10

1. Interview 
2. Completed the online monitoring list given by HSPCB

------------------------------------------------------------------------------------------------------
26-09-2017

local hwm application no. - 140419

Dorne
BMW
Application no. - 143945
Application no.- 143950
Application no. - 143955(in-progress), 143958


26-09-2017:
1. Fixed HWM SCN certificate live issue.
2. Added functionality to create and download BMW application receipt for those cases, whose file is not found on database.
3. Completed removing ganga basin column in online monitoring
4. Updated war on live



HWM serviceid: 611af1fb-4df9-4a13-8129-785a769d8bcc

4317435 
---------------------------------------------------------------------------------------------------------------
BMW aplication id whose completion status is blank: 140620


http://hrocmms.nic.in/OCMMS/industryRegMaster/updateProjectIdForGivenUserId?id=17JHA4548402&projectid=5a193653-54e7-46c4-b887-a7bbb548296

----------------------------


Organisation Validation (OV SSL)

hwm application no. - 143994 
CertificateForScnHWM


    def downLoadingCertificateForScnBmw = {

def fileDownLoad = WasteManagementCertificates.findAll("from WasteManagementCertificates afr where afr.applicationId=? and (afr.typeOfFile='CertificateForScnBMW' or afr.typeOfFile='CertificateForScnHWM') order by afr.id desc", [appId.applicationId.toLong()], [max: 1])


-------------------------------------------------------------------------
- 16AMB3136628
- d364f15f-542d-464e-9d1c-92aab0f802f1
- 3136628

http://hrocmms.nic.in/OCMMS/industryRegMaster/updateProjectIdForGivenUserId?id=16AMB3136628&projectid=d364f15f-542d-464e-9d1c-92aab0f802f1

-----------------------------------------------------------------------

local hwm application no. - 144015
144037
--------------------------------------------------------------------------
03-10-2017

HWM application no. - 143982 (Local)
- 144052

CTO application no. - 144062 (local)


When HWM application is approved or rejected, 
http://localhost:8080/HSPCB/hazardeousWasteAuthApp/showNewFormat/144052

View Refusal Order
service id = bcf33589-b4ab-468d-aafc-921d6754c236
ind_user_id = 17FAT143980
project id = 3795e7b5-e4a9-48ef-bd1c-3aa4ef677ecl


application no.                  - 144128
universal industry reg master id - 144123
industry reg master id           - 144141
edit industry profile

---------------------------------------------------------------------------
live issue - payment made but in-progress 
4250926, 2514478

04-10-2017:
1. Single Window - Working on hwm.
2. Single Window - Working on new changes for already registered user.
3. Live issue - Cto application is orpahn but noit showing in application summary.

a4ee73ec9b41122ca50e99be93689bb9

def pdf = {
  def fileLength = certFile.length()
  file.size = fileLength / 1024  //f.getSize()
  file.extension = "pdf"//extractExtension( f )
  file.data = b;
  file.name = "CertiFicate.pdf"
  file.description = "Certificate Generation Record"
  file.createdBy = session.userMaster
  file.updatedBy = session.userMaster
  file.typeOfFile = "Certificate"
  file.indApplication = indApplicationDetailsInstance
  file.appFor = indApplicationDetailsInstance.applicationFor  
}

101482

HWM application no. - 144184 

Issue: download button not showing when service is cleared
url : https://staging.investharyana.in
login id - jonsnow, password - 1234
Business Entity - myIndustrySeven
service name: Registration for recycle or reprocessing under Hazardous waste

06-10-2017:
1. In HWM integration fixed the unattented case.
2. Provided the test link and do the testing of HWM integration.
3. Merged the HWM code in live code.
4. Changes in online monitoring as specified by hspcb.
  
----------------------------------------------------------------------------------------------
live application no. - 4159023

// https://mvnrepository.com/artifact/org.glassfish.jersey.archetypes/jersey-quickstart-webapp
compile group: 'org.glassfish.jersey.archetypes', name: 'jersey-quickstart-webapp', version: '2.16'


completionStatus = completed
orphan


------------------
Please Generate Certificate for both/HWM first.

if(indApp.applicationFor == 'both/HWM'){
                    def fileRecordInstance = ApplicationFileRecord.find("from ApplicationFileRecord where indApplication=? and name = 'DigiCommonCtoBothRefCertificate.pdf' order by id desc",[indApp])


local cte application no. - 101482

09-10-2017:
1. Live issue - Fixed the close after refusal for CTE both/HWM application.
2. Updated HWM integration on live.
3. Live issue - Fixed view certificate not showing for CTE application.
4. Started working on BMW integration
                    
SELECT DISTINCT city FROM station
WHERE REGEXP '[^aeiou]$';
---------------------------------------------------------------------------------------------------------
10-10-2017:
application no. - 3710881
indUser - 4196780
indUserUniversal - 981783


local CTE application no. - 144214
Local CTE application no. - 144263



Live issue in bmw
server is busy:
4443008(C17AMB4407002), 
4422546(C17AMB4422538), 
4297769(C17PAN4285079), 
4208101(C17AMB4208086), 
4401943(C17PAN4400168), 
4589343(C17PAN4586187) 

forwarding rights not showing:
4250520(MALHOTRA NURSING HOME)
4214501

Application not closing after approve - 
4049790

144286

live application id - 245571

143937


---------------------------------------------------------
RADIANCE PRINTPACK PVT LTD
project id - 10b0d718-5405-472c-a4ea-330488458470
10b0d718-5405-472c-a4ea-330488458470



11-10-2017:
1. Solved all of the issues in BMW as specified on mail dated 10-10-2017.
2. Working on BMW integration
3. Updated live war to check single window issue


245571

245850


17REW4595426
CYGNUS MULTISPECIALITY HOSPTIAL - 2a5e340b-48e6-4c94-9825-d83c7f9050e6

1
http://hrocmms.nic.in/OCMMS/industryRegMaster/viewSingleWindowIndUser?id=17PAN4596050
http://hrocmms.nic.in/OCMMS/industryRegMaster/updateProjectIdForGivenUserId?id=17PAN4596050&projectid=18855881-023e-4e8d-8198-9e57e714cdba

2
http://hrocmms.nic.in/OCMMS/industryRegMaster/viewSingleWindowIndUser?id=17SON4596124
http://hrocmms.nic.in/OCMMS/industryRegMaster/updateProjectIdForGivenUserId?id=17SON4596124&projectid=44d23727-8ae1-4877-8c76-43f621cbffd9

3
http://hrocmms.nic.in/OCMMS/industryRegMaster/viewSingleWindowIndUser?id=17FAT4596204
http://hrocmms.nic.in/OCMMS/industryRegMaster/updateProjectIdForGivenUserId?id=17FAT4596204&projectid=87e4c968-b67f-4f13-a395-e36d63f0d5eb


4
http://hrocmms.nic.in/OCMMS/industryRegMaster/viewSingleWindowIndUser?id=17PIT4596242
http://hrocmms.nic.in/OCMMS/industryRegMaster/updateProjectIdForGivenUserId?id=17PIT4596242&projectid=fee812aa-84a4-45ff-a5c6-9aada190a557

5
http://hrocmms.nic.in/OCMMS/industryRegMaster/viewSingleWindowIndUser?id=17PIT4596259
http://hrocmms.nic.in/OCMMS/industryRegMaster/updateProjectIdForGivenUserId?id=17PIT4596259&projectid=02dff131-c41a-4908-b70b-ac351a8fa1b0

6
http://hrocmms.nic.in/OCMMS/industryRegMaster/viewSingleWindowIndUser?id=17PIT4596278
http://hrocmms.nic.in/OCMMS/industryRegMaster/updateProjectIdForGivenUserId?id=17PIT4596278&projectid=68057d50-3c1c-4b44-aefb-b982b1d65052

7
http://hrocmms.nic.in/OCMMS/industryRegMaster/viewSingleWindowIndUser?id=17SON4598755
http://hrocmms.nic.in/OCMMS/industryRegMaster/updateProjectIdForGivenUserId?id=17SON4598755&projectid=0feaa4c3-6935-40ec-b9ce-d9665c9063b6


8
http://hrocmms.nic.in/OCMMS/industryRegMaster/viewSingleWindowIndUser?id=17YAM4598752
http://hrocmms.nic.in/OCMMS/industryRegMaster/updateProjectIdForGivenUserId?id=17YAM4598752&projectid=30e73a3f-e59f-43e5-a612-b3273d2159d2


9
http://hrocmms.nic.in/OCMMS/industryRegMaster/viewSingleWindowIndUser?id=17PAN4598927
http://hrocmms.nic.in/OCMMS/industryRegMaster/updateProjectIdForGivenUserId?id=17PAN4598927&projectid=18855881-023e-4e8d-8198-9e57e714cdba


10
http://hrocmms.nic.in/OCMMS/industryRegMaster/viewSingleWindowIndUser?id=17MAH4599563
http://hrocmms.nic.in/OCMMS/industryRegMaster/updateProjectIdForGivenUserId?id=17MAH4599563&projectid=3fe5c984-6a96-499d-9334-5a68a86923a4

11
http://hrocmms.nic.in/OCMMS/industryRegMaster/viewSingleWindowIndUser?id=17FDBB4601579
http://hrocmms.nic.in/OCMMS/industryRegMaster/updateProjectIdForGivenUserId?id=17FDBB4601579&projectid=7c088e93-4c8c-4ff9-b761-8d68afee0a21

12
http://hrocmms.nic.in/OCMMS/industryRegMaster/viewSingleWindowIndUser?id=17GUSO4602252
http://hrocmms.nic.in/OCMMS/industryRegMaster/updateProjectIdForGivenUserId?id=17GUSO4602252&projectid=82a7e102-a4b4-4e63-810f-dbc2a4859010

13
http://hrocmms.nic.in/OCMMS/industryRegMaster/viewSingleWindowIndUser?id=17GUNO4602386
http://hrocmms.nic.in/OCMMS/industryRegMaster/updateProjectIdForGivenUserId?id=17GUNO4602386&projectid=6470d67c-c939-47fb-ab2b-445f07f28bc1


Given by hepc - 18855881-023e-4e8d-8198-9e57e714cdba
43e594d0-9c8f-4f74-8475-1a89d938ac1b



Vecrica Formulation
17PAN4596050 - 9812551499 - 

17PAN4598927 - 9053637862 - 4598932



----------------------------------------------------------------------------------------
local bmw application no. - 144339

12-10-2013:
1. Working on BMW integration.
2. Updated the live war and resolved the issue the user are redirected to industryHome page instead of apply consent if they have previously deleted application.


13-10-2017:
1. Working on BMW.
2. Live issue - some hazardous waste source are showing in admin side, but not in industry side so implemeted a functionality to properly assign the schedule to sources so that they will become visible in hwm form.
3. Two interviews.

----------------------------------------------------------------------------------------------------------------
16-10-2017

industry name: myHcfTestFive
mobile no. : 5555544449
bmw application no. - 144370 

bmw application no. - 144397 


SELECT (CASE WHEN  A = B and B = C and A = C
            THEN 'Equilateral',
       CASE WHEN A = B and B = C and A + B >= C and A + C >= B and B + C >= A
            THEN 'Isosceles',
       CASE WHEN A + B >= C and A + C >= B and B + C >= A
            THEN 'Scalene',     
       ELSE 
            'Not A Triangle'
       END)
FROM TRIANGLES;



SELECT * FROM "public"."industry_type_master" where industry_type ilike '%Dyes%';

ALTER TABLE industry_type_master ADD COLUMN dashboard bigint;

ALTER TABLE industry_type_master ALTER COLUMN dashboard SET DEFAULT 0;
update industry_type_master set dashboard=0;

27776

120532

16-10-2017:
1. Working on Bmw integration.
2. Merged ocmms-dashboard 17 category code

http://localhost:8080/HSPCB/industryRegMaster/downloadCertificateApi/?projectid=3795e7b5-e4a9-48ef-bd1c-3aa4ef677ecy&serviceid=3e5652fc-4aeb-4ddf-8af0-72e6f94ccb1e


BMW application no. - 144397


word - SIngleWIndowApplicationDetail

file - confirmationSubmit ==> done
file - industryRegMasterController ==> done
file - indApplicationDetailController ==> done
file - HazardeousWasteAuthApp ==> done
file - BioMedicalWasteController ==> done
file - BioMedicalWasteController ==> done
file - WasteManagementProcessingController ==> done
file - APplicationProcessingDetailsController ==> done


def isServiceFormEdited = params.isServiceFormEdited
def isServiceClearedOrRejected = params.isServiceClearedOrRejected

if(isServiceFormEdited.equals("true")){
    singleWindowApplicationDetail.isServiceFormEdited = true
}else{
    singleWindowApplicationDetail.isServiceFormEdited = false
}
if(isServiceClearedOrRejected.equals("true")){
    singleWindowApplicationDetail.isServiceClearedOrRejected = true
}else{
    singleWindowApplicationDetail.isServiceClearedOrRejected = false
}




aug - 8
sept - 9
oct - 10

winterfell inspection no. - 142620 - application no. - 142490
highgarden inspection no. - 142623 - application no. - 142466
dorne inspection no. - 142626 - application no. - 142450




name="uname"   -------------------------- done
name="investorname" 
name="address" 
name="useremail" 
name="country" 
name="state" 
name="city" 
name="niccode" 
name="pannumber" 
name="gstnumber" 
name="aadhar_number" 
name="proposedbuilt_up_area" 
name="mobile" 
name="totalproposedprojectarea" 
name="totalpurposedemployment" 
name="total_project_cost" 
name="project_site_district" 
name="landzoneuse_type" 
name="businessentity" 
name="projecttype" 
name="projectid" 
name="serviceid" 
name="projectserviceid" 


4545129 - certificate error bmw

consent application no. - 
4620646
4614081 - CTE
4620043 - CTE
4619463 - CTE
4618342 - CTO 
4617996 - CTE
4617740 - CTE
4613692 - CTO
4617178 - CTO - 2017-10-21



23-10-2017:
1. Testing  CTO/CTE MIS for single window applications and provided lastest list of same.
2. Completed auto-fetch paramenters and display in our registration
3. updated on live
4. Fixed serviceFormEdit sending issue  


local CTO application no. - 144526 
local CTE application no. - 144581, 144620  
local HWM application no. - 144638(forget it), 144644(approved), 144683 (refused)
local BMW application no. - 144718(forget it), 144730(approved), 144753 
test cases considered - CTO approved, CTE refused

4613318
projectid: 8742949a-d9a3-495f-944d-1d14393eb06b
serviceid: b27b79b9-a3ec-4eb1-9f70-3e275dd13cd6
{
  "actionTaken": "OpenComment",
  "commentByUserLogin": "Bhanu Sharma",  
  "commentDate": "2017-09-19T09:43:42.335Z",
  "comments": "Test 1",
  "projectid": "10739371-9de0-4480-9cb2-b523470e8674",
  "serviceid": "6bd18359-09f4-4c71-85d9-e4f313ccfb8d"
}

{
  "actionTaken": "OpenComment",
  "commentByUserLogin": "Negi Washing Plant",  
  "commentDate": "2017-09-14T01:09:54.625Z",
  "comments": "application submitted successfully",
  "projectid": "00a88555-ccfa-4abc-a8ef-ee7bf7fe69f3",
  "serviceid": "6bd18359-09f4-4c71-85d9-e4f313ccfb8d"
}

{
  "actionTaken": "OpenComment",
  "commentByUserLogin": "VARENDER SHARMA",  
  "commentDate": "2017-09-18T15:51:27.749Z",
  "comments": "application submitted successfully",
  "projectid": "49b201aa-e077-4381-bff9-999588ee8b2c",
  "serviceid": "6bd18359-09f4-4c71-85d9-e4f313ccfb8d"
}

testing123
testing@123


projectid - 38f7e8ec-f7ee-4b79-a513-b72ea3dda1af
serviceid - 6bd18359-09f4-4c71-85d9-e4f313ccfb8d

hrocmms.nic.in/api/webapi/hrocmms/login?projectid=38f7e8ec-f7ee-4b79-a513-b72ea3dda1af&serviceid=6bd18359-09f4-4c71-85d9-e4f313ccfb8d&investorname=sanju&address=myAddress&useremail=sanju@gmail.com&mobile=9876543210&projectserviceid=1234&businessentity=sanju_stone_crusher&city=delhi&state=delhi

String projectserviceid = params.projectserviceid
String businessentity = (((String)(params.businessentity)).replace("!", " ")).replace("*","&")
String city = (((String)(params.city)).replace("!", " ")).replace("*","&")
String state = (((String)(params.state)).replace("!", " ")).replace("*","&")

Implemented different modules like annual report, hwm   


25-10-2017:
1. Fixed single window blank page issue 
2. Merged BMW code in live code and updated the live war.
3. Completed hide traders of BMW in registration page.              



Application id = 144730

KIDS CLINIC INDIA PVT LTD


http://localhost:8080/HSPCB/industryRegMaster/viewApplicationsWhoseFormEditedStatusNotSent
http://localhost:8080/HSPCB/industryRegMaster/viewApplicationsWhoseClearedOrRejectedNotSent

Testing the send status -->
projectid: 7443ecd8-a630-4940-8994-ae2b1f80f7ab
indUser: 17PAN144524
industryRegMaster: 144524
CTO application id - 144526
jkpcb016
anil#1111


144526 cto
144753 bmw
apachectl start

RO GZB RO - remove one RO
noter
ND-C1
PA-C1
AEE-C1
57980 

198666
VSP000


144840

line no. - 3597 
line no. - 3871

line no. - 3561 // files 
line no. - 3617
1. indProductDetailsInstanceList: indProductDetailsInstanceList
def indProductDetailsInstanceList = new ArrayList()

2. consentFeeMasterInstance: consentFeeMasterInstance
def consentFeeMasterInstance = ConsentFeeMaster.findByApplication(indApplicationDetails)

3. feeBankDetailsInstanceList: feeBankDetailsInstanceList
def feeBankDetailsInstanceList = new ArrayList()

4. indWaterConsumptionDetailsInstanceList: indWaterConsumptionDetailsInstanceList
def indWaterConsumptionDetailsInstanceList = new ArrayList()

5. indWaterDischargeDetailsInstanceList: indWaterDischargeDetailsInstanceList
def indWaterDischargeDetailsInstanceList = new ArrayList()

6. indEffluentStandardDetailsInstanceList: indEffluentStandardDetailsInstanceList
def indEffluentStandardDetailsInstanceList = new ArrayList()

7. indAirStackEmmisionDetailsInstanceList: indAirStackEmmisionDetailsInstanceList
def indAirStackEmmisionDetailsInstanceList = new ArrayList()

8. indEmmisionCntrlDetailsInstanceList: indEmmisionCntrlDetailsInstanceList
def indEmmisionCntrlDetailsInstanceList = new ArrayList()

9. indAirFuelDetailsInstanceList: indAirFuelDetailsInstanceList
def indAirFuelDetailsInstanceList = new ArrayList()

10. indAirFugitiveDetailsInstanceList: indAirFugitiveDetailsInstanceList
def indAirFugitiveDetailsInstanceList = new ArrayList()

11. indEmmisionCntrlDetailsInstanceList2: indEmmisionCntrlDetailsInstanceList2
def indEmmisionCntrlDetailsInstanceList2 = new ArrayList()



application no. - 144992

144981
145120

145199

145259



http://localhost:8080/HSPCB/industryRegMaster/downloadCertificateApiEc/144981 - CTO
http://localhost:8080/HSPCB/industryRegMaster/downloadCertificateApiEc/144286 - CTE

-------------------------------------------------------------------------------------------
06-11-2017:

local application no. - 145325


http://hrocmms.nic.in/api/webapi/hrocmms/downloadCertificate?projectid=c5070200-98be-4fdd-97e7-5523b13292e4&serviceid=6bd18359-09f4-4c71-85d9-e4f313ccfb8d

<url>/OCMMS/industryRegMaster/viewApplicationsWhoseClearedOrRejectedNotSent
IndustryInspectionReport
ApplicationFileRecord()
typeOfFile = "checklist"
noteHistiryFile.typeOfFile = "regularInspectionReportOtherDocs"

{
  "actionTaken": "ServiceFormEdited",
  "commentByUserLogin": "nitasha",  
  "commentDate": "2017-10-06T09:52:00.000Z",
  "comments": "ServiceFormEdited",
  "id": "",
  "projectid": "c5070200-98be-4fdd-97e7-5523b13292e4",
  "serviceid": "6bd18359-09f4-4c71-85d9-e4f313ccfb8d"
}

17SON4586688
4586690
2017-10-04T15:14:26.150 
06/11/2017 16:19
2017-11-06T16:19:00.000Z


if ((params.group == 'xyz') && (params.category == 'None') && (params.district == 'ALL')) {
  
} else if ((params.group != 'xyz') && (params.category == 'None') && (params.district == 'ALL')) {

} else if ((params.group != 'xyz') && (params.category == 'None') && (params.district != 'ALL')) {

} else if ((params.group != 'xyz') && (params.category != 'None') && (params.district == 'ALL')) {

}  else if ((params.group != 'xyz') && (params.category != 'None') && (params.district != 'ALL')) {

}  else if ((params.group == 'xyz') && (params.category != 'None') && (params.district == 'ALL')) {

} 

application no. - 145448


http://hrocmms.nic.in/api/webapi/hrocmms/downloadCertificate?projectid=b4d9fa1c-6987-4b00-997f-53e9ef2f1d61&serviceid=6bd18359-09f4-4c71-85d9-e4f313ccfb8d

b4d9fa1c-6987-4b00-997f-53e9ef2f1d61

10-11-2017
BMW application no . - 145623 


[[1, Dddddddddddd, Dddddddddddd],
[2, Dddddddddddd, Dddddddddddd],
[3, Ccccccccccccc]]


SaveConditionsBMW
 





D:\GrailsProjects\hrocmms\grails-app\conf\DataSource.groovy
43522
4293166
D:\GrailsProjects\hrocmms\lib\iText-2.1.7.jar!\com\lowagie\text\pdf\PdfPCell.class

13-11-2017:
1. Check master branch
  test bmw certificate - done
  hwm approval rights - done 
  staging.investharyana - done
  remove green catgory - done

2. Completed 




145654 

HWM application no. - 145674

service form edited status not sent
1. 4690378
2. 4690480
3. 4690568
4. 4690695
5. 4690733
6. 4639961
7. 4691024
8. 4639993
9. 4692940
10. 4689652
11. 4690234


4690234
4690444 - done


TEST server 
10739371-9de0-4480-9cb2-b523470e8674


13-11-2017:
1. Merged bmw certificate and hwm approval rights in live code
2. Completed functionality to close the clarifictation in HWM from admin for those application who are approved. 


16-11-2017:
1. Washout redirect to home page
    InspectionNoteHistory.inspectionDescriptionNote
    InspectionNoteHistory is not null but its column 'inspectionDescriptionNote' is null
    at org.hibernate.engine.Nullability.checkNullability(Nullability.java:95)
    at org.hibernate.event.def.DefaultDeleteEventListener.deleteEntity(DefaultDeleteEventListener.java:272)
    at org.hibernate.event.def.DefaultDeleteEventListener.onDelete(DefaultDeleteEventListener.java:163)
    at org.hibernate.event.def.DefaultDeleteEventListener.onDelete(DefaultDeleteEventListener.java:74)
    at org.hibernate.impl.SessionImpl.fireDelete(SessionImpl.java:793)
    at org.hibernate.impl.SessionImpl.delete(SessionImpl.java:771)
    at sun.reflect.GeneratedMethodAccessor28018.invoke(Unknown Source)
    at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
    at java.lang.reflect.Method.invoke(Method.java:497)
    at org.springframework.orm.hibernate3.HibernateTemplate$CloseSuppressingInvocationHandler.invoke(HibernateTemplate.java:1293) 

2. HSPCB053 scientist b panchkula come in draw but its canDoInspection is false
3. Add common facility in inspection
4. store caf in our db
5. autoRenew integrate with hepc

group hissar, gurgoan
eehepc
145828


isCommonTreatmentFacility - NO / YES



16-11-2017:
1. Resolved the approval rights issue.
2. Working on add common treatment facilities in inspection draw.


Indospace Industrial Park Badli Private Limited 
17JHA4610934
14/10/2017
JHAJJAR
RED
Consent /BMW /Annual Report /Cess /HWM /Inspection /E-waste



1. bmw approval rights 

2. application 


HSPCB020
regionalofficer@10


ROCKLAND HOSPITAL

3254425 - RED
1367103 - RED
4304267 - RED



DENSO HARYANA PVT. LTD
4194125 - RED
3857433 - RED
3598219 - RED
3770125 - RED
3908289 - RED
141503 - RED
461285 - RED
4518393 - RED


ALERE MEDICAL PRIVATE LIMITED
3470373 - 
1876300 - ORANGE

HSPCB015
naveen@2017

BMW 

Sorry cannot approve 


rakesh
9873666126



Application not closed
4036867
Message
Sorry can not Approve Clarification is Raised on this application


Server busy


Satyakiran Healthcare Private Limited
----
project id of 14ROH1458345  SHIVA PETROLEUM
5a193653-54e7-46c4-b887-a7bbb5482965
----


145899


testZeroOne
145920

application no. whose note history date problem
4269229


trader twenty one CTE application id - 145945
industryTypeMaster id = 120526 (For orange)


---------------------------------
Test BMW close clarification 
application no. - 141295


jitu@123





-------------------------------------
<select name="industryType.id" id="industryType.id1" onblur="greenChng();" onchange="whiteCatchange();" style="width:300px;">
<option value="100">Not Selected</option>
<option value="4384456">Vegetable oil manufacturing including solvent extraction and refinery/ hydrogenated oils having waste water generation mare than 100 KLD</option>
<option value="3130921">DG Set of capacity of 5 MVA and above</option>
<option value="4338749">Flour Mills generating trade effuent</option>
<option value="3131158">Ayurvedic and homeopathic medicine</option>
<option value="3130952">Milk processes and dairy  products(integrated project) large and medium scale units</option>
<option value="4338761">Printing Presses without involving water polluting Process</option>
<option value="4338773">Health care Establishments i.e hospitals/ clinics without indoor facilities and having only OPD consultancy</option>
<option value="4338799">Distilled water units using boiler or furnace as source of heat</option>
<option value="3130969">Airports and Commercial Air  Strips projects Having discharge of 100 KLD or More</option>
<option value="4338817">Construction and Demolition (C and D) waste Processing and recycling units</option>
<option value="3130998">Hotels having overall waste  water generation @ 100 KLD and  more Hotels having 3 Star and above and having 100 Rooms or above</option>
<option value="4338832">Garment/Apparel manufacturing units having only garment washing, with or without boiler except bleaching, dyeing, printing, Coloring  </option>
<option value="3130926">Lead acid battery  manufacturing(excluding  assembling and charging of lead  acid battery in micro scale)</option>
<option value="3130955">Phosphorous and its compounds</option>
<option value="3131023">Oil and gas extraction including  CBM (offshore &amp; on  extraction through drilling wells)  -shore</option>
<option value="3131074">Bakery and confectionery units with  production capacity &gt; 1 TPD. ( With  ovens / furnaces)</option>
<option value="3131079">Coated electrode manufacturing</option>
<option value="3131124">Jute processing without dyeing</option>
<option value="3131126">Manufacturing of silica gel</option>
<option value="3131146">Cotton spinning and weaving (  medium and large scale)</option>
<option value="3131044">Iron &amp; Steel (involving  processing from ore/ integrated  steel plants) and or Sponge Iron  units</option>
<option value="3131051">Zinc Smelter</option>
<option value="3130979">Cement</option>
<option value="3131062">Pulp &amp; Paper ( Large-Agro +  wood) , Small Pulp &amp;  Paper ( agro based-wheat  straw/rice husk)</option>
<option value="3131059">Pharmaceuticals Basic Drugs Manufacturing Units</option>
<option value="3131207">Fish processing and packing (excluding  chilling of fishes)</option>
<option value="3131209">Forging of ferrous and non- ferrous  metals ( using oil and gas fired  furnaces)</option>
<option value="3131222">Hot mix plants</option>
<option value="3131227">Ice cream</option>
<option value="3131229">Industries engaged in recycling /  reprocessing/ recovery/reuse of  Hazardous Waste under schedule iv of  HW( M, H&amp; TBM) rules, 2008 - Items  namely -  Paint and ink Sludge/residues</option>
<option value="3131232">Industry or processes involving  foundry operations</option>
<option value="3131252">Manufacturing of Starch/Sago</option>
<option value="3131254">Mechanized laundry using oil fired  boiler</option>
<option value="3131256">Modular wooden furniture from  particle board, MDF&lt; swan timber etc,  Ceiling tiles/ partition board from saw  dust, wood chips etc., and other  agricultural waste using synthetic  adhesive resin, wooden box making (  With boiler)</option>
<option value="3131272">Potable alcohol ( IMF  L) by blending,  bottling of alcohol products</option>
<option value="3131289">Steel and steel products using  various furnaces like blast furnace  /open hearth furnace/induction  furnace/arc furnace/submerged  arc furnace /basic oxygen furnace  /hot rolling reheated furnace</option>
<option value="3131291">Stone crushers</option>
<option value="3131294">Surgical and medical products  including prophylactics and latex</option>
<option value="3132800">Vegetable oil manufacturing  including solvent extraction and  refinery /hydrogenated oils</option>
<option value="3132820">Synthetic resins</option>
<option value="3132843">Producer gas plant using conventional  up drift coal gasification ( linked to  rolling mills glass and ceramic industry  refectories for dedicated fuel supply)</option>
<option value="3132860">Candy</option>
<option value="3132886">Decoration of ceramic cups  and plates by electric furnace</option>
<option value="3132902">Glass , ceramic, earthen  potteries, tile and tile  manufacturing using  electrical kiln or not  involving fossil fuel kiln</option>
<option value="3132905">Glue from starch (physical  mixing) with gas /  electrically operated oven  /boiler.</option>
<option value="3132909">Gold and silver smithy  (purification with acid  smelting operation and  sulphuric acid polishing  operation) (using less or  equal to 1 litre of sulphuric  acid/ nitric acid per month)</option>
<option value="3132942">Leather foot wear and leather  products (excluding tanning  and hide processing except  cottage scale)</option>
<option value="3132944">Lubricating oil, greases or  petroleum based products  (only blending at normal  temperature)</option>
<option value="3132957">Polythene and plastic  processed products  manufacturing (virgin  plastic)</option>
<option value="3132961">Poultry,  Hatchery and  Piggery</option>
<option value="3132964">Power looms (without dye  and bleaching)</option>
<option value="3132967">Puffed rice (muri) (using gas  or electrical heating system)</option>
<option value="3132985">Reprocessing of waste cotton</option>
<option value="3132987">Rice mill (Rice hullers only)</option>
<option value="3132993">Rolling mill ( gas fired) and  cold rolling mill</option>
<option value="3202157">Jobbing and Machining</option>
<option value="3202160">Reel manufacturing</option>
<option value="3202164">Assembling of acid lead batteries (up to 10 batteries per  day excluding lead plate casting)</option>
<option value="3202168">Automobile fuel outlets (only dispensing)</option>
<option value="3202173">Diesel generator sets (15 KVA to 1 MVA)</option>
<option value="3131055">Oil Refinery (mineral Oil or  Petro Refineries)</option>
<option value="3131162">Building and construction project having more than 20,000 sq. m built up area having quantity of waste water generation 10 KLD to 100 KLD</option>
<option value="4338848">Garment/Apparel units involving only stiching process, without discharge of effluent and Air emissions from process</option>
<option value="3202185">Excavation of sand from the river bed (excluding  manual excavation)</option>
<option value="3202189">Infrastructure Development Project</option>
<option value="3202191">Power press</option>
<option value="3202208">Common treatment and disposal facilities(CETP, TSDF, E- waste recycling, CBMWTF, effluent conveyance project,  incinerator, solvent/acid recovery plant, MSW sanitary land  fill site)</option>
<option value="3202211">Processing of Emulsions of Oil &amp; Water</option>
<option value="3202213">Heavy engineering including ship building (with investment  on Plant &amp; Machineries more than Rs 10 crores)</option>
<option value="3202216">Hydrocyanic acid and its derivatives</option>
<option value="3203032">Industrial estates/ parks / complexes/ areas/ export processing  zones/ SEZs/ Biotech parks/ leather complex</option>
<option value="3203034">Industrial inorganic gases namely- a) Chemical gas- Acetylene, hydrogen, chlorine, fluorine,  ammonia, sulphur dioxide, ethylene, hydrogen-sulphide,  phosphine b) Hydrocarbon gases- Methane , ethane, propane</option>
<option value="3203036">Reprocessing of used oils &amp; waste oils</option>
<option value="3203924">Formulation of pesticides</option>
<option value="3298049">Recycling/Pyrolysis plant of waste pneumatic tyre/ tyre scraps</option>
<option value="3299597">Induction Furnace clubbed with AOD furnace </option>
<option value="3299606">Synthetic detergents and soaps having waste water generation more than 100 KLD (excluding formulation) </option>
<option value="3299614">Automobile servicing, repairing and painting having waste water generation more than 100 KLD (excluding only fuel dispensing)</option>
<option value="3299617">Automobile servicing, repairing and painting having waste water generation more than 100 KLD (excluding only fuel dispensing)</option>
<option value="3299622">Building and construction project more than 20,000 sq.m built up area having waste water generation more than 100 KLD</option>
<option value="3299628">Ceramics and refractories having coal consumption more than 12 MT per day</option>
<option value="3299646">Fermentation industry including manufacture of yeast, bear, distillation of alcohol (Extra  Neutral Alcohol) having discharge &gt; 100 KLD</option>
<option value="3299654">Lead metal extraction involving different furnaces through melting, refining, re-processing, casting and alloy-making </option>
<option value="3131165">Ceramics and Refractories projects having coal consumption upto 12 MT per day  </option>
<option value="3299667">Industry or processes involving foundry operation having capacity of 5 MT/hr. and more </option>
<option value="3299675">Manufacturing of lead glass</option>
<option value="3299698">Non-alcoholic beverages (soft drink) &amp; bottling of alcohol/ non alcoholic products having waste water generation more than 100 KLD</option>
<option value="3299729">Parboiled rice mills having waste water generation &gt;100 KLD or fuel consumption &gt;12 MTD or both </option>
<option value="3299737">Sewage treatment plant having capacity 100 KLD or more</option>
<option value="3299781">Recycling of used lead acid batteries </option>
<option value="3299806">Industries engaged in recycling/ reprocessing/ recovery/ reuse of hazardous waste under schedule IV of HW (M,H&amp;TBM) rules, 2008-item namely -paint and ink sludge/ residues</option>
<option value="3299848">Industries engaged in recycling/ reprocessing/recovery/reuse of Hazardous Waste under schedule IV of HW(M,H&amp; TBM) rules,2008-Items namely - used oil- as per specifications prescribed from time to time.</option>
<option value="3299857">Industries engaged in recycling/reprocessing/recovery/reuse of Hazardous Waste under schedule IV of HW(M,H&amp;TBM) rules, 2008- Item namely- Waste oil-as per specification prescribed from time to time</option>
<option value="3299864">Health Care Establishments (as defined in BMW rules) having waste water generation less than 100 KLD without incinerator</option>
<option value="3299866">Airport and commercial air strips having discharge less than 100 KLD.</option>
<option value="3299869">Railway locomotive workshop/Integrated road transport workshop/Authorized service centers(having waste-water generation &lt; 100 KLd)</option>
<option value="3299877">Manufacturing of pasted veneers using coal/wood scrap boiler or thermic fluid heater and by sun drying.</option>
<option value="3299881">Cardboards and Millboards</option>
<option value="3299886">Strawboards</option>
<option value="3299892">Formulation of Pesticides/ Insecticides.</option>
<option value="3299899">Recycling/Pyrolysis plants of waste pneumatic tyres/ tyre scarp</option>
<option value="3299903">Surgical cotton industries </option>
<option value="3299909">Inorganic chemical compounds such as chlorides/sulphates/ suphites/nitriates/oxides/ flourides/stearates of metals/cations</option>
<option value="3299915">Sodium and other silicates manufacturing</option>
<option value="3299918">Cotton coated fabrics including printing and lamination(Rexene)</option>
<option value="3299921">Friction dust</option>
<option value="3299925">Break lining/Disc break pad </option>
<option value="3299930">Chlorinated paraffin wax / plasticizers </option>
<option value="3299934">Sewage treatment plant having capacity 10 KLD or more but less than 100 KLD </option>
<option value="3299940">Infrastructure development projects having overall liquid waste generation 100 KLD or more.</option>
<option value="3131225">Hotels (&lt; 3 star) or hotels having &gt; 20  rooms and less than 100 rooms having quantity of waste water discharge less than 100 KLD</option>
<option value="3131042">Fertilizer (basic) (excluding  formulation)</option>
<option value="3130911">Isolated storage of hazardous  chemicals (as per schedule of  manufacturing, storage of  hazardous chemicals rules ,1989  as amended)</option>
<option value="3130913">Automobile Manufacturing  (integrated facilities)</option>
<option value="3130918">Manufacturing of lubricating oils  ,grease and petroleum based  products</option>
<option value="3130929">Phosphate rock processing plant</option>
<option value="3130931">Power generation plant [except Wind and Solar renewable  power plants of all capacities and  Mini Hydel power plant of  capacity &lt;25MW]</option>
<option value="3130933">Industries engaged in recycling /  reprocessing/ recovery/reuse of  Hazardous Waste under  schedule iv of HW( M, H&amp; TBM)  rules, 2008  Spent catalyst containing nickel,  cadmium, Zinc, copper, arsenic,  vanadium and cobalt,  - Items namely</option>
<option value="3130935">Processes involving chlorinated  hydrocarbons</option>
<option value="3130987">Chlorates, per  peroxides  -chlorates &amp; peroxides</option>
<option value="3130990">Chlorine, fluorine, bromine,  iodine and their compounds</option>
<option value="3131001">Manufacturing of glue and  gelatin</option>
<option value="3131025">Industry or process involving  metal surface treatment or  process such as pickling/  electroplating/paint stripping/  heat treatment using cyanide  bath/ phosphating or finishing  and anodizing / enamellings/  galvanizing</option>
<option value="3131030">Ports and harbour, jetties and  dredging operations</option>
<option value="3131036">Slaughter house (as per  notification S.O.270(E)dated  26.03.2001)and meat processing  industries, bone mill, processing  of animal horn, hoofs and other  body parts</option>
<option value="3131076">Chanachur and ladoo from puffed and  beaten rice( muri and shira) using  husk fired oven</option>
<option value="3131132">Manufacturing of tooth powder,  toothpaste, talcum powder and other  cosmetic items</option>
<option value="3131150">Almirah, Grill Manufacturing (Dry  Mechanical Process )</option>
<option value="3131179">Coal washeries</option>
<option value="3131212">Formulation/pelletization of camphor  tablets, naphthalene balls from  camphor/ naphthalene powders.</option>
<option value="3131236">Lime manufacturing (using lime  kiln)</option>
<option value="3131241">Manufacturing of glass</option>
<option value="3131258">New highway construction project</option>
<option value="3131262">Paint blending and mixing (Ball mill)</option>
<option value="3131276">Printing ink manufacturing</option>
<option value="3131297">Tephlon based products  </option>
<option value="3132803">Wire drawing and wire netting</option>
<option value="3132827">Coffee seed processing</option>
<option value="3132846">Aluminium utensils from  aluminium circles by  pressing only (dry  mechanical operation)</option>
<option value="3132848">Ayurvedic and homeopathic  medicines (without boiler)</option>
<option value="3132866">Carpentry &amp; wooden  furniture manufacturing  (excluding saw mill) with the  help of electrical (motorized)  machines such as electrical  wood planner, steel saw  cutting circular blade, etc</option>
<option value="3132868">Cement products (without  using asbestos / boiler /  steam curing) like pipe  ,pillar, jafri, well ring,  block/tiles etc.(should be  done in closed covered shed  to control fugitive emissions)</option>
<option value="3132871">Ceramic colour  manufacturing by mixing &amp;  blending only (not using  boiler and wastewater  recycling process)</option>
<option value="3132891">Digital printing on PVC  clothes</option>
<option value="3132894">Facility of handling, storage  and transportation of food  grains in bulk</option>
<option value="3132914">Heat treatment with any of  the new technology like  ultrasound probe , induction  hardening , ionization beam,  gas carburizing etc.</option>
<option value="3132946">Manufacturing of pasted  veneers using gas fired boiler  or thermic fluid heater and  by sun drying</option>
<option value="3132948">Oil mill Ghani and extraction  ( no hydrogenation /  refining)</option>
<option value="3132954">Phenyl/toilet cleaner  formulation and bottling</option>
<option value="3132973">Pulverization of bamboo and  scrap wood</option>
<option value="3132981">Ready mix cement concrete</option>
<option value="3133025">Soap manufacturing (hand  made without steam boiling  / boiler)</option>
<option value="3133032">Spice grinding (  &gt;20 hp  motor)</option>
<option value="3133034">Steel furniture without spray  painting</option>
<option value="3133037">Steeping and processing of  grains</option>
<option value="3133045">Chilling plant and ice  making without using  ammonia</option>
<option value="3133047">CO2 recovery</option>
<option value="3131012">Railway locomotive work  shop/Integrated road transport  workshop/Authorized service  centers Projects having Discharge of 100 KLD or more</option>
<option value="3131260">Non -alcoholic beverages(soft  drink) projects &amp; bottling of alcohol/non  alcoholic products having Quantity of waste water generation up to 100 KLD </option>
<option value="3133068">Cutting, sizing and polishing of  marble stone</option>
<option value="3131047">Pulp &amp; Paper ( waste paper based  units with bleaching process to  manufacture writing &amp; printing  paper)</option>
<option value="3130957">Pulp &amp; Paper ( waste paper based  without bleaching process to  manufacture Kraft paper)</option>
<option value="3133193">Surgical and medical products assembling  only (not involving effluent / emission  generating processes)</option>
<option value="3133071">Emery powder ( fine dust of  sand) manufacturing</option>
<option value="3133079">Oil and gas transportation  pipeline</option>
<option value="3133082">Seasoning of wood in steam  heated chamber</option>
<option value="3133084">Synthetic detergent  formulation</option>
<option value="3133088">Tea processing ( with boiler)</option>
<option value="3133092">Assembly of air coolers /conditioners  ,repairing and servicing</option>
<option value="3133101">Bailing (hydraulic press)of waste papers</option>
<option value="3133109">Biscuits trays etc from rolled PVC sheet (using  automatic vacuum forming machines)</option>
<option value="3133111">Blending and packing of tea</option>
<option value="3133113">Block making of printing without foundry  (excluding wooden block making)</option>
<option value="3133115">Chalk making from plaster of Paris ( only  casting without boilers etc. ( sun drying /  electrical oven)</option>
<option value="3133125">Electric lamp ( bulb) and CFL manufacturing  by assembling only</option>
<option value="3133128">Electrical and electronic item assembling (  completely dry process)</option>
<option value="3133135">Fly ash bricks/ block manufacturing</option>
<option value="3130916">Industries engaged in recycling /  reprocessing/ recovery/reuse of  Hazardous Waste under  schedule iv of HW( M, H&amp; TBM)  rules, 2008 - Items namely -  Spent cleared metal catalyst  containing copper,,  Spent cleared metal catalyst  containing zinc,,</option>
<option value="3130941">Fibre glass production and  processing (excluding moulding)</option>
<option value="3130943">Fire crackers manufacturing and  bulk storage facilities</option>
<option value="3130963">Manufacturing of paints  varnishes, pigments and  intermediate (excluding  blending/mixing)</option>
<option value="3130965">Organic Chemicals  manufacturing</option>
<option value="3130971">Asbestos and asbestos based  industries</option>
<option value="3130938">Sugar ( excluding Khandsari)</option>
<option value="3131003">Mining and ore beneficiation</option>
<option value="3131016">Yarn / Textile processing  involving any effluent/emission  generating processes including  bleaching, dyeing, printing and  colouring</option>
<option value="3131104">Compact disc computer floppy  and cassette manufacturing / Reel  manufacturing</option>
<option value="3131135">Printing or etching of glass sheet using  hydrofluoric acid</option>
<option value="3131153">Aluminium &amp; copper extraction from  scrap using oil fired furnace (dry  process only)</option>
<option value="3131182">Dairy and dairy products ( small scale)</option>
<option value="3131184">DG set of capacity &gt;1MVA but &lt; 5MVA</option>
<option value="3131187">Dry coal processing, mineral  processing, industries involving  ore sintering, pelletisating,  grinding &amp; pulverization</option>
<option value="3131215">Glass ceramics, earthen potteries and  tile manufacturing using oil and gas  fired kilns, coating on glasses using  cerium fluorides and magnesium  fluoride etc.</option>
<option value="3131217">Gravure printing, digital printing on  flex, vinyl</option>
<option value="3131238">Liquid floor cleaner, black phenyl,  liquid soap, glycerol mono-stearate  manufacturing</option>
<option value="3131267">Paints and varnishes (mixing and  blending)</option>
<option value="3131279">Printing press</option>
<option value="3131299">Thermocol manufacturing ( with  boiler)</option>
<option value="3132816">Dry cell battery ( excluding manufacturing  of electrodes) and assembling &amp; charging  of acid lead battery on micro scale</option>
<option value="3132850">Bakery /confectionery  /sweets products (with  production capacity &lt;1tpd  (with gas or electrical oven)</option>
<option value="3132874">Chilling plant, cold storage  and ice making</option>
<option value="3132877">Coke briquetting ( sun  drying)</option>
<option value="3132880">Cotton spinning and  weaving (small scale)</option>
<option value="3132899">Flour mills (dry process)</option>
<option value="3132917">Insulation and other coated  papers (excluding paper or  pipe manufacturing)</option>
<option value="3132951">Packing materials  manufacturing from non  asbestos fibre, vegetable fibre  yarn</option>
<option value="3132995">Rubber goods industry (with  gas operated baby boiler)</option>
<option value="3132999">Saw mills</option>
<option value="3133029">Spice grinding (upto  -20 HP  motor)</option>
<option value="3133040">Tyres and tube retreating  (without boilers)</option>
<option value="3133051">Distilled water ( without  boiler) with electricity as  source of heat</option>
<option value="3133059">Mineralized water</option>
<option value="3133066">Tamarind powder  manufacturing</option>
<option value="3133073">Flyash export, transport &amp;  disposal facilities</option>
<option value="3133075">Mineral stack yard / Railway  sidings</option>
<option value="3133094">Assembly of bicycles ,baby carriages and  other small non motorizing vehicles</option>
<option value="3133104">Bio fertilizer and bio-pesticides without using  inorganic chemicals</option>
<option value="3133118">Compressed oxygen gas from crude liquid  oxygen ( without use of any solvents and by  maintaining pressure &amp; temperature only for  separation of other gases)</option>
<option value="3133120">Cotton and woolen hosiers making ( Dry  process only without any dying / washing  operation)</option>
<option value="3131028">Tanneries</option>
<option value="3131064">Distillery ( molasses / grain /  yeast based)</option>
<option value="3131269">Ply wood manufacturing( including  Veneer and laminate) using the fuel such as wood or coal or any other authorized fuel with or without resin plant.</option>
<option value="3130996">Health -care Establishment / Projects having discharge of 100 KLD or More with or Without Incinerator</option>
<option value="3131194">Fermentation industry including  manufacture of yeast, beer,  distillation of alcohol having quantity of waste water discharge of 100 KLD or less </option>
<option value="3132830">Parboiled Rice Mills having quantity of waste water generation up to 100 KLD or fuel consumption up to 12 MTD or both</option>
<option value="3133132">Flavo  ured betel nuts production/ grinding (  completely dry mechanical operations)</option>
<option value="3133138">Fountain pen manufacturing by assembling  only</option>
<option value="3133140">Glass ampules and vials making from glass  tubes</option>
<option value="3133145">Glass putty and sealant ( by mixing with  machine only)</option>
<option value="3133147">Ground nut decorticating</option>
<option value="3133149">Handloom/ carpet weaving ( without dying  and bleaching operation)</option>
<option value="3133154">Leather cutting and stitching (more than 10  machine and using motor)</option>
<option value="3133158">Manufacturing of coir items from coconut  husks</option>
<option value="3133160">Manufacturing of metal caps containers etc</option>
<option value="3133163">Manufacturing of shoe brush and wire brush</option>
<option value="3133165">Medical oxygen</option>
<option value="3133171">Organic and inorganic nutrients ( by physical  mixing)</option>
<option value="3133174">Organic manure (manual mixing)</option>
<option value="3133176">Packing of powdered milk</option>
<option value="3133180">Paper pins and u clips</option>
<option value="3133182">Repairing of electric motors and generators (  dry mechanical process)</option>
<option value="3133185">Rope (plastic and cotton)</option>
<option value="3133187">Scientific and mathematical instrument  manufacturing</option>
<option value="3133189">Solar module non conventional energy  apparatus manufacturing unit</option>
<option value="3133191">Solar power generation through solar  photovoltaic cell, wind power and mini hydel  power (less than 25 MW)</option>
<option value="3185049">Screening Plant</option>
<option value="3130923">Industrial carbon including  electrodes and graphite blocks,  activated carbon, carbon black</option>
<option value="3130959">Coke making , liquefaction, coal  tar distillation or fuel gas making</option>
<option value="3130961">Manufacturing of explosives,  detonators, fuses including  management and handling  activities</option>
<option value="3130975">Basic chemicals and electro  chemicals and its derivatives  including manufacturing of acid</option>
<option value="3131005">Nuclear power plant</option>
<option value="3131010">Photographic film and its  chemicals</option>
<option value="3131021">Ship Breaking Industries</option>
<option value="3131032">Synthetic fibers including rayon  ,tyre cord, polyester filament  yarn</option>
<option value="3131072">Dismantling of rolling stocks ( wagons/  coaches)</option>
<option value="3131107">Flakes from rejected PET bottle</option>
<option value="3131110">Food and food processing including  fruits and vegetable processing</option>
<option value="3131137">Silk screen printing, sari printing by  wooden blocks</option>
<option value="3131140">Synthetic detergents and  soaps(excluding formulation)</option>
<option value="3131143">Thermometer manufacturing</option>
<option value="3131197">Ferrous and Non  - ferrous metal  extraction involving different  furnaces through melting, refining,  -processing, casting and alloy  re  making  -</option>
<option value="3131203">Fertilizer (granulation / formulation /  blending only)</option>
<option value="3131219">Heat treatment using oil fired furnace  ( without cyaniding)</option>
<option value="3131243">Manufacturing of iodized salt from  crude/ raw salt</option>
<option value="3131246">Manufacturing of mirror from sheet  glass</option>
<option value="3131250">Manufacturing of mosquito repellent  coil</option>
<option value="3131281">Reprocessing of waste plastic  including PVC</option>
<option value="3131284">Rolling mill (oil or coal fired) and cold  rolling mill</option>
<option value="3131286">Spray painting, paint baking, paint  shipping</option>
<option value="3131301">Tobacco products including  cigarettes and tobacco/opium  processes</option>
<option value="3131303">Transformer repairing/ manufacturing  ( dry process only)</option>
<option value="3131305">Tyres and tubes vulcanization/ hot  retreating</option>
<option value="3132818">Pharmaceutical formulation and for R  &amp; D purpose ( For sustained release/  extended release of drugs only and  not for commercial purpose)</option>
<option value="3132823">Synthetic rubber excluding  molding</option>
<option value="3132825">Cashew nut processing</option>
<option value="3132835">Foam manufacturing</option>
<option value="3132839">Industries engaged in recycling /  reprocessing/ recovery/reuse of  Hazardous Waste under schedule iv of  HW( M, H&amp; TBM) rules, 2008 - Items  namely -  Used Oil – As per specifications  prescribed from time to time.</option>
<option value="3132841">Industries engaged in recycling /  reprocessing/ recovery/reuse of  Hazardous Waste under schedule iv of  HW( M, H&amp; TBM) rules, 2008 - Items  namely -  Waste Oil ---As per specifications  prescribed from time to time.</option>
<option value="3132852">Bi-axially oriented PP film  along with metalizing  operations</option>
<option value="3132854">Biomass briquettes (sun  drying) without using toxic  hazardous wastes</option>
<option value="3132856">Blending of melamine resins  &amp; different powder,  additives by physical mixing</option>
<option value="3299944">Dismantling of E-waste </option>
<option value="3300130">LPG bottling plants </option>
<option value="3307819">Industries engaged in recycling/reprocessing/recovery/reuse of hazardous waste under schedule IV of HW(M,H&amp;TBM) rules,2008 items namely-Lead acid battery plates and other lead scrap/ashes/residues not covered under batteries Rules 2001.</option>
<option value="3131034">Thermal Power Plants</option>
<option value="3131040">Copper Smelter</option>
<option value="3131038">Aluminium Smelter</option>
<option value="3133053">Hotels (up to 20 rooms and  without boilers)</option>
<option value="3133057">Manufacturing of optical  lenses (using electrical  furnace)</option>
<option value="3133122">Diesel pump repairing and servicing (  complete mechanical dry process)</option>
<option value="3133130">Engineering and fabrication units (dry process  without any heat treatment / metal surface  finishing operations / painting)</option>
<option value="3131160">Brickfields ( excluding fly ash brick  manufacturing using lime process)</option>
<option value="3131205">Fish feed, poultry feed and cattle feed</option>
<option value="3132858">Brass and bell metal utensils  manufacturing from  circles(dry mechanical  operation without re-rolling  facility)</option>
<option value="3132862">Cardboard or corrugated box  and paper products  (excluding paper or pulp  manufacturing and without  using boilers)</option>
<option value="3132883">Dal Mills</option>
<option value="3131155">Automobile servicing, repairing and  painting Projects having quantity of waste water generation up to 100 KLD</option>
<option value="3131019">Chlor Alkali</option>
<option value="3300136">Sewage treatment plants having capacity less than 10 KLD </option>
<option value="3300142">Infrastructure development projects having overall liquid waste generation less than 100 KLD </option>
<option value="3300154">Automobiles manufacturing outsourcing all of the polluting activities. </option>
<option value="3300159">Refurbishing of used electrical and electronic equipments</option>
<option value="3300171">Glass 51ydel51es and vilas making from glass tubes</option>
<option value="3300195">Diesel generators sets having total capacity 1 MVA or less and equipped with acoustic enclosures along adequate stack height   </option>
<option value="3300204">Almirah, Grill Manufacturing without painting operation(Dry Mechanical process)  </option>
<option value="3300236">Industries engaged in recycling /reprocessing/ recovery/reuse of Hazardous Waste under schedule IV HW(M,H&amp;TBM) rules, 2008 -Items namely -paint and ink sludge / residues </option>
<option value="3300243">Spice girding (20 HP motor)</option>
<option value="3446537">Units engaged in  the activities of handling and management of Hazardous Waste as defined in Hazardous and other Wastes (M &amp; TM) Rules, 2016, other than those covered under any of the category of industrial sectors, such as use, treatment, processing, recovery, pre-processing, co-processing, utilization etc. of the hazardous and other wastes </option>
<option value="3703282">Leather foot wear and leather products (excluding tanning and hide processing  except cottage scale)</option>
<option value="3130993">Dyes and Dye  - Intermediates</option>
<option value="3131008">Pesticides (technical) (excluding  formulation)</option>
<option value="3131057">Petrochemicals Manufacturing (  including processing of  Emulsions of oil and water )</option>
</select>
-------------------------------------

3132830

http://hrocmms.nic.in/OCMMS/industryRegMaster/changeTypeOfIndustryBasedOnApplication/?id=4599935&industryTypeId=3132830

Steps to close the clarification on BMW applications
1. Login with Admin
2. Hit this url
http://hrocmms.nic.in/OCMMS/bioMedicalWaste/removeClarificationFromBmwApplicationSearch
3. Enter application id and click search
4. Click remove clarification button



21-11-2017:
1. Completed the functionality to close clarification on BMW from admin
2. Working on storing cafpin which is received from investharyana(80%)   
3. Resolved the live issue of industry who is registered as trader

-----------------------------------------------------------------------------------------------------
22-11-2017

1. CTO auto renewal MIS required - d
2. Problem in Approval rights
3. Changes in HWM Generation details
4. Add into online monitoring list
5. Technical error-M/s Indospace Industrial Park Badli Pvt. Ltd - application not found
6. Route application to rights region - route one group to another
7. Add Common facility to inspection
8. integrate auto-renew with hepc
9. Check why the status is not sent to hepc & check why my report to send is not working
10. cafpin store in our db

11. Fixed single window issue in doLoginAPi action in replace method of string

shiningwayindia93
neelam1234



----------------------------------------------------------------------------------------------------------
application no. - 4613318 CTE single window

setClearedRejectedStatusFalse
-----------------------------------------------------------------------------------------------------------

3334838 - unattented CTO - 16-08-2016
4269229 - note history application time


22-11-2017:
1. Completed cafpin store in our db
2. Fixed on live issue HEPC
3. Working on autoRenew MIS(70%)
---------------------------------------------------------------------------------------------------------

<form action="http://hrocmms.nic.in/api/webapi/hrocmms/login/" id="myform" method="GET" class="ng-pristine ng-valid">
<input name="uname" id="uname" value="Jindal" type="hidden"> 
<input name="investorname" id="investorname" value="Neelam" type="hidden"> 
<input name="address" id="address" value="#958, house no. 958, panchkula" type="hidden"> 
<input name="useremail" id="useremail" value="shiningwayindia93@gmail.com" type="hidden"> 
<input name="country" id="country" value="India" type="hidden"> 
<input name="state" id="state" value="Haryana" type="hidden">
<input name="city" id="city" value="Panchkula" type="hidden"> 
<input name="niccode" id="niccode" value="" type="hidden">
<input name="pannumber" id="pannumber" value="" type="hidden">
<input name="gstnumber" id="gstnumber" value="" type="hidden">
<input name="aadhar_number" id="aadhar_number" value="" type="hidden">
<input name="proposedbuilt_up_area" id="proposedbuilt_up_area" value="" type="hidden"> 
<input name="mobile" id="mobile" value="9501660091" type="hidden"> 
<input name="totalproposedprojectarea" id="totalproposedprojectarea" value="2" type="hidden"> 
<input name="totalpurposedemployment" id="totalpurposedemployment" value="10" type="hidden"> 
<input name="total_project_cost" id="total_project_cost" value="1.1975" type="hidden"> 
<input name="project_site_district" id="project_site_district" value="Panchkula" type="hidden"> 
<input name="landzoneuse_type" id="landzoneuse_type" value="Utilities" type="hidden"> 
<input name="businessentity" id="businessentity" value="Shining Way India Stone Crusher" type="hidden">
<input name="projecttype" id="projecttype" value="New Project (New Site)" type="hidden"> 
<input name="projectid" id="projectid" value="88f4e665-e8cf-406f-817e-ae1bd5a70afc" type="hidden">
<input name="serviceid" id="serviceid" value="b27b79b9-a3ec-4eb1-9f70-3e275dd13cd6" type="hidden">
<input name="projectserviceid" id="projectserviceid" value="91bc7cdf-75e7-486f-81f8-3cea6d1f0c89" type="hidden"> 
<input name="cafpin" id="cafpin" value="1217946601" type="hidden"> <input id="fillform" value="Fill Service Form" type="submit"></form>

23-11-2017:
1. Resolved live issue home page redirect
2. Interview
3. Working on HWM changes(30%)


24-11-2017:
1. Resolved live issue to fix forget password issue.
2. Working on cto auto-renew changes(30%)



27-11-2017:
"For upload certificate"

1. Point 7 - current date
2. Fetch last inspection report through draw - if not found
3. C.A. Certificate regarding capital investment cost w.r.t. land building, plant and machinery of the proposed project.
4. Full name of certificates
5. officer side - any changes except the documents



def caCertificateFile = request.getFile('caCertificate')
def analysisReportForAirFile = request.getFile('analysisReportAir')
def analysisReportForWaterFile = request.getFile('analysisReportWater')
def analysisReportForNoiseFile = request.getFile('analysisReportNoise')
def undertakingFile = request.getFile('undertaking')



27-11-2017:
1. Working on autoRenew changes as specified by HSPCB(50%)


28-11-2017
autoRenew application no. - 
application no. - 145296


-- auto-generated definition
create table application_auto_renew
(
  id bigint not null
    constraint application_auto_renew_pkey
      primary key,
  version bigint not null,
  application_id bigint not null
    constraint application_auto_renew_application_id_key
      unique
    constraint fk3301ea4c15ed9f5b
      references ind_application_details,
  c01 varchar(255) not null,
  c02 varchar(255) not null,
  c03 varchar(255) not null,
  c04 varchar(255) not null,
  c05 varchar(255) not null,
  c06 varchar(255) not null,
  c07 varchar(255) not null,
  c08 varchar(255) not null,
  c09 varchar(255) not null,
  c10 varchar(255) not null,
  c11 varchar(255) not null,
  c12 varchar(255) not null,
  c13 varchar(255) not null,
  c14 varchar(255) not null,
  c15 varchar(255) not null,
  date_created timestamp not null,
  last_updated timestamp not null
)
;


CTO autoRenew application no. - 146061 - 146061
Live issue:
17-11-2017 - payment
20-07-2017 - note history
4368281 - 

-----------------------------------------------------------------------------------
bmw
4281548
vinay
system@1


06/11/2017 13:53:49
06/11/2017 15:06:16
06/11/2017 15:06:16
06/11/2017 15:06:17

-----------------------
live isssue clarification in BMW but close after approval
4240180
----------------------
live issue note history 30-11-2017
4248264 - hwm



-----------------------------------------
30-11-2017:
1. Resolved live issue in BMW note history
2. Completed changes in approval rights of BMW
3. Updated live war
1. Working on autoRenew changes(70%)








































import java.util.Scanner;
import java.util.ArrayList;
class TestClass {
    static int findMaxLengthOf1(StringBuffer s){
        int length = 0;
        int maxLength = 0;
        int sizeOfString = s.length();
        for(int i = 0; i < sizeOfString; i++){
            if(s.charAt(i) == '1'){
                length++;
            }else{
                if(length > maxLength){
                    maxLength = length;
                }
                length = 0;
            }
        }
        return maxLength;
    }
    public static void main(String args[] ) throws Exception {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int k = sc.nextInt();
        ArrayList<String> output = new ArrayList<String>();
        StringBuffer s = new StringBuffer(sc.next());
        String query[] = new String[k];
        for(int i = 0; i < k; i++){
            query[i] = sc.next();
        }
        for(int i = 0; i < k; i++){
            if(query[i].length() == 1){
                System.out.println(findMaxLengthOf1(s));
            }else{
                int index = Integer.parseInt(query[i].substring(2));
                s.setCharAt(index,'1');
            }
        }
        
        

    }
}




10 4 
7 1 4 3 1 6 4 2 5 1 
3 4 
1 2
2 7
6 7


0
1
1
2


-----------------------------------------------
04-12-2017:

BMW application no. - 143395
HWM application no. - 142226


04-12-2017:
1. Completed Auto Renew at industry side when clarification is raised on application.
2. Completed  In BMW and HWM to remove check to close application after approval/refusal even if clarification is reply is not made.
3. Working on auto renew at officer side(50%).


05-12-2017:
application date issue:
4368281

--------------------------------------------------------------------------------------
CAF PIN - service form edited status not sent-->

1477568790 - e2cb0995-a2ad-414c-88df-e8561b490f0b(project id) - b27b79b9-a3ec-4eb1-9f70-3e275dd13cd6(service id) -
application no. - 4623668 - application date - 27/10/2017 10:02 AM 

6031433006 - 0e358720-6080-41d5-83dc-5496b80bb396(project id) - b27b79b9-a3ec-4eb1-9f70-3e275dd13cd6(serviceid)
application no. - 4623332 - application date - 27/10/2017 15:57 PM


8505459064 - fe3a5e71-a45c-4276-818b-4e7c329dcc8e(project id) - b27b79b9-a3ec-4eb1-9f70-3e275dd13cd6(serviceid) 
application no. - 3981342 - application date - 13/11/2017 16:18 PM

5211199456 - ad1aca5d-1c37-4821-93b2-2f4b825034e9(project id) - b27b79b9-a3ec-4eb1-9f70-3e275dd13cd6(service id)
application no. - 4634367 - application date - 27/10/2017 12:01 PM


1. http://hrocmms.nic.in/api/webapi/hrocmms/downloadCertificate/?projectid=e2cb0995-a2ad-414c-88df-e8561b490f0b&serviceid=b27b79b9-a3ec-4eb1-9f70-3e275dd13cd6

2. http://hrocmms.nic.in/api/webapi/hrocmms/downloadCertificate/?projectid=0e358720-6080-41d5-83dc-5496b80bb396&serviceid=b27b79b9-a3ec-4eb1-9f70-3e275dd13cd6

3. http://hrocmms.nic.in/api/webapi/hrocmms/downloadCertificate/?projectid=fe3a5e71-a45c-4276-818b-4e7c329dcc8e&serviceid=b27b79b9-a3ec-4eb1-9f70-3e275dd13cd6

4. http://hrocmms.nic.in/api/webapi/hrocmms/downloadCertificate/?projectid=ad1aca5d-1c37-4821-93b2-2f4b825034e9&serviceid=b27b79b9-a3ec-4eb1-9f70-3e275dd13cd6
------------------
application no. - 4619463

----------------------
local projectid - 3795e7b5-e4a9-48ef-bd1c-3aa4ef677ece 
application no. - 143486 143532
serviceid - 3795e7b5-e4a9-48ef-bd1c-3aa4ef677ece

localhost:8080/HSPCB/industryRegMaster/downloadCertificateApi/?projectid=3795e7b5-e4a9-48ef-bd1c-3aa4ef677ece&serviceid=b27b79b9-a3ec-4eb1-9f70-3e275dd13cd6

Certificate1
Certificate1

05-12-2017:
1. Resolved live issue in note history dat
2. Resolved 'service form edited' status sent to HEPC
3. Working on autoRenew changes at officer side(70%)

------------------------------------------------------
live issue: 06-12-2017
Date: 06-12-2017 
Note history show 05-12-2017 received date but message to chairman show 100 days is crossed.
1. Application no. - 4269725 - ANCALIMA LIFESCIENCES LTD. 
Date :   05/12/2017 16:18:19
2. Application no. - 4268148 - BAJAJ INDUSTRIES
Date :   05/12/2017 12:03:04


Issue : BMW authorization certificate
Issue: Rights not showing to RO

Details = Ruhil Promoters Pvt. Ltd.
caf pin = 7243399478 
application no. = 4700235




-----------------------------------------------------------
CertificateForWater
CertificateForHwm
CertificateForAirDegi
CertificateForWaterDegi
CertificateForHwmDegi
RefusalCertificateForBoth
CertificateForAir
CertificateForHwm
DigiCommonCtoCertificate
Certificate
Certificate1
CertificateForExtension - added
CertificateForExtenDegi - added 
CertificateForHwmDegi 


06-12-2017:
1. Fixed Download Certificate through api for CTE Exten on HEPC.
2. Working on online monitoring (50%)



pramid 2014
time machine 
flatliners
das experiment


1.  bmw issues - certificate
2.  inspection add common facility
3.  inpection diff module
4.  temp draw washout
5.  hwm scheduler 3 add
6.  bmw approval rights problem
7.  digital sign
8.  dashboard add, cte
9.  bmw format
10. cto renewal integration
11. hide bmw and hwm
12. sms chairman
13. mis error
14. rfd report
15. change group of application
16. inspection module


appid11
142187



4726582

4761730
------------------------------------------------------
08-12-2017:
userid: 17JHA4548402
Balaji foundry issue: - 4548432 <-- application no.
5a193653-54e7-46c4-b887-a7bbb5482965
5a193653-54e7-46c4-b887-a7bbb548296

http://hrocmms.nic.in/OCMMS/industryRegMaster/updateProjectIdForGivenUserId?id=17JHA4548402&projectid=5a193653-54e7-46c4-b887-a7bbb5482965


http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4548432
http://hrocmms.nic.in/OCMMS/industryRegMaster/setClearedRejectedStatusFalse/?applicationId=4548432

nitesh@1




bioCert1
66
1245
1343



bioCert2
1353

15PIT2071560
rkrayon@123


-------------------------
local bmw application -146281 
local bmw application - 146316 

noofbeds
noOfBedsCbmwtf


name="hcfType"


ironFist - 133889
local bmw application no. - 146334 


PdfReader reader = new PdfReader(...);
AcroFields acroFields = reader.getAcroFields();
List<String> signatureNames = acroFields.getSignatureNames();



local hwm application no. - 146386

bmw
4351484
Goodyear India Limited

4237578
HSPCB041
pollution@777



12-12-2017:
1. Fixed live issue in BMW application
2. Completed digital Sign work
3. Merge and tested HWM Scedule work
4. Merge and tested autoRenew MIS


Find the maximum number of edges you can remove from the tree to get a forest such that each connected component of the forest contains an even number of nodes.

10 9
2 1
3 1
4 3
5 2
6 1
7 2
8 6
9 8
10 8


---------------------------------
13-12-2017:
1. auto renew integrate hepc
2. cte renewal integrate
3. prepare and send excel of service form edited
4. create a table that keep track of all the open comment status
5. create a scheduler to automate the process
6. Why status is not sent

-------------------------------------------
service form edited status not sent:

1. 
indUser - 17FDBB3984280
date created - 2017-12-09 16:45:24.744  
application id - 4198251
projectid - 6f3e9a9f-dad7-4a86-9a3a-c675dba32842
serviceid - 6bd18359-09f4-4c71-85d9-e4f313ccfb8d  
application for - CTO

application received date - 25/05/2017 12:03:03

2. 
indUser - 15PAN1878218
date created - 2017-11-17 13:56:23.835   
application id - 4416953
projectid - b1f335c4-aec4-46b8-aecf-9bbc1ecde778  
serviceid - 6bd18359-09f4-4c71-85d9-e4f313ccfb8d  
application for - CTO

application received date - 04/08/2017 18:10:33

3.
indUser - 17FDBD3843226
date created - 2017-12-04 12:15:37.033
application id - 3843250
projectid - 9ba175b1-dd58-4a8d-85b7-233d0be5779c  
serviceid - b27b79b9-a3ec-4eb1-9f70-3e275dd13cd6 
application for - CTE

application received date - 08/02/2017 14:56:19

4. 
indUser - 17GUSO4377453
date created - 2017-12-01 18:00:24.515
application id - 4474593
projectid - e383fbd7-994f-4075-a69f-428cf7cf1321 
serviceid - 6bd18359-09f4-4c71-85d9-e4f313ccfb8d 
application for - CTO

IT IS GRANTED

application received date - 28/08/2017 12:46:20

5.
indUser - 13KAR143855
date created - 2017-11-23 16:58:50.322
application id - 4303990
projectid - 8f99515e-dbdf-4908-aee5-2ab5e9a66e45
serviceid - 6bd18359-09f4-4c71-85d9-e4f313ccfb8d
application for - CTO

application received date - 30/06/2017 13:37:48

6.
indUser - 14SON1119346
date created - 2017-11-24 12:50:19.444
application id - 4158017
projectid - 5f911dd3-1465-4ea6-94b3-f98dc06c5e39
serviceid - 6bd18359-09f4-4c71-85d9-e4f313ccfb8d
application for - CTO

application received date - 05/05/2017 17:10:57

7.
indUser - 14ROH1069051
date created - 2017-12-06 19:40:09.336
application id - 3895812
projectid - 09e8118c-c57f-4eb5-99f3-1050fdadfec6
serviceid - 6bd18359-09f4-4c71-85d9-e4f313ccfb8d
application for - CTO

application received date - 27/02/2017 16:47:24



13-12-2017:
1. Prepared the query to give provide list of projectid whose service form edited must be sent
2. Working on hepc report to resolve why application status is not sent 
3. Updated live war with hwm schedule, auto renew mis, and digital sign work


--------------------------------------------------------------------------------------
14-12-2017:

String roleId
String roleName
String officerName
String groupId
String groupName
Date pendingSince
String pendingWith


--------------------------------------------------------


local application no. - 146061


14-12-2017:
1. Completed auto renew officer side.
2. Resolved Live issue to edit industry profile having reserved profile.
3. Merged and tested route application to different group.


cto air
4577153


#6bada5">CTE<
#758eb7">CTO Auto Ren
HARI PATH LAB
--------------------------------------------------------------------------
18-12-2017

---------------------------CTE--------------------------

1. projecid - 77264d4e-b974-4da6-8cda-d04335962b6d
   cafpin - 3299074451
   application id - 4588548

   http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4588548

2. projectid - 645f0730-a97b-4ebf-85df-aa1aed399cba
   cafpin - 5506775984
   application id - 4588923

   http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4588923

3. projectid - ef98fc2c-4ea2-4788-9b67-afb7abb127f0
   cafpin - 3532333732
   application id - 4596175

   http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4596175

4. projectid - 02dff131-c41a-4908-b70b-ac351a8fa1b0
   cafpin - 9376814901
   application id - 4596261

   http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4596261

5. projectid - 78d733ef-8957-4cb6-a9b8-1a7ec12af967
   cafpin - 2279697463
   application id - 4599935

   http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4599935  

6. projectid - 82a7e102-a4b4-4e63-810f-dbc2a4859010
   cafpin - 1475239340
   application id - 4602254

   http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4602254

7. projectid - 56cf902a-310c-4bb6-bcd3-29ac49cfc113
   cafpin - 6107817073
   application id - 4604485

   http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4604485        

8. projectid - 43fc0f16-6909-4703-923c-6ba97accfe77
   cafpin - 4772024628
   application id - 4605553

   http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4605553

9. projectid - 2f56f536-5e08-41e7-a21f-bf1274848883
   cafpin - 5753205322
   application id - 4610073

   http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4610073

10. projectid - d0764f52-12de-4776-9d80-f5a6603d9f4c
    cafpin - 5071600594
    application id - 4611005

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4611005

11. projectid - 75825187-ca4a-4481-9874-20dfc95216ae
    cafpin - 2477957572
    application id - 4611747

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4611747    

12. projectid - cb456a3b-1ed3-46e9-b343-6544f92c03a3
    cafpin - 1265365289
    application id - 4623307

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4623307    

13. projectid - 99e0d3d3-4cca-4d47-878a-b3222c66c55a
    cafpin - 1315144199
    application id - 4761922

    It is pending at industry side
    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4761922    

14. projectid - fea64697-b12f-4759-94e5-b3f708c5d8d3
    cafpin - 7981869897
    application id - 4589498

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4589498    


15. projectid - 4b97e0c3-6525-4885-8ddf-b1338e3ee6d5
    cafpin - 513437983
    application id - 4616840

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4616840    


16. projectid - e56aedff-dc26-4c72-9ab7-11b4bbbb1455
    cafpin - 3407081570
    application id - 4617740

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4617740    

17. projectid - 82e2cbb1-787c-4eef-ab3b-ec6c74894c6d 
    cafpin - 2202883331
    application id - 4617996

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4617996    

18. projectid - 4f10d878-285e-4fab-9d31-62d013688134
    cafpin - 2829079361
    application id - 4616727

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4616727    


19. projectid - 08104d27-aa9f-4348-ad36-0496693435db
    cafpin - 8450588029
    application id - 4614081

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4614081    

20. projectid - a9b979be-db77-4542-b879-59a10b39bd5e
    cafpin - 9930648856
    application id - 4634257

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4634257    


21. projectid - 6fdb3200-f843-4142-92ce-f7e8a5475290
    cafpin - 4340594886
    application id - 4639525

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4639525


22. projectid - 9069ba3d-4fa7-416a-a4dd-b8ac9c36a0e9
    cafpin - 6289502038
    application id - 4616838

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4616838    

23. projectid - e7ef0b9c-a911-4ab1-8a73-769e7c1ebe9d
    cafpin - 1082587860
    application id - 4640081

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4640081    

24. projectid - 2f376345-af68-472e-b75b-91b344dfb7aa
    cafpin - 9798599014
    application id - 4643596

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4643596    


25. projectid - adb8c4a6-61a5-41c7-97a0-b86ea5c5e297
    cafpin - 6100843511
    application id - 4651831

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4651831    


26. projectid - 4690bb7d-5cec-44b0-9f7f-22276e957455
    cafpin - 3779267766
    application id - 4654298

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4654298    


27. projectid - f31e2342-7eb5-4241-bc55-def670010efa
    cafpin - 5300064567
    application id - 4620043

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4620043    


28. projectid - 10668a3a-dc2a-4304-82a7-9a9eff0d22c7
    cafpin - 1604972247
    application id - 4609089

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4609089    

29. projectid - 286e085d-0b60-4bb4-96d1-aef649c1b59a
    cafpin - 7969079326
    application id - 4662855

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4662855    

30. projectid - 68d70828-0b19-41bf-bd84-bce70c6d1100
    cafpin - 4216549583
    application id - 4641376

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4641376    

31. projectid - 6470d67c-c939-47fb-ab2b-445f07f28bc1
    cafpin - 9286618672
    application id - 4602392

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4602392    

32. projectid - 943db30a-4eec-4e8f-aa37-afff4cd2fc48
    cafpin - 2737654420
    application id - 4623220

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4623220    


33. projectid - 55890f9b-0f65-4c7d-81f6-7db35e8a27b5
    cafpin - 8291552514
    application id - 4612470

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4612470    


34. projectid - d61f1e02-a631-4000-81b4-12e5e635e7d9
    cafpin - 3334620937
    application id - 4641495

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4641495    

35. projectid - 25fbb32c-be45-4411-9385-a9069d2b4c90 
    cafpin - 4671465346
    application id - 4651538

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4651538    

36. projectid - b97e3bd5-5291-4d27-8bd5-99f1624d457a
    cafpin - 7566067017
    application id - 4603150

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4603150    

37. projectid - 185f7752-42a1-42af-b65e-b4e670df40f0
    cafpin - 6434247915
    application id - 4590154

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4590154    


38. projectid - d909e3b7-c85f-409b-ad7c-78b657858e81
    cafpin - 5813327205
    application id - 4588760

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4588760    


39. projectid - 392d9ea6-8ed8-4bbd-ab2a-9dc0b422de69
    cafpin - 1049169969
    application id - 4570886

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4570886    

40. projectid - 2d9efa62-61e8-4cec-8bae-681192c43c83
    cafpin - 4283634860
    application id - 4571525

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4571525    

41. projectid - 23718762-3bfa-415f-b783-ae73e6bdd122
    cafpin - 557569615
    application id - 4573060

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4573060    

42. projectid - c87b7814-7020-4a50-a0f2-83659bc6a3f4
    cafpin - 1342483987
    application id - 4574049

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4574049    

43. projectid - ab7d7752-1c5b-444f-a996-7db7624544e2
    cafpin - 5644253615
    application id - 4574696

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4574696    


44. projectid - d77fe47f-ea0f-4ea6-8a33-0c4a74e83d61
    cafpin - 4842899172
    application id - 4656296

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4656296    

45. projectid - bf0fb552-35b3-44a1-b7ce-3fea44c8792e
    cafpin - 7351955372
    application id - 4574964

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4574964    

46. projectid - 01e91771-d63a-459f-8576-c91c7b70a23b
    cafpin - 2095663808
    application id - 4576633

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4576633    

47. projectid - 1e7287b2-3c5c-4a4b-bcdc-0f3557cfc2b6
    cafpin - 2438534393
    application id - 4720335

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4720335    


48. projectid - b8ebb4e1-b450-4388-9690-5231eef74aea
    cafpin - 1286321865
    application id - 4713593

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4713593    


49. projectid - 010b1b5b-b6dd-47dc-b3b9-f162158586c0
    cafpin - 6566744289
    application id - 4579448

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4579448    

50. projectid - 541544d3-3378-4305-a09f-cff5156bb0dc
    cafpin - 2167096951
    application id - 4579599

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4579599    

51. projectid - e83bffe2-c692-4185-8c7a-e3cbdaf3ef84
    cafpin - 370612792
    application id - 4581274

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4581274    

52. projectid - 89a04720-a343-456a-85ab-6860014f4e6b
    cafpin - 3150223517
    application id - 4582392

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4582392    

53. projectid - ed9b476d-cf95-46bb-85eb-1e99152e2684
    cafpin - 1832930943
    application id - 4582568 

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4582568    

54. projectid - 6a2b53bb-b3c1-4301-af4a-fa84c1994427 
    cafpin - 6368215506
    application id - 4583858

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4583858    

55. projectid - 7e4f4ed0-a86c-44cd-8919-65d4f4fb55fd
    cafpin - 4968308662
    application id - 4586290

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4586290    

56. projectid - 10d219d5-a8c8-4dd0-adab-79429fa8e8b3
    cafpin - 0428418114
    application id - 4586133

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4586133    

57. projectid - b654947f-817e-4530-aa35-f2d0e79107d5
    cafpin - 9802031544
    application id - 4587079

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4587079    

58. projectid - c9cb12fa-bb17-4f68-8ed0-ba1d7dbdb17f
    cafpin - 8782758635
    application id - 4587895

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4587895  

59. projectid - a2cae41d-473d-4b40-9761-adecd791ab92
    cafpin - 8328606858
    application id - 4586959

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4586959    

60. projectid - 4dd8ab6a-5423-44f3-9981-79222e45f053
    cafpin - 3234260196
    application id - 4588248

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4588248    

61. projectid - bfe3cf11-8d02-41a5-b740-f867655c2dd9
    cafpin - 5611422804
    application id - 4746543

    Application is pending
    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4746543    

62. projectid - f1c9a11c-5021-4d50-84e6-99ce62f977be
    cafpin - 8084449836
    application id - 4733418

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4733418 

63. projectid - 5124932c-0433-403c-b664-f1dca04ee129
    cafpin - 7936681406
    application id - 4779934

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4779934  

64. projectid - 7f6d1171-57fc-468f-b085-9142aa6190fe
    cafpin - 4031154769
    application id - 4791418

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4791418    

65. projectid - 5f911dd3-1465-4ea6-94b3-f98dc06c5e39
    cafpin - 7557566575
    application id - 4726938

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4726938



-------------------- CTO ------------------------        

01. projectid - 093d9db4-a5eb-4e40-9fe5-8e5035dc8a77
    cafpin - 1809905325
    application id - 4639582

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4639582    

02. projectid - 82b8de25-143e-45eb-9676-aaaa9dc6df84
    cafpin - 6843027494
    application id - 4587178

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4587178 

03. projectid - 1fcfbd86-31ce-4511-aeb6-61264bbc8a9d
    cafpin - 9912114977
    application id - 4639870

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4639870    

04. projectid - 59ee0f35-df50-4269-a561-ecc5388f4aa8
    cafpin - 9688999799
    application id - 4645241

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4645241    

05. projectid - c81fc1d6-124d-435c-8146-46c5e00f95c1
    cafpin - 4787492066
    application id - 4640885

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4640885    

06. projectid - fbd7b896-2b89-46af-8a10-c94b357ec7f8
    cafpin - 7422105733
    application id - 4640964

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4640964  

07. projectid - a70a956b-2c34-4d5d-9c52-c3a2bc0f69c7
    cafpin - 6000677696
    application id - 4775068

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4775068    

08. projectid - 974333dc-81d1-43e8-a161-a539136111b0
    cafpin - 7183175675
    application id - 4640014

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4640014 

09. projectid - 44d23727-8ae1-4877-8c76-43f621cbffd9
    cafpin - 5671553910
    application id - 4618342

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4618342    

10. projectid - c24827bc-b8e8-4b9c-ad4a-61567f21ba04
    cafpin - 5018639241
    application id - 4620646

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4620646    

11. projectid - 2b74ba35-a8fa-4744-a352-cf2ecd559476
    cafpin - 5598652650
    application id - 4639434

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4639434    

12. projectid - b80d756f-668d-4c83-84b5-70bb14a58161
    cafpin - 1737818201
    application id - 4576521

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4576521

13. projectid - 9b127df1-29e4-4c6d-aa16-072181275ed7
    cafpin - 1688432545
    application id - 4562194

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4562194    

14. projectid - 17804cf5-43c2-49aa-829b-67cc4a88d201
    cafpin - 8013356387
    application id - 4562327

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4562327 

15. projectid - 0673a219-d686-4b8c-9dee-766808353cc2
    cafpin - 9219698055
    application id - 4561901

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4561901    

16. projectid - 003b990f-c753-4267-ac92-712182f8f545
    cafpin - 1077920061
    application id - 4576546

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4576546    

17. projectid - ba2fef35-7162-4899-8d7d-cf595958599d
    cafpin - 1334125049
    application id - 4577468

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4577468    

18. projectid - b4d9fa1c-6987-4b00-997f-53e9ef2f1d61
    cafpin - 7270271407
    application id - 4577528

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4577528

19. projectid - 4329c75a-2f5f-4da5-9bf3-ac9be95b63aa
    cafpin - 1468957557
    application id - 4571889

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4571889    

20. projectid - 71e0e4b2-ff49-494b-99d0-1302296f6a31
    cafpin - 7528658953
    application id - 4583893

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4583893 

21. projectid - d364f15f-542d-464e-9d1c-92aab0f802f1
    cafpin - 3353417800
    application id - 4582591

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4582591    

22. projectid - f18eaedd-0034-4da4-906f-cc95418ec5a7
    cafpin - 4992731015
    application id - 4584271

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4584271    

23. projectid - 5407be91-ee70-4a02-9551-fc948098d955
    cafpin - 7912134210
    application id - 4586966

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4586966    

24. projectid - 65ccc7bd-8920-4350-a348-38c648d4ec34
    cafpin - 1399913350
    application id - 4587746

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4587746                

25. projectid - 16658d2c-5156-45ec-a6d9-74093245e873
    cafpin - 8513299594
    application id - 4589971

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4589971  

26. projectid - bc70698d-bda6-494f-9ecc-3d046f793194
    cafpin - 2727287467
    application id - 4594814

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4594814                  

27. projectid - 9fe51eef-352a-4d94-892f-5280c78bb65b
    cafpin - 4192423531
    application id - 4602384

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4602384                  

28. projectid - 2c1480c5-41aa-45f4-937e-47d333ba69a7
    cafpin - 6394240364
    application id - 4603174

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4603174  

29. projectid - 8d166830-b371-418f-80a2-9024112baae8
    cafpin - 8849223868
    application id - 4603275

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4603275                  

30. projectid - 9fe51eef-352a-4d94-892f-5280c78bb65b
    cafpin - 4192423531
    application id - 4602384

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4602384                  


31. projectid - 147c8def-c918-4f7c-82f1-63a6a169e9f8
    cafpin - 5429454645
    application id - 4610824

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4610824  

32. projectid - 796a8196-585f-40e2-86ac-f3270178a851
    cafpin - 5628545673
    application id - 4617178

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4617178                  

33. projectid - 7b3bda97-fc34-4f8e-8ae4-c50a62274e5d
    cafpin - 3278024470
    application id - 4613692

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4613692                  

34. projectid - 67487316-14fb-4724-a41b-f6e7076d6019
    cafpin - 9340790552
    application id - 4640922

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4640922  

35. projectid - dd460a96-1649-41b1-987e-39ab158cf6ea
    cafpin - 9677174926
    application id - 4788959

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4788959                  

36. projectid - 36fbfaad-25a7-4462-8fba-209f8ee89da1
    cafpin - 7873591729
    application id - 4794470

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4794470    


37. projectid - 26481a33-f291-499c-b43d-f230ce3d0dfc
    cafpin - 899948087
    application id - 4795154

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4795154  

38. projectid - 3aaf92ae-fac7-4a3b-8b4b-fbc663cb9007
    cafpin - 3882464593
    application id - 4796664

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4796664     


---------------- HWM -----------------                 

01. It is actually for CTO
    projectid - f18eaedd-0034-4da4-906f-cc95418ec5a7
    cafpin - 4992731015
    application id - 4584271

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4584271                  

02. projectid - f6a10d7d-39dc-4a42-afb6-d9d506f085dc
    cafpin - 2805811798
    application id - 4640024

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4640024  

03. projectid - 093d9db4-a5eb-4e40-9fe5-8e5035dc8a77
    cafpin - 
    application id - 4639582

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4639582                  

04. projectid - 374812eb-ef4a-4c2f-9cee-f0c5980f7712
    cafpin - 7326121904
    application id - 4655925

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4655925                  

05. projectid - 9ba175b1-dd58-4a8d-85b7-233d0be5779c
    cafpin - 3402966773
    application id - 3843250 
    serviceid - b27b79b9-a3ec-4eb1-9f70-3e275dd13cd6  
    application for - CTE

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=3843250                  

06. projectid - bf1c08d4-3003-4ce8-852e-db382819cbf3
    cafpin - 3635596283
    application id - 4582689

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4582689  

07. projectid - e2989124-fb56-4af8-bdf2-060727a5ed66
    cafpin - 3025045149
    application id - 4670296

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4670296                  

08. projectid - 2b74ba35-a8fa-4744-a352-cf2ecd559476
    cafpin - 5598652650
    application id - 4639434

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=                  

09. projectid - cfd9793c-626f-4e60-bfbe-9a92e160eca0
    cafpin - 856229928
    application id - 4763956

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4763956                  

10. projectid - 3aaf92ae-fac7-4a3b-8b4b-fbc663cb9007
    cafpin - 3882464593
    application id - 4796664

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4796664

------------- BMW ----------      

01. projectid - 7b3bda97-fc34-4f8e-8ae4-c50a62274e5d
    cafpin - 3278024470
    application id - 4613692

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=4613692                  

02. projectid - 
    cafpin - 
    application id - 

    http://hrocmms.nic.in/OCMMS/industryRegMaster/setFormEditedStatusFalse/?applicationId=   

----------
service form edited not sent because required service not on hepc
1. 4198251
2. 4416953
3. 3843250
4. 4474593
5. 4303990
6. 4158017
7. 3895812
8. 4794470                   
                  
                 
18-12-2017:
1. Completed view form for auto renew MIS
2. Completed hide Manually route application to other group link for officers.
3. Merged HWM prev cto/cte and dashboard code and provided test link.
4. Working on send status to HEPC(50%)



hazardeousWasteAuthApp/searchApp
hwm application no. - 145874

19-12-2017:
1. Live issue HEPC CTO application in-progress not able to edit consent to date
2. Started working on CTO auto renew integration
3. Merged 17 category code in live code



induser - industry reg master - 582706
application no. - 4821902


16GUNO3182550
password - graco@123
industry reg master universal - 3182550




146640

20-12-2017
1. Checked and resolved BMW HCF is selected but not able to save in-progress.
2. Working on auto-renew integration(60%)
3. Fixed 17 category code and updated on live.

4786516

21-12-2017:
1. Updated the agenda of meeting and work status.
2. Changes in popFeeOtherDetails - added performance security fee
3. Working on issue that autoRenew application is not visible at industry side



3182585
3596643 -- > CTO pre

4863728

26-12-2017:
1. Checking and try to resolve payment issue.
2. Merged and tested caf pin search in consent, bmw and hwm
3. Merged and tested manually route application to other group for bmw and hwm

----------------------------------------------------------------------------------------------------------
27-12-2017:

to do:
1. complete the bmw bedded in officer side. (done)
2. update live war to test.
3. complete the autoRenew testing and provide test link.
4. fix the service form not edited that is created by me.
5. update added column in biomedical waste test and live server.


projectid = 7cdd6bc3-3fad-40b9-a159-39a3fa535efb
cafpin = 8897336814


previous one = 7897c082-6423-42e8-bfcb-f2f2d429a339
previous caf pin = 1910152357
13GUSO461285
http://hrocmms.nic.in/OCMMS/industryRegMaster/updateProjectIdForGivenUserId?id=13GUSO461285


4883757

146316

4584396



01-01-2017:
1. Complete the 17 category code.
2. send the status of the applications.
3. write the scheduler.


app no. - 4802624
app no. - 4803535 


CTE application status not sent
4802624

CTO
4726739

CTO
4650747


indUse
14PAL978298

14PAN149870

18PAN691132
36967



CTE renewal -
caf pin - 1798607057
application no. - 4793614
projectid - 30da66e8-9235-42c9-8610-df4e87b9eb93
service id - b27b79b9-a3ec-4eb1-9f70-3e275dd13cd6


4619380

masterMergeNewUserLogin



service form edited
1. 4198251 25/05/2017 12:03:03 4785236 - d
2. 4416953 04/08/2017 18:10:33 4710605 - d
3. 3843250 08/02/2017 14:56:19 4762161 - d
4. 4474593 28/08/2017 12:46:20 4755676 - d
5. 4303990 30/06/2017 13:37:48 4727958 - d
6. 4158017 05/05/2017 17:10:57 4730066 - d
7. 3895812 27/02/2017 16:47:24 4773252 - d
8. 4872464 29/12/2017 12:24:39 4923134 -- do not delete --
9. 4912193 30/12/2017 15:53:23 4935733 - d


sercive cleared or rejected
1. 4416953 
2. 3843250
3. 4474593
4. 4303990
5. 4158017


Mandatory, editable which one, autofetch
application receipt - 
date from to date to
trader of hwm 
1. Name - fe
2. address of trader ,  and  (Text Box)
3. designation
4. mobile no. 
5. Fax number
6. e-mail
7. TIN/VAT Number/ Import/ Export code (Text Box) -m
8. Description and quantity of other waste to be imported. (Text Box) (text area) - m
9. Details of storage, If any (Text Box) (text area)
5. Names and address of authorized actual user (Text Box) (text area)


09-01-2018:

1. 

duplicate application - 3923863
3923863 r
3453207 r
4600876 a


BMW application
4642375

application id  singleWindowApplication
3895812         4943429

2249.75

local CTO application no. - 148403

industry profile edit no. of beds
H17REW4685231
hspcb@123


godzilla 2 2014
transformers 2017


Taking logs:

1. inspection report ---> resolved
HSPCB014
kamaljit#66

4890656

2. consent approval of --> pending
HSPCB023
ahlawat@321

4821217
4772900

3. server is busy on industry login 
14GUSO635477
dev@5477
4886603


indUser = 4886793
indUserUniversal = 635477




4. application for change autoRenew
4881850
HSPCB077
system@1



--------------
148592

This authorisation shall be in force till the Hospital is operational
auto renew application = 148679


Thiocolchic oside,Montelukast Sodium,Febuxostat,Mycophenol ate Mofetil,Mycophenol ate Sodium,Pentazocin e,Gemcitabin e,Irinotecan,Sunitinb,Uramustine,Strontium Renelate,Capcetabin e,


,,,,,0,,,,,,0,,,,,,0,,,,,,0,,,,,,0,


0,0,0,,,,0,0,0,,,,0,0,0,,,,0,0,0,,,,0,0,0,,,,


Suntril Pharmaceuticals Private Limited,Plot No. 219, Industrial Area HSIIDC, Alipur, Barwala

Process Residues and wastes,Spent catalyst / spent carbon,Off specification products,Chemical sludge from waste water  treatment,Discarded containers / barrels / liners  contaminated with hazardous  wastes/chemicals,Used/spent oil,


http://localhost:8080/HSPCB/industryRegMaster/changeIndustryRegMasterUniversal/?applicationId=148679&industryRegMaster=599914


localhost:8080/HSPCB/industryRegMaster/showIndustryRegMasterDetails/?industryRegMaster=982512


454-488


cec62f7341516f46054c60bd483ee2982b78de75
----------------------------------------------------------------------------------------------------

