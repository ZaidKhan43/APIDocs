# Resend Verify Email

**URL** : `/api/RESEND_VERIFY_EMAIL/`

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
    "email": "Verify Email",

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