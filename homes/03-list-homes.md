# List Homes By Property Id

List all homes which authorized user is an Owner or Member in specify property.

**URL** : `{endpoint}/v2/homes/all/:propertyId`

**Method** : `GET`

**Auth required (Bearer token)** : YES

**URL Parameters** : `propertyId = [desc: Property Id, type: string]`


## Success Response

**Code** : `200 OK`

**Content examples**
This example, user want to get all homes in Property Perfect.

```json
{
    "result": {
        "homes": [
            {
                "_id": "605069c10668ee0ce4f4ffd4",
                "name": "Home 09",
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
                "image": "/uploads/images/oneapp_1619012498340.jpeg"
            }
        ]
    }
}
```