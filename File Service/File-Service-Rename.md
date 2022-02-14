# File-Service-Rename

**URL** : `/api/file-service/Rename/`

**Method** : `PATCH`

**Auth required** : NO

**Data constraints**

```json
{
    "Id": "[Id]",
    "Title": "[Title]",
    
    
}
```
**Data example**

```json
{
     "Id": "2322",
    "Title": "Vcollab",

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