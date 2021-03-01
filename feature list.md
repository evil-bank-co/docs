https://docs.google.com/document/d/1-Q4EiVuIJ-wak6u_OQc3VaCWjDSiNZLjrsQmoIGvma8/edit

Features for evil bank:
- Users
  - Support for 2FA
- Accounts - https://en.wikipedia.org/wiki/International_Bank_Account_Number
  - One user can have more than one account
  - Different currencies
  - Different features
  - Transaction list
- Contacts
- Cards
  - Payments from cards should appear in transaction list
  - Payments made from cards should be validated by logging into the account and approving
  - Card payments can be classified as fraudulent for up to 14 days after purchase - need to provide reason
  - There should be a ratelimit on cards. No more than one transaction every 5s
- Admin interface
  - Allow reversal of charges
  - Block anyone’s card
