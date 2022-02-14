# Folder-Service-Info

**URL** : `/api/folder-service/Info/`

**Method** : `GET`

**Auth required** : NO

**Data constraints**

```json
{
    "Id": "[Id]",
    "FileName": "[Filename]",
    
    
}
```
**Data example**

```json
{
     "Id": "2322",
    "FileName": "text file",

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