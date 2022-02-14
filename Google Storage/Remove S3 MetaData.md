# Remove S3 MetaData

**URL** : `/api/REMOVE_S3_METADATA/`

**Method** : `DELETE`

**Auth required** : NO

**Data constraints**

```json
{
    "Title": "[Title]",
    "Text": "[Text]",
   
    
}
```
**Data example**

```json
{
    "Title": "Remove Subscription?",
    "Text": "This will remove all s3 Metadata",

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