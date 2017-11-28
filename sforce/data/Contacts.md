# Contacts
Type | Count
-----|------
All | 11,910
Active | 10,756
Deleted | 1,154

## Active
Type | Count | File | Criteria
-----|-------|------|----------
Active, Bounced | 894 | ex-currentContactFields.csv | Field 'ISEMAILBOUNCED' = 'TRUE'
Active, NOT Bounced | 9,862 | ex-currentContactFields.csv | Field 'ISEMAILBOUNCED' = 'FALSE'

Identify:
- Duplicate Contacts
- Contacts not associated with an Account
- Contacts with Generic E-Mail Addresses
- Contacts with operational E-Mail Addresses
- Contacts with 2 Email Addresses

Update:
- Account
- Phone
- Title / Salutation
- Contact Status: DEPARTMENT, CONTACT_SOURCE, NO_LONGER_EMPLOYED, 
- Email Status: HASOPTEDOUTOFEMAIL, DONOTCALL, OPT_IN, 
- Contact Information: INDUSTRY, PRIMARY_CONTACT, WEB_SERVICES_CONTACT, CONTACT_S_DETAIL_ROLE, APPLICATION_SERVER (move to Account?)
