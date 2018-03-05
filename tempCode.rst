Temp Code
=========

<input type="date"
  name="licenceDateOfExpiry"
  class="input-xs form-control"
  min='1980-01-01' max='2080-01-01'>
  18c82b0da1b34d88460cc7e6b0f9a889cb950a05 - regular inspection
  3fc646dee4543afb4d28e6fa57fc42025a192d44 - master

  15PAN103181,

  HSPCB020, HSPCB007

  def recordCertificateList = RecordCertificateHWM.executeQuery("select rc.id from RecordCertificateHWM rc, WasteManagementPendingDetails asr where cast(rc.application.id as string) = asr.applicationId and "+
               	"rc.expiryDate >= '" + df.format(today120) + "' and rc.expiryDate < '" + df.format(today) + "' and asr.role.group.groupName = '" + params.groupId +
                       "' and asr.applicationStatus = 'approved' " +
                       "order by rc.id")



 date(to_date(nt.valeur,'DD-MM-YYYY HH:MI:SS'))

 59197cf36de27eb4d9873fb7db2a2a80f96cb6b0 - merged code
 9515c5753f7cbccfde103154b60cd18051d3e0b7 - regularInspection code
changes -
 updateApplicationCountAllModule

 added -
 noteHistoryForDashboard
20/09/2016 to 4/06/2016
================================================================================
27-06-2017:
bmw application no. : 140992 , 141048

ApplicationFileRecord - typeOfFile

applicationType: CTE
  typeOfFile: Certificate, Certificate1

applicationType: CTO or HWM
  applicationFor: air
    applicationStatus: approved
      typeOfFile: CtoCertificate, DigiCommonCtoCertificate, CertificateForAir, CertificateForAirDegi
    else:
      typeOfFile: CertificateForAir, CertificateForAirDegi
  applicationFor: water
      applicationStatus: approved
      else:
      typeOfFile: CtoCertificate, DigiCommonCtoCertificate, CertificateForWater, CertificateForWaterDegi
        typeOfFile: CertificateForWater, CertificateForWaterDegi
  applicationFor: both
      applicationStatus: approved
          typeOfFile:  CtoCertificate, DigiCommonCtoCertificate
      applicationStatus: rejected
          typeOfFile: RefusalCertificateForBoth, DigiCommonCtoBothRefCertificate
      else:
          instance1 = CertificateForAir, CertificateForAirDegi
          instance2 = CertificateForWater, CertificateForWaterDegi

    applicationFor: both/HWM
        applicationStatus: approved
            typeOfFile:  CtoCertificate, DigiCommonCtoCertificate
        applicationStatus: rejected
            typeOfFile:  CtoCertificate, DigiCommonCtoCertificate
    applicationFor: air/HWM
    applicationFor: water/HWM
    applicationFor: HWM



    bmw application no. : 141148





    ---------------------increase size--------------
    table: RecordCertificateBMW
    column: copyTo

    table: wasteManagementProcessing
    column: clarificationNote(mandatory)
            approve_note
            file_note
            inspection_close_note
            inspection_note
            reject_note

----------------------drop table--------------------
table: hwminspection_report


----------------reopen application number---------
1. 3686291
2. 3606397
3. 3977036
4. 3507068
5. 3705308


----------- industry not showing -----------------
id: 13REW36597
application no. -  2770534


----------------- develpment work ----------------
wolworine application no. - 141238

bmw application no. - 141295
hwm application no. - 141320
table: wasteManagementCertificates
applicationFor - HWM
createdBy - HSPCB020
description - Certificate Generation Record
extension - pdf
name - DigitalCertificateForBMW.pdf
typeOfFIle - DigitalCertificateForBMW
updatedBy - HSPCB020

table: recordCertificateBmw
authorizationFOr - BMW
issueDate -
expiryDate -
subject - DigitalCertificateForBMW
createdBy - HSPCB020
reference no. - get input from form
updated by - HSPCB020



BMW application no. - 141499



--------------- work done on test db -----------
table: cessReturn
col:
selfAssessmentOrder : f
appDel
clarification
clarificationClose


table: cessProcessing
col: selfAssessmentOrder : f


-------------- mango industry ---------------------
consent application no. : 141525


