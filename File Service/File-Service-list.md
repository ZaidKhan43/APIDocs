# File-Service-list

**URL** : `/api/file-service/list/`

**Method** : `GET`

**Auth required** : NO

**Data constraints**

```json
{
    "File Url": "[File Url]",
    "Folder Url": "[Folder Url]",
    
}
```
**Data example**

```json
{
     "File Url": "File Url",
    "Folder Url": "Folder Url",

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