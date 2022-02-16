# Create
Used to collect token for registered user.
**URL** : `//user-service/create`

**Method** : `POST`

**Auth required** : NO

**Data constraints**

```json
{
    email: "zaid@abc.com"
    password: "system"
}
```
**Data example**

```json
{
    email: "zaid@abc.com"
    password: "system"
}
```

## Success Response

**Code** : `201 OK`

**Content example**

```json
{"user":{"_id":"620d2e0b05e5d5460c87bc60","email":"zaid@abc.com","emailVerified":true,"createdAt":"2022-02-16T17:02:03.707Z","updatedAt":"2022-02-16T17:02:05.382Z","__v":0,"emailToken":"69f4a0ecb2f16064da7df1ee1bec627cc8e018d0bf2d7038e3e7e80a42f71701ffb7c2b3ae8e48761095029f89bc2d26125947ab172106087973ad1e84694efe745dd323d357c78cc40fcb02f51ab21bb95a5b3764aa37b6d3aa397bb0a6a6475277766ace5baf55e3d08140a40d07cf59436e9b6c9f0bf2d0d462490aa58f708224d9f73a05f1eb4d5ff43ca652fe689739f41def52ff441f76c854e1a0357b5e8df5ff73a08f4631692c9993d07685c8dfa3187bcff109c78710ecb6761fd0ae3b351ee5862165c886ec67b9f3e28f7c30c31d2b1316e0b95ec84e9e3d89e49b7c602feb79d4f0d0544b44b61574385992113ab82c500a361265851650dfa1e9039f4fb24d9e6954ca162a0d334e909123bd263a26568dce4261a8c6c2a875913543792cb6cbb26e9bdc77d4f6541d"}}
```
