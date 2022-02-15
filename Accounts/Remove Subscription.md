# Remove Subscription

**URL** : `/api/Remove_SUBSCRIPTION/`

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
    "Text": "This will remove all Vcollab Drive files",

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