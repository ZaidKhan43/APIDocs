# Folder-Service-Move

**URL** : `/api/folder-service/Move/`

**Method** : `PATCH`

**Auth required** : NO

**Data constraints**

```json
{
    "Id": "[Id]",
    "Parent": "[Parent]",
    
    
}
```
**Data example**

```json
{
     "Id": "2322",
    "Parent": "Vcollab",

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