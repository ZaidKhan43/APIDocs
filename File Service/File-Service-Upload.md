# File-Service-Upload

**URL** : `/file-service/upload`

**Method** : `POST`

**Auth required** : NO

**Data constraints**

```json
{
    filename: Error.txt
    parent: /
    parentList: /
    currentID: 0e887d73-8967-4338-b5af-b043e2dc0463
    size: 4963
    file: (binary)
    
}
```
**Data example**

```json
{
    filename: Error.txt
    parent: /
    parentList: /
    currentID: 0e887d73-8967-4338-b5af-b043e2dc0463
    size: 4963
    file: (binary)

}
```

## Success Response

**Code** : `200 OK`

**Content example**

```json{
  "_id": "620d014a05e5d5460c87bc5f",
  "filename": "Error.txt",
  "uploadDate": "2022-02-16T13:51:06.801Z",
  "length": 4963,
  "metadata": {
    "owner": "61f7b576ac857c0c106c4112",
    "parent": "/",
    "parentList": "/",
    "hasThumbnail": false,
    "thumbnailID": "",
    "isVideo": false,
    "size": "4963",
    "IV": {
      "type": "Buffer",
      "data": [
        154,
        125,
        109,
        140,
        90,
        160,
        254,
        107,
        96,
        137,
        89,
        149,
        138,
        28,
        25,
        66
      ]
    },
    "s3ID": "84a38c28-32ed-4411-a482-3ac035b84d74"
  },
  "__v": 0
}
```