-------------- annual report -----------------------
application no. : 141718

--- HWM ----
application no. - 142024
close verification on 25-07-2017 at 9:54


----------------------------------------------------
1. indName
2. bmw id
3. bed
4. yellow
5. red
6. white
7. blue
8. gsd
9. color


1. web ser - 15
2. single - 30 days
3. Report

------ annual report -----
no. 142112

Date: 02-08-2017
cto live issue-
application no. - 4302619
In application search it is showing unattented. But it is not visible in Application summary.
4302619
bhanusharma.a3@gmail.com
142226


Renew, Auto renew, Add prev consent, Single window,
hide registration from public


--------------------------------------------------------------------------------
indName: myHospital
occMobile: 4561230789
occEmail: bhanu@gmail.com
http://localhost:9999/api/webapi/hrocmms/login?name=myHospital&mobile_no=4561230789&email_address=bhanu@gmail.com

http://localhost:9999/api/webapi/hrocmms/login?name=myHospital&mobile_no=4561230789&email_address=bhanu@gmail.com&address=xyz

http://localhost:9999/api/webapi/hrocmms/login?name=myAnotherHospital&mobile_no=4561000789&email_address=bhanu@gmail.com&address=abc&caf_unique_no=1111

http://localhost:9999/api/webapi/hrocmms/login?uname=myAnotherHospital&mobile=4561000789&useremail=bhanu@gmail.com&address=abc&projectid=1111

onclicking inprogress application wer go to
controller: indApplicationDetails action: doGetShow
From this action we either go to doShow.gsp or doEdit.gsp(based on params.edit)

On doShow.gsp there is edit button on clicking it we  again go to action: doGetShow (this time send edit params)
Now inside goGetShow action since - params.edit = 1 therfore, render view: doEdit

Inside doEdit After filling the application details we go to action: saveNew 



----------------------------------------------------------------------------------------------------

Live issue :
application no. - 3154022
Date of payment receipt (industry) - 28-05-2017
Date of receipt (Board) - 21-03-2016  

-----------------------------------------------------------------

Live issue Date: 30-08-2017
Application no. - 4310967
Actual - CTE
Showing - CTO
 
https://staging.investharyana.in/#/

4101235


142852,
142904,
142950,

143029


localhost:9999/api/webapi/hrocmms/downloadCertificate/?projectid=<projectid>&serviceid=<serviceid>

Application no - 143088

17PAN4080650
anil#777


(version, 0                                       
application_id, 4168193
buildup_area, 1.0
cat_unit, '1'
complaint, 'NO'
complaint_details, ''
cooling_effluent, '1'
court_case, 'NO'
court_case_details, ''
cover_undereia, '1'
d_sch_proper_or_not_proer, 'Not-Selected'
d_sch_proper_or_not_proer_etp,  'Not-Selected'
d_sch_proper_or_not_proer_stp, 'Not-Selected'
d_sch_short_comings,  ''
d_sch_short_comings_etp, ''
d_sch_short_comings_stp, ''
d_sch_submitted_or_not_submitted, 'Not-Selected'
d_sch_submitted_or_not_submitted_etp, 'Not-Selected'
d_sch_submitted_or_not_submitted_stp, 'Not-Selected'
devices, ''
domestic_eff, '1'
ind_address, 'VILLAGE KURALI, INDRI ROAD'
ind_name, 'PRABHAT FERTILIZER AND CHEMICAL WORKS',
local_clearence, '1'
manufacturing_process, '1'
mode_of_disposal, ''
name_of_product, 'Proposed Zinc Polyphosphate,Proposed Micronutrient EDTA,Proposed Copper Sulphate,Existing MAGANESE SULPHATE,Existing ZINC SULPHATE MONOHYDRATE,Existing MICRONUTRIANT MIXTURE FERTILIZERS (GREEN),Existing ZINC SULPHATE HEPTAHYDRATE,Existing ORGANIC MANURE/ORGANIC FERTILIZERS(Green),Existing BIO FERTILIZER/BIO PESTICIDES UNDER GREEN,'
noc_fee_req, '1',
performance_bond, '1'
primary_devices,  ''
receipt_date,  '04/09/2017'
recomendation, '1'
reg_under_registration, '1'
secondary_devices, ''
source_of_trade_effluent, '1'
tertiary_devices, ''
total_effulent,  '3'
total_land_area, 1.0
trade_eff, '1',
id, 4497057
) values 

