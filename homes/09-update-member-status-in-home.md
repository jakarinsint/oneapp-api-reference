# Update Member Status in Home

Update member status in specific home.

**URL** : `{endpoint}/v2/homes/member/status/:homeId/:uid`

**Method** : `PUT`

**Auth required (Bearer token)** : YES

**URL Parameters** : `homeId = [desc: Home Id, type: string]` and `uid = [desc: User Id, type: string]`

**Body constraints (form-data)**

```json
{
    "status": "0"
}
```


## Success Response

**Code** : `204 No Content`
