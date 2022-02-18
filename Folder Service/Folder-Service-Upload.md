# Folder-Service-Upload

**URL** : `/folder-service/upload`

**Method** : `POST`

**Auth required** : NO

**Data constraints**

```json
{
    "name": "Test"
    "owner": "61f7b576ac857c0c106c4112"
    "parent": "/"
    "parentList": ["/"]
    
}
```
**Data example**

```json
{
    "name": "Test"
    "owner": "61f7b576ac857c0c106c4112"
    "parent": "/"
    "parentList": ["/"]

}
```

## Success Response

**Code** : `200 OK`

**Content example**

```json
{
    "parentList": 
    [
        "/"
    ],
    "_id": "620cfbd205e5d5460c87bc5d",
    "name": "Test",
    "parent": "/",
    "owner": "61f7b576ac857c0c106c4112",
    "createdAt": "2022-02-16T13:27:46.021Z",
    "updatedAt": "2022-02-16T13:27:46.021Z",
    "__v": 0
}
```
