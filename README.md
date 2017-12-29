## ImmiDb 
#### A Simple Database Application for Immigration Law Practitioners 

| Functionality | ImmiDb <br>(Dec 2017)| Practice Panther <br>(Dec 2017)| 
|--------------------------------------|----------------------------------------------|--------------------------------------------------------|
||||
|<h5>Overview</h5>|Simple Client Application for Immigration Practioners focused on ease of use with basic billing, invoicing, reporting, client tracking, notes, tasks, email and calendar integration, and USCIS and Immigration Court integrations |Impressively extensive and broad functionality to fit many law practices|
|Demo version |https://sample.immidb.net/ <br>Log in as user 'oliver' and 'test' (pw).  All data is fake and randomly generated|Contact Practice Panther for demo|
||||
|<h5>Cost</h5>|Currently privately licensed and supported.  Non-profits/pro-bono offices can contact info@immidb.net for at-cost implementations (~$40 per month to cover infrastructure costs).|$59 per user per month ($49 per user per month if pay annually).  Includes all functionality.  External services that are integrated (eg; dropbox, email, etc) are paid seperately|
||||
|<h5>Clients/Client Data</h5>|||
|Client Search|✅Yes. google like search: single search box searches across multiple client fields|✅Yes|
|Notes|✅Yes. Recorded by user and date. Alert other ImmiDb users via email or ImmiDb messages.|✅Yes|
|Contacts (non-client)|⌧No|✅Yes|
|Create custom fields|⌧No|✅Yes|
|Tags|⌧No|✅Yes|
|Client List|✅Yes (filter by assigned, A-Number, Citizenship, Open Status|✅Yes (assumed)|
||||
|<h5>Matters</h5>|⌧No. Matters do not exist as separate entities in ImmiDb|✅Yes|
||||
|<h5>Immigration Integrations</h5>|||
|USCIS Case Status Integration|✅Yes. USCIS Case status pulled live when client is displayed for one or multiple USCIS Receipt Numbers|⌧No|
|US Immigration Court (EOIR) Integration|✅Yes. View Immigration Court Hearings and Case Status by Client (via A-Number). Automated sync with EOIR site would typically occur overnight but can be adjusted to be more frequent |⌧No|
|Immigration Forms|⌧No|✅Yes. Via integration with [borderwise](https://www.borderwise.co/)
||||
|<h5>Documents</h5>|✅Yes. Attach documents to a client.|✅Yes. Extensive integration with various services|
|Dropbox integration|⌧No|✅Yes|
|Box.com integration|⌧No|✅Yes|
|Microsoft Office Integration|⌧No|✅Yes|
||||
|<h5>Financial/Billing</h5>|||
|Overall financail reporting|✅Yes. Totals of Invoiced, Payments, Filing Expenses, Client Balances, Trust Balances by overall, year, month, day|✅Yes|
|Trust Reporting|✅Yes. Balances by year, month, day|✅Yes|
|Client Reporting|✅Yes. Filter by Invoiced, Payments, Balances, Txtn Dates|✅Yes|
|Financial Transaction Reporting|✅Yes. Filter by transaction date|✅Yes (Assumed)|
|Customized Invoices|✅Yes.Customized letterhead & footers|✅Yes (Assumed)|
|Record Trust transfers simply|✅Yes. Record transfers to Trust easily either via a client or when viewing list of transactions (such as payments by date)|?|
|Record Trust to business account transfers simply|✅Yes. Record transfers from Trust account to business acount easily when viewing list of Trust (and other) balances by Client|?|
|Set permissions on who can enter/view which financial data|✅Yes|✅Yes|
|Allow various rate models|⌧No. Billing is simply by entering an amount for Invoiced,  Payment or Filing Expenses|✅Yes.|
|External payment integration|⌧No.|✅Yes. Lawpay, Stripe, Paypal, authorize.net|
|Track time and expenses|⌧No.|✅Yes|
|QuickBjooks integration|⌧No.|✅Yes|
||||
|<h5>Email Integration</h5>|||
|Notify other users when creating notes|✅Yes|✅Yes (?)|
|Create email|Partial. Only when creating notes and to email other database users.|✅Yes|
|Attach email to Client &/or Matters from outside of database|⌧No|✅Yes. When creating an email outside of the database, can cc a database Contact or Matter to attach it.  Contacts and Matters are automatically added as Outlook contacts to easily cc. |
|MailChimp integration|⌧No|✅Yes|
||||
|<h5>Calendar</h5>|||
|Google Calendar Integration|✅Yes|✅Yes|
|Outlook Integration|✅Yes. One-way: ImmiDb to Outlook via Google Sync. [See this topic.](https://github.com/immidb/idb/issues/108)|✅Yes. 2-way syncing Outlook to Practice Panther|
||||
|<h5>Misc</h5>|||
|Integration with mobile and ipad|Viewable on mobile and ipad but not specifically designed for smaller views|✅Yes|
|Recent Activity View|⌧No. See all of Client detail on one page including all recent activity but no view across clients of recent activity.|✅Yes|
|Download/export data from database|⌧No. Cannot download directly from app.  Sys admins can export the data|✅Yes|
||||
|<h5>Workflow</h5>|||
|Tasks|✅Yes|✅Yes|
|Tasks integrated into Outlook|⌧No|✅Yes|
|Create custom workflows|⌧No|✅Yes.  With triggers and alerts|
|Create checklists|⌧No|✅Yes|
|Zapier integration|⌧No|✅Yes|
||||
|<h5>Audit/Change Tracking</h5>|||
|Change tracking|✅Yes.  All data changes recorded by date and user.  Viewable by sys admins only|✅Yes (confirm)|
|Change Undo|Partial. Can undo any change to a client with one click until move to another client (or page)|? Have recycle bin|
||||
|<h5>Training/Documentation</h5>|||
|Training|⌧No|✅Yes with training videos|
|Documentation|Partial.  In-app help dialogs but no external documentation|?|
||||
|<h5>Support</h5>|||
|Online reporting of production issues|Depends on implementation.  Each ImmiDb is a standalone implementation.|✅Yes|
|Online bug reporting|✅Yes [Open Bugs](https://github.com/immidb/idb/issues?q=is%3Aissue+is%3Aopen+label%3A0Bug)|<h4>?</h4>|
|Online feature request reporting|✅Yes [Open Feature Requests](https://github.com/immidb/idb/issues?q=is%3Aissue+is%3Aopen+label%3A0Feature)|<h4>?</h4>|
|Support forum|✅Yes. Issues, bugs and questions are tracked [here](https://github.com/immidb/idb/issues).|✅Yes|
|Tech support|⌧No|✅Yes. Via email, message or phone.|
|Frequency of updates|19 releases in 2017 with dozens of new features [Releases since v2.0.0 on Sept 8, 2017](https://github.com/immidb/idb/milestones?state=closed)|[More than 50 releases of new features in 2017](https://www.practicepanther.com/law-firm-practice-management-software/)|
||||
|<h5>Security</h5>|||
|Set permissions for users|✅Yes. Can determine which users can see which data and functionality.|✅Yes. Can determine which users can see which data and functionality.|
|Data privacy(data not accessible by sys admins)|✅Yes.Database can be established on a private servers and network.|✅Yes. Data resides on Practice Panther infrastructure but is not accessible by Practice Panther unless authorized for support purposes.|
|Data encrypted|✅Yes. Choose to implement with data encryption.  Passwords are automatically encrypted regardless of backend implementation |✅Yes. 256 bit encryption|
|2 Factor Authentication|✅Yes. Administratively set when and how 2 factor is turned on for users such as required when logging in from unknown IP addresses|?|
|HIPAA complian|⌧No. Not reviewed for HIPAA|✅Yes. "HIPAA compliant file management"|
||||
|<h5>Infrastructure</h5>|||
|Can be deployed to private network|✅Yes. ImmiDb is deployed via Docker Containers which can be deployed to any infrastructure of your choice that support Docker Containers including Linux, Microsoft Servers, AWS, Microsoft Azure, Google Cloud |⌧No.  Hosted by Practice Panther on Microsoft Azure cloud|
|Data backups|✅Yes. As deployed |✅Yes|
|IP Address Restrictions|✅Yes. Administratively restrict access to IPs that you choose |?|
|Query data via API|⌧No. ImmiDb queries and updates data via a backend REST API which can be accessed by developers but is not intended for end user queries|✅Yes [Swagger API](https://www.practicepanther.com/law-office-software-api/)|
||||
|<h5>Company</h5>|||
|For profit|TBD (Open Source or Commercial)|✅Yes|
|Number of Law Office Implementations|1|"In 2016 we had a 97% satisfaction rating from thousands of law firms."|
|How long has app been in production|Since 2014|Since 2012|
|# of employees|None|Dozens; hq in Miami, FL|

