# Folder-Service-Upload

**URL** : `/api/folder-service/upload/`

**Method** : `POST`

**Auth required** : NO

**Data constraints**

```json
{
    "Name": "[Name]",
    "Owner": "[Owner]",
    "Parent": "[Parent]",
    
}
```
**Data example**

```json
{
     "Name": "Zaid",
    "Owner": "Vcollab",
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