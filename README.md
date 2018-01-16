## ImmiDb 
###### A Simple and Easy to Use Database Application for Immigration Law Practitioners 
ImmiDb is currently a privately licensed, non-commercial software designed for an Immigration Law practice that has been in use and continually upgraded with new functionality since 2014.  It is designed for easy deployments for individual law practices to private networks or cloud infrastructures such as Microsoft Azure or Amazon Web Services. 

#### Basic functionality comparison

| Functionality | ImmiDb<br>(Jan 2018)| [Practice Panther](https://practicepanther.com/) <br>(Jan 2018)| [INSZoom](https://www.inszoom.com/)<br>(Jan 2018) |
|--------------------------------------|----------------------------------------------|--------------------------------------------------------|--------------------------------------------------------|
||||||
|<h5>Overview</h5>|Easy to use for Immigration Practioners covering basic functionality; integrated with USCIS Case Status and Immigration Court|Extensive and broad functionality with a modern interface and many integration options to fit many law practices|Specific to Immigration Law Practioners integrating with over 500 forms and related functionality including submitting government forms online |
|Demo version |https://sample.immidb.net/ |Contact Practice Panther for demo. [youtube training videos](https://www.youtube.com/results?search_query=practicepanther)|Contact INSZoom for demo|
|||||
|<h5>Cost</h5>|Currently privately licensed and supported.  Non-profits/pro-bono offices can contact info@immidb.net for at-cost implementations (~$40 per month to cover infrastructure costs).|$59 per user per month ($49 per user per month if pay annually).  Includes all functionality.  External services that are integrated (eg; dropbox, email, etc) are separate|From $30 per user per month to $150 per user per month depending on functionality chosen.  "Most popular" is "Zoom Pro Law" which is $100 per user per month with $499 setup fee. Functionality listed below is for Zoom Pro Law unless other indicated|
|||||
|<h5>Clients/Client Data</h5>|||
|Client Search|✅Yes. google like search: single search box searches across multiple client fields|✅Yes|✅Yes|
|Notes|✅Yes. Alert other ImmiDb users via email or ImmiDb messages.|✅Yes|✅Yes|
|User to user In-app Messaging|Partial. Alert other users via in-app messaging on Notes|✅Yes|?|
|Contacts (non-client)|⌧No|✅Yes|✅Yes. Called prospects by default.|
|Create custom fields|⌧No|✅Yes|✅Yes|
|Tags|⌧No|✅Yes|✅Yes (assumed)|
|Client List|✅Yes (filter by assigned, A-Number, Citizenship, Open Status|✅Yes (assumed)|✅Yes|
|||||
|<h5>Matters</h5>|⌧No. Matters do not exist as separate entities in ImmiDb|✅Yes|✅Yes (called Cases by default but can modify to your own term)|
|||||
|<h5>Immigration Integrations</h5>|||
|USCIS Case Status Integration|✅Yes. USCIS Case status pulled live when client is displayed for one or multiple USCIS Receipt Numbers|⌧No|Partial: can enter USCIS receipt numbers and link directly to USCIS Case Status site to see current status|
|US Immigration Court (EOIR) Integration|✅Yes. View Immigration Court Hearings and Case Status by Client (via A-Number). Automated sync with EOIR site would typically occur overnight but can be adjusted to be more frequent |⌧No|⌧No|
|||||
|<h5>Immigration Integrations</h5>|||
|Immigration Forms|⌧No|✅Yes. Via integration with [borderwise](https://www.borderwise.co/)|✅Yes|
|Online govrenment forms filing / integration |⌧No|?|✅Yes. "e-filing" "e-file a range of forms directly on the government websites"|
|||||
|<h5>Documents</h5>|✅Yes. Attach documents to a client.|✅Yes. Extensive integration with various services|✅Yes|
|Dropbox integration|⌧No|✅Yes|⌧No|
|Box.com integration|⌧No|✅Yes|⌧No|
|Microsoft Office Integration|⌧No|✅Yes|⌧No|
|||||
|<h5>Financial/Billing</h5>|||
|Overall financial reporting|✅Yes. Totals of Invoiced, Payments, Filing Expenses, Client Balances, Trust Balances by overall, year, month, day|✅Yes|✅Yes|
|Trust Reporting|✅Yes. Balances by year, month, day|✅Yes|?|
|Client Reporting|✅Yes. Filter by Invoiced, Payments, Balances, Txtn Dates|✅Yes|✅Yes|
|Financial Transaction Reporting|✅Yes. Filter by transaction date|✅Yes (Assumed)|✅Yes|
|Customized Invoices|✅Yes.Customized letterhead & footers|✅Yes (Assumed)|✅Yes|
|Record Trust transfers simply|✅Yes. Record transfers to Trust easily either via a client or when viewing list of transactions (such as payments by date)|?|?|
|Record Trust to business account transfers simply|✅Yes. Record transfers from Trust account to business acount easily when viewing list of Trust (and other) balances by Client|?|?|
|Set permissions on who can enter/view which financial data|✅Yes|✅Yes|Partial.  Can only set permissions for all or none of Billing: not functionality within Billing|
|Allow various rate models|⌧No. Billing is simply by entering an amount for Invoiced,  Payment or Filing Expenses|✅Yes.|? "define fee structures"|
|External payment integration|⌧No.|✅Yes. Lawpay, Stripe, Paypal, authorize.net|authorize.net|
|Track time and expenses|⌧No|✅Yes|✅Yes|
|QuickBooks integration|⌧No|✅Yes|⌧No
|||||
|<h5>Email Integration</h5>|||
|Notify other users when creating notes|✅Yes|✅Yes (?)|?|
|Create email|Partial. Only when creating notes and to email other database users.|✅Yes|✅Yes|
|Attach email to Client &/or Matters from outside of database|⌧No|✅Yes. When creating an email outside of the database, can cc a database Contact or Matter to attach it.  Contacts and Matters are automatically added as Outlook contacts to easily cc. |?|
|Email invoices to clients?|⌧No|✅Yes (confirm)|✅Yes|
|MailChimp integration|⌧No|✅Yes|?|
|||||
|<h5>Calendar</h5>|||
|Google Calendar Integration|✅Yes|✅Yes|✅Yes|
|Outlook Integration|✅Yes. One-way: ImmiDb to Outlook via Google Sync. [See this topic.](https://github.com/immidb/idb/issues/108)|✅Yes. 2-way syncing Outlook to Practice Panther|✅Yes. 1 or 2 way?|
|||||
|<h5>Software Interface</h5>|||
|Browser/web based|✅Yes|✅Yes|✅Yes|
|Customizable branding|✅Yes. Your company name and logo.  Custom web site addresses using your domain.|?|?|
|Integration with mobile and ipad|⌧No. Viewable on mobile and ipad but not specifically designed for smaller views|✅Yes|⌧No. Viewable on mobile and ipad but not specifically designed for smaller views
|User customizable portal pages|⌧No|?|✅Yes|
|Recent Activity View|⌧No. See all of Client detail on one page including all recent activity but no view across clients of recent activity.|✅Yes|Partial|
|Custom/user defined reports|⌧No|✅Yes|✅Yes|
|||||
|<h5>Misc</h5>|||
|Download/export data from database|⌧No. Cannot download directly from app.  Sys admins can export the data|✅Yes|?|
|Client Access|⌧No|?)|✅Yes.  Multiple ways to grant individual clients access to update their information and upload documents|
|Shipping tracking|⌧No|?|✅Yes|
|||||
|<h5>Workflow</h5>|||
|Tasks|✅Yes|✅Yes|✅Yes|
|Tasks integrated into Outlook|⌧No|✅Yes|?|
|Questionnaires|⌧No|?|✅Yes|
|Checklists|⌧No|✅Yes|✅Yes|
|Alerts & Notifications|⌧No|✅Yes|✅Yes|
|Create custom workflows|⌧No|✅Yes.  With triggers and alerts|✅Yes|
|Create checklists|⌧No|✅Yes|✅Yes|
|Zapier integration|⌧No|✅Yes|⌧No|
|Workflow outsourcing|⌧No|?|✅Yes "Outsource portions of your workflow through the Vendor Partner module"|
|||||
|<h5>Audit/Change Tracking</h5>|||
|Change tracking|✅Yes.  All data changes recorded by date and user.  Viewable by sys admins only|✅Yes. See all changes by person and time. |✅Yes (full user & timestamp for every change?)|
|Change Undo for User|Partial. Can undo any change to a client with one click until move to another client (or page)|? Have recycle bin|⌧No|
|||||
|<h5>Training/Documentation</h5>|||
|Training|⌧No|✅Yes with training videos|Training videos available for clients.|
|Documentation|Partial.  In-app help dialogs but no external documentation|?|Training "articles" but not step by step documentation.  Setup fee includes 1x1 training via webex|
|||||
|<h5>Support</h5>|||
|Online reporting of production issues|Depends on implementation.  Each ImmiDb is a standalone implementation.|✅Yes|⌧No|
|Online bug reporting|✅Yes [Open Bugs](https://github.com/immidb/idb/issues?q=is%3Aissue+is%3Aopen+label%3A0Bug)|<h4>?</h4>|?|
|Online feature request reporting|✅Yes [Open Feature Requests](https://github.com/immidb/idb/issues?q=is%3Aissue+is%3Aopen+label%3A0Feature)|<h4>?</h4>|Online "what's in progress" articles|
|Support forum|✅Yes. Issues, bugs and questions are tracked [here](https://github.com/immidb/idb/issues).|✅Yes|⌧No|
|Tech support|⌧No|✅Yes. Via email, message or phone.|✅Yes. "Customer care" 24x7x365|
|Frequency of updates|19 releases in 2017 with dozens of new features [Releases since v2.0.0 on Sept 8, 2017](https://github.com/immidb/idb/milestones?state=closed)|[More than 50 releases of new features in 2017](https://www.practicepanther.com/law-firm-practice-management-software/)|Typically several updates per month|
|||||
|<h5>Security</h5>|||
|Set permissions for users|✅Yes. Can determine which users can see which data and functionality.|✅Yes. Can determine which users can see which data and functionality.|Partial. Can set who can see which modules such as billing but may not be able to set permissions lower than that. |
|Data privacy(data not accessible by sys admins)|✅Yes.Database can be established on a private servers and network.|✅Yes. Data resides on Practice Panther infrastructure but is not accessible by Practice Panther unless authorized for support purposes.|✅Yes.  Data and app are not accessed unless authorized.|
|Data encrypted|✅Yes. Choose to implement with data encryption.  Passwords are automatically encrypted regardless of backend implementation |✅Yes. 256 bit encryption|✅Yes. 256 bit encryption|
|2 Factor Authentication|✅Yes. Administratively set when and how 2 factor is turned on for users such as required when logging in from unknown IP addresses|✅Yes. But may be only available for Enterprise edition.|
|HIPAA complian|⌧No. Not reviewed for HIPAA|✅Yes. "HIPAA compliant file management"|?|
|||||
|<h5>Infrastructure</h5>|||
|Can be deployed to private network|✅Yes. ImmiDb is deployed via Docker Containers which can be deployed to any infrastructure of your choice that support Docker Containers including Linux, Microsoft Servers, AWS, Microsoft Azure, Google Cloud |⌧No.  Hosted by Practice Panther on Microsoft Azure cloud infrastructure|⌧No.  Hosted by INSZoom on Amazon Web Services cloud infrastructure|
|Data backups|✅Yes. As deployed |✅Yes|✅Yes|
|IP Address Restrictions|✅Yes. Administratively restrict access to IPs that you choose |?|✅Yes|
|Query data via API|⌧No. ImmiDb queries and updates data via a backend REST API which can be accessed by developers but is not intended for end user queries|✅Yes [Swagger API](https://www.practicepanther.com/law-office-software-api/)|✅Yes.  For developers?|
|||||
|<h5>Company</h5>|||
|For profit|TBD (Open Source or Commercial)|✅Yes|✅Yes|
|Number of Law Office Implementations|1|"In 2016 we had a 97% satisfaction rating from thousands of law firms."|?|
|How long has app been in production|Since 2014|Since 2012|Since 1999|
|# of employees|One contributor|Dozens; hq in Miami, FL|25-35 in US (San Francisco), 100+ in India|

