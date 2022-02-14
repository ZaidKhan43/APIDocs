# Reset Password

**URL** : `/api/RESET_PASSWORD/`

**Method** : `POST`

**Auth required** : NO

**Data constraints**

```json
{
    "id": "[id]",
    "Password" :"[Password]"
    
   
    
}
```
**Data example**

```json
{
     "passwordToken": "1111",
    "Password" :"abcd"

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