0 9015 483 483

139864,
HSPCB024

HSPCB079
ramshiv@1

-----------------------------------------------
[
    {
        "approved_beyond_time": 2,
        "approved_within_time": 24,
        "pending_beyond_time": 486,
        "pending_with_applicant": 0,
        "pending_within_time": 8,
        "servicename": "cto",
        "total_approved": 26,
        "total_pending": 494,
        "total_recieved": 580
    },
    {
        "approved_beyond_time": 1,
        "approved_within_time": 3,
        "pending_beyond_time": 0,
        "pending_with_applicant": 0,
        "pending_within_time": 1,
        "servicename": "hwm",
        "total_approved": 4,
        "total_pending": 1,
        "total_recieved": 6
    },
    {
        "approved_beyond_time": 0,
        "approved_within_time": 7,
        "pending_beyond_time": 0,
        "pending_with_applicant": 0,
        "pending_within_time": 5,
        "servicename": "bmw",
        "total_approved": 7,
        "total_pending": 5,
        "total_recieved": 12
    }
]

-------------------------------------------------------------------

[
    {
        "approved_beyond_time": 0,
        "approved_within_time": 8,
        "pending_beyond_time": 2,
        "pending_with_applicant": 0,
        "pending_within_time": 7,
        "servicename": "cto",
        "total_approved": 8,
        "total_pending": 9,
        "total_recieved": 18
    },
    {
        "approved_beyond_time": 0,
        "approved_within_time": 8,
        "pending_beyond_time": 2,
        "pending_with_applicant": 0,
        "pending_within_time": 7,
        "servicename": "cto",
        "total_approved": 8,
        "total_pending": 9,
        "total_recieved": 18
    },
    {
        "approved_beyond_time": 0,
        "approved_within_time": 7,
        "pending_beyond_time": 0,
        "pending_with_applicant": 0,
        "pending_within_time": 5,
        "servicename": "bmw",
        "total_approved": 7,
        "total_pending": 5,
        "total_recieved": 12
    }
]
--------------------------------------------------------------------------------
punia@007

Dr Sheorans Ultrasound and Imaging Centre

-------------------------------------------------------------------------
sameName industry
mobile no. - 1237596840

-------------------------------------------------------------------
projectid: 396fe9d0-f4f0-4bfc-b246-1b2673f51859
service id: 6bd18359-09f4-4c71-85d9-e4f313ccfb8d
projectserviceid: e4b39a74-e78f-4b2d-bb25-b3919c3e6fa9

projectid: 396fe9d0-f4f0-4bfc-b246-1b2673f51859
service id: 6bd18359-09f4-4c71-85d9-e4f313ccfb8d
projectid: e4b39a74-e78f-4b2d-bb25-b3919c3e6fa9
-------------------------------------------------------------------
projectid: a41e3c97-8666-49e4-af83-3c609a3b103f
serviceid: 6bd18359-09f4-4c71-85d9-e4f313ccfb8d
projectserviceid: 39fadab0-69b5-4c8d-8370-96f6d83154ec



--------------------------------------------------------------
application no. - 140188  (myIndustry4)

application no. - 140222 (myIndustry6)

----------------------------------------
pro : dddf7c65-0b71-4a02-9ef2-5ec75d727edc
serv: 6bd18359-09f4-4c71-85d9-e4f313ccfb8d
proser: 6f136058-f254-4bd2-b6c0-136a42108fa6

140246
-------------------------------------------------------
pro: c129b2e5-2c6c-4041-9358-23a17be5a42d
serv: 6bd18359-09f4-4c71-85d9-e4f313ccfb8d
proser: a555b3d2-64a5-4e9d-b791-329919d46dd6


--------------------------------------------------
application no. : 140302(myIndustry10)

------------------------------------------------------
application no. - 143220 (myIndustry11) local

-----------------------------------------------------------
haryana 25_7_2017 - satish project 

-------------------------------------------------------------
projectid: a0ed14e3-70cb-4c2f-9247-9bbac0e7f6f9


