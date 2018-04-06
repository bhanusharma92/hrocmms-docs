March 2018
==========

05-03-2018
----------

Work:

1. Work on CTE auto renew on *dev-cteAutoRenewHepc* branch


CTE renewal serviceid ``eb1a6f0a-acd5-4d46-9d5c-39a6c87833f6``
CTE serviceid ``b27b79b9-a3ec-4eb1-9f70-3e275dd13cd6``							

CTO renewal serviceid ``1654c348-99ea-4f28-bfdd-bbc3af2ced74``
CTO serviceid ``6bd18359-09f4-4c71-85d9-e4f313ccfb8d``

CTE application number - 150629

06-03-2018
----------

Work:

1. Work on CTE auto renew on *dev-cteAutoRenewHepc* branch

eb1a6f0a-acd5-4d46-9d5c-39a6c87833f6
eb1a6f0a-acd5-4d46-9d5c-39a6c87833f6
MainTain$1974

application no. - 4839846
https://hrocmms.nic.in/OCMMS/industryRegMaster/deleteSingleWindowApplicationDetail?id=5048752


caf pin - 4440143034, no application is applied 
caf pin - 416274249, no application is applied 
caf pin - 2169713545, no application 

CTO renew application 
1. 1609496926 - no record found
	CTO renewal is the case of pre integration and is applied on 24-01-2018
2. 2515195801
	* 4422049 - CTO - 10-12-2017 - refused - status already sent
	* 4786752 - HWM - 10-12-2017 - approved - status already sent
	CTO renewal is the case of pre integration and is applied on 13-01-2018
3. 3043721990
	* 4737353 - CTO - status sent
	CTO renewal is the case of pre integration and is applied on 23-01-2018
4. 9970065576 - no record found
	CTO renewal is the case of pre integration and is applied on 13-01-2018
5. 5564024621 - no record found
	CTO renewal is the case of pre integration and is applied on 25-01-2018
6. 8599251752
	* 5005265 - CTO autoRenew - 25-01-2018 - pending - form edited already sent
	* 5029694 - HWM - 25-01-2018 - pending - form edited already sent
7. 8753591920
	* 5059388 - CTO autoRenew - 02-02-2018 - pending - form edited already sent
8. 4440143034 - no record found
	CTO renewal is the case of pre integration and is applied on 23-12-2017	
9. 2169713545 - no record found
   CTO renewal is the case of pre integration and is applied on 06-12-2017
10. 5201949512 - no record found
	CTO renewal is the case of pre integration and is applied on 16-01-2018
11. 3654115849
	* 5050673 - CTO autoRenew - 02-02-2018 - pending - form edited already sent


application status sent by parveen
1. 7771225800/CTO/5002517
	* 5002517
2. 0034013798/CTO/4976689
	* 4976689 - CTO - approved - cleared not sent
	* 4976745 - HWM - approved - cleared not sent
3. 8626673131/CTO/5059105
	* 4989956 - CTO - application is deleted
	* 5059105 - CTE - approved and status is sent
4. 0034013798/HWM/4976745
	* 4976689 - CTO - approved - status not sent
	* 4976745 - HWM - approved - status not sent
5. 1637901787/CTE/5006723
	* 5006723 - CTE - approved - status not sent

application processing details instance not found for application no. - 5074699
application processing details instance not found for application no. - 5086925

15PAN103181

javax.net.ssl.SSLHandshakeException: sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: unable to find valid certification path to requested target

06-03-2018:
1. Completed the cte auto renew integration locally.

15PAN105908


07-03-2018:

2. 1310102374
	application id = 4858156 CTO not on hepc
	application id = 4801977 HWM 

3. 8468577615
	application id = 4949193
	DELETE FROM single_window_application_detail WHERE application_id = '4949193';

4. 1265365289
	application id = 4999555 CTO -- this one - autoRenew
	application id = 4623307 CTE - done
	application id = 5048541 BMW - done
	DELETE FROM single_window_application_detail WHERE application_id = '4999555';

