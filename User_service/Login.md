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
	
    "user": {
    "storageData": {
    "storageSize": 42645,
    "storageLimit": 0
    },
    "_id": "61f7b576ac857c0c106c4112",
    "email": "zaid@gmail.com",
    "emailVerified": true,
    "createdAt": "2022-01-31T10:09:58.894Z",
    "updatedAt": "2022-02-17T04:54:50.889Z",
    "__v": 0,
    "emailToken": "9000a4ef1f7188e1571d9c9e6df86062e4f92e3d1dec38baf981c3e9e8434ed6433b7310316cc03a486469ef20d04ab211e6e14cf6cf3c83d2e5a73788202ed30e7916da9a27a5db956d10d3c8a9a8a3bfe65a0bf2847663bd026dfc339a41213186f5f6fda861e885144581a6817333e33b7f0c8c451778647744faa75dcf352ce7ca89ca761d5f4691c35cb8f911bd1da1da9594c33c9aa81d5cac6b2a35fa051f3a3897acf508477efcf4d88682d1db044bd9f9d8b8c2612257b4de0542b7256a78f4de5eea44f415e5116371819b3f754f864bba1129c4aa8a42e2d5d279ef6b62575b31d7eacf350c60234b954116532fdbf533e7118b97d199955f9d2c7112f3136b334ea2e149aba4a1ab8c556a4446f7f193803de0c45a96dc458ec5c7c8468568554560e1999ad320470ed3",
    "passwordResetToken": "669d814ecac45f481ccba99d01bef6358fe7a8c72f37d79717d9221a5aea4c566ce679076621535d734fa86d3e03faf66fba23eae358defe1d220703cb4a42ea822580b7571c4e3af71459ceeabb0e8df735e14df8239d1a89380bd31d0001fb0a61c692bfb57aeff4c1db8abd1e36262ce7d85074d2a56e3ae1167381ad93d3960087d205d0f8df8ff10f668b953e154026f20529061a2ed2a3401710cf15994349be0df64985b4910e88d876ed4f7301697ec6eb218870590b57e4209d3270d6adede44d985cb3552a28b111b44a8f0468b0103c315c150c8f56b996d1859c0b40b023f5e1f6c4326cabc35f23a8c64c49198457112d3f91b5c8446510a76a504c8ac283b606c963a92c322c826eda6c0c238b5ed543c35029421879c0f642da35f61cd6bdd3de68124241dcabdf54"
  }
	
```
