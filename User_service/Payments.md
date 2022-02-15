# Payments

**URL** : `/api/PAYMENTS/`

**Method** : `GET`

**Auth required** : NO

**Data constraints**

```json
{
    "Invoice Details": "[Details]",
  
}
```
**Data example**

```json
{
     "Invoice Details": "Details",
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