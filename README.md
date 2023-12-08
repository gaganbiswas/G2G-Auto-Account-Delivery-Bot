# G2G Auto Account Delivery

## Installation

- Download Zip - [Click here to download](https://github.com/gaganbiswas/G2G-Auto-Account-Delivery-Bot/archive/refs/heads/main.zip)
- Install the app by running the .exe file.
- Run the app as administrator. (This is only required if you are installing the app in C: drive where exclusive permission is required).
- Click on `Settings` and enter your `refresh_token` and `active_device_token` cookies and save the file. (Entering `G2GSESID_V4` is not necessary.)
- Access the cookie by going to www.g2g.com then pressing CTRL + SHIFT + I -> Application -> Cookies -> https://www.g2g.com
- Add your accounts to be sold inside by clicking the `Manage Accounts`.
- Run the application.

```
// Example of Accounts.json
[
  {
    "target_title": "The title of the listing this account is meant to deliver.",
    "account_id": "username",
    "password": "password",
    "first_name": "name",
    "last_name": "last",
    "account_country": "Country",
    "date_of_birth": "0000-00-00",
    "email_account": "email",
    "email_password": "email_pass",
    "secret_question": "None",
    "secret_answer": "None",
    "additional_note": "note"
  },
  {
  ... Another account
  }
]
```

## Notes
Actively maintained by
- [@gaganbiswas](https://github.com/gaganbiswas)
