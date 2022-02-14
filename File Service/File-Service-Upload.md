# File-Service-Upload

**URL** : `/api/File-service/upload/`

**Method** : `POST`

**Auth required** : NO

**Data constraints**

```json
{
    "FileName": "[FileName]",
    "Size": "[Size]",
    "Parent": "[Parent]",
    
}
```
**Data example**

```json
{
     "FileName": "Zaid",
    "Size": "23kb",
    "Parent": "VCollab",

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