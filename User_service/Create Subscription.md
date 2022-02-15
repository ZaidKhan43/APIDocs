# Create Subscription

**URL** : `/api/CREATE_SUBSCRIPTION/`

**Method** : `POST`

**Auth required** : NO

**Data constraints**

```json
{
    "Payment": "[Payment]",
    "Card Number": "[CreditCardNumber]",
    "Expiry": "[Expiry]",
    "Cvv" : "[Cvv]"
    
}
```
**Data example**

```json
{
    "Payment": "Payment Loading"
    "Card Number": "[12345677]",
    "Expiry": "[08/22]",
    "Cvv" : "[123]"

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