# Microsoft.Insights

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## actionGroups

![cleanliness](https://img.shields.io/badge/cleanliness-31.58%25%20(18%20/%2057)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2039)-red)

### \$.properties.actionGroupName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | No Swagger            |

### \$.properties.armRoleReceivers[*].useCommonAlertSchema

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Default* (false)    | No Swagger            |
| 2018-09-01  | Default* (false)    | No Swagger            |
| 2019-06-01  | Default* (false)    | No Swagger            |

### \$.properties.automationRunbookReceivers[*].useAadAuth

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Default* (false)    | No Swagger            |
| 2019-06-01  | Default* (false)    | No Swagger            |

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
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.emailReceivers[*].useCommonAlertSchema

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Default (false)     | No Swagger            |
| 2018-03-01  | Default (false)     | No Swagger            |
| 2018-09-01  | Default (false)     | No Swagger            |

### \$.properties.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Default* (true)     | No Swagger            |
| 2018-09-01  | Default* (true)     | No Swagger            |
| 2019-06-01  | Default* (true)     | No Swagger            |

### \$.properties.logicAppReceivers[*].callbackUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |
| 2018-03-01  | Unknown             | No Swagger            |
| 2019-03-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.logicAppReceivers[*].useCommonAlertSchema

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Default* (false)    | No Swagger            |
| 2018-03-01  | Default* (false)    | No Swagger            |

### \$.properties.webhookReceivers

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-09-01  | Unknown             | No Swagger            |

### \$.properties.webhookReceivers[*].enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.webhookReceivers[*].serviceUri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | No Swagger            |

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
| 2017-04-01  | Unknown             | No Swagger            |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-09-01  | Unknown             | No Swagger            |
| 2019-03-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-09-01  | Unknown             | No Swagger            |
| 2019-03-01  | Unknown             | No Swagger            |

## activityLogAlerts

![cleanliness](https://img.shields.io/badge/cleanliness-50.00%25%20(6%20/%2012)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%206)-red)

### \$.properties.actions.actionGroups[*].enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.dependsOn

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Default* (true)     | No Swagger            |

### \$.properties.mode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

## alertrules

![cleanliness](https://img.shields.io/badge/cleanliness-83.33%25%20(10%20/%2012)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties.action

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.condition.timeAggregation

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

## autoScaleSettings

![cleanliness](https://img.shields.io/badge/cleanliness-36.96%25%20(17%20/%2046)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2029)-red)

### \$.properties.apiVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.properties.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.properties.httpsOnly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |

### \$.properties.mode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.properties.profiles

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.properties.profiles[*].capacity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.properties.profiles[*].capacity.maximum

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.properties.profiles[*].capacity.minimum

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.properties.profiles[*].capacity.scaleType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.properties.profiles[*].notifications

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
| 2015-04-01  | Unknown             | No Swagger            |

### \$.properties.profiles[*].rules[*].metricTrigger.metricResourceUri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |

### \$.properties.profiles[*].rules[*].scaleAction.cooldown

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |

### \$.properties.targetResourceLocation

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.properties.targetResourceUri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |

## components/currentBillingFeatures

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2012)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | No Swagger            |

### \$.properties.CurrentBillingFeatures

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | No Swagger            |

### \$.properties.CurrentBillingFeatures[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | No Swagger            |

### \$.properties.DataVolumeCap.MaxHistoryCap

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01         | Default* (1000)     | No Swagger            |
| 2018-05-01-preview | Default* (1000)     | No Swagger            |

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

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01         | Unknown             | No Swagger            |
| 2018-05-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | No Swagger            |

## components/proactiveDetectionConfigs

![cleanliness](https://img.shields.io/badge/cleanliness-86.67%25%20(13%20/%2015)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-05-01-preview | Unknown             | No Swagger            |

### \$.properties.ruleDefinitions

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-05-01-preview | Unknown             | No Swagger            |

## components

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-brightgreen) ![progress](https://img.shields.io/badge/progress-100.00%25%20(55%20/%2055)-brightgreen)

### \$.kind

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2014-04-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-05-01) |
| 2014-08-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-05-01) |
| 2015-05-01         | Unknown             | Put-as-patch                                          |
| 2018-05-01-preview | Unknown             | Put-as-patch                                          |

### \$.properties.Application_Id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | Put-as-patch          |

### \$.properties.Application_Type

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-05-01) |
| 2015-05-01  | Unknown             | Put-as-patch                                          |

### \$.properties.Application_type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | Put-as-patch          |

### \$.properties.CustomMetricsOptedInType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | Put-as-patch          |

### \$.properties.DisableIpMasking

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Default* (true)     | Put-as-patch          |

### \$.properties.Flow_Type

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2014-04-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-05-01) |
| 2014-08-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-05-01) |
| 2015-05-01         | Unknown             | Put-as-patch                                          |
| 2018-05-01-preview | Unknown             | Put-as-patch                                          |

