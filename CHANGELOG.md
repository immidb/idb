[<span class="headeranchor"></span>](#knn-database-change-log)Change Log
=====================================================================================

#### v2.10.0: [Priority Date, Tabbing](https://github.com/immidb/idb/milestone/16?closed=1) (Jan 18, 2018)
- [[160]](https://github.com/tonybranfort/immidb/issues/160) (feat) Add Priority Date to client detail
- [[89]](https://github.com/tonybranfort/immidb/issues/89) (feat) Tab key should put focus on next logical cell
- [[174]](https://github.com/tonybranfort/immidb/issues/174) (bug) 'TAB' after editing field sometimes scrolls to odd positions
- [[173]](https://github.com/tonybranfort/immidb/issues/173) (bug) Client DOB is displaying based on local time


#### v2.9.0: [EOIR Multi Attorney, Case Type](https://github.com/immidb/idb/milestone/15?closed=1) (Jan 15, 2018)
- [[149]](https://github.com/tonybranfort/immidb/issues/149) (feat) Update EOIR case to accept multiple attorneys
- [[171]](https://github.com/tonybranfort/immidb/issues/171) (feat) Remove Attorneys from EOIR that are removed from EOIR immigration court site
- [[168]](https://github.com/tonybranfort/immidb/issues/168) (feat) Change Case Number to Case Type, multi-select with typeahead
- [[169]](https://github.com/tonybranfort/immidb/issues/169) (feat) Add alert list view (admin)
- [[167]](https://github.com/tonybranfort/immidb/issues/167) (feat) Add version to Nav settings menu
- [[170]](https://github.com/tonybranfort/immidb/issues/170) (bug) Issue w/ changing a Derivative from manual A-Number to a Client w/ A-Number

#### v2.8.1: [EOIR Bug Fixes](https://github.com/immidb/idb/milestone/13?closed=1) (Dec 28, 2017)
- [[166]](https://github.com/tonybranfort/immidb/issues/166) (bug) EOIR Load login failure improvement
- [[165]](https://github.com/tonybranfort/immidb/issues/165) (bug) Unable to update user EOIR password on user profile page


#### v2.8.0: [Create Base Alerts (admin only)](https://github.com/immidb/idb/milestone/12?closed=1) (Dec 20, 2017)
- [[158]](https://github.com/tonybranfort/immidb/issues/158) (feat) Alerts: Create Base;Alert sysadmin on app server reboot (no end user functionality change)

#### v2.7.0: [File upload, view previously created invocies, +](https://github.com/immidb/idb/milestone/12?closed=1) (Dec 18, 2017)
- [[111]](https://github.com/tonybranfort/immidb/issues/111) (feat) Ability to view Invoices previously created
- [[153]](https://github.com/tonybranfort/immidb/issues/153) (feat) User's ability to upload files related to a client
- [[157]](https://github.com/tonybranfort/immidb/issues/157) (feat) Add functionality to record unique event id in logging (no end user change)
- [[159]](https://github.com/tonybranfort/immidb/issues/159) (bug) Fix bug Unable to save user password

#### v2.6.0: [Reformatted Invoice to PDF, EOIR updates, +](https://github.com/immidb/idb/milestone/11?closed=1) (Dec 6, 2017)
- [[152]](https://github.com/tonybranfort/immidb/issues/152) (feat) Reformat Invoice - First page as overview / Txtn List start on 2nd page
- [[134]](https://github.com/tonybranfort/immidb/issues/134) (feat) Print Invoice to pdf rather than html
- [[94]](https://github.com/tonybranfort/immidb/issues/94) (feat) Client Invoice template should be user maintainable
- [[148]](https://github.com/tonybranfort/immidb/issues/148) (feat) EOIR Case List display updates
- [[15]](https://github.com/tonybranfort/immidb/issues/15) (perf) Create database index for Messages filtering on 'markedRead'
- [[151]](https://github.com/tonybranfort/immidb/issues/151) (bug) Fix Client Search not searching some fields if line break in multi line field
- [[150]](https://github.com/tonybranfort/immidb/issues/150) (bug) Fix Logo is not appearing in Nav bar
- [[21]](https://github.com/tonybranfort/immidb/issues/21) (bug) Fix Logo in nav flashes on any navigation
- [[147]](https://github.com/tonybranfort/immidb/issues/147) (framework) Upgrade to node 8.9

#### v2.5.0: [EOIR Case Detail View](https://github.com/immidb/idb/milestone/10?closed=1) (Nov 26, 2017)
- [[131]](https://github.com/tonybranfort/immidb/issues/131) (feat) Add EOIR case detail view (on client detail page)
- [[142]](https://github.com/tonybranfort/immidb/issues/142) (feat) Update EOIR Court Hearings list: show Client(s) with link to client(s), aNbr, formatting updates
- [[144]](https://github.com/tonybranfort/immidb/issues/144) (feat) Formatting updates to Client Detail: Add section panel headers (no functionality change)
- [[146]](https://github.com/tonybranfort/immidb/issues/146) (feat) Checkbox buttons should also require click before edit; eg, Client Detail txtn buttons "Balanced","Txtns Verified" now require one click to turn it to edit mode and then a 2nd click to toggle the value (check/unchecked)
- [[145]](https://github.com/tonybranfort/immidb/issues/146) (feat) Always scroll to top of Client Detail on search or transition
- [[141]](https://github.com/tonybranfort/immidb/issues/146) (feat) Add auth to eoir hearings list

#### v2.4.0: [Add EOIR Court Calendar; ng-upgrade prep](https://github.com/immidb/idb/milestone/9?closed=1) (Nov 12, 2017)
- [[130]](https://github.com/tonybranfort/immidb/issues/130) (feat) Add the EOIR Immigration Court view and show on the home page. 
- [[133]](https://github.com/tonybranfort/immidb/issues/133) (change) Print invoice to html rather than pdf (remove dependence on phantom/phantomjs frameworks)
- [[137]](https://github.com/tonybranfort/immidb/issues/130) (fix) Remove client phone number from invoice (was displaying the old client number: pre v.2.2.0)
- [[128]](https://github.com/tonybranfort/immidb/issues/128) (fix) Fix "Message has no associated note" error that was occurring when user device dropped network connection (like when device would go to sleep) and client note modal was left open.
- [[129]](https://github.com/tonybranfort/immidb/issues/129) (fix) Clicking new Task button on Client Detail shows error in log (no functionality impact)
- [[136]](https://github.com/tonybranfort/immidb/issues/136) Minor update to client search (no functionality impact other than possible performance improvement)
- [[127]](https://github.com/tonybranfort/immidb/issues/127) (feat) Add Webpack and Typescript to prepare for ng-upgrade (coding framework change; no functionality impact)
- [[138]](https://github.com/tonybranfort/immidb/issues/138) (feat) Test & upgrade to mongo database version 3.4 (from 3.2) (framework change; no functionality impact)

#### v2.3.0: [Load eoir cases](https://github.com/tonybranfort/immidb/milestone/8?closed=1) (Oct 15, 2017)
- [[86]](https://github.com/tonybranfort/immidb/issues/86) (feat) Load eoir immigration court info from eoir site.  This is for the data load only; is not yet visible to users.  
- [[126]](https://github.com/tonybranfort/immidb/issues/126) (bug) Client search by phone shows the old phone (< v2.1) in client search results.


#### v2.2.0 [Phones & EOIR Prep](https://github.com/tonybranfort/immidb/milestone/5?closed=1) (Sept 31, 2017)
- [[33]](https://github.com/tonybranfort/immidb/issues/33) (feat) Ability to enter multiple phone numbers for a client 
- [[87]](https://github.com/tonybranfort/immidb/issues/87) (feat) EOIR login info added to User profile
- [[91]](https://github.com/tonybranfort/immidb/issues/91) (feat) Prevent Invalid A-Numbers on Client and Derivatives
- [[75]](https://github.com/tonybranfort/immidb/issues/75) (feat) Enter key saves field when editing
- [[125]](https://github.com/tonybranfort/immidb/issues/125) (feat) Update Delete Icon graphic; show on Txtn List row hover
- [[98]](https://github.com/tonybranfort/immidb/issues/98) (bug) Parentheses or other special characters could cause client search error

#### v2.1.0: Txtn List by Date (Sept 18, 2017)
- [[1]](https://github.com/tonybranfort/immidb/issues/1) Create Transaction List by Date
- [[58]](https://github.com/tonybranfort/immidb/issues/58) Paginate Client List (faster)
- [[81]](https://github.com/tonybranfort/immidb/issues/81) Reformat Client Name on Client Detail page
- [[77]](https://github.com/tonybranfort/immidb/issues/77) Upgrade and test on nodejs 6.11.3


#### v2.0.1: Patches (Sept 10, 2017)
- [[72]](https://github.com/tonybranfort/immidb/issues/72) Message Notify dropdown closes when selecting element in dropdown (should stay open)
- [[38]](https://github.com/tonybranfort/immidb/issues/38) Auth selector dropdown should stay open upon selection
- [[69]](https://github.com/tonybranfort/immidb/issues/69) Deleted Client transactions being included in Txtn Summary
- [[71]](https://github.com/tonybranfort/immidb/issues/71) Unable to change User Role via Login name dropdown when on Client Detail and Home pages


#### v2.0.0 : Client Detail Rewrite (Sept 08, 2017)
* General / Navigation
  - [10](https://github.com/tonybranfort/immidb/issues/10) Create client 'refid': a simpler, more useable client id.  client refId is displayed in url rather than client _id. 
  - [67](https://github.com/tonybranfort/immidb/issues/67) Create home page that is displayed on login.  Currently has no detail, will be added later. 
  - [51](https://github.com/tonybranfort/immidb/issues/51) Print Invoice button now in upper Nav. 
  - [53](https://github.com/tonybranfort/immidb/issues/53), [36](https://github.com/tonybranfort/immidb/issues/36), [65](https://github.com/tonybranfort/immidb/issues/65) Create New Client and New Transaction modals.  Button for each now in upper Nav. 
  - Client name displayed in Nav. Previously viewed clients in session can be recalled via dropdown next to nav client search. Client Search always in upper nav. 
  - [62](https://github.com/tonybranfort/immidb/issues/62) Fix derivative client name & ARN for display and search


* Client Detail
  - [34](https://github.com/tonybranfort/immidb/issues/34) Undo capability while on page. Consistent field display indicating if user changed value
  - Layout changes (non major) for more consistent display
  - USCIS App List shows additional detail including days pending
  - [14](https://github.com/tonybranfort/immidb/issues/14) Only show first 10 calendar appointments for a client (in case recurring appointment)
  - [52](https://github.com/tonybranfort/immidb/issues/52) Notes list - Show only one line per note in notes list; show 5 notes 

* Transaction Summary
  - [57](https://github.com/tonybranfort/immidb/issues/57) Add filter to Txtn Summary by Client default to Trust Balance <> 0, sort by Trust Balance descending 
  - [49](https://github.com/tonybranfort/immidb/issues/49) Add New Txtn button to Txtn Summary by Client list rows
  - [57](https://github.com/tonybranfort/immidb/issues/57) Add pagination to Txtn Summary by Client (show first 100 rows by default)


* Bug Fixes
  - [51](https://github.com/tonybranfort/immidb/issues/51) "Unable to Retrieve Note" error
  - [12](https://github.com/tonybranfort/immidb/issues/12) Fatal server error from google calendar callback

* Framework (non-functional)
  - [54](https://github.com/tonybranfort/immidb/issues/54) Upgrade to Angularjs 1.6 from 1.3
  - [63](https://github.com/tonybranfort/immidb/issues/63) Upgrade Mongoose framework from 4.7.7 to 4.10.5
  - [68](https://github.com/tonybranfort/immidb/issues/68) Upgrade angular-bootstrap from 0.13 to 2.5
  - [66](https://github.com/tonybranfort/immidb/issues/66) Convert to ui-router from angularjs $routeProvider


### Mar 11, 2017 - v1.22.1 : Message List Pagination minor
------------------------------------------------------------------------------------------------------------------------
- Message service - modify const to var for invoice creation

## Mar 11, 2017 - v1.22.0 : Message List Pagination
------------------------------------------------------------------------------------------------------------------------
#### Message List
- Show only the first 20 unread messages in the message list displayed in left pane. Can show more unread messages by expanding list by clicking more icon at bottom of list. 

### Feb 24, 2017 - v1.21.3 : Minor non-functional for login/session
- Minor non-functional update on ping retrieval to prevent error in browser log

### Feb 24, 2017 - v1.21.2 : Minor security login updates
#### Security login / session updates
- Add check to log user out automatically when session expires rather than waiting for next user request
- Update to brute force check so that successful login resets brute force counter for that IP

### Feb 11, 2017 - v1.21.1 : Minor Invoice updates
#### Invoice
- Update invoice pagination for better pdf fit
- Use config port for target invoice url (no functional impact)

## Feb 11, 2017 - v1.21.0 : Continued Security Hardening; Company logo  
------------------------------------------------------------------------------------------------------------------------

#### Security updates (no user impact)
- Framework packages updated to current versions for security, currency and performance 
- nodejs upgraded to 6.9
- Additional framework packages added for security hardening including to mitigate brute force attacks
- Google tokens encrypted
- Logging and error tracking updated 

#### Administration 
- Company logo can now be uploaded and administered (admin/company)

#### Client-detail
- Added keyboard short ('s') for nav client search.  (Keyboard shortcuts vary by browser: 'alt-s' for Chrome, 'shift-alt-s' for Firefox)

#### Invoice
- Invoice pdf may have slight changes in font sizes and pagination (but no change in content) due to version upgrade in pdf creator package

#### Error Messages
- Server error messages returned to users, included database errors, updated

### Jan 24, 2017 - v1.20.1 : Txtns view bug fix  

#### Client transactions
- Fix bug where a transaction that only has details entered is not displayed for non-FIN

## Jan 21, 2017 - v1.20.0 : Security - MFA, User Roles, Login  
------------------------------------------------------------------------------------------------------------------------

#### New Functionality Changes
- Multi-Factor Authentication (MFA) available
- New Admin functionality / pages: Company, Notifications (login), Users, Security (MFA, IP Addresses, MFA Devices), Twilio
- User page updates:  for admins to allow MFA options, cell phone (text), roles
- User change roles option (if have multiple) and choose which are on at login
- Client Balance and Trust Balance added to Txtns page
- Bug fix: txtns from previously viewed client still displayed when click New Click button
- Admin auths fully controls restricted elements; hard coded restrictions removed
- Login page notifications and company info

#### Changes which do not directly affect front-end functionality
- Change user role (singular) to roles (multiple)
- Remove login page from angular app
- Implement cookies for session and to identify which devices are known/passed MFA checks
- Security hardening in back-end data with encryption 

## Nov 27, 2016 - v1.19 : Transaction Summary by Client  
------------------------------------------------------------------------------------------------------------------------

#### Txtn Summary
- Add report to view transaction totals and balances by client 
- Add tabs to Txtn Summary page - "by date", "by client"
- Display Txtn Totals on Txtn Summary page only

## Sept 29, 2016 - v1.18 : Calendar Repeating Events  
------------------------------------------------------------------------------------------------------------------------

#### Calendar
- Add functionality to be able to create Repeating (Recurring) Calendar Events

#### Nav
- Update logo 

#### Invoice
- Update Header & Footers for greater flexibility

#### Client-Detail Transactions
- Fix bug where transaction list was sometimes cut off if too long

## Sept 12, 2016 - v1.17.1 : Meta bug fix 
------------------------------------------------------------------------------------------------------------------------

#### Meta
- Fix bug when adding a new Fixed Value would not be added if it was the first Fixed Value

## Sept 11, 2016 - v1.17.0 : Meta 
------------------------------------------------------------------------------------------------------------------------

#### Meta
- Add ability to edit Meta (field) values.  'Meta Admin' appears under configuration menu. 

#### Auth
- Add functionality to edit authorizations at Object and Property levels

#### Task
- Add type-ahead to task task input box (values controlled via Meta Task.Task)

#### Misc
- Modify most modal pop-ups so they won't close if you click outside the modal

## Aug 7, 2016 - v1.16.0 : 
------------------------------------------------------------------------------------------------------------------------

#### Client Detail 
- **File Location**: New field. Included in client search. 
- **Assigned**: Can now enter mulitiple users as assigned to a client (used to be just one).  
- **Derivative Comment**: New field on add/edit Derivative.  Included in client search. 
- **Tasks list**: Bug fixed where filter on task list tab by task name or due date affected task list on client detail page.

#### User Maintenance
- A user can now be disabled.  Previously had to be deleted when no long a user.  Disabling a user removes them from being a valid selection in user dropdowns including client assigned, uscis app submitted, task assigned.  But fields will still retain a disabled user until re-assigned.  Assigned filters will continue to allow a disabled user in the dropdown until that disabled user is no longer a value within that respective filter field.  

## July 23, 2016 - v1.15.0 : Client Search Improvement
------------------------------------------------------------------------------------------------------------------------

####  Client Search
- Improved client search in nav bar that allows multiple query terms and partial terms for searching and includes name, phone, language, address, alien registration number, applications, derivatives, email, case overview, country of citizenship, case number and invoice comment in the search by default.  Search results display fields that match and highlight terms that match.

#### Client Detail 
- **Office**: New field; dropdown with Minneapolis & New York
- **Bond Obligor**: New field as textbox
- **Txtns Balanced**: New field as checkbox
- **Derivatives**: Add 'Sibling' and 'Other' to relationship type dropdown
- Minor usability change: Add print invoice button above transaction list; update format with Invoice OK by KNN button. 

## June 26, 2016 - v1.14.0 : Back-end security update (flex-acl); minor functionality changes
------------------------------------------------------------------------------------------------------------------------

####  Client List
- Add spinner that indicates when client lists are loading

#### Other
- Txtn smry formatting updates
- Diminish periodic calendar events retrieval timeout error (from google) by adding automatic retry

#### Maintenance / Non-functional changes
- Replace back end api security with flex-acl
- Minify js files 

##May 2, 2016 - v1.13.0 : Google Calendar Appointments
------------------------------------------------------------------------------------------------------------------------

####  Google Calendar Appointments
- Google Calendar Appointments can be added, modified or deleted within the application. 
- Add Calendar Appointment button added to nav bar.  
- Appointments can be associated with a one or more client by selecting those client(s) on the add/edit appointment modal within the app.  If an appointment is associated with a client(s), those appointments are listed on that client's client detail page.  
- Currently scheduled appointments are displayed in the start time dropdown on the add/edit appointment modal window to easily see any potential conflicts.  
- Appointment title is automatically updated with client's display name and A-Number when a client is picked on a appoinment. 
- Modifications to appointments made outside of the app such as in Google or Outlook will be reflected immediately within the app and vice-versa.  (Appointments are not saved in this database but saved to and pulled from Google.)
- Appointments that are not made within the app currently cannot be modified within the app such as to assign a client to it. 

#### Google Login
- Non-functional changes maded to Google Login (no change to user interface).  Login moved from client side to server side.  

#### Client Detail Transactions
- Fix bug that sometimes changed the default transaction date from today to tomorrow. 


##Februay 12, 2016 - v1.12.0 : USCIS case status
------------------------------------------------------------------------------------------------------------------------

####  Client Detail - Applications
- Display 'live' case status pulled from [USCIS case status website](https://egov.uscis.gov/casestatus/landing.do) using receipt number
    * Display on Application List on client detail page
    * Display on Add/Edit Application modal whenever 13 digit receipt # is entered


##Februay 7, 2016 - v1.11.0 : Tasks
------------------------------------------------------------------------------------------------------------------------

####  Tasks
- Add task and task list functionality
  - Create and edit tasks (Add task on nav bar)
  - View and filter tasks on task list (Task list from nav bar)
  - Assign task to one or more clients and see their tasks on the client detail page 
  - Assign task to one or more users; each sees their tasks in their default task list
  - Users notified of new tasks assigned to them by others via task badge count in nav
  - Mark tasks complete, cancelled, important

#### Nav Updates
- Update "Client Search By" in Nav 
    * Is now a dropdown to select which fields to search by (previously was an input box)
    * Can now search by case number
- "Add note" button changed to an icon

#### Client Detail
- "Add Client" button changed to an icon
- Transactions grid modified for better viewability (no scroll bars) 


##Februay 1, 2016 - v1.10.4 : Transaction table editing issue fix
------------------------------------------------------------------------------------------------------------------------

####  Client Detail - Txtns
- Fix txtn editing issues caused by upgrade of google Chrome browser.  
- Txtn cells are now edited with a double-click rather than single click. 
- Upgrade from ngGrid 2.x to uiGrid 3.1 to resolve the txtn editing issue. 

##January 24, 2016 - v1.10.3 : Minor Bug Fixes
------------------------------------------------------------------------------------------------------------------------

####  Client Detail
- Txtns: Don't allow txtns to be saved without a txtn date; display error.  Txtns Summary: Don't error out if txtns don't have a txtn date. 

#### Email
- Fix where email icons were incorrectly showing in message list and on note / notify log for users that were included in a message that weren't sent an email but other users in that same message were sent an email.  

#### Non-functional
- Fix errors being logged without createdUID

##January 5, 2016 - v1.10.2 : Fix Email Send Failure
-------------------------------------------------------------------------------------------------------------------------

#### Fix issue when emails would not be sent when 3 or more recipients are chosen
- If 3 or more recipients were chosen for email in Notify on a note, the note would be saved but an error (not displayed) would prevent 
- Add error catch so that if email object is invalid (as was the case here), the error is displayed.

##December 19, 2015 - v1.10.1 : Gmail Expiring Login Fix
------------------------------------------------------------------------------------------------------------------------

#### Fix issue of expiring Gmail login causing authentication error
- Gmail login would expire causing an authentication error when sending an email from withing the application.  
- Clicking the Email button next to a user in the Notify (Notes) dropdown automatically checks if the login is expired.  If it is, it will log the user into google.    
- Nav now reflects when the login expires


##December 12, 2015 - v1.10.0 : Gmail
------------------------------------------------------------------------------------------------------------------------

#### Gmail - Login 
- Integrate Gmail login.  Prompt to log into Gmail occurs automatically when the app is first loaded.  Nav bar shows Gmail Address and ability to log out (or log in if not logged in). 

#### Client Detail : Add/Edit Note 
- Now have the ability to select "Email" from the Notify dropdown for a user on the Add/Edit Note dialog.  Selecting this will email that note to the KNN user.  
- Message history popup shows the Gmail icon next to the message if it was emailed for that user.  
- Message list has a Gmail icon next to the message if it was emailed. 


##November 17, 2015 - v1.9.1 : Fix IP Addresses 
------------------------------------------------------------------------------------------------------------------------

#### Fix
- Administrative update only to fix list of known ip locations (office, home, etc) as ip addresses in web server now are ipv6 mapped addresses.  No functionality changes. 


##November 6, 2015 - v1.9.0 : Error Handling Updates
------------------------------------------------------------------------------------------------------------------------

#### Error Handling 

-   Mostly an administrative update to better handle errors if/when they occur on the server.  This can occur, for example, if an invalid value is attempted to be saved and is not handled correctly in the code.  
-   Errors are displayed more consistently when they occur at top of page with additional detail .  
-   Errors that occur on server are more consistently handled and recorded to the errors database.    

#### Client-Detail 
-   **Transaction Amounts** - Only allow numbers to be entered into any of the transaction amount fields.  Previously any non-number could be entered which generated an error.  
-   **Delete Transactions** - Delete is disabled on transactions that have other financial history or detail associated with them that prevents being deleted.   

[<span class="headeranchor"></span>](#October 12-2015-v180-client-search)October 12, 2015 - v1.8.0 : Client Search 
------------------------------------------------------------------------------------------------------------------------

#### [<span class="headeranchor"></span>](#client-detail)Client Detail 

-   **Client Search By (in top nav bar):** Add ability to search clients by : 
      - Derivatives (derivative name and alien registration number)
      - Address (street1, street2, city, zip)
      - Alien Registration Number
      - Citizenship
      - Language
      - Applications (form number, receipt number)
      - Phone
      - AKA (included whenever searching by name)
-   **Client AKA:** Add AKA field.  Re-arrange other fields to accomodate
-   **Applications:** Can now enter any Form Number on an application; not just limited to those in the Form Number dropdown 


[<span class="headeranchor"></span>](#September-22-2015-v170-client-applications)September 22, 2015 - v1.7.0 : Client Applications 
------------------------------------------------------------------------------------------------------------------------

#### [<span class="headeranchor"></span>](#client-detail)Client Detail

-   **Applications:** Add Functionality to Create & View information about Client Applications: 
      - New Fields include **Application**:  
          - Form Number
          - Receipt Number
          - Status
          - Submitted By
          - Submitted Date
          - Received Date
          - Note
      - Click "+" button next to "Application" to add information about a new Application.
      - Applications are listed on the Client Detail page (can be more than one application).
      - Click an Application in this list to view the details, modify or delete the infomration about an Application.
-   **Transactions:** Fix Transaction date so that when you click on an existing Transaction date, the date isn't deleted.  Also, now prevents a Transaction from being saved without a Transaction date.  

[<span class="headeranchor"></span>](#august-24-2015-v160-client-open-close)August 24, 2015 - v1.6.0 : Client Open Close {#august-24-2015-v160-client-open-close}
------------------------------------------------------------------------------------------------------------------------

#### [<span class="headeranchor"></span>](#client-detail)Client Detail

-   **Open/Close:** Add Open/Close dropdown on Client Detail page.
-   **Delete:** Move Delete button under Open/Close dropdown
-   **Date Opened/Closed:** Remove Date Opened & Date Closed fields.
    These are now automatically captured when the file is opened, closed
    & re-opened.
-   **File Box Number:** Add File Box Number field

#### [<span class="headeranchor"></span>](#client-list)Client List:

-   **Client List Closed:** Add list of Closed clients
-   **Client List All:** Add Open Status and Open Date Fields. Remove
    Closed date field.
-   **Client List Last Payment:** Add filter to each field, Add
    openStatus field

[<span class="headeranchor"></span>](#july-15-2015-v150-client-list-last-payment)July 15, 2015 - v1.5.0 : Client List Last Payment {#july-15-2015-v150-client-list-last-payment}
----------------------------------------------------------------------------------------------------------------------------------

#### [<span class="headeranchor"></span>](#client-list_1)Client List {#client-list_1}

-   **Last Payment:** Add list of clients with the date of their Last
    Payment and Balance to the Client List page.s

#### [<span class="headeranchor"></span>](#client-detail_1)Client Detail: {#client-detail_1}

-   **Invoice button:** The Invoice button on the Client Detail page is
    disabled if the “Invoice OK?” button hasn’t been selected &gt;

#### [<span class="headeranchor"></span>](#non-functional-maintenance-no-direct-change-on-functionality-seen)Non-functional / Maintenance (no direct change on functionality seen) :

-   Server url auth api rewritten for greater flexibility & to
    accomodate url query parameters
    -   Several server framework packages upgraded

[<span class="headeranchor"></span>](#june-11-2015-v140-messages)June 11, 2015 - v1.4.0 : Messages {#june-11-2015-v140-messages}
--------------------------------------------------------------------------------------------------

#### [<span class="headeranchor"></span>](#messages)Messages :

-   You can now send Messages to other KNN database users. A Message
    List in the left nav shows you the Messages that have been sent
    to you. A Message Button in the top nav indicates how many unread
    messages are available for you. Clicking this button opens and
    closes the left pane that has your Message List.
-   **Creating Messages:**
    -   Messages are sent from the Add/Edit Notes pop-up. You can either
        send a Message on a new Note you are creating or by opening an
        existing Note.
    -   A “Notify” button has been added to the Add/Edit Notes pop-up
        modal which is a dropdown of Users that you can select (one
        or multiple) to send the Message to. You can also indicate if
        the Message is FYI or Important. If Important, a red flash icon
        appears in the top Message Button and next to the Message in the
        Message List.
    -   When creating a new Note, you can send it as a Message only
        without saving it as a Note; click the dropdown next to “Save
        and Send” and instead click the “Send Only” button
    -   An Envelope icon next to the Notify button indicates that at
        least one Message has been sent on that Note.
    -   An Envelope icon next to a User’s name in the Notify dropdown
        indicates that they have been sent a Message of that Note.
        Hovering your mouse over the envelope displays when the Messages
        were sent.
    -   A Note can not be edited or deleted if a Message has been sent
        on it.
-   **Message list:**
    -   Messages can be deleted by clicking the ‘X’ button in the upper
        left corner of the Message in the Message List.
    -   Clicking the Client Name in a Message shows that Client.
    -   Clicking the Message body in a Message pops up the full Note.

#### [<span class="headeranchor"></span>](#top-nav-top-nav-bar-is-now-always-visisble-doesnt-scroll-off-the-page-when-scrolling-down)Top Nav: Top Nav Bar is now always visisble; doesn’t scroll off the page when scrolling down. {#top-nav-top-nav-bar-is-now-always-visisble-doesnt-scroll-off-the-page-when-scrolling-down}

#### [<span class="headeranchor"></span>](#notes)Notes :

-   Add Note “+” icon at top of Notes List on Client Detail has
    been removed. Click “Add Note” button in the top nav bar remains.
-   Notes List now just shows latest 2 notes by default rather than 5
    notes (click “Show More Notes” button has not changed to see
    all notes)
-   Remove time from Notes shown in Notes List - just show date. Time of
    Note create can be seen by opening the Note
-   Envelope icon appears in front of Notes in Notes List that have
    Messages that have been sent on them.
-   Error message added to Add/Edit Note popup modal if invalid Client
    is entered in Client box. This prevents a Note from being saved
    without a valid Client

#### [<span class="headeranchor"></span>](#non-functional-maintenance-no-direct-change-on-functionality-seen_1)Non-functional / Maintenance (no direct change on functionality seen) : {#non-functional-maintenance-no-direct-change-on-functionality-seen_1}

-   User administration updates: add long & shortdisplay names
-   Upgrade Mongo Database from version 2.6.3 to 3.0.3
-   Upgrade Angular-bootstrap framework from 0.12.1 to 0.13.0

[<span class="headeranchor"></span>](#may-1-2015-v130-notes)May 1, 2015 - v1.3.0 : Notes {#may-1-2015-v130-notes}
----------------------------------------------------------------------------------------

#### [<span class="headeranchor"></span>](#client-detail_2)Client Detail : {#client-detail_2}

-   **Notes:** Change Notes so that they are transactional rather just
    one Notes text box on the Client Detail page.
    -   Notes are now a list on the Client Detail page sorted by
        date/time of when the note was created with the most recent at
        the top. Notes marked “Important” sort to the top. First 5 notes
        are displayed by default. Click “Show More Notes” to show
        all notes.
    -   Notes can be added by clicking the “Add Note” button in the Nav
        Bar or by clicking the “+” icon next to the Notes List.
    -   Person and date/time is automatically recorded with the note.
    -   Click a note in the list to view, edit or delete that note.
    -   Mark Note as “Important” by clicking the flash icon button. This
        causes that note to sort to the top of the list and to
        be highlighted.
    -   Select a different client in the Notes pop-up by selecting and
        typing the client name if needed
-   **Transactions:** Add Confirmation pop-up when delete icon is
    clicked for a Transaction.
-   **Case Overview:** Add Case Overview text box for recording more
    static overall information about the client case.

#### [<span class="headeranchor"></span>](#non-functional-maintenance-no-direct-change-on-functionality-seen_2)Non-functional / Maintenance (no direct change on functionality seen) : {#non-functional-maintenance-no-direct-change-on-functionality-seen_2}

-   Rewrite service on how data is saved. No impact to functionality
    seen on front-end.

[<span class="headeranchor"></span>](#february-16-2015-v120-derivatives)February 16, 2015 - v1.2.0 : Derivatives {#february-16-2015-v120-derivatives}
----------------------------------------------------------------------------------------------------------------

#### [<span class="headeranchor"></span>](#client-detail_3)Client Detail : {#client-detail_3}

-   **Derivatives**: Can now add derivatives. See Client Detail page.
    Click the “+” icon to add a derivative. Click the pencil icon next
    to a derivative to edit or delete a derivative. Derivative can
    either be an existing client (as shown in dropdown list) or a
    non-client by just typing in the name.
-   **Delete client**: Added ability to delete a client. On Client
    Detail page click the button with “…” which will drop down the
    option to Delete Client. Select that and then answer prompt to
    confirm delete. The client is archived (not fully erased) but will
    not appear anywhere in the app (searches, lists, txtns, etc).
-   **“Typeahead”** : Add typeahead (dropdown) for language, city and
    citizenship fields on client detail for faster and consistent entry.
    Previous values that have been enetered in that field on other
    clients are shown in the dropdown list if it has been entered on at
    least 2 other clients (to weed out typos). Some values that have
    been entered are specifically excluded in the dropdown list to
    eliminate duplicates with slight differences (eg; “St. Paul” vs
    “St Paul”)
-   **Page layout** : Modify layout of Client Detail page slightly so
    that it fully uses the width of the browser. Previously there was
    quite a bit of white space on the left and right sides.

#### [<span class="headeranchor"></span>](#client-list_2)Client List : {#client-list_2}

-   **New Fields** : Add fields Assigned, Alien Registration Nbr,
    Citizenship, Date Opened, Date Closed with ability to sort & filter.
-   **Format** : Change to table format from “pill” format

#### [<span class="headeranchor"></span>](#non-functional-maintenance-no-direct-change-on-functionality-seen_3)Non-functional / Maintenance (no direct change on functionality seen) : {#non-functional-maintenance-no-direct-change-on-functionality-seen_3}

-   **Client change log**: Log has been added to capture changes
    to clients. These change logs aren’t visible in the app yet but this
    will help with debugging, displaying change logs in the future and
    adding functionality later for “undo”.
-   **Safer client save**: When saving a client, just the one edited
    field is updated in the database on that client rather than all of
    the data for that client as was happening previously. (The save
    occures whenever you edit a field and move out of the field such as
    tabbing or clicking somewhere else). This will reduce the risk of
    one person’s changes inadvertently overwriting another peron’s if
    they are editing the same client at the same time.
-   Fix fatal server error that occurred if an invalid client id is
    entered manually into the address bar (was previuosly caught if
    client id was invalid string length; now captures error if valid
    string lenghth but not any matching client). Now an error is simply
    displayed on the client detail page and is logged to the
    errors database.
-   Server updates for security packages and version jpgrades.

[<span class="headeranchor"></span>](#jan-26-2015-v110-real-time-cross-user-client-updates-pubsub)Jan 26, 2015 - v1.1.0 : Real-time cross-user client updates (pub/sub) {#jan-26-2015-v110-real-time-cross-user-client-updates-pubsub}
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

-   **Automatically update client lists when when another person adds /
    changes a client - without having to refresh the browser.** If
    another person adds a client, for example, it will automatically
    appear when you try to search for that client - without a
    browser refresh.
-   **Add fields to client detail page :**
    -   Assigned
    -   Date Closed
    -   Invoice OK? / Invoice OK by KNN toggle button
-   Error catching & messsaging. Error message appears on client detail
    page :
    -   If error occurs when client is saved
    -   If incorrectly formatted date is entered
    -   If an incorrect client id is entered manually in the address bar
        to retrieve a client
    -   If any server errors occur. Errors that occur on server during
        client save are logged for debugging.
-   Backend changes on how changes on client detail page are identified,
    captured and saved. Should be no visible/functional change.
-   Backend change to allow real-time communication & updates between
    users (this is how the first item was implemented)

[<span class="headeranchor"></span>](#jan-4-2015-v100-client-list-and-date-fixes)Jan 4, 2015 v1.0.0 : Client List and date fixes {#jan-4-2015-v100-client-list-and-date-fixes}
--------------------------------------------------------------------------------------------------------------------------------

-   Add Client List page
-   Fix Date Opened and Date of Birth fields on the client detail page.
    These fields were not displaying or saving correctly

[<span class="headeranchor"></span>](#dec-8-2014-user-logon)Dec 8, 2014: User Logon
-----------------------------------------------------------------------------------

-   Add User Login, Logout and User Administration
-   Add user name into nav bar for menu (logout); add nav bar setup icon
    for change log
-   Client detail: Add email address and office notes
-   Invoice: Add email address and questions for Amali text
-   Minor font changes on invoice pdf
-   Upgrade angular and bootstrap frameworks

[<span class="headeranchor"></span>](#nov-12-2014-fix-transaction-date-display)Nov 12, 2014: Fix transaction date display
-------------------------------------------------------------------------------------------------------------------------

-   Transaction dates on the Client Detail page were being *displayed*
    one day off for transactions prior to Nov, 2014. (for example, a
    3-24-2012 transaction date was being displayed as 3-23-2012 even
    though the database had the correct date as 3-24-2012).

-<!-- <p>This was due to the timezone offset by the browser (browsers adjust dates displayed based on the timezone that the user has set on their workstation).  Dates are stored in the database as UTC (Coordinated Universal Time which is mostly equivalent to Greenwhich Meantime, GMT, but is the current standard for base timezone on servers) and the or-
-<p>The fix was to change the time on all transaction dates in the database to 12:00 UTC so the 5 (or 6) hour offset to Central Time will not incorrectly display the previous day .  No functionality or coding changes; data change only.  Preference would be to ignore time on all transaction dates but that would mostly require changing the date to a str-</p> -->

[<span class="headeranchor"></span>](#nov-11-2014-add-client-invoice)Nov 11, 2014: ADD Client Invoice
-----------------------------------------------------------------------------------------------------

-   Add ability to view and print client invoice. “Invoice” button is
    now on the Client Detail page. When clicked, it displays a PDF of
    the client invoice.
