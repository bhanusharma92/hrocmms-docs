January 2018
============

12-01-2018
----------

1. service form edited status not sent - completed
	cafpin = 9696535359
	application no = 4972333

	issue - many applications are there whose status are not sent
	reason - pkix path build fail

2. Completed the print form of application receipt  - completed

3. BMW certificate changes like - completed
	a. two grant from to
	b. fetch the no. of beds from certificate

	these points done and merged in testAll branch

4. Updating the live war - compelted
	update the new column added in bio_medical_waste table
		UPDATE bio_medical_waste SET  beddedornonbedded = '' WHERE beddedornonbedded IS NULL;
	update the new columns added in record_certificatebmw table	
		UPDATE record_certificatebmw SET beddedornonbedded = '' WHERE beddedornonbedded IS NULL;
		UPDATE record_certificatebmw SET categoryofHCF = '' WHERE categoryofhcf IS NULL;
		UPDATE record_certificatebmw SET authorization_for = '1950-01-01' WHERE authorization_for IS NULL;
		UPDATE record_certificatebmw SET authorization_to = '1950-01-01' WHERE authorization_to IS NULL;

15-01-2018
-----------

5. application no. - 4834313
   login id - 13HIS125869
   password - dcmt@12345
   payment completed but not showing to industry

   This application is in id of - 14REW850705
   and its password - 65214

6. in industry home page server is busy 
	userid=14GUSO635477
	password=dev@5477

	application no.=4886603
	this appliction is in the same account but showing server is busy


	to resolve the issue change in indUser/industryHome.gsp

8. approval/refusal are not showing to officer => completed industry profile
	userid=HSPCB023
	password=alhawat@321 <-- it might be changed
	application no.=4772900 --> industry type mismatch
	application no.=4821217 --> industry type mismatch

	for these applications the industry type does not match

	in bmw approve refuse is showing

9. Application and userid not found on ocmms 
	application no=981823
	userid=14PAL978298

10. A new parameter projectlevel (with possible values d or e) is passed in URL for those services which are integrated with HEPC. It is used to identify the level at which project (CAF) is to be dealt. Value of d for parameter signifies DLCC and e signifies EEC.
	Kindly add the same in your records.

11. HSPCB023  => completed
	capital investment = 306 lakh 
	approval - 4570892
	approval rights are not showing
	because the approval rights will only be shown to cap ins of more than 10 crore

12. HSPCB077
	system@1
	BMW applocation
	4781724 - server busy --> code applied
	4821030 - server busy --> code applied
	4749357 - certrificate not generate refresh to home page while generting certificate --> hopefully it will be fixed
	4013436 refusal certifiacte generate link not shown 

13. 17 category
	51 
	48 bhadurgarh
	140 +

14. HWM application -
	note history show different name
	Ramansethi
	SYSTEM@1

16-01-2018
----------

1. application no. - 4834313 ==> completed
   login id - 13HIS125869
   password - dcmt@12345
   payment completed but not showing to industry

   This application is in id of - 14REW850705
   and its password - 65214

   indApplicationDetails.appDel:true
   applicationPendingDetails.pendingWith: HSPCB049
   bankTransactionDetails[3].amount:1.0
   bankTransactionDetails[4].amount:50000.0
   bankTransactionDetails[5].amount:10000.0

2. Application and userid not found on ocmms
	application no=981823
	userid=14PAL978298

3. A new parameter projectlevel (with possible values d or e) is passed in URL for those services which are integrated with HEPC. It is used to identify the level at which project (CAF) is to be dealt. Value of d for parameter signifies DLCC and e signifies EEC.
	Kindly add the same in your records.

4. MIS of 17 category

5. HWM application
   note history show different name
   Ramansethi
   SYSTEM@1 

   14PAN1025892
   VIPUL@123





17-01-2018
----------

1. Completed the unhide BMW and HWM module and and hide the apply authorization in both the modules.
2. Resolved the live issue to in add view delete of verification report of HWM
3. Resolved the live issue in certificate generation of BMW module.
4. Updated the live war.


19-01-2018
----------