### \$.properties.ImmediatePurgeDataOn30Days

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-05-01-preview | Default* (true)     | Put-as-patch          |

### \$.properties.IngestionMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | Put-as-patch          |

### \$.properties.Name

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2014-04-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-05-01) |
| 2014-08-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-05-01) |
| 2015-05-01         | Unknown             | Put-as-patch                                          |
| 2018-05-01-preview | Unknown             | Put-as-patch                                          |

### \$.properties.Request_Source

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2014-04-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-05-01) |
| 2014-08-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-05-01) |
| 2015-05-01         | Unknown             | Put-as-patch                                          |
| 2018-05-01-preview | Unknown             | Put-as-patch                                          |

### \$.properties.Retention

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2014-04-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-05-01) |
| 2015-05-01         | Unknown             | Put-as-patch                                          |
| 2018-05-01-preview | Unknown             | Put-as-patch                                          |

### \$.properties.RetentionInDays

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2014-04-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-05-01) |
| 2015-05-01         | Unknown             | Put-as-patch                                          |
| 2018-05-01-preview | Unknown             | Put-as-patch                                          |

### \$.properties.SamplingPercentage

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-05-01) |
| 2015-05-01  | Unknown             | Put-as-patch                                          |

### \$.properties.Ver

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2014-04-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-05-01) |
| 2014-08-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-05-01) |
| 2015-05-01         | Unknown             | Put-as-patch                                          |
| 2018-05-01-preview | Unknown             | Put-as-patch                                          |

### \$.properties.application_Type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | Put-as-patch          |

### \$.properties.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | Put-as-patch          |

### \$.properties.publicNetworkAccessForIngestion

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2014-04-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-05-01) |
| 2014-08-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-05-01) |
| 2015-05-01         | Unknown             | Put-as-patch                                          |
| 2018-05-01-preview | Unknown             | Put-as-patch                                          |

### \$.properties.publicNetworkAccessForQuery

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2014-04-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-05-01) |
| 2014-08-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-05-01) |
| 2015-05-01         | Unknown             | Put-as-patch                                          |
| 2018-05-01-preview | Unknown             | Put-as-patch                                          |

### \$.properties.retentionDays

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-05-01-preview | Unknown             | Put-as-patch          |

### \$.tags

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2014-04-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-05-01) |
| 2014-08-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-05-01) |
| 2015-05-01         | Unknown             | Put-as-patch                                          |
| 2018-05-01-preview | Unknown             | Put-as-patch                                          |

### \$.tags.*

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2014-04-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-05-01) |
| 2014-08-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-05-01) |
| 2015-05-01         | Unknown             | Put-as-patch                                          |
| 2018-05-01-preview | Unknown             | Put-as-patch                                          |

## diagnosticsettings

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2066)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-07-01         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | No Swagger            |

### \$.properties.eventHubAuthorizationRuleId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.eventHubId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.logAnalyticsDestinationType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.logging.retention

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-07-01  | Unknown             | No Swagger            |

### \$.properties.logs

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-07-01         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-05-01-preview | Unknown             | No Swagger            |

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

### \$.properties.logs[*].omsRetentionPolicyInDaysPolicy

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.logs[*].retentionInDays

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.logs[*].retentionPolicy

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.logs[*].retentionPolicy.condition

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.logs[*].retentionPolicy.day

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.logs[*].retentionPolicy.days

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-09-01         | Default (0)         | No Swagger            |
| 2017-05-01-preview | Default (0)         | No Swagger            |

### \$.properties.logs[*].retentionPolicy.enabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-07-01         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.metrics

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-07-01         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-05-01-preview | Unknown             | No Swagger            |

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

### \$.properties.metrics[*].omsRetentionPolicyInDaysPolicy

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.metrics[*].retentionPolicy

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-07-01         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.metrics[*].retentionPolicy.day

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.metrics[*].retentionPolicy.days

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-07-01         | Default* (0)        | No Swagger            |
| 2016-09-01         | Default* (0)        | No Swagger            |
| 2017-05-01-preview | Default* (0)        | No Swagger            |