6. 7313435970
	application id = 4883757 CTO - to be delete
	application id = 5010635 HWM
	DELETE FROM single_window_application_detail WHERE application_id = '4883757';

7. 7566336077
	application id = 4707687 CTO 
	service service form edited status= true and service cleared = true

8. 8773945167
	application id = 4842236 CTO = not on hepc
	application id = 4869551 HWM
	application id = 5115436 HWM	
	DELETE FROM single_window_application_detail WHERE application_id = '4842236';	

9. 8158613883
	application id = 4895800 CTO
	application id = 5124359 CTO ==> in doubt now
	DELETE FROM single_window_application_detail WHERE application_id = '4895800'
	-- DELETE FROM single_window_application_detail WHERE application_id = '5124359'

10. 8158613883
	application id = 5124359 CTO
	9 and 10 are same

11. 8656271553
	application id = 4872464 CTO
	application id = 5092340 CTE
	DELETE FROM single_window_application_detail WHERE application_id = '4872464'


12. 6703347360
	application id = 4888088 CTO = approved  30/12/2017 
	application id = 5018298 
	DELETE FROM single_window_application_detail WHERE application_id = '4888088'

13. 9587801514
	application id = 4605318 CTE rejected 10th month - present on hepc and status sent
	application id = 4198251 CTO
	DELETE FROM single_window_application_detail WHERE application_id = '4198251'

14. 8380150260
	application id = 5017247 - CTO 



14GUSO1463084
9085677798


local HWM application no. - 150743

07-03-2018:
1. Fixed the errors on test link and provided test link.
2. Working on changes in trader hwm (40%)
3. VC with HSPCB
4. Resolved the live issue that industry is claiming not able to register but when i tried it got registered.


IndUser.find("from IndUser where industryRegMaster = ? ", [ins.indUserUniversal]).cafpin


action="http://164.100.163.19/api/webapi/hrocmms/login/"

action="http://staging.hrocmms.nic.in/api/webapi/hrocmms/login/"


4999578

15FDBB1776914
mkbhatta@914

08-03-2018:
1. completed the trader changes and provided the test link.
2. provide the status of application and there status as required by hspcb
3. provide the status of paymesnt issue.
4. working on merging satish code.

15PAN102394
anil#777
f1941c14490503daa1a1d7ff4dd89a01
3714


09-03-2018:
1. Completed the merging and testing of MIS of BMW and HWM
2. Completed the satish code merge and test
3. Completed the change of CTE renewal service id for testing and updated test link
4. Working on updating HWM and BMW all summary during processing


getDataHwm 331
wasteManagemenetPendingDetailsController 2743
RouteWasteManagement.groovy 264
wasteMNagementProcessingDetailsController 8161

http://localhost:9999/api/webapi/hrocmms/downloadCertificate/?projectid=e383fbd7-994f-4075-a69f-428cf7cf13wa&serviceid=a2f9f150-02eb-4ef7-8989-ef43b2f6eb49

150607

12-03-2018
1. Completed the change in CTE renewal certificate and updated test link.
2. VC with HSPCB
3. Fixed the live issue in deleted application report
4. Working on resolving BMW issue(50%)

13-03-2018
1. 14PAN101782

6729

13-03-2018:
1. Working on sending of status for deleted application(50%).
2. Code review and testing of CTE renew and trader and updated it on live.

14-03-2018

To do:

1. To complete send status for deleted application.
2. Merge and test the new MIS made by satish
3. industry management taking too much time.

cto = 144526
cto auto renew = 147182
cte = 145945
cte auto renew = 150444 -- a2f9f150-02eb-4ef7-8989-ef43b2f6eb49
hwm = 150615
bmw = 144753

143280
5                   7        10             12             15                             20

15-03-2018:
1. Completed the send status 

143298

1. one to one
2. industries if register
3. 


New Enterprise/Expansion/Diversification

Renew of Factory Registration / CTO / Boiler

select gm.id, count(*) from GroupMaster as gm left join AllSummaryReport as asr on (cast(gm.id as string) = asr.groupId) where gm.groupDesc='CONSENT' and asr.applicationStatus='approved'  group by gm.id order by gm.id


