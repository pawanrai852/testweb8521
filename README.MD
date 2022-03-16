
# Proxy Locations

We will help you to Find the Locations where the Proxy is used inside this Branch

Note: Proxy is only for Devlopment Enviroment

## Proxy URL

```http
  http://OutboundProxyLoadBalancer-2cd9c26cbebfd325.elb.us-east-1.amazonaws.com:3128
```

## config.json uses Proxy

### 1. Location of Config.json

```http
  sh-apis\NodeJS_API\src\config\config.json
```
#### Deatils

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `Query`   | `Athena` | **Required**. For Query Athena DataBase |
| `Email`   | `SMTP`   | **Required**. For Sending SMTP Emails   |

## channel-config.controller.ts used Proxy

### 2. Location of channel-config.controller.ts

```http
  sh-apis\NodeJS_API\src\controllers\api\channel\channel-config.controller.ts
```
#### Deatils

| Parameter | Type     | Description                  |
| :-------- | :------- | :-------------------------   |
| `channel` | `Set Config` | **Required**. For API to work |

# Secret Manager Location

Used to retrive the secrets from AWS Secret Manager
### 1. Location of secret-manager.ts

```http
  sh-apis\NodeJS_API\src\secret-manager.ts
```

### 2. How to Use

``` http
  const retrieveSecrets = require("secret-manager.ts");
```


# Athena Location 

Used to use athena

### 1. Location of athena Helper

```http
  import AthenaHelper from '../../../../util/athenaHelper';
```
