# Update Home By Home Id

Update home's name and home's image by home Id of the currently Authenticated User along with basic
subscription information.

**URL** : `{endpoint}/v2/homes/update/:homeId`

**Method** : `PUT`

**Auth required (Bearer token)** : YES

**URL Parameters** : `homeId = [desc: Home Id, type: string]`

**Body constraints (form-data)**

```json
{
    "name": "Home 02",
    "homeImage": "home_02.jpeg",
}
```

![alt text for screen readers](/assets/images/update-home.png "Sample body data")

## Success Response

**Code** : `200 OK`

**Content examples**
The api shall return the updated home info to caller.


```json
{
    "result": {
        "homeInfo": {
            "_id": "605069c10668ee0ce4f4ffd4",
            "name": "Home 02",
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
                    "image": "/uploads/images/oneapp_1615428568976.png"
                },
                {
                    "customerId": "604979b77b715c0897189e15",
                    "firstName": "test_jakarin",
                    "lastName": "test_sint",
                    "role": "member",
                    "status": "0",
                    "image": "/uploads/images/oneapp_1615428568976.png"
                }
            ],
            "image": "/uploads/images/oneapp_1619012498340.jpeg"
        }
    }
}
```