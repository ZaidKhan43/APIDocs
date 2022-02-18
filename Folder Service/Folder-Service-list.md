# Folder-Service-list

**URL** : `/folder-service/list/`

**Method** : `GET`

**Auth required** : NO

**Data constraints**

```json
{
    "parent": "/"
    "type": "mongo"
    
}
```
**Data example**

```json
{
    "parent": "/"
    "type": "mongo"

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
    "_id": "6200ceb38adb8029d8ce77ba",
    "name": "abcd",
    "parent": "/",
    "owner": "61f7b576ac857c0c106c4112",
    "createdAt": "2022-02-07T07:48:03.050Z",
    "updatedAt": "2022-02-07T07:48:03.050Z",
    "__v": 0
}
```
