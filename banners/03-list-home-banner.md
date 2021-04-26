# List Home Banners by Property Id


**URL** : `{endpoint}/v2/homes/banner/list/:propertyId`

**Method** : `GET`

**Auth required (Bearer token)** : YES

**Caller is able to set criteria by specific projectId as request body**

```json
{
    "projectId": "607ea72a6e25fa2542b2f3fe"
}
```

## Success Response

**Code** : `200 OK`

```json
{
    "result": {
        "banners": [
            {
                "_id": "60866bb15dfd054acbf8ac44",
                "propertyId": "607ea6766e25fa2542b2f3e2",
                "projectId": "607ea72a6e25fa2542b2f3fe",
                "bannerNameEn": "Test Property Perfect Banner 02",
                "title": "Advertisment",
                "content": "a public and typically formal statement about a fact, occurrence, or intention. Test 02",
                "image": "/uploads/banners/oneapp_1619422129661.png"
            },
            {
                "_id": "60866ba05dfd054acbf8ac43",
                "propertyId": "607ea6766e25fa2542b2f3e2",
                "projectId": "607ea72a6e25fa2542b2f3fe",
                "bannerNameEn": "Test Property Perfect Banner 01",
                "title": "Advertisment",
                "content": "a public and typically formal statement about a fact, occurrence, or intention. Test 01",
                "image": "/uploads/banners/oneapp_1619422112139.png"
            }
        ]
    }
}
```
