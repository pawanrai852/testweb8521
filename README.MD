
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

### 3.1 account-journey.controller.ts used Athena Helper

```http
  sh-apis\NodeJS_API\src\controllers\api\report\account-journey\account-journey.controller.ts
```

### 3.2 campaign-journey-report.controller.ts used Athena Helper

```http
  sh-apis\NodeJS_API\src\controllers\api\report\campaign-journey\campaign-journey-report.controller.ts
```

### 3.3 competittor.controller.ts used Athena Helper

```http
  sh-apis\NodeJS_API\src\controllers\api\report\competittor-landscape\competittor.controller.ts
```

### 3.4 executivesummary.controller.ts used Athena Helper

```http
  sh-apis\NodeJS_API\src\controllers\api\report\executive-summary\executivesummary.controller.ts
```

### 3.5 get-geo.controller.ts used Athena Helper

```http
  sh-apis\NodeJS_API\src\controllers\api\report\geo\get-geo.controller.ts
```

### 3.6 operation.controller.ts used Athena Helper

```http
  sh-apis\NodeJS_API\src\controllers\api\report\operational-insight\operation.controller.ts
```

### 3.7 orders.controllers.ts used Athena Helper

```http
  D:\sh-apis\NodeJS_API\src\controllers\api\report\orders\orders.controllers.ts
```

### 3.8 organic-search.controller.ts used Athena Helper

```http
  sh-apis\NodeJS_API\src\controllers\api\report\organic-search\organic-search.controller.ts
```

### 3.9 paid-search.controller.ts used Athena Helper

```http
  sh-apis\NodeJS_API\src\controllers\api\report\paid-search\paid-search.controller.ts
```

### 3.10 paid-shopping.controller.ts used Athena Helper

```http
  sh-apis\NodeJS_API\src\controllers\api\report\paid-shopping\paid-shopping.controller.ts
```

### 3.11 paid-social.controller.ts used Athena Helper

```http
  sh-apis\NodeJS_API\src\controllers\api\report\paid-social\paid-social.controller.ts
```

### 3.12 get-site-traffic.controller.ts used Athena Helper

```http
  sh-apis\NodeJS_API\src\controllers\api\report\traffic\get-site-traffic.controller.ts
```

### 3.13 video.controller.ts used Athena Helper

```http
  sh-apis\NodeJS_API\src\controllers\api\report\video\video.controller.ts
```

### 3.14 affiliatesService.ts used Athena Helper

```http
  sh-apis\NodeJS_API\src\services\affiliatesService.ts
```

### 3.15 anomaliesReportService.ts used Athena Helper

```http
  sh-apis\NodeJS_API\src\services\anomaliesReportService.ts
```

### 3.16 attributionReportService.ts used Athena Helper

```http
  sh-apis\NodeJS_API\src\services\attributionReportService.ts
```

### 3.17 audienceReportService.ts used Athena Helper

```http
  D:\sh-apis\NodeJS_API\src\services\audienceReportService.ts
```

### 3.18 campaignJourneyReportService.ts used Athena Helper

```http
  sh-apis\NodeJS_API\src\services\campaignJourneyReportService.ts
```

### 3.19 campaignManagerReportService.ts used Athena Helper

```http
  sh-apis\NodeJS_API\src\services\campaignManagerReportService.ts
```

### 3.20 dashboardService.ts used Athena Helper

```http
  sh-apis\NodeJS_API\src\services\dashboardService.ts
```

### 3.21 organicService.ts used Athena Helper

```http
  sh-apis\NodeJS_API\src\services\organicService.ts
```

### 3.22 paidDisplayService.ts used Athena Helper

```http
  sh-apis\NodeJS_API\src\services\paidDisplayService.ts
```

### 3.23 sentimentsAnalysisReportService.ts used Athena Helper

```http
  sh-apis\NodeJS_API\src\services\sentimentsAnalysisReportService.ts
```

### 3.24 sentimentsReportService.ts used Athena Helper

```http
  sh-apis\NodeJS_API\src\services\sentimentsReportService.ts
```

### 3.25 settingServices.ts used Athena Helper

```http
  sh-apis\NodeJS_API\src\services\settingServices.ts
```

### 3.26 spendService.ts used Athena Helper

```http
  sh-apis\NodeJS_API\src\services\spendService.ts
```

### 3.27 allocationService.ts used Athena Helper

```http
  sh-apis\NodeJS_API\src\services\planning\allocationService.ts
```

### 3.28 planningService.ts used Athena Helper

```http
  sh-apis\NodeJS_API\src\services\planning\planningService.ts
```
