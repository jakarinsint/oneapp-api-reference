# Get Default Home

Get default home details of the currently Authenticated User along with basic
subscription information.

**URL** : `{endpoint}/v2/homes/default/get`

**Method** : `GET`

**Auth required (Bearer token)** : YES

## Success Response

**Code** : `200 OK`

**Content examples**


```json
{
    "result": {
        "defaultHome": {
            "_id": "605069c10668ee0ce4f4ffd4",
            "name": "Home 09",
            "image": "/uploads/images/oneapp_1619012498340.jpeg",
            "info": {
                "property": {
                    "_id": "607ea6766e25fa2542b2f3e2",
                    "nameTh": "Property Perfact",
                    "nameEn": "Property Perfact"
                },
                "project": {
                    "_id": "607ea72a6e25fa2542b2f3fe",
                    "nameTh": "Perfect place",
                    "nameEn": "Perfect place"
                },
                "homeAddress": "No27. Soi Sukhumvit 11, Khlong Toei Nuea, Watthana, Bangkok 10110"
            }
        }
    }
}
```