1. File getDataTrader.groovy
	routeApp action changed
	added the traderAllSummary 

2. File TraderController.groovy
	// bhanu code start; date: 18-01-2018
	def deleteApplicationShow = { ...}
	def deleteApplication = { ... }
	// bhanu code ends; date: 18-01-2018

	added file deleteApplicationShow.gsp in view/trader

3. industryRegMaster/create1.gsp
	<!-- bhanu commented code start; date: 19-01-2018 -->
	...
	<!-- bhanu commented code ends; date: 19-01-2018 -->

4. 	autoRenew Application wrong details are shown in the application
	application no. - 4834577
	userid: 15REW2293751
	password: 96267

5. 91f340e6-b0c2-44c7-bd6f-679a5f7bb072 7892263444

6. 149188		


Site designed, hosted by National Informatics center.
 @ Content Owned, Updated and Maintained by Haryana State Pollution Control Board  

 7. 177 panipat - revera part 2 - 3243277 - 3243277 date - 1-10-2016 to 30-09-2017
 	647 reject part 1 30-9-2021 - 3618716 - 3618463 date - 1-04-2017 to 30-09-2021
 	657 revera part - 3618354 -             3091175 date - 15-05-2016 to 30-09-2018

 	13PIT512080
 	13PIT543818 ad0cec4de77ef5ace60ea3d9447a37c9
 	13PIT512392 

 	some of the application may be rejected
 	last application

Auto renew application of userid 15REW2293751 and password 96267 issue is resolved. Just Add the analysis reports and update the application form.
	15REW2293751
	96267 	
19-01-2017:



addCommonFacilityInspection
dashboard_integration
mergeBmwBedded
testAjax
trader
trader2


ricemillsaini
sainiricemill1234*

22-01-2017
----------

1. File getDataTrader.groovy
	routeApp action changed
	added the traderAllSummary 

2. File TraderController.groovy
	// bhanu code start; date: 18-01-2018
	def deleteApplicationShow = { ...}
	def deleteApplication = { ... }
	// bhanu code ends; date: 18-01-2018

	// bhanu code start; date: 22-01-2018
    def generateCertificate = {...}
    // bhanu code ends; date: 22-01-2018

	added file deleteApplicationShow.gsp in view/trader

3. industryRegMaster/create1.gsp
	<!-- bhanu commented code start; date: 19-01-2018 -->
	...
	<!-- bhanu commented code ends; date: 19-01-2018 -->

4. index.gsp
   <!-- bhanu code start; date: 22-01-2018 -->
   ...
   <!-- bhanu code ends; date: 22-01-2018 -->	

5. consentApprovalRights/create1.gsp
	// bhanu code start; date: 22-01-2018
	...
	// bhanu code ends; date: 22-01-2018

	search - hideShowCapitalInvestmentTrader()

6. File TraderPendingDetailsController.groovy
	serch bhanu 

7. userMasterController.groovy
	// bhanu code starts; date: 24-01-2018	
	...
	// bhanu code ends; date: 24-01-2018

8. New file added in userMaster
	wasteManagementEmpTraderVertical
	wasteManagementAdminTraderVertical

9. change in traderPendingDetails/traderPendingList.gsp and traderProcessingDetails/appProcessing.gsp
	search g:include
	added
	<g:include controller="userMaster" action="wasteManagementAdminTraderVertical"/>
	and 
	<g:include controller="userMaster" action="wasteManagementEmpTraderVertical"/>

10. change in traderProcessingDetails/appProcessing.gsp
	search 'View Application Form'
	change link to /trader/doGetShowPop/

11. in traderController.groovy
	// bhanu code start; date: 24-01-2018
	def doGetShowPop = { ... }
	def searchApp = { ... }
	// bhanu code ends; date: 24-01-2018

12. new file added in trader/searchApp.gsp



indApplicationDetails.id:3618716

indApplicationDetails.indUser.id:543818

indApplicationDetails.indUserUniversal.id:543818

indApplicationDetails.applicationType:CTO

indApplicationDetails.applicationFor:both

indApplicationDetails.applicationDate:2016-12-24 14:38:14.224

