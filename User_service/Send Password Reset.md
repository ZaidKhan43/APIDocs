# Send Password Reset

**URL** : `/api/ADD_GOOGLE_STORAGE/`

**Method** : `POST`

**Auth required** : NO

**Data constraints**

```json
{
    "email": "[email]",
    
   
    
}
```
**Data example**

```json
{
    "email": "Check your email",

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