https://www.youtube.com/watch?v=Mp4Fy9TDU_Y&index=1&list=PLd3UqWTnYXOn7zNVRm_ZjnWqnf5osnKxq

15-03-2018:
1. Working on report number 009, Industry grant/refuse district wise list(75%).
2. Completed the changes on home page as specified by HSPCB
3. Changing the title of monitoring report in all modules


5159539 - vinod kumar - 8366505187

12PAN28635
320bbf73a59e2e40857f6883470e8f7c



1. completed the report no. 009
2. resolved the live issue in deleted application send status


http://rockon.com/

www.rockon.com

"C:\Program Files\Java\jdk1.8.0_131\bin\java" "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA 2017.3.1\lib\idea_rt.jar=57746:C:\Program Files\JetBrains\IntelliJ IDEA 2017.3.1\bin" -Dfile.encoding=UTF-8 -classpath home.Main

21

live issue:

1. extra link visible in application id - no issue
	officer user id - HSPCB028
	officer password - System@123 
	application no. - 4895706
2. annual report submit error
	industry login id - H18KAR212644
	industry password - system@1
	it is resolved i have submitted the annual report with application no. - 5211275

3. view form error for CTE exten(autoRenew)
	officer id - HSPCB081
	officer password - sachin@grs1
	application no. - 5204266
4. payment issue - fee deducted but application not completed
	aplication no. - 5179932

1. rough
	local CTO application no. 150558
	live


1317017
select * from ind

Trust building, 

SCF-32, sector 13, HUDA, Bhiwani Ph. 01664-240259

20-03-2018

1. waste tracking provide the test link
2. 

<% System.out.println("roleMasterInstance?.group...."+roleMasterInstance?.group.id) 
                  def noList=RoleMaster.findAll("from RoleMaster where group=? and roleStatus='active' order by priority",[roleMasterInstance.group])
                  System.out.println("rnoList...."+noList) 
                  System.out.println("rnoList...."+noList.size())
                  List myList = new ArrayList();
                  myList=myList+-1;
                  myList=myList+roleProfileAssignmentInstance?.role.priority;
                 for(int a=0;a<=noList.size();a++){
               	 if(noList[a]){
                 if(noList[a].priority!=a){
               	myList=myList+a
               	 }
                  }}
                  %>


def edit = {
   	ArrayList myArrayList2 = new ArrayList()
   	def empList=UserProfile.list()
   	
   	for(int q=0;q<empList.size();q++)
   	{
   	
    if((empList.get(q)).status=="active")
   	{
   	
    myArrayList2.add((empList.get(q)))
   	}
   	
   	
   	}
  if(params.grp == null || params.grp == "")
  {
  flash.message = "Please Select The Role to be Updated"
  redirect(action:updateRoleManagement)
  }
  else
  {
     def roleMasterInstance = RoleMaster.get( (params.grp).toLong())
     def noList=RoleMaster.findAll("from RoleMaster where group=? and roleStatus='active' order by priority",[roleMasterInstance.group])
     def noListPriority = noList.priority 
     println("noList: " + noList)
     println("noListPriority: " + noListPriority)
     List myList = new ArrayList();
     myList.add(-1);
     for(int a=0;a<noList.size();a++){
   		myList.add(a)	
   	 }
   	 }
       	 if(isNotInList){
        myList.add(String.valueOf(a))
       	 }
     }
     println("myList: " + myList)
    def roleProfileAssignmentInstance=RoleProfileAssignment.findByRole(roleMasterInstance)
  if(!roleMasterInstance) {
           flash.message = "Role not found with id ${params.id}"
           redirect(action:updateRoleManagement)
       }
       else {
           return [ myArrayList2:myArrayList2,
                    roleMasterInstance : roleMasterInstance ,roleProfileAssignmentInstance:roleProfileAssignmentInstance
                    , myList: myList]
       }
  }
   }  


