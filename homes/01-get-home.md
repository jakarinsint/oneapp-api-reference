# Get Home By Home Id

Get home details by home Id of the currently Authenticated User along with basic
subscription information.

**URL** : `{endpoint}/v2/homes/get/:homeId`

**Method** : `GET`

**Auth required (Bearer token)** : YES

**URL Parameters** : `homeId = [desc: Home Id, type: string]`

## Success Response

**Code** : `200 OK`

**Content examples**


```json
{
    "result": {
        "homeInfo": {
            "_id": "605069c10668ee0ce4f4ffd4",
            "name": "Home 07",
            "info": {
                "properties": {
                    "_id": "607ea6766e25fa2542b2f3e2",
                    "nameTh": "Property Perfact",
                    "nameEn": "Property Perfact"
                },
                "projects": {
                    "_id": "607ea72a6e25fa2542b2f3fe",
                    "nameTh": "Perfect place",
                    "nameEn": "Perfect place"
                },
                "homeAddress": "No27. Soi Sukhumvit 11, Khlong Toei Nuea, Watthana, Bangkok 10110"
            },
            "members": [
                {
                    "customerId": "607d0719977fd0189caf6d03",
                    "firstName": "Jakarin",
                    "lastName": "Sintupanpratum",
                    "role": "owner",
                    "status": "0",
                    "image": "/uploads/images/1615428568976_Snip25640309_3.png"
                },
                {
                    "customerId": "604979b77b715c0897189e15",
                    "firstName": "test_jakarin",
                    "lastName": "test_sint",
                    "role": "member",
                    "status": "0",
                    "image": "/uploads/images/1615428568976_Snip25640309_3.png"
                }
            ],
            "image": "/uploads/images/oneapp_1618997368312.jpeg"
        }
    }
}
```