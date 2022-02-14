# Folder-Service-Remove

**URL** : `/api/folder-service/Remove/`

**Method** : `DELETE`

**Auth required** : NO

**Data constraints**

```json
{
    "Id": "[Id]",
    "ParentList": "[ParentList]",
    
    
}
```
**Data example**

```json
{
     "Id": "2322",
    "ParentListr": "Vcollab",

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