# Create google Storage URL

**URL** : `/api/CREATE_GOOGLE_STORAGE_URL/`

**Method** : `POST`

**Auth required** : NO

**Data constraints**

```json
{
    "Client ID": "[ID]",
    "Client Key": "[Key]",
    "Client Redirect": "[Text]"
    
}
```
**Data example**

```json
{
    "Client ID": "123",
    "Client Key": "8883",
    "Client Redirect": "[Text]"

}
```

## Success Response

**Code** : `200 OK`

**Content example**

```json
{
    "token": "93144b288eb1fdccbe46d6fc0f241a51766ecd3d"
}
```