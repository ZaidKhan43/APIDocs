# Login
Used to collect token for registered user.
**URL** : `/user-service/login`

**Method** : `POST`

**Auth required** : YES

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
    "email": "zaid@vcollab.com",
    "password": "system"
}
```

## Success Response

**Code** : `200 OK`

**Content example**

```json
{"user":{"storageData":{"storageSize":37682,"storageLimit":0},"_id":"61f7b576ac857c0c106c4112","email":"zaid@gmail.com","emailVerified":true,"createdAt":"2022-01-31T10:09:58.894Z","updatedAt":"2022-02-16T07:08:07.864Z","__v":0,"emailToken":"9000a4ef1f7188e1571d9c9e6df86062e4f92e3d1dec38baf981c3e9e8434ed6433b7310316cc03a486469ef20d04ab211e6e14cf6cf3c83d2e5a73788202ed30e7916da9a27a5db956d10d3c8a9a8a3bfe65a0bf2847663bd026dfc339a41213186f5f6fda861e885144581a6817333e33b7f0c8c451778647744faa75dcf352ce7ca89ca761d5f4691c35cb8f911bd1da1da9594c33c9aa81d5cac6b2a35fa051f3a3897acf508477efcf4d88682d1db044bd9f9d8b8c2612257b4de0542b7256a78f4de5eea44f415e5116371819b3f754f864bba1129c4aa8a42e2d5d279ef6b62575b31d7eacf350c60234b954116532fdbf533e7118b97d199955f9d2c7112f3136b334ea2e149aba4a1ab8c556a4446f7f193803de0c45a96dc458ec5c7c8468568554560e1999ad320470ed3"}}
```