indApplicationDetails.applicationName:Riviera Home Furnishings Pvt. Ltd.

indApplicationDetails.certificateFor:new

indApplicationDetails.completionStatus:pending

indApplicationDetails.annualProdCap:5000.0

indApplicationDetails.noOfStack:0

indApplicationDetails.authorFor:

indApplicationDetails.clarification:false

indApplicationDetails.inspection:false

indApplicationDetails.recieptNo:

indApplicationDetails.bookNo:

indApplicationDetails.recieptDate:2016-12-24 14:38:12.778

indApplicationDetails.actualApplicationDate:2016-12-24 14:38:12.778

indApplicationDetails.consentFrom:01/04/2017

indApplicationDetails.consentTo:31/03/2020

indApplicationDetails.capitalInvestment:298.089996

indApplicationDetails.dateOfcommisioning:01/06/2007

indApplicationDetails.appDel:true

indApplicationDetails.cafUniqueNo:


1. completed the view form of trader application form industry side.
2. working on search application trader.
3. Fixed consent status live issue.
4. Add options in additional fee details.

For upload certificate


25-01-2018:

1. remove project id of user id
updateProjectIdForGivenUserId
Hp v Punia Ymn: Singal window id-PRtoKBPLPGpipeline Psw-PRKBP@2016
Hp v Punia Ymn: Hspcb id-16KAR3142996 psw-PRKBP@2016


previous single window user no. - 100f2ec5-ca5d-4b5f-9a70-d726fd770000
previous caf pin - 0170017845


16PIT3404123 PRKBP@2016 083785c3-9764-4f6b-b27a-d688ce767af9 0869107546

now i am setting the project id to blank

trader - 149480


trader changes:
1. note history industry side
2. show cause can be raised without preparing its certificate.
3. note history does not show the show cause is raised.



29-01-2018
----------


1. HazardousSourceGenMaster - schedule 1, 2 , 3, 4
2. HazardousCategoryMaster store th foreign key for HazardousSourceGenMaster
3. WasteManagementIndustryVerticalPageForHwm uncommented for testing remember to comment them again

4. call 
	description of waste - it is dropdown or textbox
	reminder of trader test link


A uniform string is a string consisting of a single character repeated zero or more times. For example, ccc and a are uniform strings, but bcb and cd are not (i.e., they consist of more than one distinct character).

Given a string s , , let U be the set of weights for all possible uniform substrings (contiguous) of string . You have to answer n queries, where each query i consists of a single integer x(i), . For each query, print Yes on a new line if x(i) E U; otherwise, print No instead.

U = {
	a = 1
	b = 2
	c = 3
	cc = 6
	d = 4
	dd = 8
	ddd = 12
	e = 5
}
1
abccddde
6
1
3
12
5
9
10

/Sub Class/Basel no./Waste

Name of Process Waste(Category No)

Detail/Reason of Subclass/Basel no./Waste

149619

