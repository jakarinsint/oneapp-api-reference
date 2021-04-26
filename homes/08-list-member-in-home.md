# List all Members in Home

List all members in home by home Id. Allow user who is a owner or member in home calls the api.

**URL** : `{endpoint}/v2/homes/member/list/:homeId`

**Method** : `GET`

**Auth required (Bearer token)** : YES

**URL Parameters** : `homeId = [desc: Home Id, type: string]`


## Success Response

**Code** : `200 OK`

**Content examples**
This example, user want to get all homes in Property Perfect.

```json
{
    "result": {
        "homeId": "605069c10668ee0ce4f4ffd4",
        "myRole": "owner",
        "myStatus": "0",
        "members": [
            {
                "customerId": "607d0719977fd0189caf6d03",
                "firstName": "Jakarin",
                "lastName": "Sintupanpratum",
                "role": "owner",
                "status": "0",
                "image": "/uploads/images/1615428568976_Snip25640309_3.png"
            }
        ]
    }
}
```
