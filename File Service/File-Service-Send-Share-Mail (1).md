# File-Service-Send-Share-Mail

**URL** : `/api/file-service/send-share-mail/`

**Method** : `POST`

**Auth required** : NO

**Data constraints**

```json
{
    "Id": "[Id]",
    "resp": "[resp]"
    
    
}
```
**Data example**

```json
{
     "Id": "2322",
    "Resp": "Response",

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