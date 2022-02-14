# Change Password

**URL** : `/api/CHANGE_PASSWORD/`

**Method** : `POST`

**Auth required** : NO

**Data constraints**

```json
{
    "New Password": "[new password]",
    "Old Password": "[old password]"
    
}
```
**Data example**

```json
{
     "New Password": "12345",
    "Old Password": "09877"

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