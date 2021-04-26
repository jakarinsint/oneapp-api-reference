# Update Home Banner by Banner Id


**URL** : `{endpoint}/v2/homes/banner/update/:bannerId`

**Method** : `PUT`

**Auth required (Bearer token)** : YES

**Body constraints (form-data)**

```json
{
    "propertyId": "607ea6766e25fa2542b2f3e2",
    "projectId": "607ea6766e25fa2542b2f3e2",
    "bannerNameEn": "Test Property Perfect Banner",
    "startDate": "04/23/2021",
    "endDate": "05/23/2021",
    "title": "Advertisment",
    "content": "a public and typically formal statement about a fact, occurrence, or intention.",
    "bannerImage": "files://home_pf_test.png",
}
```

## Success Response

**Code** : `204 No Content`
