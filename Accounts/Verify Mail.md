# Verify Mail

**URL** : `/api/VERIFY_MAIL/`

**Method** : `POST`

**Auth required** : NO

**Data constraints**

```json
{
    "Email Token": "[id]",
   
    
}
```
**Data example**

```json
{
    "Email Token": "211212",

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