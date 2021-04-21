# Update Current User

Update the details of the currently Authenticated User along with basic
subscription information.

**URL** : `{endpoint}/v2/users/me`

**Method** : `PUT`

**Auth required (Bearer token)** : YES

**Body constraints**

```json
{
    "firstName": "Jakarin",
    "lastName": "Sintupanpratum",
    "gender": "male",
    "dateOfBirth": "02/28/1982"
}
```

## Success Response

**Code** : `200 OK`

**Content examples**


```json
{
    "result": {
        "user": {
            "firstName": "Jakarin",
            "lastName": "Sintupanpratum",
            "email": "jakarin@gmail.com",
            "mobileNumber": "0649954161",
            "gender": "male",
            "dateOfBirth": "02/28/1982"
        }
    }
}
```