### \$.properties.metrics[*].retentionPolicy.enabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-07-01         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.metrics[*].retentionPolicy.retentionInDays

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-07-01  | Unknown             | No Swagger            |

### \$.properties.metrics[*].timeGrain

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.metrics[*].timegrain

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.metrics[*].workspaceId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.mode

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.properties.networkAcls

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | No Swagger            |

### \$.properties.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | No Swagger            |

### \$.properties.status

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | No Swagger            |

### \$.properties.storageAccountId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-07-01  | Unknown             | No Swagger            |

### \$.properties.storageAccountName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | No Swagger            |

### \$.properties.workspaceId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-05-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-07-01         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-05-01-preview | Unknown             | No Swagger            |

## metricAlerts

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2034)-red)

### \$.properties.Enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.EvaluationFrequency

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.actions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.actions[*].actionGroupId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.actions[*].aznsAction

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.actions[*].emailSubject

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.actions[*].email_subject

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.actions[*].enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.actions[*].sendToServiceOwners

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

### \$.properties.criteria.allOf[*].skipMetricValidation

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
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.evaluationFrequency

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.groupShortName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.isEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.isMigrated

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Default (true)      | No Swagger            |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.scopes[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.severity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Default* (0)        | No Swagger            |

### \$.properties.targetResourceRegion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.targetResourceType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.templateSpecificParameters

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.templateSpecificParameters.direction

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
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.windowsize

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

## scheduledqueryrules

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2023)-red)

### \$.properties.action.actionGroup

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-09-01-preview | Unknown             | No Swagger            |
| 2018-04-16         | Unknown             | No Swagger            |

### \$.properties.action.aznsAction

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-16  | Unknown             | No Swagger            |

### \$.properties.action.status

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-09-01-preview | Unknown             | No Swagger            |

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

### \$.properties.etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-16  | Unknown             | No Swagger            |

### \$.properties.mode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-16  | Unknown             | No Swagger            |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-16  | Unknown             | No Swagger            |

### \$.properties.severity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-16  | Unknown             | No Swagger            |

### \$.properties.skuType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-09-01-preview | Unknown             | No Swagger            |

### \$.properties.source.dataSourceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-16  | Unknown             | No Swagger            |

### \$.properties.source.queryType

| API version | Detected noise type     | Determined noise type |
| ----------- | ----------------------- | --------------------- |
| 2018-04-16  | Default ("ResultCount") | No Swagger            |

### \$.properties.source.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-16  | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-09-01-preview | Unknown             | No Swagger            |
| 2018-04-16         | Unknown             | No Swagger            |

### \$.tags.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-09-01-preview | Unknown             | No Swagger            |
| 2018-04-16         | Unknown             | No Swagger            |

## webtests

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2027)-red)

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
| 2015-05-01  | Unknown             | No Swagger            |

### \$.properties.Enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-05-01  | Unknown             | No Swagger            |

### \$.properties.Frequency

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-05-01  | Unknown             | No Swagger            |

### \$.properties.Kind

| API version | Detected noise type    | Determined noise type |
| ----------- | ---------------------- | --------------------- |
| 2015-05-01  | Default* ("multistep") | No Swagger            |

### \$.properties.Locations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | No Swagger            |

### \$.properties.Name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | No Swagger            |

### \$.properties.SyntheticMonitorId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01         | Unknown             | No Swagger            |
| 2015-05-01         | Unknown             | No Swagger            |
| 2018-05-01-preview | Unknown             | No Swagger            |

### \$.properties.description

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | No Swagger            |

### \$.properties.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | No Swagger            |

### \$.properties.etag

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-05-01-preview | Unknown             | No Swagger            |

### \$.properties.failedLocationCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | No Swagger            |

### \$.properties.frequency

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | No Swagger            |

### \$.properties.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | No Swagger            |

### \$.properties.locations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | No Swagger            |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | No Swagger            |

### \$.properties.syntheticMonitorId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | No Swagger            |

### \$.properties.timeout

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-05-01  | Unknown             | No Swagger            |

### \$.tags.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01         | Unknown             | No Swagger            |
| 2015-05-01         | Unknown             | No Swagger            |
| 2018-05-01-preview | Unknown             | No Swagger            |

## workbooks

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%206)-red)

### \$.properties.sourceId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-17-preview | Unknown             | No Swagger            |

### \$.properties.tags

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
