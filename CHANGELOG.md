[<span class="headeranchor"></span>](#knn-database-change-log)ImmiDB Change Log
=====================================================================================

### v2.56.1 May 11, 2021
- [[315]](https://github.com/tonybranfort/immidb/issues/315) PATCH uscis app status is not showing dropdown values 

### v2.56.0 May 11, 2021
- [[314]](https://github.com/tonybranfort/immidb/issues/314) MINOR Stop auto-scroll to top of client page when invalid uscis receipt number 

### v2.55.1 May 10, 2021
- PATCH idb-ng client-detail : Remove field added for debugging 

### v2.55.0 May 05, 2021
- [[311]](https://github.com/tonybranfort/immidb/issues/311) Add: Filter and view USCIS App Fields on Client List: Form Number, App Status, Date Submitted, Clock Calculated
- [[312]](https://github.com/tonybranfort/immidb/issues/312) Fix: Client data sometimes shows prev client data when switching clients (such as Notes list)
- Dependent libaries maint updates (idb-ng): Remove un-used packages and app files 

### v2.54.0 April 21, 2021
- [[309]](https://github.com/tonybranfort/immidb/issues/309) Show openStatus in Client Search results
- [[310]](https://github.com/tonybranfort/immidb/issues/310) Fix minor bug:  Client list filter does not show "splat" options if there is only one item in meta values
- Dependent libaries maint updates  

### v2.53.5 April 15, 2021
- Fix user session changeRoles (from 2.53.4) - affects Admin roles only
- Dependent libaries maint updates  

### v2.53.4 April 14, 2021
- Dependent libaries maint updates (no funtionality changes) 

### v2.53.3 April 8, 2021
- Dependent libaries maint updates (no funtionality changes) 

### v2.53.2 April 8, 2021
- Update clock-report query (manual report)
- Minor code fix for calculate clock (no functionality difference)

### [v2.53.1] April 1, 2021
- Fix invoice pdf creation error occurring in test (only)

### [v2.53.0] March 29, 2021
- Update uscis clock fields for minor improvements: 
  - Default Clock Start Date automatically to today when enter Clock Start Days
  - Don't show uscis app list column header row if no uscis apps in list (client page)
  - Better handling of undo on Clock Start Days / Date fields
  - Minor fix on calculate clock days adjusting for local time
- Minor fix to prevent console log hasEditAccess errors on uscis app page

### [v2.52.0] March 28, 2021
- Add Clock fields: clock start days, clock start date, calculated clock

### [v2.51.0] March 26, 2021
- Update EOIR views to fully display EOIR proceedings and changes (IER-49) 
- 
#### [v2.50.2] Jan 5, 2021
- [[307]](https://github.com/tonybranfort/immidb/issues/307) Fix bug:  Eoir Cases on Client page not shown if Duplicated ANbr on Derivatives 

#### [v2.50.1] Oct 19, 2020
- Fix for ref #306 for getting current Eoir Hearings

#### [v2.50.0] Oct 18, 2020
- [[306]](https://github.com/tonybranfort/immidb/issues/306) Update EOIR data pull to use new EOIR service
- Remove 'What Changed' (New/Update) filter from Eoir Changes list (on home page)"

#### [v2.49.0] May 26, 2020
- Change: Remove Eoir Changes from Eoir Case modal window (temporary) for potential db perf issues

#### [v2.48.0] Mar 29, 2020
- [[303]](https://github.com/tonybranfort/immidb/issues/303) Feature: Notify Assigned when File attached to Client
- [[304]](https://github.com/tonybranfort/immidb/issues/304) Fix bug: Typeahead incorrectly shows Current DB Values when Fixed Values Only

#### [v2.47.0] Mar 25, 2020
- [[302]](https://github.com/tonybranfort/immidb/issues/302) Feature: Notify Assigned when new Note created

#### [v2.46.0] Mar 18, 2020
- [[301]](https://github.com/tonybranfort/immidb/issues/301) Fix: Client list does not fully load when clicking more pages"

#### [v2.45.0] Add client fields Oct 1, 2019
- [[295]](https://github.com/tonybranfort/immidb/issues/295) Add Client `Filed With` field
- [[299]](https://github.com/tonybranfort/immidb/issues/299) Add Client `Deadline` field
- [[298]](https://github.com/tonybranfort/immidb/issues/298) Add type-ahead to Client 'File Box Number' field
- [[297]](https://github.com/tonybranfort/immidb/issues/297) Stop browser autofill on Client Search field

#### [v2.44.0] Add 'Subject Of Record' as USCIS Domain July 3, 2019
- [[294]](https://github.com/tonybranfort/immidb/issues/294) Feature : Add 'Subject Of Record' as USCIS Domain (Form G-639)

#### [v2.43.0] Add Case Overview to Case List (All) July 1, 2019
- [[293]](https://github.com/tonybranfort/immidb/issues/293) Feature : Add Case Overview to Case List (All)

#### [v2.42.4] EOIR Load updates (June 10, 2019)
- Update @immidb/eoir 2.0.11->2.0.12: increase pw type delay (no functionality change)
- [[292]](https://github.com/tonybranfort/immidb/issues/292) EOIR Load: Increase max errors (timeout) before fail (no functionality changes)

#### [v2.42.3] Update @immidb/eoir to v2.0.11 (June 10, 2019)
- No functionality changes

#### [v2.42.2] Update @immidb/eoir to v2.0.10; fix eoir db disconnect (June 9, 2019)
- No functionality changes

#### [v2.42.1] Fixes for Addresses (May 29, 2019)
- [[288]](https://github.com/tonybranfort/immidb/issues/288) Fix bug : Address not printing on invoice
- [[291]](https://github.com/tonybranfort/immidb/issues/291) Remove client-list address column/filter options
- [[290]](https://github.com/tonybranfort/immidb/issues/290) Allow address uniType to be deleted (select blank)
- [[289]](https://github.com/tonybranfort/immidb/issues/289) Remove unitNbr from address model (no functionality change)


#### [v2.42.0] Add Employers/Employment History (May 28, 2019)
- [[32]](https://github.com/tonybranfort/immidb/issues/32) Allow multiple addresses per client with dates, mail, physical
- [[286]](https://github.com/tonybranfort/immidb/issues/286) Reformat Address / Address List and Add "In Care of Name" address field

#### [v2.41.0] Add Employers/Employment History (May 21, 2019)
- [[282]](https://github.com/tonybranfort/immidb/issues/282) Add Employers / Employment History
- [[283]](https://github.com/tonybranfort/immidb/issues/283) Add DBA Name and E-Verify Company Name to Business Details
- [[284]](https://github.com/tonybranfort/immidb/issues/284) Move to @immidb/idb-change from @immidb/idb-common/lib/change (no functionality change)

#### [v2.40.1] Add ability to create a Client as a Business (May 17, 2019)
- [[285]](https://github.com/tonybranfort/immidb/issues/285) Upgrade mongoose 5.2 and require mongo 3.6 (No functionality changes)

#### [v2.40.0] Add ability to create a Client as a Business (Apr 23, 2019)
- [[281]](https://github.com/tonybranfort/immidb/issues/281) Add ability to create a Client as a Business

#### [v2.39.1] Add EOIR last updated dates (Mar 17, 2019)
- [[280]](https://github.com/tonybranfort/immidb/issues/280) Add EOIR last updated dates

#### [v2.38.0] EOIR Load updates (no end user changes) (Mar 12, 2019)

#### [v2.37.1] Add client note when replying to email from note (Mar 1, 2019)
- [[231]](https://github.com/tonybranfort/immidb/issues/231) Add client note when replying to email from note 

#### [v2.36.0] Email to Note functionality (Feb 23, 2019)
- [[276]](https://github.com/tonybranfort/immidb/issues/276) Email to Note functionality 
- [[274]](https://github.com/tonybranfort/immidb/issues/274) Add idb pubsub (no end user changes)

#### [v2.35.1] USCIS view updates / add idb-auth-svc (Feb 18, 2019)
- Fix uscis-api fillFormFile call response (body) to UsciSvc

#### [v2.35.0] USCIS view updates / add idb-auth-svc (Feb 15, 2019)
- [[271]](https://github.com/tonybranfort/immidb/issues/271) USCIS Case Status incorrectly saying "Blank Case Status" instead of Invalid Reciept Number
- [[268]](https://github.com/tonybranfort/immidb/issues/268) Change "USCIS Applications" header on client page to "Immigration Applications"
- [[266]](https://github.com/tonybranfort/immidb/issues/266) Client App list should not say "Invalid Receipt Number" if receipt number is blank
- No functionality/user impact:
    - [[270]](https://github.com/tonybranfort/immidb/issues/270) Changes necessary for google+ api shutdown planned for March 7
    - [[272]](https://github.com/tonybranfort/immidb/issues/272) idb-common api body and error changes
    - [[273]](https://github.com/tonybranfort/immidb/issues/273) idb now uses idb-auth-svc

#### [v2.34.0] USCIS Case Status cache (January 27, 2019)
- [[11]](https://github.com/tonybranfort/immidb/issues/11) Cache uscis case status (only minor changes to user front-end)
- [[243](https://github.com/tonybranfort/immidb/issues/243) Don't display page errors when uscis case status unvailable

#### [v2.33.0] Node upgrade (8.11.3->10.15.0) (January 20, 2019)
- [[261]](https://github.com/tonybranfort/immidb/issues/261) Add new/update filter for eoir changes
- [[262]](https://github.com/tonybranfort/immidb/issues/262) Add eoir changes to eoir case modal
- [[263]](https://github.com/tonybranfort/immidb/issues/263) Add Place of Birth Fields (City/Town, State, Country) to Client and as fillable on USCIS Forms
- Upgrade nodejs from 8.11.3 to 10.15.0 (no functionality changes)
- Perf Report : Update daily to show all apis hit 
- Other USCIS Forms Update : Add Beneficiary to I-130

#### [v2.32.1] Remove Angular (v2) (Jan 11, 2019)
- [[260]](https://github.com/tonybranfort/immidb/issues/260) Remove Angular (2+); now using just AngularJS (no functionality changes)
- Update eoir changes report to use get-changes / qryFilter (no functionality changes)

#### [v2.32.0] Add user based fields to uscis forms (Jan 8, 2019)
- [[258]](https://github.com/tonybranfort/immidb/issues/258) (feat) Add user based fillable fields to USCIS forms
- [[257]](https://github.com/tonybranfort/immidb/issues/257) (bug) Deleting uscis app doesn't remove from client search index
- [[259]](https://github.com/tonybranfort/immidb/issues/259) (bug) Chrome autofill on edit fields
- Package updates (no functionality changes): Update express-brute-mongoose, twilio, karma. Remove gulp. 

#### [v2.31.1] USCIS App minor fixes/updates (Jan 4, 2019)
- [[254]](https://github.com/tonybranfort/immidb/issues/254) (bug) Fix Undo on USCIS Form/App Edit page not working corrrectly
- [[255]](https://github.com/tonybranfort/immidb/issues/255) (bug) Fix Client link in Editable Field should route to client w/o showing field as editable first
- [[256]](https://github.com/tonybranfort/immidb/issues/256) (bug) Fix Calendar Title is not updated correctly when changing clients on Edit Event Modal

#### [v2.31.0] Editable Client Fields for USCIS Forms (Dec 22, 2018)
- [[252]](https://github.com/tonybranfort/immidb/issues/252) (feature) Editable client fields specific to each USCIS Form
- [[253]](https://github.com/tonybranfort/immidb/issues/253) (bug) Client search autofill popup layover issue from new version of Chrome

#### [v2.30.3]  (Dec 9, 2018)
- Fix EOIR changes report showing changes to syncId (imtroduced with v2.30.2)

#### [v2.30.2]  (Dec 8, 2018)
- [[251]](https://github.com/tonybranfort/immidb/issues/251) Improve EOIR sync job runtime
- [[250]](https://github.com/tonybranfort/immidb/issues/250) Add front end response time reporting for client

#### [v2.30.1]  (Dec 1, 2018)
- [[249]](https://github.com/tonybranfort/immidb/issues/249) Client info not filling when "Open Filled Form" on New USCIS App Modal

#### [v2.30.0]  (Nov 30, 2018)
- [[247]](https://github.com/tonybranfort/immidb/issues/247) Add eoir process to auto create missing clients (option not turned on for existing apps)
- [[246]](https://github.com/tonybranfort/immidb/issues/246) Add daily performance report (no user functionality change)
- [[245]](https://github.com/tonybranfort/immidb/issues/245) Upgrade socket-io (no user functionality change)
- [[248]](https://github.com/tonybranfort/immidb/issues/248) Add authentication to idb socket (no user functionality change)

#### [v2.29.0] Create USCIS App Page (non-modal) for editing (Nov 21, 2018)
- [[242]](https://github.com/tonybranfort/immidb/issues/242) Create USCIS App Page (non-modal) for editing
- server npm audit fix 'critical' : no functionality change
- [[243]](https://github.com/tonybranfort/immidb/issues/243) i243 data cleanup: remove client.applications data (no functionality change)
- Update eoir load to not remove users for 20 days instd of 1 hr when case not found for user

#### [v2.28.0] Create uscisapps data collection; move data from clients.applications (no user functionality change)  (Nov 8, 2018)
- [[243]](https://github.com/tonybranfort/immidb/issues/243) Create uscisapps data collection; move data from clients.applications
- idb-ng npm audit fix (no major semvar changes; no user functionality changes)

#### [v2.27.0] Populate law firm info on uscis forms (Nov 3, 2018)
- [[239]](https://github.com/tonybranfort/immidb/issues/239) Populate law firm info on uscis forms
- [[240]](https://github.com/tonybranfort/immidb/issues/240) Populate uscis forms using uscis-svc rather than idb-forms-svc (no end user functionality change)

#### [v2.26.0] Begin using uscis-svc with all pdf forms loaded (Oct 25, 2018)
- [[235]](https://github.com/tonybranfort/immidb/issues/235) USCIS All forms available + uscis app modal changes

#### [v2.25.1]  (Oct 9, 2018)
- Update eoir run-load for idb-common db.init

#### [v2.25.0]  (Sept 28, 2018)
- Use @immidb/idb-common qry-filter-api (no functionality change)
- Move `change` and `qry-filter-api` to idb-common

#### [v2.24.0 Fill A-Number and DOB on USCIS Forms](https://github.com/immidb/idb/milestone/30?closed=1) (Sept 14, 2018)
- [[230]](https://github.com/tonybranfort/immidb/issues/230) Fill A-Number on uscis pdf forms
- [[232]](https://github.com/tonybranfort/immidb/issues/232) Fill DOB on uscis pdf forms
- [[233]](https://github.com/tonybranfort/immidb/issues/233) Minor Application modal view updates; link to uscis form site

#### [v2.23.0 Update services logging (no user functionality changes)](https://github.com/immidb/idb/milestone/29?closed=1) (Sept 11, 2018)
- [[228]](https://github.com/tonybranfort/immidb/issues/228) Add timestamp, user, req info on services logging (no user functionality change)
- [[229]](https://github.com/tonybranfort/immidb/issues/229) Ability to pass request context to idb services

#### [v2.22.0 Populate Forms](https://github.com/immidb/idb/milestone/28?closed=1) (Aug 28, 2018)
- [[185]](https://github.com/tonybranfort/immidb/issues/185) List and Populate USCIS PDF Forms
- [[226]](https://github.com/tonybranfort/immidb/issues/226) Move forms data into sys database (no user functionality changes)
- [[227]](https://github.com/tonybranfort/immidb/issues/227) Move to Kubernetes (no user functionality changes)

#### v2.21.1 Minor logging update; no functionality change (July 24, 2018)

#### [v2.21.0: Logging Changes (no functionality change)](https://github.com/immidb/idb/milestone/27?closed=1) (July 24, 2018)
- [[224]](https://github.com/tonybranfort/immidb/issues/224) Log updates: response time, user id; log to file (no functionality change)
- [[225]](https://github.com/tonybranfort/immidb/issues/225) Settings / About version should be dynamic (no functionality change)
- [[221]](https://github.com/tonybranfort/immidb/issues/221) (bug) Can still click/generate Invoice when Invoice Print button is disabled

#### [v2.20.0: EOIR Change List Updates; SMS Text Err Fix](https://github.com/immidb/idb/milestone/26?closed=1) (July 22, 2018)
- [[222]](https://github.com/tonybranfort/immidb/issues/222) (feat) EOIR Change List Attnys, Client Links
- [[223]](https://github.com/tonybranfort/immidb/issues/223) (bug) SMS Text giving error 'createdUser_id is required'

#### [v2.19.0: Microsoft Email Integration](https://github.com/immidb/idb/milestone/25?closed=1) (July 19, 2018)
- [[220]](https://github.com/tonybranfort/immidb/issues/220) (feat) Microsoft Email Integration
- [[218]](https://github.com/tonybranfort/immidb/issues/218) (feat) Security updates; admin view and remove current user sessions

#### v2.18.3: Fix eoir sync failure caused by EOIR web site changes (July 12, 2018)
- [[217]](https://github.com/tonybranfort/immidb/issues/217) Fix: EOIR web site changes causing eoir sync failure
- [[216]](https://github.com/tonybranfort/immidb/issues/216) (feat) Don't report error on dropped ping connection
- [[215]](https://github.com/tonybranfort/immidb/issues/215) (bug) console error if missing last name on user profile (no functionality change)

#### v2.18.2: EOIR sync job update; no functionality changes (June 25, 2018)
- [[214]](https://github.com/tonybranfort/immidb/issues/214)  update @immidb/eoir to v2.0.2 for EOIR load/sync; no functionality change

#### v2.18.1: Sysadmin Auth updates minor fixes; no functionality changes (June 22, 2018)
- [[213]](https://github.com/tonybranfort/immidb/issues/213) Fix auth updates not allowed on some fields (sysadmin)

#### v2.18.0: Add Microsoft login; update top nav (June 22, 2018)
- [[212]](https://github.com/tonybranfort/immidb/issues/212) Add Microsoft login; update top nav

#### v2.17.1: Package maintenance updates; no functionality changes (June 21, 2018)
- [[211]](https://github.com/tonybranfort/immidb/issues/211) Server package updates for security and currency; no functionality changes

#### [v2.17.0: Notes always editable ](https://github.com/immidb/idb/milestone/23?closed=1) (June 14, 2018)
- [[210]](https://github.com/tonybranfort/immidb/issues/210) (feat) Notes should always be editable
- [[209]](https://github.com/tonybranfort/immidb/issues/209) (bug) Email incorrectly has 'KNN database note'

#### [v2.16.0: View recent EOIR changes](https://github.com/immidb/idb/milestone/22?closed=1) (June 7, 2018)
- [[154]](https://github.com/tonybranfort/immidb/issues/154) (feat) Ability to view EOIR court info that has recently changed
- [[202]](https://github.com/tonybranfort/immidb/issues/202) (feat) System Initiation / Default Updates (No functionality changes)
- [[205]](https://github.com/tonybranfort/immidb/issues/205) (bug) Unable to edit Meta Admin Fixed Values in certain situations

#### v2.15.3: Remove Invoice login bypass (June 6, 2018)
- [[203]](https://github.com/tonybranfort/immidb/issues/203) (bp) Remove Invoice login bypass (no functionality change)

#### v2.15.2: Fix for MFA Requires Remember Device (June 6, 2018)
- [[201]](https://github.com/tonybranfort/immidb/issues/201) (bug) MFA Requires 'Remember Device'

#### v2.15.1: Fix for Invoice Login Error (June 4, 2018)
- [[156]](https://github.com/tonybranfort/immidb/issues/156) (bug) Invoice Login Error

#### [v2.15.0: Misc minor updates](https://github.com/immidb/idb/milestone/21?closed=1) (March 27, 2018)
- [[190]](https://github.com/tonybranfort/immidb/issues/190) (feat) Add Case Type to Txtns Summary by Client
- [[199]](https://github.com/tonybranfort/immidb/issues/199) (feat) Change New Txtn button on Txtn Summary by Client
- [[196]](https://github.com/tonybranfort/immidb/issues/196) (feat) Filters for meta types of Dates should not allow 'Contains'
- [[197]](https://github.com/tonybranfort/immidb/issues/197) (feat) Display last checked on EOIR Case Details
- [[164]](https://github.com/tonybranfort/immidb/issues/164) (feat) Provide Reminder Message about Outlook when creating new Calendar appointment
- [[200]](https://github.com/tonybranfort/immidb/issues/200) (bug) Derivative Type / Relationship are switched on Derivative Dialog
- [[198]](https://github.com/tonybranfort/immidb/issues/198) (feat) EOIR load not deleting un-assigned users

#### [v2.14.0: EOIR login fix; filter/client-list updates](https://github.com/immidb/idb/milestone/20?closed=1) (March 19, 2018)
- [[110]](https://github.com/tonybranfort/immidb/issues/110) (feat) Ability to edit Client data directly in Client List
- [[195]](https://github.com/tonybranfort/immidb/issues/195) (feat) Allow expand all on filter values (splats)
- [[119]](https://github.com/tonybranfort/immidb/issues/119) (feat) Ability to add Client Tags
- [[194]](https://github.com/tonybranfort/immidb/issues/194) (bug) Fix for EOIR site login change
- [[189]](https://github.com/tonybranfort/immidb/issues/189) (bug) EOIR load should only un-assign users if no error on EOIR run

#### [v2.13.0: Invoice cover page updates](https://github.com/immidb/idb/milestone/19?closed=1) (March 7, 2018)
- [[192]](https://github.com/tonybranfort/immidb/issues/192) (feat) Modify Invoice cover page - remove totals

#### [v2.12.0: Client List Filters](https://github.com/immidb/idb/milestone/17?closed=1) (March 3, 2018)
- [[193]](https://github.com/tonybranfort/immidb/issues/193) (feat) Update Client List filters to view more columns and filters
- [[79]](https://github.com/tonybranfort/immidb/issues/79) (feat) Default Client List to Open only
- [[187]](https://github.com/tonybranfort/immidb/issues/187) (feat) Add Date Opened to client page
- [[182]](https://github.com/tonybranfort/immidb/issues/182) (feat) Add 'Petitioner' to Derivative Type
- [[181]](https://github.com/tonybranfort/immidb/issues/181) (feat) Don't call for auths until needed (no end user funtionality change)
- [[46]](https://github.com/tonybranfort/immidb/issues/46) (feat) Client Assigned should display user display name rather than user id
- [[186]](https://github.com/tonybranfort/immidb/issues/186) (bug) Client List sort only sorts rows displayed
- [[179]](https://github.com/tonybranfort/immidb/issues/179) (bug) Filter dates are sometimes not displayed correctly on initial load
- [[178]](https://github.com/tonybranfort/immidb/issues/178) (bug) Unable to delete filter on Summary by Client report

#### [v2.11.0: SMS Texting](https://github.com/immidb/idb/milestone/18?closed=1) (Jan 27, 2018)
- [[175]](https://github.com/tonybranfort/immidb/issues/175) (feat) Ability to send SMS Texts from Immidb
- [[177]](https://github.com/tonybranfort/immidb/issues/177) (feat) Nav updates: New Text Msg, More Buttons DD
- [[176]](https://github.com/tonybranfort/immidb/issues/176) (feat) Add caching to getting auths (no end user impact)

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