30-01-2018
org.hibernate.HibernateException: Javassist Enhancement failed: AirEmiControlMeasureMaster
	at org.hibernate.proxy.pojo.javassist.JavassistLazyInitializer.getProxy(JavassistLazyInitializer.java:142)
	at org.hibernate.proxy.pojo.javassist.JavassistProxyFactory.getProxy(JavassistProxyFactory.java:72)
	at org.hibernate.tuple.entity.AbstractEntityTuplizer.createProxy(AbstractEntityTuplizer.java:402)
	at org.hibernate.persister.entity.AbstractEntityPersister.createProxy(AbstractEntityPersister.java:3483)
	at org.hibernate.event.def.DefaultLoadEventListener.createProxyIfNecessary(DefaultLoadEventListener.java:298)
	at org.hibernate.event.def.DefaultLoadEventListener.proxyOrLoad(DefaultLoadEventListener.java:219)
	at org.hibernate.event.def.DefaultLoadEventListener.onLoad(DefaultLoadEventListener.java:126)
	at org.hibernate.impl.SessionImpl.fireLoad(SessionImpl.java:905)
	at org.hibernate.impl.SessionImpl.internalLoad(SessionImpl.java:873)
	at org.hibernate.type.EntityType.resolveIdentifier(EntityType.java:590)
	at org.hibernate.type.EntityType.resolve(EntityType.java:412)
	at org.hibernate.engine.TwoPhaseLoad.initializeEntity(TwoPhaseLoad.java:139)
	at org.hibernate.loader.Loader.initializeEntitiesAndCollections(Loader.java:877)
	at org.hibernate.loader.Loader.doQuery(Loader.java:752)
	at org.hibernate.loader.Loader.doQueryAndInitializeNonLazyCollections(Loader.java:259)
	at org.hibernate.loader.Loader.doList(Loader.java:2228)
	at org.hibernate.loader.Loader.listIgnoreQueryCache(Loader.java:2125)
	at org.hibernate.loader.Loader.list(Loader.java:2120)
	at org.hibernate.loader.criteria.CriteriaLoader.list(CriteriaLoader.java:118)
	at org.hibernate.impl.SessionImpl.list(SessionImpl.java:1596)
	at org.hibernate.impl.CriteriaImpl.list(CriteriaImpl.java:306)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:39)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:25)
	at java.lang.reflect.Method.invoke(Method.java:592)
	at org.codehaus.groovy.runtime.callsite.PojoMetaMethodSite$PojoCachedMethodSiteNoUnwrapNoCoerce.invoke(PojoMetaMethodSite.java:229)
	at org.codehaus.groovy.runtime.callsite.PojoMetaMethodSite.call(PojoMetaMethodSite.java:52)
	at org.codehaus.groovy.runtime.callsite.AbstractCallSite.call(AbstractCallSite.java:120)
	at org.codehaus.groovy.grails.plugins.orm.hibernate.HibernatePluginSupport$_addQueryMethods_closure38_closure84.doCall(HibernatePluginSupport.groovy:455)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:39)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:25)
	at java.lang.reflect.Method.invoke(Method.java:592)
	at org.codehaus.groovy.reflection.CachedMethod.invoke(CachedMethod.java:86)
	at groovy.lang.MetaMethod.doMethodInvoke(MetaMethod.java:234)
	at groovy.lang.MetaClassImpl.invokeMethod(MetaClassImpl.java:1061)
	at groovy.lang.ExpandoMetaClass.invokeMethod(ExpandoMetaClass.java:910)
	at groovy.lang.MetaClassImpl.invokeMethod(MetaClassImpl.java:892)
	at groovy.lang.Closure.call(Closure.java:279)
	at org.codehaus.groovy.runtime.ConvertedClosure.invokeCustom(ConvertedClosure.java:48)
	at org.codehaus.groovy.runtime.ConversionHandler.invoke(ConversionHandler.java:77)
	at $Proxy8.doInHibernate(Unknown Source)
	at org.springframework.orm.hibernate3.HibernateTemplate.doExecute(HibernateTemplate.java:419)
	at org.springframework.orm.hibernate3.HibernateTemplate.execute(HibernateTemplate.java:339)
	at sun.reflect.GeneratedMethodAccessor4765.invoke(Unknown Source)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:25)
	at java.lang.reflect.Method.invoke(Method.java:592)
	at org.codehaus.groovy.runtime.callsite.PojoMetaMethodSite$PojoCachedMethodSite.invoke(PojoMetaMethodSite.java:188)
	at org.codehaus.groovy.runtime.callsite.PojoMetaMethodSite.call(PojoMetaMethodSite.java:52)
	at org.codehaus.groovy.runtime.callsite.AbstractCallSite.call(AbstractCallSite.java:124)
	at org.codehaus.groovy.grails.plugins.orm.hibernate.HibernatePluginSupport$_addQueryMethods_closure38.doCall(HibernatePluginSupport.groovy:451)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:39)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:25)
	at java.lang.reflect.Method.invoke(Method.java:592)
	at org.codehaus.groovy.reflection.CachedMethod.invoke(CachedMethod.java:86)
	at groovy.lang.MetaMethod.doMethodInvoke(MetaMethod.java:234)
	at groovy.lang.MetaClassImpl.invokeMethod(MetaClassImpl.java:1061)
	at groovy.lang.ExpandoMetaClass.invokeMethod(ExpandoMetaClass.java:910)
	at groovy.lang.MetaClassImpl.invokeMethod(MetaClassImpl.java:892)
	at groovy.lang.Closure.call(Closure.java:279)
	at org.codehaus.groovy.runtime.metaclass.ClosureStaticMetaMethod.invoke(ClosureStaticMetaMethod.java:55)
	at org.codehaus.groovy.runtime.callsite.StaticMetaMethodSite$StaticMetaMethodSiteNoUnwrapNoCoerce.invoke(StaticMetaMethodSite.java:148)
	at org.codehaus.groovy.runtime.callsite.StaticMetaMethodSite.call(StaticMetaMethodSite.java:88)
	at org.codehaus.groovy.runtime.callsite.CallSiteArray.defaultCall(CallSiteArray.java:43)
	at org.codehaus.groovy.runtime.callsite.AbstractCallSite.call(AbstractCallSite.java:116)
	at org.codehaus.groovy.runtime.callsite.AbstractCallSite.call(AbstractCallSite.java:124)
	at IndApplicationDetailsController$_closure53.doCall(IndApplicationDetailsController:5022)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:39)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:25)
	at java.lang.reflect.Method.invoke(Method.java:592)
	at org.codehaus.groovy.runtime.callsite.PogoMetaMethodSite$PogoCachedMethodSiteNoUnwrapNoCoerce.invoke(PogoMetaMethodSite.java:266)
	at org.codehaus.groovy.runtime.callsite.PogoMetaMethodSite.callCurrent(PogoMetaMethodSite.java:51)
	at org.codehaus.groovy.runtime.callsite.CallSiteArray.defaultCallCurrent(CallSiteArray.java:47)
	at org.codehaus.groovy.runtime.callsite.AbstractCallSite.callCurrent(AbstractCallSite.java:142)
	at org.codehaus.groovy.runtime.callsite.AbstractCallSite.callCurrent(AbstractCallSite.java:150)
	at IndApplicationDetailsController$_closure53.doCall(IndApplicationDetailsController)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:39)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:25)
	at java.lang.reflect.Method.invoke(Method.java:592)
	at org.codehaus.groovy.reflection.CachedMethod.invoke(CachedMethod.java:86)
	at groovy.lang.MetaMethod.doMethodInvoke(MetaMethod.java:234)
	at groovy.lang.MetaClassImpl.invokeMethod(MetaClassImpl.java:1061)
	at groovy.lang.ExpandoMetaClass.invokeMethod(ExpandoMetaClass.java:910)
	at groovy.lang.MetaClassImpl.invokeMethod(MetaClassImpl.java:892)
	at groovy.lang.Closure.call(Closure.java:279)
	at groovy.lang.Closure.call(Closure.java:274)
	at org.codehaus.groovy.grails.web.servlet.mvc.SimpleGrailsControllerHelper.handleAction(SimpleGrailsControllerHelper.java:363)
	at org.codehaus.groovy.grails.web.servlet.mvc.SimpleGrailsControllerHelper.executeAction(SimpleGrailsControllerHelper.java:243)
	at org.codehaus.groovy.grails.web.servlet.mvc.SimpleGrailsControllerHelper.handleURI(SimpleGrailsControllerHelper.java:203)
	at org.codehaus.groovy.grails.web.servlet.mvc.SimpleGrailsControllerHelper.handleURI(SimpleGrailsControllerHelper.java:138)
	at org.codehaus.groovy.grails.web.servlet.mvc.SimpleGrailsController.handleRequest(SimpleGrailsController.java:88)
	at org.springframework.web.servlet.mvc.SimpleControllerHandlerAdapter.handle(SimpleControllerHandlerAdapter.java:48)
	at org.codehaus.groovy.grails.web.servlet.GrailsDispatcherServlet.doDispatch(GrailsDispatcherServlet.java:264)
	at org.springframework.web.servlet.DispatcherServlet.doService(DispatcherServlet.java:807)
	at org.springframework.web.servlet.FrameworkServlet.processRequest(FrameworkServlet.java:571)
	at org.springframework.web.servlet.FrameworkServlet.doPost(FrameworkServlet.java:511)
	at javax.servlet.http.HttpServlet.service(HttpServlet.java:727)
	at javax.servlet.http.HttpServlet.service(HttpServlet.java:820)
	at org.mortbay.jetty.servlet.ServletHolder.handle(ServletHolder.java:502)
	at org.mortbay.jetty.servlet.ServletHandler$CachedChain.doFilter(ServletHandler.java:1124)
	at org.springframework.web.filter.OncePerRequestFilter.doFilter(OncePerRequestFilter.java:70)
	at org.mortbay.jetty.servlet.ServletHandler$CachedChain.doFilter(ServletHandler.java:1115)
	at org.springframework.web.filter.OncePerRequestFilter.doFilter(OncePerRequestFilter.java:70)
	at org.mortbay.jetty.servlet.ServletHandler$CachedChain.doFilter(ServletHandler.java:1115)
	at org.mortbay.jetty.servlet.ServletHandler.handle(ServletHandler.java:361)
	at org.mortbay.jetty.security.SecurityHandler.handle(SecurityHandler.java:216)
	at org.mortbay.jetty.servlet.SessionHandler.handle(SessionHandler.java:181)
	at org.mortbay.jetty.handler.ContextHandler.handle(ContextHandler.java:766)
	at org.mortbay.jetty.webapp.WebAppContext.handle(WebAppContext.java:417)
	at org.mortbay.jetty.servlet.Dispatcher.forward(Dispatcher.java:334)
	at org.mortbay.jetty.servlet.Dispatcher.forward(Dispatcher.java:126)
	at org.codehaus.groovy.grails.web.util.WebUtils.forwardRequestForUrlMappingInfo(WebUtils.java:293)
	at org.codehaus.groovy.grails.web.util.WebUtils.forwardRequestForUrlMappingInfo(WebUtils.java:269)
	at org.codehaus.groovy.grails.web.util.WebUtils.forwardRequestForUrlMappingInfo(WebUtils.java:261)
	at org.codehaus.groovy.grails.web.mapping.filter.UrlMappingsFilter.doFilterInternal(UrlMappingsFilter.java:181)
	at org.springframework.web.filter.OncePerRequestFilter.doFilter(OncePerRequestFilter.java:76)
	at org.mortbay.jetty.servlet.ServletHandler$CachedChain.doFilter(ServletHandler.java:1115)
	at org.codehaus.groovy.grails.web.sitemesh.GrailsPageFilter.obtainContent(GrailsPageFilter.java:171)
	at org.codehaus.groovy.grails.web.sitemesh.GrailsPageFilter.doFilter(GrailsPageFilter.java:110)
	at org.mortbay.jetty.servlet.ServletHandler$CachedChain.doFilter(ServletHandler.java:1115)
	at org.codehaus.groovy.grails.web.servlet.filter.GrailsReloadServletFilter.doFilterInternal(GrailsReloadServletFilter.java:101)
	at org.springframework.web.filter.OncePerRequestFilter.doFilter(OncePerRequestFilter.java:76)
	at org.mortbay.jetty.servlet.ServletHandler$CachedChain.doFilter(ServletHandler.java:1115)
	at org.codehaus.groovy.grails.web.servlet.mvc.GrailsWebRequestFilter.doFilterInternal(GrailsWebRequestFilter.java:65)
	at org.springframework.web.filter.OncePerRequestFilter.doFilter(OncePerRequestFilter.java:76)
	at org.mortbay.jetty.servlet.ServletHandler$CachedChain.doFilter(ServletHandler.java:1115)
	at org.springframework.web.filter.CharacterEncodingFilter.doFilterInternal(CharacterEncodingFilter.java:96)
	at org.springframework.web.filter.OncePerRequestFilter.doFilter(OncePerRequestFilter.java:76)
	at org.springframework.web.filter.DelegatingFilterProxy.invokeDelegate(DelegatingFilterProxy.java:236)
	at org.springframework.web.filter.DelegatingFilterProxy.doFilter(DelegatingFilterProxy.java:167)
	at org.mortbay.jetty.servlet.ServletHandler$CachedChain.doFilter(ServletHandler.java:1115)
	at org.mortbay.jetty.servlet.ServletHandler.handle(ServletHandler.java:361)
	at org.mortbay.jetty.security.SecurityHandler.handle(SecurityHandler.java:216)
	at org.mortbay.jetty.servlet.SessionHandler.handle(SessionHandler.java:181)
	at org.mortbay.jetty.handler.ContextHandler.handle(ContextHandler.java:766)
	at org.mortbay.jetty.webapp.WebAppContext.handle(WebAppContext.java:417)
	at org.mortbay.jetty.handler.HandlerWrapper.handle(HandlerWrapper.java:152)
	at org.mortbay.jetty.Server.handle(Server.java:324)
	at org.mortbay.jetty.HttpConnection.handleRequest(HttpConnection.java:534)
	at org.mortbay.jetty.HttpConnection$RequestHandler.content(HttpConnection.java:879)
	at org.mortbay.jetty.HttpParser.parseNext(HttpParser.java:741)
	at org.mortbay.jetty.HttpParser.parseAvailable(HttpParser.java:213)
	at org.mortbay.jetty.HttpConnection.handle(HttpConnection.java:403)
	at org.mortbay.io.nio.SelectChannelEndPoint.run(SelectChannelEndPoint.java:409)
	at org.mortbay.thread.QueuedThreadPool$PoolThread.run(QueuedThreadPool.java:522)