https://staging.investharyana.in/#/serviceclearanceaction/
a0ed14e3-70cb-4c2f-9247-9bbac0e7f6f9/serviceLog/
project id: a0ed14e3-70cb-4c2f-9247-9bbac0e7f6f9
service id: 6bd18359-09f4-4c71-85d9-e4f313ccfb8d
project service id: d51302a5-fabf-4dbb-9996-b5a8659596f5

application no. : 143245, 143261, 143277, 143309, 
143325

---------------------------
https://staging.investharyana.in/#/serviceclearanceaction/
41c7396e-e56e-42d4-90dc-7d511e032f1d/serviceLog/
41c7396e-e56e-42d4-90dc-7d511e032f1d/
6bd18359-09f4-4c71-85d9-e4f313ccfb8d

SNo.0:  assigOnDate: null
SNo.0:  assignBy: null
SNo.0:  departmentName: HARYANA STATE POLLUTION CONTROL BOARD
SNo.0:  formFilledBy: null
SNo.0:  formFilledOnDate: null
SNo.0:  formFilledStatus: false
SNo.0:  id: d51302a5-fabf-4dbb-9996-b5a8659596f5
SNo.0:  isAssigned: false
SNo.0:  isDimmed: false
SNo.0:  isPaymentMade: false
SNo.0:  isPaymentVerified: false
SNo.0:  isRequired: true
SNo.0:  lastactiondate: 2017-09-11T05:30:34.657Z
SNo.0:  latestComments: Service Marked as Required
SNo.0:  paymentMadeOnDate: null
SNo.0:  projectid: a0ed14e3-70cb-4c2f-9247-9bbac0e7f6f9
SNo.0:  requireMarkedBy: jonsnow
SNo.0:  requireMarkedOnDate: 2017-09-11T05:30:34.657Z
SNo.0:  serviceDuration: 45
SNo.0:  serviceFee: null
SNo.0:  serviceName: Consent to Operate - Air-Water
SNo.0:  serviceStage: Stage-III
SNo.0:  serviceid: 6bd18359-09f4-4c71-85d9-e4f313ccfb8d
SNo.0:  status: Pending

{
    "id": "d51302a5-fabf-4dbb-9996-b5a8659596f5",
    "projectid": "a0ed14e3-70cb-4c2f-9247-9bbac0e7f6f9",
    "serviceid": "6bd18359-09f4-4c71-85d9-e4f313ccfb8d",
    "isRequired": true,
    "requireMarkedOnDate": "2017-09-11T05:30:34.657Z",
    "requireMarkedBy": "jonsnow",
    "isAssigned": false,
    "assigOnDate": null,
    "assignBy": null,
    "formFilledStatus": false,
    "isPaymentMade": false,
    "isPaymentVerified": false,
    "formFilledOnDate": null,
    "formFilledBy": null,
    "paymentMadeOnDate": null,
    "status": "Pending",
    "latestComments": "Service Marked as Required",
    "departmentName": "HARYANA STATE POLLUTION CONTROL BOARD",
    "serviceName": "Consent to Operate - Air-Water",
    "serviceStage": "Stage-III",
    "isDimmed": false,
    "serviceDuration": 45,
    "serviceFee": null,
    "lastactiondate": "2017-09-11T05:30:34.657Z"
}

Working--->
{
  "assigOnDate": null,
  "assignBy": null,
  "departmentName": "HARYANA STATE POLLUTION CONTROL BOARD",
  "formFilledBy": null,
  "formFilledOnDate": "2017-08-30T13:05:14.365Z",
  "formFilledStatus": true,
  "id": "d51302a5-fabf-4dbb-9996-b5a8659596f5",
  "isAssigned": false,
  "isDimmed": false,
  "isPaymentMade": false,
  "isPaymentVerified": false,
  "isRequired": true,
  "lastactiondate": "2017-09-11T05:30:34.657Z",
  "latestComments": "Service Marked as Required",
  "paymentMadeOnDate":null,
  "projectid": "a0ed14e3-70cb-4c2f-9247-9bbac0e7f6f9",
  "requireMarkedBy": "jonsnow",
  "requireMarkedOnDate": "2017-09-11T05:30:34.657Z",
  "serviceDuration": 45,
  "serviceFee": 45,
  "serviceName": "Consent to Operate - Air-Water",
  "serviceStage": "Stage-III",
  "serviceid": "6bd18359-09f4-4c71-85d9-e4f313ccfb8d",
  "status": "Pending"
}