addCommonFacilityInspection
dashboard_integration
dev-trader
t-del-status-mis
waste-tracking
remote/origin/dev-trader
remote/origin/waste-tracking

dev2 ==> copy dev2-deletedStatusHepc
Thu Oct 30 05:44:42 GMT 2014

EEE MMM dd HH:mm:ss z yyyy      



git add .
git commit -m "saved my work"

git checkout master
git reset --hard origin/master


git branch myMisBranch
git checkout myMisBranch

// now work on this myMisBranch


javax.net.ssl.SSLHandshakeException: sun.security.validator.ValidatorException: PKIX path building failed: sun.security.provider.certpath.SunCertPathBuilderException: 
unable to find valid certification path to requested target


21-03-2018

local CTE application id - 150986


22-03-2017:

1. Deposit consent fees  ID 14FDBB1441986 and password 26886
2. 8724459947
3. 4400509 H17FDBD4400462 not found on ocmms


H17FDBD4400462
5a085dc3cb8c282f44d5f4889c7e91eb


133605 BMW Annual Report


1. myMis branch - rename MIS pragya mam code
2. dev2-red-im-mis-o: 17 red catregory, and inspection management
3. dev2 - color: color horizontal, annual report last activity, mis home page text


3576543210

18PAN606948

TSDF001

vehicle number
1234

dfdfsdfs

jnks@123

4400509


Ramki
2131231

HR-66-A-8996



unmerged branch
1. addCommonFacility inspection
2. dashboard inspection
3. dev-trader
4. dev2-test-p-wt
5. t-del-status-mis
6. waste-tracking
7. remote/origin/dev-trader
8. remote/origin/waste-tracking


test
user@123


HR-38-U-9245

23-03-2018:
1. Done testing 


fd4659813cd8544ec603d41d7865083966f85651


https://hrocmms.nic.in/OCMMS/

https://hrocmms.nic.in/OCMMS/industryRegMaster/bankTransactionDetailsById/?id=5193446



DeletedApplicationBmw, DeletedApplicationHwm
Long applicationId
String deletionDate


https://hrocmms.nic.in/OCMMS/industryRegMaster/updateProjectIdForGivenUserId?id=16SON3083801



27-03-2018:
1. Updated the payment MIS. Now if they are searched region wise, result is coming in 1-2 minutes but if all regions are selected it is still taking time.
2. Completed the changes of displying the given text in all modules pending page, search page and mis as required by chairman sir.
3. Updated th live war.


------------

contact us
color

table mis
37597158b1c0fffe074c3ed7d592463908a7fe3f



6673785283

932414c5-bded-478a-83e6-7ba8497f7af6



28-03-2018:
1. Completed the merge and test of pending report 008, contact us target="_blank" and updated live war.
2. changes in page to show all the mis in single page.
3. Resolved the query that a user is registered twice on hepc but they are claiming otherwise.  


Saroj@123


cbtf

eb1a6f0a-acd5-4d46-9d5c-39a6c87833f6 - cte autoRenewal LIve
a2f9f150-02eb-4ef7-8989-ef43b2f6eb49 - cte autoRenewal test


2845707144



02-04-2018:
1. merged, tested and provided he test link for hwm certificate, color change in vertical menu
2. Completed the funtionality of field - do you want to apply HWM/trader according to requirement
3. Started working on back button concept

n = 3
1
2
3
4 -> 3
5 -> 2
6 -> 1


1 = 1
2 = 3
3 = 5
4 = 


1. back button 
2. waste tracking
3. 

http://164.100.163.19/TRACK/checkStatus?vehicleNo=HR-66-A-8996

http://164.100.163.19/api/webapi/waste/HR-66-A-8996



to do - 
mis 11 make same as admin

annual report year not coming

grails create-service BrowserBack

1. Completed the changes as specified by HSPCB on the test link. All changes are also done on live.
2. Merged and tested the CTE Auto Renewal MIS in live code
3. Working on back button(10%).


MIS data not coming 						
18, 20, 21


industryList 

6806
7888



total points received, total number of points done on live




