## ImmiDB Admin How To

  [How to Access Admin](#user-content-how-to-access-admin)<br>
  [How to Edit User Profile](#user-content-how-to-edit-user-profile)<br>
  [How to Edit a Password](#user-content-how-to-edit-a-password)<br>
  [What are User Roles](#user-content-user-roles)<br>
  [How to Enable/Disable User Roles](#user-content-how-to-enable-user-roles)<br>
  [How to Set up EOIR Integration](#user-content-set-up-eoir-integration)<br>
  [How to Set up SMS Texting](#user-content-twilio-setup)<br>


<a id="how-to-access-admin"></a>
### How to Access Admin
1. [Verify](#user-content-how-to-enable-user-roles) that you have an [Admin role (ADM or AOM)](#user-content-user-roles)
2. Make sure that you have an Admin [role enabled/applied](#user-content-how-to-enable-user-roles)
3. Click the Nav Setup icon and then click "Admin"

  <img src="https://immidb.net/imgs/space_indent.png" 
    width="60" height="10" style="border:5px solid black"/>
  <img src="https://immidb.net/imgs//nav_setup_menu.png" 
    width="225" height="200" style="border:5px solid black"/>

4. You should see the Admin tabs similar to the following based on your role. Click the appropriate tab (eg, 'Company', 'Users', etc). 

  <img src="https://immidb.net/imgs/space_indent.png" 
    width="60" height="10" style="border:5px solid black"/>
  <img src="https://immidb.net/imgs//admin_subnav.png" 
    width="600" height="150" style="border:5px solid black"/>


<a id="how-to-edit-user-profile"></a>
### How to Edit User Profiles

Only Admin roles (ADM, OAM) have authority by default to view and edit User Profiles including passwords. 

1. [Go to Admin](#user-content-how-to-access-admin)
2. Click Users

<a id="how-to-edit-a-password"></a>
### How to Edit an Encrypted Field like a Password
Some fields like passwords are "double" encrypted.  All data is encrypted at rest and in transit but especially sensitive data like passwords provides another layer of encryption.  You can identify these fields by the eye icon to the right of the field. Click the eye icon to view and edit the field.  After editing the field, click tab or enter like any other field, to save it. 'Undo' is not available on these fields. 

  <img src="https://immidb.net/imgs/space_indent.png" 
    width="20" height="10" style="border:5px solid black"/>
  <img src="https://immidb.net/imgs//user_password.png" 
    width="300" height="80" style="border:5px solid black"/>

  <img src="https://immidb.net/imgs/space_indent.png" 
    width="20" height="10" style="border:5px solid black"/>
  <img src="https://immidb.net/imgs//user_password_edit.png" 
    width="300" height="80" style="border:5px solid black"/>


<a id="user-roles"></a>
### What are User Roles
The role(s) that are are assigned to a user determine what access that user has.  Roles are assigned to users on their User Profile page.  

  <img src="https://immidb.net/imgs/space_indent.png" 
    width="20" height="10" style="border:5px solid black"/>
  <img src="https://immidb.net/imgs//user_roles_select.png" 
    width="800" height="200" style="border:5px solid black"/>

Each user must be assigned the BAS ('Basic') role which provides minimum access.  The 'Roles to Include on Login' allows for enabling or disabling Roles by that user.  In the above example, the user would only have the BAS role on login but could quickly enable the 'ADM' role after login when needed.  This is to prevent accidental changes authorized by higher level roles or limiting what is viewed on a user's screen (eg, FIN role).  

The system defaults for user roles are: 
* __BAS - 'Basic'. Required for each user. Provides most client functionality__ including:
  * Create clients
  * View and edit client information except as listed in roles below
  * View Client List and filter clients
  * Search all clients 
  * Cannot view or edit : 
  	* Admin functions (ADM, AOM)
  	* Trust and Transaction Summaries (FIN, FAS)
  	* Txtn columns or any data related to "Txfr to Trust", "Txfr to Business", "Trust Balance"

* __FAS - 'Financial Assistant'.  Access to BAS Transaction details for any single date__; ie, the "Txtns" / "Txtns" tab/sub-tab. This is intended mainly to allow these users to reconcile payments received for a given date. Does not allow access to Fincial Summaries (FIN). 

* __FIN- 'Financial'. FULL financial authority__ including: 
  * Full access to transaction totals and summaries: 'Txtn' tab with 'Summary by Date', 'Summary by Client', 'Txtns' (for a given date)
  * Full view and edit for Trust amounts: Client txtn columns "Txfr to Trust", "Txfr to Business", "Trust Balance"

* __OAM - "Office Admin"__.  Allows limited access to Application Admin functions including: 
  * View 
  	* Admin Company info
  	* Notices
  	* Security
  	* Logs 
  * Edit 
  	* User info (Can only add/remove FAS, OAM roles for users)
  	* Admin Docs & Files (Invoice header/footer)
  	* Alerts
  * View and Edit select Meta 
  * Does not include access to any other roles if not added explicitly (eg, BAS + OAM would not including any FAS or FIN access)

* __ADM - 'Application Admin'__. Highest Admin authority after System Admin. All OAM access plus
  * Edit 
    * Security
    * Admin User info - all roles except SYS
  * Does not include access to any other roles if not added explicitly (eg, BAS + OAM would not including any FAS or FIN access)

* __SYS__ -  'System Admin'.  Full access to all admin functions.  

<a id="how-to-enable-user-roles"></a>
### How to Apply (Enable/Disable) User Roles
This explains how to enable and disable user roles to which you are authorized.  See [User Roles](#user-content-user-roles) on authorizing roles for each user.

If a user has more than just the BAS role, the other Roles can be enabled and disabled after login.  This is to prevent accidental changes authorized by higher level roles or limiting what is viewed on a user's screen (eg, FIN role).  

1. Select the dropdown next to your Name in the upper right nav

    This shows which roles you are authorized for.  This user, 'TESTADM', is authorized to the BAS, ADM and FIN roles.  S/he currently has just the ADM role enabled (BAS is always enabled).  

  <img src="https://immidb.net/imgs/space_indent.png" 
    width="20" height="10" style="border:5px solid black"/>
  <img src="https://immidb.net/imgs//user_login_roles.png" 
    width="200" height="300" style="border:5px solid black"/>

2. Check/Uncheck those roles to which you want access.

    In the above example, TESTADM can select the FIN role.  S/he will automically be logged back in with the BAS, ADM and FIN roles with access to all functionality for those roles.  

<a id="set-up-eoir-integration"></a>
### How to Set Up EOIR Integration

1. Confirm with your Sys Admin that daily EOIR sync is set up
  
    This setup is normally done on initial database setup.  The EOIR sync job typically runs nightly.  Check with your Sys Admin for more information.

2. Enter EOIR ID and EOIR Password on User Profile page.  
    
    See [How to enter a password](#user-content-how-to-edit-a-password). 

  <img src="https://immidb.net/imgs/space_indent.png" 
    width="20" height="10" style="border:5px solid black"/>
  <img src="https://immidb.net/imgs//user_eoir.png" 
    width="400" height="100" style="border:5px solid black"/>

3. Keep your EOIR Password in sync with the ImmiDB EOIR password

    The EOIR ID and Password must match the same ID and password used to log into [the EOIR court site](https://portal.eoir.justice.gov/).  
    
    Whenever you change the password on the EOIR site, remember to also update it in your ImmiDB user profile.  If not, the database admin will receive an alert that the sync job failed for logging in that user.  


<a id="twilio-setup"></a>
### How to Set Up SMS Texting 
To send texts (see [How to Send an SMS Text](https://immidb.net/how_to.html#user-content-send-an-sms-text) ) from ImmiDB, a Twilio account with an SMS phone number needs to be established.  This is also required to send Texts for Multi-Factor Authentication (MFA).  The Twilio cost is based on the number of texts that you send but the cost is quite reasonable; most smaller firms would see only a few dollars a month.  

1. Create a Twilio Account https://www.twilio.com

2. Create your new phone number in Twilio.  It only needs to be SMS enabled for these purposes. 

3. Enter the Twilio AuthID, Auth Token and your new Twilio phone number in ImmiDB Admin / Twilio 

  <img src="https://immidb.net/imgs/space_indent.png" 
    width="20" height="10" style="border:5px solid black"/>
  <img src="https://immidb.net/imgs//admin_twilio2.png" 
    width="700" height="325" style="border:5px solid black"/>