Caused by: java.lang.NullPointerException
	at javassist.util.proxy.RuntimeSupport$DefaultMethodHandler.invoke(RuntimeSupport.java:37)
	at AirEmiControlMeasureMaster_$$_javassist_319.$getStaticMetaClass(AirEmiControlMeasureMaster_$$_javassist_319.java)
	at AirEmiControlMeasureMaster.<init>(AirEmiControlMeasureMaster.groovy)
	at AirEmiControlMeasureMaster_$$_javassist_319.<init>(AirEmiControlMeasureMaster_$$_javassist_319.java)
	at sun.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method)
	at sun.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:39)
	at sun.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:27)
	at java.lang.reflect.Constructor.newInstance(Constructor.java:501)
	at java.lang.Class.newInstance0(Class.java:350)
	at java.lang.Class.newInstance(Class.java:303)
	at org.hibernate.proxy.pojo.javassist.JavassistLazyInitializer.getProxy(JavassistLazyInitializer.java:139)
	... 147 more

	indRegNum

	PrevenTion#1961

CTO completed application
149729

/home1/logs



session.indUser = 1 -> indName = 1
industryProfile = indName = 2

application.status = in-progress indUser.indName = 1


A numeric string 's' is beautiful if it can be split into a sequence of two or more positive integers, a1, a2, a3, a4, satisfying the following conditions

1. a[i] - a[i-1] = 1 for any 1< i <= n
2. No a[i] contain leading zeros. For example we can split s = 10203 into the sequence {1, 02, 03} but it is not beautiful because 02 and 03 have leading zero.
3. The contents of sequence cannot be rearranged. For example we can split = 312 into the sequence {3, 1, 2} but it breaks out first contraints ie. 1 - 3 != 1


Some beautiful string are:
1234 = 1 + 2 + 3 + 4
91011 = 9 + 10 + 11
99100 = 99 + 100


You must perform q queries, where each query consists of some string s. For each query, print whether or not the string is beautiful on a new line. If it's beautiful, print YES x, where is the first number of the increasing sequence (if there are multiple such values of , choose the smallest); otherwise, print NO instead 


Input format
The first line contains an integer denoting q (the number of strings to evaluate). 
Each of the subsequent lines contains some string for a query.

Output Format
For each query, print its answer on a new line (i.e., either YES x where is the smallest first number of the increasing sequence, or NO).


Sample Input
7
1234
91011
99100
101103
010203
13
1


Sample Output
YES 1
YES 9
YES 99
NO
NO
NO
NO


