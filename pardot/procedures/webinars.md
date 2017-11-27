# Pre-Webinar E-Mails

## Salesforce
### 1. Create New Campaign
- **Name**: WBNR - [Name] - [MMM-YYYY]
- **Add Campaign Member Statuses**:
  - Opened
  - Registered
  - Attended
  - Absent

### 2. Create Report for E-Mail List
- 
### 3. Add E-Mail List to Campaign
- 

## Pardot
### 1. Create New List E-Mail
- Select E-Mail Template “Webinar: Invitation” to create the first e-mail, specifying “#1” in the title
- Edit E-Mail contents
- 

### 2. Copy E-Mail #1 for #2 and #3
- Edit content as needed.
- In "Sending" tab, ensure the following Settings:
  - On Open: Set Prospect's Source Campaign to "Webinar"
  - On Click: Add Tags "wbnr-cta-click"
  - On Unsubscribe: Remove from List "Webinars"

### Result
1. Once the recipient successfully submits the Zoom Webinar Form,
  - the recipient will automatically be added to the List “Webinar Registrations.” This list will then be used as the Suppression List when sending E-Mails #2 and #3.
  - the recipient will automatically be added to the List “Webinars,” which allows them to opt-out from the E-Mail Preferences page
  - the recipient will automatically be added to the corresponding Salesforce Campaign, which allows us to report on the number of recipients who are “touched” by the different campaigns

# Post-Webinar E-Mails
1.	“Webinar: Attendees”
2.	“Webinar: Absentees”
