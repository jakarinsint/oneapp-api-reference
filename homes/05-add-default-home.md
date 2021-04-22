# Add Default Home (In case of user is an Owner) by Home Id

Add default home by home Id of the currently Authenticated User along with basic
subscription information.

**URL** : `{endpoint}/v2/homes/default/add/:homeId`

**Method** : `POST`

**Auth required (Bearer token)** : YES

**URL Parameters** : `homeId = [desc: Home Id, type: string]`


## Success Response

**Code** : `204 No Content`
