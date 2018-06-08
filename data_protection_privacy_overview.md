## ImmiDB
###### General Overview of Data Privacy & Protection

June 8, 2018

#### Who has access
Only the the users to which you grant access and the ImmiDB Sys Admin have access to your database.  You will always know who has access to your data and, when accessed by ImmiDB for support, when it is accessed.  

Your data is your data.  It will never be shared in any form - electronically, verbally, or otherwise - with anyone without your express consent.   Your database implementation is specific to your law firm with different security authentication than other database implementations. Your data and authenticaion is separated physically and security-wise from other immigration law office implementations.  This includes server logins, application encryption keys and front-end sysadmin access.  Your servers reside in a virtual private network that can only be accessed via a web gateway (ie, the database login via the browser) or server login which is restricted to only the Sys Admin IP addresses.  

#### Encryption
The data is encrypted at rest and in transit (between the servers and browser).   Passwords and other especially sensitive data has an extra layer of encryption.  You can tell these fields as they are not displayed in the browser until that field is clicked.  

#### Sys Admin Access
The Sys Admin can and will access non-client and non-financial information in and about your database such as admin setup, logs and information to understand usage (the amount of space used, hits, etc) for infrastructure requirements. 

You will always be informed if the Sys Admin or anyone from ImmiDB accesses your data (eg, client and financial data) at the time that they access it. This is true of however the data is accessed; ie, on the "back end" or directly through the browser.   If it's a non-production issue, they will get your approval first.  If it's a production issue that is immediately affecting the usability of your database, they'll assume that you are ok that they access whatever data is needed to fix the issue as quickly as possible and keeping you informed during and after the issue.  

It is also possible to remove access even for the Sys Admin.  It will affect upgrades and support but is a perfectly viable option.  

#### Data Change Logs
Data changed via the application front end and for data conversions is logged with date and user.  These change logs are not available via the front end but can be provided manually if/when needed.  

#### Data Export
Just let your Sys Admin know and they can manually export and provide you the database data in files.  

#### Application Updates
Your Sys Admin will inform you prior to scheduled application updates.  These updates are normally done after normal business hours; ie, evenings and weekends.  It's common that these application updates require data updates / conversions.  If so, your Sys Admin also let you know that they may be viewing your data to verify those data conversions.  

#### Data Backups
Your data is backed up nightly.  Those backups are available for at least one month.  These backups are intended for full database recovery in the event of a significant unplanned event.  

