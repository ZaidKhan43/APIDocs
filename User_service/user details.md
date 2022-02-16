# User Details
Used to collect details of user.
**URL** : `/user-service/user`

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
{"_id":"61f7b576ac857c0c106c4112","emailVerified":true,"email":"zaid@gmail.com"}
```
