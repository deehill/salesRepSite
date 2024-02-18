
readme_github_landingPage_overview_feb15_23.txt
This is intended to be a rough overview of the landingpage project for the JNI project. JNI is simply a placeholder name.  (It'll be changed later.)

Overall, JNI is intended to provide the cheapest textbooks possible to target colleges in the US. Think Chegg+The local bookstore. The ultimate idea is to have a user/student, get to the "bookstoreApp" and be presented the book/price based on the class the user selects. If the user buys the book, it gets shipped directly from the distributor. Nothing really special about the overall process. 

However, to get the "cheapest" book, JNI can't add a "cost" to the book, or it wouldn't be the "cheapest"!

JNI intends to create potential revenue by having local businesses that have an interest in the college community/students to advertise to the college users via the booksite, as well as eventually allowing having the system be a recruiting platform to businesses looking at the college community. 

To test all of this, and to verify it will work, we intend to have a series of MArketing/LandingPages directed to the different target users, for the overall system.

The basic JNI environment/world and the landing pages currently looks like:

UserLandingPageApp
 -tgts college students/users for cheap/cheaper textbooks
 -invites user to join, to be able to refer other users
 -overview of what/how the overall JNI process works
	bookstore
	local business advertising network
	recruiting platform
	access to select/currated Saas/AI applications -JNI Education Network
	
 -User Benefits/Pros/Cons


LocalBizLandingPageApp
 -tgts local businesses who want to engage/advertise to local 
	college students/users
 -invites local biz to join
 -overview of what/how the overall JNI/(local Biz) process works
	bookstore
	local business advertising network
	recruiting platform
	
 -Local Biz Benefits/Pros/Cons


SalesRepLandingPageApp
 -tgts college students/users who want to be a "SalesRep"
 -user would have joined the JNI system to view books
	from the "bookstoreApp"
 -invites localBiz tgts to join, need to define the "compensation"
	process
 -overview of what/how the overall Sales/Process works
	compensation process
	requirements to be a SalesRep
	advertising understanding - given this is what's being 
	 offered to the localbiz
	local business advertising network
	
 -Sales/Rep Benefits/Pros/Cons



AdServer Platform
adServerLandingPage
	Demonstrates to the LocalBiz how to advertise to the College User 
	 via the Booksite/messaging
	How to create basic ad campaigns
 -lets LocalBiz get familar with self advertising on the platform/process
 -overview of what/how the overall Ad Process works
	local business advertising network
	how it ties into the bookstore process
	different ad tiers -- features/pricing


JNI Bookstore
 The reason for the overall process!!
 -Bookstore Process/Platform allows the user to signup/register to 
	get the cheapest books possible
 -User selects classes, site displays the book data/price
 -user can place in cart/purchase
 -process works like other sites
 -user gets to refer other users to buy
 	referral process gets more benefits 
	 from local biz partners/saas partners/etc


Admin Platform
AdminProcessLandingPage
 Define/Create Admin Platform for Landing Page apps
 -used internally -- not for external users
 Manage/track/deal with site data
 All the usual Admin functions
 Placeholder for now


CRM/Database Platform
CRMProcessLandingPage
 -tie into the above LandingPage webapps to manage/track data
 -generate reports/analysis
 -define required functions/actions
 -placeholder
 -etc



MonitoringProcessLandingPage
 Define/Create Monitoring Platform for Landing Page apps/users/servers
 -used internally -- not for external users
 Manage/track/deal with site data/server/db/user/networ activity
 All the usual Monitoring functions
 Placeholder for now


test dev servers
-will run on digital ocean droplets
 ubunutu
 php/python/node
 mysql/postgres
 etc


documentation/comments/issues
 github for now
 some sort of projMgmt platform asap


to start:
 there is/are initial websites located at 
http://161.35.5.174/wave/# <<< composer app  more less demonstrative of UX/UI
http://161.35.5.174/lpuser  <<< reactjs  doesnt work

https://github.com/adith-a-danthi/hoobank.git <<<  reactjs
 /*
	it appears the test github hobank doesnt have a build folder..
	--not sure what has to happen to get this to rnu 
 */
https://github.com/thedevdojo/wave.git  <<<< wave


***!!! need to figure out how to build/install/run a sample reactjs/apache2/ubuntu test app



