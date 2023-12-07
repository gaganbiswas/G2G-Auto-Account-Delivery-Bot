# G2G Auto Account Delivery

## Installation

- Download Zip
- Enter your `refresh_token` and `active_device_token` cookies into `Settings.json` file, entering `G2GSESID_V4` is not necessary.
- Access the cookie by going to www.g2g.com then pressing CTRL + SHIFT + I -> Application -> Cookies -> https://www.g2g.com
- The `Accounts.json` holds your accounts to be sold.

```
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
