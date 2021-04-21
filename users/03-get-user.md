# Get User By UserId

Get the details of the currently Authenticated User along with basic
subscription information.

**URL** : `{endpoint}/v2/users/:uid`

**Method** : `GET`

**Auth required (Bearer token)** : YES

**URL Parameters** : `uid = [desc: User Id, type: string]`

## Success Response

**Code** : `200 OK`

**Content examples**


```json
{
    "result": {
        "user": {
            "firstName": "test_fristname",
            "lastName": "test_lastname",
            "email": "test@mail.com",
            "mobileNumber": "0891111111",
            "gender": "male",
            "dateOfBirth": "04/19/2021"
        }
    }
}
```