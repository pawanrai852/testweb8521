
# Proxy Locations

We will help you to Find the Locations where the Proxy is used inside this Branch

Note: Proxy is only for Devlopment Enviroment

## 1. Proxy URL

```http
  http://OutboundProxyLoadBalancer-2cd9c26cbebfd325.elb.us-east-1.amazonaws.com:3128
```

## config.json uses Proxy

### 1.1 Location of Config.json

```http
  sh-apis\NodeJS_API\src\config\config.json
```
#### Deatils

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `Query`   | `Athena` | **Required**. For Query Athena DataBase |
| `Email`   | `SMTP`   | **Required**. For Sending SMTP Emails   |

## channel-config.controller.ts used Proxy

### 1.2 Location of channel-config.controller.ts

```http
  sh-apis\NodeJS_API\src\controllers\api\channel\channel-config.controller.ts
```
#### Deatils

| Parameter | Type     | Description                  |
| :-------- | :------- | :-------------------------   |
| `channel` | `Set Config` | **Required**. For API to work |

# Secret Manager Location

Used to retrive the secrets from AWS Secret Manager
### 2 Location of secret-manager.ts

```http
  sh-apis\NodeJS_API\src\secret-manager.ts
```

## secret-manager.ts used

### 2.1 app.ts used Secret Manager

```http
  sh-apis\NodeJS_API\src\app.ts
```

### 2.2 secretManagerService.ts used Secret Manager

```http
  sh-apis\NodeJS_API\src\services\secretManagerService.ts
```

# Athena Location 

For use of athena queries

### 3. Location of athena Helper

```http
  sh-apis\NodeJS_API\src\util\athenaHelper.ts
```


## Athena Helper used

### Files inside Which Athena Helper is used

```http
  3.1 sh-apis\NodeJS_API\src\controllers\api\report\account-journey\account-journey.controller.ts
  3.2 sh-apis\NodeJS_API\src\controllers\api\report\campaign-journey\campaign-journey-report.controller.ts
  3.3 sh-apis\NodeJS_API\src\controllers\api\report\competittor-landscape\competittor.controller.ts
  3.4 sh-apis\NodeJS_API\src\controllers\api\report\executive-summary\executivesummary.controller.ts
  3.5 sh-apis\NodeJS_API\src\controllers\api\report\geo\get-geo.controller.ts
  3.6 sh-apis\NodeJS_API\src\controllers\api\report\operational-insight\operation.controller.ts
  3.7 sh-apis\NodeJS_API\src\controllers\api\report\operational-insight\operation.controller.ts
  3.8 sh-apis\NodeJS_API\src\controllers\api\report\orders\orders.controllers.ts
  3.9 sh-apis\NodeJS_API\src\controllers\api\report\organic-search\organic-search.controller.ts
  3.10 sh-apis\NodeJS_API\src\controllers\api\report\paid-search\paid-search.controller.ts
  3.11 sh-apis\NodeJS_API\src\controllers\api\report\paid-shopping\paid-shopping.controller.ts
  3.12 sh-apis\NodeJS_API\src\controllers\api\report\paid-social\paid-social.controller.ts
  3.13 sh-apis\NodeJS_API\src\controllers\api\report\traffic\get-site-traffic.controller.ts
  3.14 sh-apis\NodeJS_API\src\controllers\api\report\video\video.controller.ts
  3.15 sh-apis\NodeJS_API\src\services\affiliatesService.ts
  3.16 sh-apis\NodeJS_API\src\services\anomaliesReportService.ts
  3.17 sh-apis\NodeJS_API\src\services\attributionReportService.ts
  3.18 sh-apis\NodeJS_API\src\services\audienceReportService.ts
  3.19 sh-apis\NodeJS_API\src\services\campaignJourneyReportService.ts
  3.20 sh-apis\NodeJS_API\src\services\campaignManagerReportService.ts
  3.21 sh-apis\NodeJS_API\src\services\dashboardService.ts
  3.22 sh-apis\NodeJS_API\src\services\organicService.ts
  3.23 sh-apis\NodeJS_API\src\services\paidDisplayService.ts
  3.24 sh-apis\NodeJS_API\src\services\sentimentsAnalysisReportService.ts
  3.25 sh-apis\NodeJS_API\src\services\sentimentsReportService.ts
  3.26 sh-apis\NodeJS_API\src\services\settingServices.ts
  3.27 sh-apis\NodeJS_API\src\services\spendService.ts
  3.28 sh-apis\NodeJS_API\src\services\planning\allocationService.ts
  3.29 sh-apis\NodeJS_API\src\services\planning\planningService.ts

```






