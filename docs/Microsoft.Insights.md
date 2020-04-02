# Microsoft.Insights

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## actionGroups

![9.68%25](https://img.shields.io/badge/9.68%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-red)

### \$.properties.armRoleReceivers[*].useCommonAlertSchema

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Default* (false)    | No Swagger            |
| 2018-09-01  | Default* (false)    | No Swagger            |

### \$.properties.automationRunbookReceivers[*].useAadAuth

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Default* (false)    | No Swagger            |

### \$.properties.azureFunctionReceivers[*].httpTriggerUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.azureFunctionReceivers[*].useCommonAlertSchema

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Default* (false)    | No Swagger            |

### \$.properties.emailReceivers

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | Unknown               |

### \$.properties.emailReceivers[*].useCommonAlertSchema

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Default (false)     | No Swagger            |
| 2018-03-01  | Default (false)     | No Swagger            |
| 2018-09-01  | Default (false)     | No Swagger            |

### \$.properties.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Default* (true)     | Default (true)        |
| 2018-09-01  | Default* (true)     | Default (true)        |
| 2019-06-01  | Default* (true)     | Default (true)        |

### \$.properties.logicAppReceivers[*].callbackUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |
| 2019-03-01  | Unknown             | No Swagger            |

### \$.properties.logicAppReceivers[*].useCommonAlertSchema

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Default* (false)    | No Swagger            |
| 2018-03-01  | Default* (false)    | No Swagger            |

### \$.properties.webhookReceivers

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-09-01  | Unknown             | Unknown               |

### \$.properties.webhookReceivers[*].enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.webhookReceivers[*].useAadAuth

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Default (false)     | No Swagger            |
| 2018-03-01  | Default (false)     | No Swagger            |
| 2018-09-01  | Default (false)     | No Swagger            |
| 2019-03-01  | Default (false)     | No Swagger            |

### \$.properties.webhookReceivers[*].useCommonAlertSchema

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Default (false)     | No Swagger            |
| 2018-03-01  | Default (false)     | No Swagger            |
| 2019-03-01  | Default (false)     | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | Unknown               |
| 2018-03-01  | Unknown             | Unknown               |
| 2018-09-01  | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-09-01  | Unknown             | No Swagger            |
| 2019-03-01  | Unknown             | No Swagger            |

## activityLogAlerts

![20.00%25](https://img.shields.io/badge/20.00%25-%E2%98%85★%E2%98%86☆☆☆☆☆☆☆-orange)

### \$.properties.dependsOn

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Default* (true)     | Default (true)        |

### \$.properties.mode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

## alertrules

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.action

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.condition.timeAggregation

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

## autoScaleSettings

![5.56%25](https://img.shields.io/badge/5.56%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-red)

### \$.properties.apiVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.properties.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | Default (true)        |

### \$.properties.mode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | Unknown               |

### \$.properties.profiles

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | Unknown               |

### \$.properties.profiles[*].capacity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.properties.profiles[*].capacity.maximum

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.properties.profiles[*].rules[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.properties.profiles[*].rules[*].metricTrigger.dividePerInstance

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.properties.profiles[*].rules[*].metricTrigger.metricResourceLocation

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |

### \$.properties.profiles[*].rules[*].scaleAction.cooldown

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.properties.targetResourceLocation

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | Unknown               |

## components/currentBillingFeatures

!> No Swagger.

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | No Swagger            |

### \$.properties.CurrentBillingFeatures

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | No Swagger            |

### \$.properties.DataVolumeCap.ResetTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | No Swagger            |

### \$.properties.DataVolumeCap.StopSendNotificationWhenHitCap

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Default (false)     | No Swagger            |

### \$.properties.DataVolumeCap.StopSendNotificationWhenHitThreshold

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Default (false)     | No Swagger            |

### \$.properties.DataVolumeCap.WarningThreshold

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Default* (0)        | No Swagger            |

### \$.properties.EndTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | No Swagger            |

## components/proactiveDetectionConfigs

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-05-01-preview | Unknown             | Unknown               |

### \$.properties.ruleDefinitions

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-05-01-preview | Unknown             | Unknown               |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-05-01-preview | Unknown             | No Swagger            |

## components

![40.32%25](https://img.shields.io/badge/40.32%25-%E2%98%85★★★%E2%98%86☆☆☆☆☆-yellow)

### \$.kind

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01         | Unknown             | No Swagger            |
| 2014-08-01         | Unknown             | No Swagger            |
| 2015-05-01         | Unknown             | Unknown               |
| 2018-05-01-preview | Unknown             | Unknown               |

### \$.properties.ApplicationType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | No Swagger            |

### \$.properties.Application_Type

| API version | Detected noise type | Determined noise type                                    |
| ----------- | ------------------- | -------------------------------------------------------- |
| 2014-04-01  | Unknown             | No Swagger, Default ("web") (inheritted from 2015-05-01) |
| 2015-05-01  | Unknown             | Default ("web")                                          |

### \$.properties.Application_type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | Default ("web")       |

### \$.properties.DisableIpMasking

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Default* (true)     | Unknown               |

### \$.properties.Flow_Type

| API version        | Detected noise type | Determined noise type                                          |
| ------------------ | ------------------- | -------------------------------------------------------------- |
| 2014-04-01         | Unknown             | No Swagger, Default ("Bluefield") (inheritted from 2015-05-01) |
| 2014-08-01         | Unknown             | No Swagger, Default ("Bluefield") (inheritted from 2015-05-01) |
| 2015-05-01         | Unknown             | Default ("Bluefield")                                          |
| 2018-05-01-preview | Unknown             | Default ("Bluefield")                                          |

### \$.properties.ImmediatePurgeDataOn30Days

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-05-01-preview | Default* (true)     | Unknown               |

### \$.properties.Name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01         | Unknown             | No Swagger            |
| 2014-08-01         | Unknown             | No Swagger            |
| 2015-05-01         | Unknown             | No Swagger            |
| 2018-05-01-preview | Unknown             | No Swagger            |

### \$.properties.Request_Source

| API version        | Detected noise type | Determined noise type                                     |
| ------------------ | ------------------- | --------------------------------------------------------- |
| 2014-04-01         | Unknown             | No Swagger, Default ("rest") (inheritted from 2015-05-01) |
| 2014-08-01         | Unknown             | No Swagger, Default ("rest") (inheritted from 2015-05-01) |
| 2015-05-01         | Unknown             | Default ("rest")                                          |
| 2018-05-01-preview | Unknown             | Default ("rest")                                          |

### \$.properties.Retention

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01         | Unknown             | No Swagger            |
| 2015-05-01         | Unknown             | No Swagger            |
| 2018-05-01-preview | Unknown             | No Swagger            |

### \$.properties.RetentionInDays

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2014-04-01         | Unknown             | No Swagger, Default (90) (inheritted from 2015-05-01) |
| 2015-05-01         | Unknown             | Default (90)                                          |
| 2018-05-01-preview | Unknown             | Default (90)                                          |

### \$.properties.Ver

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01         | Unknown             | No Swagger            |
| 2014-08-01         | Unknown             | No Swagger            |
| 2015-05-01         | Unknown             | No Swagger            |
| 2018-05-01-preview | Unknown             | No Swagger            |

### \$.properties.amlApiDataFetcherId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |

### \$.properties.applicationId

| API version | Detected noise type | Determined noise type                              |
| ----------- | ------------------- | -------------------------------------------------- |
| 2014-04-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-05-01) |
| 2015-05-01  | Unknown             | Read-only                                          |

### \$.properties.application_Type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | Default ("web")       |

### \$.properties.clientPortalApiId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |

### \$.properties.dccmdFileSenderId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |

### \$.properties.httpsOnly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |

### \$.properties.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | No Swagger            |

### \$.properties.locdCollectorId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |

### \$.properties.locdWebApiId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |

### \$.properties.mode

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01         | Unknown             | No Swagger            |
| 2018-05-01-preview | Unknown             | No Swagger            |

### \$.properties.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | No Swagger            |

### \$.properties.publicNetworkAccessForIngestion

| API version        | Detected noise type | Determined noise type                                                |
| ------------------ | ------------------- | -------------------------------------------------------------------- |
| 2014-04-01         | Unknown             | No Swagger, Default ("Enabled") (inheritted from 2018-05-01-preview) |
| 2014-08-01         | Unknown             | No Swagger, Default ("Enabled") (inheritted from 2018-05-01-preview) |
| 2015-05-01         | Unknown             | No Swagger, Default ("Enabled") (inheritted from 2018-05-01-preview) |
| 2018-05-01-preview | Unknown             | Default ("Enabled")                                                  |

### \$.properties.publicNetworkAccessForQuery

| API version        | Detected noise type | Determined noise type                                                |
| ------------------ | ------------------- | -------------------------------------------------------------------- |
| 2014-04-01         | Unknown             | No Swagger, Default ("Enabled") (inheritted from 2018-05-01-preview) |
| 2014-08-01         | Unknown             | No Swagger, Default ("Enabled") (inheritted from 2018-05-01-preview) |
| 2015-05-01         | Unknown             | No Swagger, Default ("Enabled") (inheritted from 2018-05-01-preview) |
| 2018-05-01-preview | Unknown             | Default ("Enabled")                                                  |

### \$.properties.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01         | Unknown             | No Swagger            |
| 2014-08-01         | Unknown             | No Swagger            |
| 2015-05-01         | Unknown             | Unknown               |
| 2018-05-01-preview | Unknown             | Unknown               |

### \$.tags.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01         | Unknown             | No Swagger            |
| 2014-08-01         | Unknown             | No Swagger            |
| 2015-05-01         | Unknown             | No Swagger            |
| 2018-05-01-preview | Unknown             | No Swagger            |

## diagnosticsettings

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-07-01         | Unknown             | Unknown               |
| 2016-09-01         | Unknown             | Unknown               |
| 2017-05-01-preview | Unknown             | Unknown               |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | Unknown               |

### \$.properties.eventHubAuthorizationRuleId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-01-preview | Unknown             | Unknown               |

### \$.properties.logAnalyticsDestinationType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-07-01         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-05-01-preview | Unknown             | Unknown               |

### \$.properties.logging.retention

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-07-01  | Unknown             | No Swagger            |

### \$.properties.logs

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-07-01         | Unknown             | Unknown               |
| 2016-09-01         | Unknown             | Unknown               |
| 2017-05-01-preview | Unknown             | Unknown               |

### \$.properties.logs[*]

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-07-01         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.logs[*].enabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.logs[*].retentionPolicy

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-07-01         | Unknown             | No Swagger            |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.logs[*].retentionPolicy.condition

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.logs[*].retentionPolicy.days

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-09-01         | Default* (0)        | No Swagger            |
| 2017-05-01-preview | Default* (0)        | No Swagger            |

### \$.properties.logs[*].retentionPolicy.enabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.metrics

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-07-01         | Unknown             | Unknown               |
| 2016-09-01         | Unknown             | Unknown               |
| 2017-05-01-preview | Unknown             | Unknown               |

### \$.properties.metrics.aggregations[*].retention

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-07-01  | Unknown             | No Swagger            |

### \$.properties.metrics[*]

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-07-01         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.metrics[*].category

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-07-01         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.metrics[*].categoty

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.metrics[*].enabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.metrics[*].retentionPolicy

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-07-01         | Unknown             | No Swagger            |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.metrics[*].retentionPolicy.day

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.metrics[*].retentionPolicy.days

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-01-preview | Default* (0)        | No Swagger            |

### \$.properties.metrics[*].retentionPolicy.enabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-07-01         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.metrics[*].timeGrain

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-07-01         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-07-01         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.status

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | No Swagger            |

### \$.properties.storageAccountId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-07-01         | Unknown             | Unknown               |
| 2017-05-01-preview | Unknown             | Unknown               |

### \$.properties.storageAccountName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | No Swagger            |

### \$.properties.workspaceId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-01-preview | Unknown             | Unknown               |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-07-01         | Unknown             | Unknown               |
| 2016-09-01         | Unknown             | Unknown               |
| 2017-05-01-preview | Unknown             | No Swagger            |

## metricAlerts

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.Enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | Unknown               |

### \$.properties.EvaluationFrequency

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | Unknown               |

### \$.properties.actions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | Unknown               |

### \$.properties.actions[*].aznsAction

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.actions[*].email_subject

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.criteria.AllOf

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.criteria.allOf

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.criteria.allOf[*].alertSensitivity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.criteria.allOf[*].criterionType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.criteria.allOf[*].failingPeriods

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.criteria.allOf[*].metricNamespace

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.dependsOn

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | Unknown               |

### \$.properties.evaluationFrequency

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | Unknown               |

### \$.properties.isEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.isMigrated

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Default* (true)     | No Swagger            |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.targetResourceRegion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | Unknown               |

### \$.properties.targetResourceType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | Unknown               |

### \$.properties.templateSpecificParameters

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.templateType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.windowSize

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | Unknown               |

### \$.properties.windowsize

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

## scheduledqueryrules

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.action.actionGroup

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-09-01-preview | Unknown             | No Swagger            |

### \$.properties.action.status

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-09-01-preview | Unknown             | No Swagger            |
| 2018-04-16         | Unknown             | No Swagger            |

### \$.properties.action.trigger.consecutiveBreach

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-09-01-preview | Unknown             | No Swagger            |
| 2018-04-16         | Unknown             | No Swagger            |

### \$.properties.action.trigger.metricTrigger.metricTriggerType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-16  | Unknown             | No Swagger            |

### \$.properties.action.trigger.thresholdOperator

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-16  | Unknown             | No Swagger            |

### \$.properties.apiVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-16  | Unknown             | No Swagger            |

### \$.properties.displayName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-09-01-preview | Unknown             | No Swagger            |
| 2018-04-16         | Unknown             | No Swagger            |

### \$.properties.mode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-16  | Unknown             | No Swagger            |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-16  | Unknown             | No Swagger            |

### \$.properties.skuType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-09-01-preview | Unknown             | No Swagger            |
| 2018-04-16         | Unknown             | No Swagger            |

### \$.properties.source.queryType

| API version | Detected noise type      | Determined noise type |
| ----------- | ------------------------ | --------------------- |
| 2018-04-16  | Default* ("ResultCount") | Unknown               |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-09-01-preview | Unknown             | No Swagger            |
| 2018-04-16         | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-16  | Unknown             | No Swagger            |

## webtests

![25.00%25](https://img.shields.io/badge/25.00%25-%E2%98%85★★%E2%98%86☆☆☆☆☆☆-orange)

### \$.properties.Application_Type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |

### \$.properties.Configuration.WebTest

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-05-01  | Unknown             | Unknown               |

### \$.properties.Description

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | Unknown               |

### \$.properties.Enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-05-01  | Unknown             | Unknown               |

### \$.properties.Frequency

| API version | Detected noise type | Determined noise type                                  |
| ----------- | ------------------- | ------------------------------------------------------ |
| 2014-04-01  | Unknown             | No Swagger, Default (300) (inheritted from 2015-05-01) |
| 2015-05-01  | Unknown             | Default (300)                                          |

### \$.properties.Kind

| API version | Detected noise type    | Determined noise type |
| ----------- | ---------------------- | --------------------- |
| 2015-05-01  | Default* ("multistep") | Default ("ping")      |

### \$.properties.Locations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | Unknown               |

### \$.properties.Name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | Unknown               |

### \$.properties.SyntheticMonitorId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-05-01  | Unknown             | Unknown               |

### \$.properties.description

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | Unknown               |

### \$.properties.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | Unknown               |

### \$.properties.failedLocationCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | No Swagger            |

### \$.properties.frequency

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | Default (300)         |

### \$.properties.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | Default ("ping")      |

### \$.properties.locations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | Unknown               |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | Unknown               |

### \$.properties.syntheticMonitorId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | Unknown               |

### \$.properties.timeout

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | Default (30)          |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-05-01  | Unknown             | No Swagger            |

## workbooks

!> No Swagger.

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.sourceId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-17-preview | Unknown             | No Swagger            |

### \$.properties.timeModified

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-17-preview | Unknown             | No Swagger            |

### \$.properties.userId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-17-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-17-preview | Unknown             | No Swagger            |

### \$.tags.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-17-preview | Unknown             | No Swagger            |
