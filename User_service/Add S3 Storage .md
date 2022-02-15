# Add S3 Storage

**URL** : `/api/ADD_S3_STORAGE/`

**Method** : `POST`

**Auth required** : NO

**Data constraints**

```json
{
    "Id": "[id]",
    "Bucket" :"[Bucket]",
    "Key" :"[Key]"
    
}
```
**Data example**

```json
{
     "Id": "123",
    "Bucket" :"S3 Bucket",
    "Key" :"57678"

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