output of println -->
{"assigOnDate":"null",
"assignBy":"null",
"departmentName":"HARYANA STATE POLLUTION CONTROL BOARD",
"formFilledBy":"null",
"formFilledOnDate":"2017-09-11T07:05:59.713Z",
"formFilledStatus":"true",
"id":"d51302a5-fabf-4dbb-9996-b5a8659596f5",
"isAssigned":"false",
"isDimmed":"false",
"isPaymentMade":"false",
"isPaymentVerified":"false",
"isRequired":"true",
"lastactiondate":"2017-09-11T05:30:34.657Z",
"latestComments":"Service Marked as Required",
"paymentMadeOnDate":"null",
"projectid":"a0ed14e3-70cb-4c2f-9247-9bbac0e7f6f9",
"requireMarkedBy":"jonsnow",
"requireMarkedOnDate":"2017-09-11T05:30:34.657Z",
"serviceDuration":"45",
"serviceFee":"45",
"serviceName":"Consent to Operate - Air-Water",
"serviceStage":"Stage-III",
"serviceid":"6bd18359-09f4-4c71-85d9-e4f313ccfb8d",
"status":"Pending"}



"{" +
                    "\"assigOnDate\":\"" + assigOnDate +"\"," +
                    "\"assignBy\":\""+ assignBy +"\"," +
                    "\"departmentName\":\"" + departmentName + "\"," +
                    "\"formFilledBy\":\"" + formFilledBy + "\"," +
                    "\"formFilledOnDate\":\"" + formFilledOnDate + "\"," +
                    "\"formFilledStatus\":\"" + true + "\"," +
                    "\"id\":\"" + id + "\"," +
                    "\"isAssigned\":\"" + isAssigned + "\"," +
                    "\"isDimmed\":\"" + isDimmed + "\"," +
                    "\"isPaymentMade\":\"" + isPaymentMade + "\"," +
                    "\"isPaymentVerified\":\"" + isPaymentVerified + "\"," +
                    "\"isRequired\":\"" + isRequired + "\"," +
                    "\"lastactiondate\":\"" + lastactiondate + "\"," +
                    "\"latestComments\":\"" + latestComments + "\"," +
                    "\"paymentMadeOnDate\":\"" + paymentMadeOnDate + "\"," +
                    "\"projectid\":\"" + projectid + "\"," +
                    "\"requireMarkedBy\":\"" + requireMarkedBy + "\"," +
                    "\"requireMarkedOnDate\":\"" + requireMarkedOnDate + "\"," +
                    "\"serviceDuration\":\"" + serviceDuration + "\"," +
                    "\"serviceFee\":\"" + serviceFee + "\"," +
                    "\"serviceName\":\"" + serviceName + "\"," +
                    "\"serviceStage\":\"" + serviceStage + "\"," +
                    "\"serviceid\":\"" + serviceid + "\"," +
                    "\"status\":\"" + status + "\"" +
                    "}").getBytes("UTF8"

------------------------------------------------------------------------------------------------------

myIndustry13
projectid: 3795e7b5-e4a9-48ef-bd1c-3aa4ef677ece
service id: 6bd18359-09f4-4c71-85d9-e4f313ccfb8d
project service id: 123654

------------------------------------------------------------------------------------------------------

Industry - Dorne(local)
HWM application no. - 143384

hspcb035


Live inspection draw - 09-2017
Prabha Coaters,
Plot No. 437, EPZ, Sector-58, Faridabad

ASHOKA INDUSTRIES,
Plot No. 581, Sectror 58, EPZ, Faridabad
143395 
---------------------------------------------------------------------------------------------------------
14-09-2017:

CTE application no. - 143430

164.100.163.19/api/webapi/hrocmms/login/

hrocmms.nic.in/api/webapi/hrocmms/login/ 

143532 

-----------------------------------------------------------------------------------------
Date: 18-09-207
staging investharyana - 
CTE application no. - 
140839