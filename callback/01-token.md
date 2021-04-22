# Authentication API

Request ADMD's token by CODE and populate OneApp token for client side.

**URL** : `{gw_endpoint}/v1/callback/auth/token`

**Method** : `POST`


**Body constraints**

```json
{
    "code": "k1NrCjej6v8mhY550kL0G9az4xtvcpGv4f6q6hN6r3e5"
}
```


## Success Response

**Code** : `200 OK`

**Content examples**


```json
{
    "admd_token": {
        "access_token": "eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCIsImtpZCI6Ikk3cTlSYW1VMjcifQ.eyJpc3MiOiJzcmYuYWlzLmNvLnRoL2FkbWQiLCJzdWIiOiJ0b2tlbl9hdXRoZW50aWNhdGlvbl9jb2RlIiwiYXVkIjoiUXNXQjlRRTFNcSs4SUdkWDdraU5Da3dKdHlqd1Bnd0E3UWMxSWp0VzVmL1lrYi9UeEFTT2p3PT0iLCJleHAiOjE2MTkwNzk4NzAsImlhdCI6MTYxOTA3NjI3MCwianRpIjoiNUFlY1JvMUdNRTFjN3ZQcWIzWXUwTSIsInBpZCI6IkE2MkJHb1lNMU1aRGFKdXQ0cFlNb3BPb0RpU3NJQWo2US9oUjh3dGMycHU9IiwiY2xpZW50IjoiTXpBeE16VXNZV2x6YzIxaGNuUnNhWFpwYm1kMk0zeENjbTkzYzJWeWZERXVNQzR3Iiwic3NpZCI6IkF4QnVvS2VGZGUwRDkwMjIyQ1B2OGkiLCJ1aWQiOiI2NjE2MTAwMjA3Mzc3NTkiLCJhdXQiOnsidHlwZSI6Im1zaXNkbiIsImFjdGlvbiI6ImxvZ2luIiwibG9naW5fY2hhbm5lbCI6Im1zaXNkbl9wYXNzd29yZCIsIm5ldHdvcmsiOiJhbm9ueW1vdXMifSwiaWRwIjoiYWlzIn0.KGZztJ5EsWOZoJrYpcVaJlVGWbjXWwq5mHp-nuWPD3I7iRQye3POo1EO6uM31YRYoPdC0k9G7_78iy-DfOpaI2cj7Dk8jg_zrMeIoVcZrRyvNINv8KHG8Gq1umFlKbmgiNQ61m24Mk-Smyn7vCQDd1pkx6Pw1MFO58r4aeSiLc8",
        "refresh_token": "NUh6QzBFbjltTW5vNzE2ODI5SW4xNjE5MDc2MjcwAxBuoKeFde0D90222CPv8i",
        "refresh_token_expires_in": 86400,
        "token_type": "bearer",
        "expires_in": 3600,
        "id_token": "eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCIsImtpZCI6InBmaU82NlJId1QifQ.eyJpc3MiOiJzcmYuYWlzLmNvLnRoL2FkbWQiLCJzdWIiOiJpZFRva2VuIiwiYXVkIjoiUXNXQjlRRTFNcSs4SUdkWDdraU5Da3dKdHlqd1Bnd0E3UWMxSWp0VzVmL1lrYi9UeEFTT2p3PT0iLCJleHAiOjE2MTkwNzk4NzAsImlhdCI6MTYxOTA3NjI3MCwianRpIjoid3ZXZHlHWUdEczc3MTZjOVM3cjBsRCIsImF1dCI6eyJ0eXBlIjoibXNpc2RuIiwiYWN0aW9uIjoibG9naW4iLCJsb2dpbl9jaGFubmVsIjoibXNpc2RuX3Bhc3N3b3JkIiwibmV0d29yayI6ImFub255bW91cyJ9LCJub25jZSI6IkFETUQtMjEwNDIycHgxQ1FPQXp4aUkiLCJpbmZvIjp7InB1YmxpY19pZCI6IjA2NDk5NTQxNjEiLCJmaXJzdG5hbWUiOiJKYWthcmluIiwibGFzdG5hbWUiOiJTaW50In19.KWTz3LC8sqJZHLt-VvzAWnHEcHfqwREkzW_Mhy4Q64DcrcE-oWJIFgxiXBtjoHwI95Q6fjkxXvmWvwpNWWzKogGnaoul8PH7bdPD3LCCA6RIHLQ1EeU1T6FhP6RLc61SzRCZSv8n1I_suTfL2ZBHTF4nbw58-3gZ3NqTPhcp9hc"
    },
    "oneapp_token": {
        "access_token": "eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE2MTkwNzk4NzAsImlhdCI6MTYxOTA3NjI3MCwiaW5mbyI6eyJ1aWQiOiI2MDdkMDcxOTk3N2ZkMDE4OWNhZjZkMDMifX0.yj2VrMeBUugw3d9AOcCytkOjapBQNIJo9idD5KHQsIU",
        "token_type": "bearer",
        "expires_in": 1619079870
    }
}
```