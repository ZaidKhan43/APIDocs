# Create
Used to collect token for registered user.
**URL** : `/api/create/`

**Method** : `POST`

**Auth required** : NO

**Data constraints**

```json
{
    "email": "[valid email address]",
    "password": "[password in plain text]"
}
```
**Data example**

```json
{
    "email": "zaid@gmail.com",
    "password": "zaid"
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