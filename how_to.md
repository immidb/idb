## ImmiDB How To 

__A partial list of [ImmiDB functionality](https://immidb.net/) help and instructions:__

* [Open/Edit USCIS Form](#user-content-open-uscis-form)<br>
* [Change Client Status](#user-content-change-client-status)<br>
* [Delete a Client](#user-content-delete-a-client)<br>
* [Send an SMS Text](#user-content-send-an-sms-text)<br>
* [View EOIR Calendar](#user-content-view-eoir-court-calendar)<br>
* [View Recent EOIR Changes](#user-content-view-recent-eoir-changes)<br>
* [View EOIR Details For Client](#user-content-view-eoir-details-for-client)<br>
* [Modify Invoice Messages](#user-content-invoice-message)<br>
* [Admin](https://immidb.net/how_to_admin.html)

<a id="open-uscis-form"></a>
### Open/Edit USCIS Form

1. Open a New or Existing Application on the Client Page by clicking the "<b>+</b>" next to the <b>Applications</b> header or click one of the Applications already listed

  <img src="https://immidb.net/imgs/space_indent.png" 
    width="30" height="10" style="border:5px solid black"/>
  <img src="./imgs/client_application.png" 
    width="800" height="300" style="border:5px solid black"/>

2. Select the form in the <b>Form Number</b> box (can type partial form number to search).  

    The applicable PDF forms with their effective date are listed under <b>USCIS Forms</b> on the right. 
    
    <b>'F'</b> indicates that at least some form fields will be populated from the currently selected Client when you open the form. 

  <img src="https://immidb.net/imgs/space_indent.png" 
    width="30" height="10" style="border:5px solid black"/>
  <img src="./imgs/application_modal.png" 
    width="800" height="500" style="border:5px solid black"/>

3. Click the Form listed under <b>USCIS Forms</b> that you want to open.  The form will open in new browser tab.

4. Continue to edit form fields in the browser to complete the form. When completed, save by clicking the download button OR click the Print button and choose pdf. 

    <b>Note: To re-open and continue editing the form after it has been saved, open it in the Chrome browser rather than in Adobe Reader</b>.  Adobe Reader will not allow the form to continue to be edited in most situations.

  <img src="https://immidb.net/imgs/space_indent.png" 
    width="30" height="10" style="border:5px solid black"/>
  <img src="./imgs/pdf_form.png" 
    width="800" height="300" style="border:5px solid black"/>


<a id="change-client-status"></a>
### Change Client Status
Client Status includes 'Open', 'Closed' and 'Deleted'

1. Click Client Status to edit it. 

  <img src="https://immidb.net/imgs/space_indent.png" 
    width="20" height="10" style="border:5px solid black"/>
  <img src="https://immidb.net/imgs/client_status_1.png" 
    width="800" height="130" style="border:5px solid black"/>

2. Click it again to see the dropdown options ('Open', 'Closed', 'Deleted')

  <img src="https://immidb.net/imgs/space_indent.png" 
    width="20" height="10" style="border:5px solid black"/>
  <img src="https://immidb.net/imgs/client_status_2.png" 
    width="200" height="150" style="border:5px solid black"/>

3. Select the Client Status desired ('Open', 'Closed', 'Deleted')

<a id="delete-a-client"></a>
### Delete a Client

1. Click Client Status to edit it. 

  <img src="https://immidb.net/imgs/space_indent.png" 
    width="20" height="10" style="border:5px solid black"/>
  <img src="https://immidb.net/imgs/client_status_1.png" 
    width="800" height="130" style="border:5px solid black"/>

2. Click it again to see the dropdown options ('Open', 'Closed', 'Deleted')

  <img src="https://immidb.net/imgs/space_indent.png" 
    width="20" height="10" style="border:5px solid black"/>
  <img src="https://immidb.net/imgs/client_status_2.png" 
    width="200" height="150" style="border:5px solid black"/>

3. Select 'Deleted'

    The client is marked as Deleted so it will not appear in searches or the client list.  It still exists in the database though and can be Un-deleted by returning to that client URL directly (you'll see a message indicating it is deleted) and then change the Client Status to 'Open' or 'Closed'.


<a id="send-an-sms-text"></a>
### Send an SMS Text
An SMS text (typical phone text) can be sent if the Admin / Twilio has been set up by the database admin.  See [Admin / How to Set Up SMS Texting](https://immidb.net/how_to_admin.html#user-content-twilio-setup). 

There are 2 ways in which an SMS Text can be sent.  
##### Send an SMS Text from the Nav Bar

  <img src="https://immidb.net/imgs/space_indent.png" 
    width="20" height="10" style="border:5px solid black"/>
  <img src="https://immidb.net/imgs/nav_menu_sms.png" 
    width="250" height="100" style="border:5px solid black"/>

##### Send an SMS Text by client phone number
When viewing a client who has phone numbers entered, hover over the phone number and click the SMS Text button when it appears. 

  <img src="https://immidb.net/imgs/space_indent.png" 
    width="20" height="10" style="border:5px solid black"/>
  <img src="https://immidb.net/imgs/client_send_text.png" 
    width="400" height="150" style="border:5px solid black"/>

You can then enter/change the recipient phone number and message.  Any previous texts sent to that phone number are displayed at bottom in Text Message History. 

  <img src="https://immidb.net/imgs/space_indent.png" 
    width="20" height="10" style="border:5px solid black"/>
  <img src="https://immidb.net/imgs/text_modal.png" 
    width="600" height="400" style="border:5px solid black"/>


<a id="view-eoir-court-calendar"></a>
### View EOIR Court Calendar

The EOIR Court Hearings Calendar is displayed on the Home page. 

1. Click 'Home' in the top navigation.

    The EOIR Court Hearings Calendar will be displayed. 

  <img src="https://immidb.net/imgs/space_indent.png" 
    width="20" height="10" style="border:5px solid black"/>
  <img src="https://immidb.net/imgs//eoir_hearings_calendar.png" 
    width="800" height="300" style="border:5px solid black"/>

  _(Randomly generated names, A-Numbers and data : does not reflect any real people)_

The 'Clients' column lists and links to the database clients and their derivatives that match on A-Number. 

Click any other column in a row to [see the EOIR details](#user-content-view-eoir-details-for-client).

See [Admin/Set Up EOIR](https://immidb.net/how_to_admin.html#user-content-set-up-eoir-integration) to set up EOIR and Attorneys for EOIR sync 

<a id="view-recent-eoir-changes"></a>
### View Recent EOIR Court Changes

The Recent EOIR Changes list is displayed on the Home page below the EOIR Hearings Calendar.  This shows the changes that have occurred within the last 20 days as detected by the EOIR sync process. 

Click 'Home' in the top navigation and scroll down to see the Recent EOIR Changes
  <img src="https://immidb.net/imgs/space_indent.png" 
    width="20" height="10" style="border:5px solid black"/>
  <img src="https://immidb.net/imgs//eoir_changes.png" 
    width="900" height="325" style="border:5px solid black"/>

The 'New' and 'Old' fields will give an abbreviated view of what changed.  Click 'Details' to see the full change details. 


Click any other column in a row to [see the EOIR details](#user-content-view-eoir-details-for-client).

See [Admin/Set Up EOIR](https://immidb.net/how_to_admin.html#user-content-set-up-eoir-integration) to set up EOIR and Attorneys for EOIR sync 

<a name="view-eoir-details-for-client"></a>
### View EOIR Court Details for Client

The EOIR details for a client can be displayed several ways. 

1. Click a row in the [EOIR Court Hearings Calendar](#user-content-view-eoir-court-calendar)
2. Click a row in the [EOIR Recent Changes](#user-content-view-recent-eoir-changes)
3. Click a row in the EOIR Immigration Court Cases on the Client page for a client (scroll down on the client page to that section)

  <img src="https://immidb.net/imgs/space_indent.png" 
    width="20" height="10" style="border:5px solid black"/>
  <img src="https://immidb.net/imgs//client_eoir.png" 
    width="800" height="250" style="border:5px solid black"/>
    _(Randomly generated names, A-Numbers and data : does not reflect any real person)_

  If a client has EOIR information as matched by the A-Number directly for the client or any of its derivatives, those EOIR Court items will be listed in this section. 

  After clicking a row, the full details are displayed that have been pulled from the EOIR court site. 

  <img src="https://immidb.net/imgs/space_indent.png" 
    width="20" height="10" style="border:5px solid black"/>
  <img src="https://immidb.net/imgs//eoir_details.png" 
    width="600" height="500" style="border:5px solid black"/>
<br>_(Randomly generated names, A-Numbers and data : does not reflect any real person)_

<a name="invoice-message"></a>
### Modify Invoice Messages

Here's how to modify the message that appears on the Invoice: 

You can add/edit the Invoice message specific to each Client by editing the "Invoice Comment" field in the Case Information field on that Client's page. 

  <img src="https://immidb.net/imgs/space_indent.png" 
    width="20" height="10" style="border:5px solid black"/>
  <img src="https://immidb.net/imgs/client_invoice_comment.png" 
    width="200" height="200" style="border:5px solid black"/>

You can also modify the standard Invoice Message that appears on every invoice created: see [How to Modify Invoice Messages for all Clients](https://immidb.net/how_to_admin.html#user-content-invoice-message)
