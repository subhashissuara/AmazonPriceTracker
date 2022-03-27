# Amazon Price Tracker

A python script to automate the process of tracking price drops on Amazon. When the script detects a price drop, it notifies via given email.

## Requirements

Create a config.py file with the following variables

```
PRODUCTS_TO_TRACK = ["B07ZRXF7M8", "B09G9HRYFZ"]
FROM_EMAIL_ID = ""
FROM_EMAIL_ID_PASSWORD = ""
TO_EMAIL_ID = ""
SMTP_HOST = "smtp.gmail.com"
SMTP_PORT = 587
```

`python >= 3.6`

`pip install requests-html`
