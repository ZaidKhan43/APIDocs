# User Details
Used to collect details of user.
**URL** : `/api/USER_DETAILED/`

**Method** : `GET`

**Auth required** : NO

**Data constraints**

```json
{
    "name": "[valid name]",
    "email": "[valid email address]",
}
```
**Data example**

```json
{
    "name": zaid
    "email": "zaid@gmail.com",
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