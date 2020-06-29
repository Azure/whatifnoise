# Microsoft.Sql

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## locations/instanceFailoverGroups

![cleanliness](https://img.shields.io/badge/cleanliness-78.57%25%20(11%20/%2014)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%203)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | No Swagger            |

### \$.properties.managedInstancePairs[*].primaryManagedInstanceId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | No Swagger            |

### \$.properties.readOnlyEndpoint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | No Swagger            |

## managedinstances/databases/securityalertpolicies

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties.disabledAlerts

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.emailAddresses

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

## managedInstances/databases

![cleanliness](https://img.shields.io/badge/cleanliness-58.82%25%20(10%20/%2017)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%207)-red)

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.catalogCollation

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.collation

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.properties.createMode

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.properties.recoverableDatabaseId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.properties.restorePointInTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.properties.sourceDatabaseId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

## managedinstances/keys

![cleanliness](https://img.shields.io/badge/cleanliness-80.00%25%20(4%20/%205)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties.uri

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | No Swagger            |

## managedinstances/securityalertpolicies

![cleanliness](https://img.shields.io/badge/cleanliness-55.56%25%20(5%20/%209)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%204)-red)

### \$.properties.disabledAlerts

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.emailAddresses

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.properties.retentionDays

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Default* (0)        | No Swagger            |

## managedInstances/vulnerabilityAssessments

![cleanliness](https://img.shields.io/badge/cleanliness-75.00%25%20(6%20/%208)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties.retentionDays

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.storageContainerPath

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

## managedInstances

![cleanliness](https://img.shields.io/badge/cleanliness-0.00%25%20(0%20/%2030)-red) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2030)-red)

### \$.identity

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.administratorLogin

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.collation

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.dnsZonePartner

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.hardwareFamily

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.proxyOverride

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.publicDataEndpointEnabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.storageSizeInGB

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.subnetId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.timezoneId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.vCores

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.sku.capacity

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.sku.family

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.sku.tier

| API version        | Detected noise type         | Determined noise type |
| ------------------ | --------------------------- | --------------------- |
| 2019-06-01-preview | Default* ("GeneralPurpose") | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.tags.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

## servers/administrators

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%207)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.login

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |

### \$.properties.sid

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |

### \$.properties.tenantId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

## servers/advisors

![cleanliness](https://img.shields.io/badge/cleanliness-80.00%25%20(4%20/%205)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties.autoExecuteValue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | Unknown               |

## servers/auditingPolicies

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%205)-red)

### \$.properties.eventTypesToAudit

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |

### \$.properties.storageAccountKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |

### \$.properties.storageAccountName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |

### \$.properties.storageAccountResourceGroupName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |

### \$.properties.storageAccountSubscriptionId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |

## servers/auditingSettings

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2041)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.IsAzureMonitorTargetEnabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.properties.State

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.properties.auditActionsAndGroups

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | No Swagger            |
| 2017-10-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.auditingState

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.properties.eventTypesToAudit

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.properties.isAzureMonitorTargetEnabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-Preview | Unknown             | No Swagger            |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | No Swagger            |
| 2017-10-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.isStorageSecondaryKeyInUse

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Default (false)     | No Swagger            |
| 2017-03-01-preview | Default (false)     | No Swagger            |

### \$.properties.retentionDays

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | No Swagger            |
| 2017-10-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.state

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.properties.storageAccountAccessKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-Preview | Unknown             | No Swagger            |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.storageAccountName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.properties.storageAccountResourceGroupName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.storageAccountSubscriptionId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.storageEndpoint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-Preview | Unknown             | No Swagger            |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | No Swagger            |
| 2017-10-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.workspaceId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | No Swagger            |

## servers/databases/advisors

![cleanliness](https://img.shields.io/badge/cleanliness-60.00%25%20(3%20/%205)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties.autoExecuteValue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |

## servers/databases/auditingPolicies

![cleanliness](https://img.shields.io/badge/cleanliness-68.18%25%20(15%20/%2022)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%207)-red)

### \$.properties.auditLogsTableName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | Unknown               |

### \$.properties.auditingState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |

### \$.properties.eventTypesToAudit

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |

### \$.properties.fullAuditLogsTableName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |

### \$.properties.retentionDays

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |

### \$.properties.useServerDefault

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |

## servers/databases/auditingSettings

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2017)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.properties.State

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.auditActionsAndGroups

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.properties.comments

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.isAzureMonitorTargetEnabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Default (false)     | No Swagger            |
| 2017-03-01-preview | Default (false)     | No Swagger            |

### \$.properties.isStorageSecondaryKeyInUse

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Default* (false)    | No Swagger            |
| 2017-03-01-preview | Default* (false)    | No Swagger            |

### \$.properties.retentionDays

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Default* (0)        | No Swagger            |

### \$.properties.state

| API version        | Detected noise type   | Determined noise type |
| ------------------ | --------------------- | --------------------- |
| 2017-03-01-preview | Default* ("Disabled") | No Swagger            |

### \$.properties.storageAccountAccessKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.properties.storageAccountSubscriptionId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.properties.storageEndpoint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

## servers/databases/backupLongTermRetentionPolicies

![cleanliness](https://img.shields.io/badge/cleanliness-0.00%25%20(0%20/%207)-red) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%207)-red)

### \$.properties.monthlyRetention

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | Unknown               |
| 2017-10-01-preview | Unknown             | No Swagger            |

### \$.properties.weekOfYear

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Default (0)         | No Swagger            |

### \$.properties.weeklyRetention

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.properties.yearlyRetention

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |
| 2017-10-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

## servers/databases/backupshorttermretentionpolicies

![cleanliness](https://img.shields.io/badge/cleanliness-50.00%25%20(1%20/%202)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | No Swagger            |

## servers/databases/datamaskingpolicies

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |

## servers/databases/extendedauditingsettings

![cleanliness](https://img.shields.io/badge/cleanliness-81.82%25%20(9%20/%2011)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties.isStorageSecondaryKeyInUse

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Default* (false)    | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

## servers/databases/extensions

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2016)-red)

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | No Swagger            |

### \$.properties.administratorLogin

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | No Swagger            |

### \$.properties.administratorLoginPassword

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | No Swagger            |

### \$.properties.authenticationType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |

### \$.properties.operationMode

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | No Swagger            |

### \$.properties.storageKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | No Swagger            |

### \$.properties.storageKeyType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | No Swagger            |

### \$.properties.storageUri

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |

## servers/databases/securityAlertPolicies

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2012)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.disabledAlerts

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.emailAddresses

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.retentionDays

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Default (0)         | No Swagger            |
| 2014-04-01         | Default (0)         | No Swagger            |
| 2018-06-01-preview | Default (0)         | No Swagger            |

### \$.properties.storageAccountAccessKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |

### \$.properties.useServerDefault

| API version        | Detected noise type   | Determined noise type |
| ------------------ | --------------------- | --------------------- |
| 2014-04-01-preview | Default* ("Disabled") | No Swagger            |
| 2014-04-01         | Default* ("Disabled") | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

## servers/databases/syncGroups/syncMembers

![cleanliness](https://img.shields.io/badge/cleanliness-80.00%25%20(8%20/%2010)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties.password

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.skipInitSync

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Default* (false)    | No Swagger            |

## servers/databases/transparentDataEncryption

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%203)-red)

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | No Swagger            |

## servers/databases/vulnerabilityAssessments

![cleanliness](https://img.shields.io/badge/cleanliness-37.50%25%20(3%20/%208)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%205)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.properties.State

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.properties.retentionDays

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.properties.storageContainerPath

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

## servers/databases

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-93.60%25%20(117%20/%20125)-brightgreen)

### \$.managedBy

| API version        | Detected noise type | Determined noise type                                         |
| ------------------ | ------------------- | ------------------------------------------------------------- |
| 2014-04-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2014-04-01)         |
| 2014-04-01         | Unknown             | Put-as-patch                                                  |
| 2015-05-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2017-03-01-preview) |
| 2017-03-01-preview | Unknown             | Put-as-patch                                                  |

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | Put-as-patch          |
| 2017-10-01-preview | Unknown             | Put-as-patch          |

### \$.properties.autoPauseDelay

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | Put-as-patch          |
| 2019-06-01-preview | Unknown             | Put-as-patch          |

### \$.properties.catalogCollation

| API version        | Detected noise type | Determined noise type                                         |
| ------------------ | ------------------- | ------------------------------------------------------------- |
| 2017-03-01-preview | Unknown             | Put-as-patch                                                  |
| 2017-10-01-preview | Unknown             | Put-as-patch                                                  |
| 2018-06-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-06-01-preview) |
| 2019-06-01-preview | Unknown             | Put-as-patch                                                  |

### \$.properties.collation

| API version        | Detected noise type | Determined noise type                                         |
| ------------------ | ------------------- | ------------------------------------------------------------- |
| 2014-04-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2014-04-01)         |
| 2014-04-01         | Unknown             | Put-as-patch                                                  |
| 2015-01-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2017-03-01-preview) |
| 2017-03-01-preview | Unknown             | Put-as-patch                                                  |
| 2017-10-01-preview | Unknown             | Put-as-patch                                                  |
| 2018-06-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-06-01-preview) |
| 2019-06-01-preview | Unknown             | Put-as-patch                                                  |

### \$.properties.containmentState

| API version        | Detected noise type | Determined noise type                                         |
| ------------------ | ------------------- | ------------------------------------------------------------- |
| 2015-01-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2017-10-01-preview) |
| 2015-05-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2017-10-01-preview) |
| 2017-10-01-preview | Unknown             | Put-as-patch                                                  |

### \$.properties.createMode

| API version        | Detected noise type | Determined noise type                                         |
| ------------------ | ------------------- | ------------------------------------------------------------- |
| 2014-04-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2014-04-01)         |
| 2014-04-01         | Unknown             | Put-as-patch                                                  |
| 2015-05-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2017-03-01-preview) |
| 2017-03-01-preview | Unknown             | Put-as-patch                                                  |
| 2017-10-01-preview | Unknown             | Put-as-patch                                                  |
| 2019-06-01-preview | Unknown             | Put-as-patch                                                  |

### \$.properties.currentServiceObjectiveId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01         | Unknown             | No Swagger            |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.earliestRestoreDate

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01         | Unknown             | No Swagger            |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.edition

| API version        | Detected noise type | Determined noise type                                         |
| ------------------ | ------------------- | ------------------------------------------------------------- |
| 2014-04-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2014-04-01)         |
| 2014-04-01         | Unknown             | Put-as-patch                                                  |
| 2017-03-01-preview | Unknown             | Put-as-patch                                                  |
| 2017-10-01-preview | Unknown             | Put-as-patch                                                  |
| 2018-06-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-06-01-preview) |
| 2019-06-01-preview | Unknown             | Put-as-patch                                                  |

### \$.properties.elasticPoolId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.elasticPoolName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01         | Unknown             | Put-as-patch          |
| 2017-10-01-preview | Unknown             | Put-as-patch          |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.isUpgradeRequested

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2014-04-01-preview | Default (false)     | No Swagger, Put-as-patch (inheritted from 2014-04-01) |
| 2014-04-01         | Default (false)     | Put-as-patch                                          |
| 2015-01-01         | Default (false)     | No Swagger                                            |
| 2015-05-01-preview | Default (false)     | No Swagger                                            |

### \$.properties.licenseType

| API version        | Detected noise type | Determined noise type                                         |
| ------------------ | ------------------- | ------------------------------------------------------------- |
| 2017-03-01-preview | Unknown             | Put-as-patch                                                  |
| 2017-10-01-preview | Unknown             | Put-as-patch                                                  |
| 2018-06-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-06-01-preview) |
| 2019-06-01-preview | Unknown             | Put-as-patch                                                  |

### \$.properties.longTermRetentionBackupResourceId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | Put-as-patch          |

### \$.properties.maxSizeBytes

| API version        | Detected noise type | Determined noise type                                         |
| ------------------ | ------------------- | ------------------------------------------------------------- |
| 2017-03-01-preview | Unknown             | Put-as-patch                                                  |
| 2017-10-01-preview | Unknown             | Put-as-patch                                                  |
| 2018-06-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-06-01-preview) |
| 2019-06-01-preview | Unknown             | Put-as-patch                                                  |

### \$.properties.minCapacity

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | Put-as-patch          |
| 2019-06-01-preview | Unknown             | Put-as-patch          |

### \$.properties.readReplicaCount

| API version        | Detected noise type | Determined noise type                                         |
| ------------------ | ------------------- | ------------------------------------------------------------- |
| 2017-03-01-preview | Unknown             | Put-as-patch                                                  |
| 2017-10-01-preview | Unknown             | Put-as-patch                                                  |
| 2018-06-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-06-01-preview) |
| 2019-06-01-preview | Unknown             | Put-as-patch                                                  |

### \$.properties.readScale

| API version        | Detected noise type | Determined noise type                                         |
| ------------------ | ------------------- | ------------------------------------------------------------- |
| 2014-04-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2014-04-01)         |
| 2014-04-01         | Unknown             | Put-as-patch                                                  |
| 2017-03-01-preview | Unknown             | Put-as-patch                                                  |
| 2017-10-01-preview | Unknown             | Put-as-patch                                                  |
| 2018-06-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-06-01-preview) |
| 2019-06-01-preview | Unknown             | Put-as-patch                                                  |

### \$.properties.recoverableDatabaseId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | Put-as-patch          |

### \$.properties.requestedServiceObjectiveId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | Put-as-patch          |

### \$.properties.requestedServiceObjectiveName

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2014-04-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2014-04-01) |
| 2014-04-01         | Unknown             | Put-as-patch                                          |
| 2017-03-01-preview | Unknown             | Put-as-patch                                          |

### \$.properties.restorePointInTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | Put-as-patch          |

### \$.properties.sampleName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | Put-as-patch          |
| 2017-10-01-preview | Unknown             | Put-as-patch          |
| 2019-06-01-preview | Unknown             | Put-as-patch          |

### \$.properties.serviceLevelObjective

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | Put-as-patch          |
| 2019-06-01-preview | Unknown             | Put-as-patch          |

### \$.properties.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | Put-as-patch          |

### \$.properties.sourceDatabaseDeletionDate

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | Put-as-patch          |

### \$.properties.sourceDatabaseId

| API version        | Detected noise type | Determined noise type                                         |
| ------------------ | ------------------- | ------------------------------------------------------------- |
| 2015-05-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2017-03-01-preview) |
| 2017-03-01-preview | Unknown             | Put-as-patch                                                  |
| 2017-10-01-preview | Unknown             | Put-as-patch                                                  |
| 2019-06-01-preview | Unknown             | Put-as-patch                                                  |

### \$.properties.storageAccountType

| API version        | Detected noise type | Determined noise type                                         |
| ------------------ | ------------------- | ------------------------------------------------------------- |
| 2017-03-01-preview | Default ("GRS")     | Put-as-patch                                                  |
| 2017-10-01-preview | Default ("GRS")     | Put-as-patch                                                  |
| 2018-06-01-preview | Default ("GRS")     | No Swagger, Put-as-patch (inheritted from 2019-06-01-preview) |
| 2019-06-01-preview | Default ("GRS")     | Put-as-patch                                                  |

### \$.properties.zoneRedundant

| API version        | Detected noise type | Determined noise type                                         |
| ------------------ | ------------------- | ------------------------------------------------------------- |
| 2014-04-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2014-04-01)         |
| 2014-04-01         | Unknown             | Put-as-patch                                                  |
| 2015-01-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2017-03-01-preview) |
| 2015-05-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2017-03-01-preview) |
| 2017-03-01-preview | Unknown             | Put-as-patch                                                  |
| 2017-10-01-preview | Unknown             | Put-as-patch                                                  |
| 2019-06-01-preview | Unknown             | Put-as-patch                                                  |

### \$.sku

| API version        | Detected noise type | Determined noise type                                         |
| ------------------ | ------------------- | ------------------------------------------------------------- |
| 2017-03-01-preview | Unknown             | Put-as-patch                                                  |
| 2017-10-01-preview | Unknown             | Put-as-patch                                                  |
| 2018-06-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-06-01-preview) |
| 2019-06-01-preview | Unknown             | Put-as-patch                                                  |

### \$.sku.capacity

| API version        | Detected noise type | Determined noise type                                         |
| ------------------ | ------------------- | ------------------------------------------------------------- |
| 2017-10-01-preview | Unknown             | Put-as-patch                                                  |
| 2018-06-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-06-01-preview) |
| 2019-06-01-preview | Unknown             | Put-as-patch                                                  |

### \$.sku.family

| API version        | Detected noise type | Determined noise type                                         |
| ------------------ | ------------------- | ------------------------------------------------------------- |
| 2017-10-01-preview | Unknown             | Put-as-patch                                                  |
| 2018-06-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-06-01-preview) |
| 2019-06-01-preview | Unknown             | Put-as-patch                                                  |

### \$.sku.name

| API version        | Detected noise type | Determined noise type                                         |
| ------------------ | ------------------- | ------------------------------------------------------------- |
| 2017-10-01-preview | Unknown             | Put-as-patch                                                  |
| 2018-06-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-06-01-preview) |
| 2019-06-01-preview | Unknown             | Put-as-patch                                                  |

### \$.sku.size

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | Put-as-patch          |
| 2019-06-01-preview | Unknown             | Put-as-patch          |

### \$.sku.tier

| API version        | Detected noise type | Determined noise type                                         |
| ------------------ | ------------------- | ------------------------------------------------------------- |
| 2017-10-01-preview | Unknown             | Put-as-patch                                                  |
| 2018-06-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-06-01-preview) |
| 2019-06-01-preview | Unknown             | Put-as-patch                                                  |

### \$.tags

| API version        | Detected noise type | Determined noise type                                         |
| ------------------ | ------------------- | ------------------------------------------------------------- |
| 2014-04-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2014-04-01)         |
| 2014-04-01         | Unknown             | Put-as-patch                                                  |
| 2015-05-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2017-03-01-preview) |
| 2017-03-01-preview | Unknown             | Put-as-patch                                                  |
| 2017-10-01-preview | Unknown             | Put-as-patch                                                  |
| 2019-06-01-preview | Unknown             | Put-as-patch                                                  |

### \$.tags.*

| API version        | Detected noise type | Determined noise type                                         |
| ------------------ | ------------------- | ------------------------------------------------------------- |
| 2014-04-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2014-04-01)         |
| 2014-04-01         | Unknown             | Put-as-patch                                                  |
| 2015-01-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2017-03-01-preview) |
| 2017-03-01-preview | Unknown             | Put-as-patch                                                  |
| 2017-10-01-preview | Unknown             | Put-as-patch                                                  |
| 2019-06-01-preview | Unknown             | Put-as-patch                                                  |

## servers/elasticPools

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2032)-red)

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01         | Unknown             | No Swagger            |
| 2017-10-01-preview | Unknown             | No Swagger            |

### \$.properties.databaseDtuMax

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | No Swagger            |

### \$.properties.databaseDtuMin

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | No Swagger            |

### \$.properties.dtu

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | No Swagger            |

### \$.properties.edition

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | No Swagger            |

### \$.properties.licenseType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | No Swagger            |

### \$.properties.maxSizeBytes

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.perDatabaseSettings

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | No Swagger            |

### \$.properties.storageMB

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | No Swagger            |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-10-01-preview | Unknown             | No Swagger            |

### \$.properties.zone,Redundant

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | No Swagger            |

### \$.properties.zoneRedundant

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Default (false)     | No Swagger            |
| 2014-04-01         | Default (false)     | No Swagger            |
| 2015-05-01-preview | Default (false)     | No Swagger            |
| 2017-10-01-preview | Default (false)     | No Swagger            |
| 2019-06-01-preview | Default (false)     | No Swagger            |

### \$.sku.capacity

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | No Swagger            |

### \$.sku.family

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.sku.tier

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01         | Unknown             | No Swagger            |
| 2017-10-01-preview | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |

## servers/encryptionProtector

![cleanliness](https://img.shields.io/badge/cleanliness-66.67%25%20(4%20/%206)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties.serverKeyName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

## servers/extendedauditingsettings

![cleanliness](https://img.shields.io/badge/cleanliness-63.64%25%20(7%20/%2011)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%204)-red)

### \$.properties.isAzureMonitorTargetEnabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Default* (false)    | No Swagger            |

### \$.properties.isStorageSecondaryKeyInUse

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Default* (false)    | No Swagger            |

### \$.properties.storageAccountSubscriptionId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.properties.storageEndpoint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

## servers/failoverGroups

![cleanliness](https://img.shields.io/badge/cleanliness-57.14%25%20(8%20/%2014)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%206)-red)

### \$.kind

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.databases

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.databases[*]

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.readOnlyEndpoint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.serverName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

## servers/firewallRules

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2010)-red)

### \$.kind

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | No Swagger            |
| 2017-10-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.endIpAddress

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.startIpAddress

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |

## servers/jobAgents

![cleanliness](https://img.shields.io/badge/cleanliness-88.89%25%20(8%20/%209)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

## servers/keys

![cleanliness](https://img.shields.io/badge/cleanliness-33.33%25%20(2%20/%206)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%204)-red)

### \$.kind

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.creationDate

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.thumbprint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.uri

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

## servers/securityAlertPolicies

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2014)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.disabledAlerts

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.emailAccountAdmins

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.properties.emailAddresses

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.retentionDays

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Default (0)         | No Swagger            |
| 2017-03-01-preview | Default (0)         | No Swagger            |

### \$.properties.storageAccountAccessKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.storageAccountSubscriptionId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.storageEndpoint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | No Swagger            |

## servers/virtualNetworkRules

![cleanliness](https://img.shields.io/badge/cleanliness-0.00%25%20(0%20/%204)-red) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%204)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.ignoreMissingVnetServiceEndpoint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Default (false)     | No Swagger            |
| 2019-06-01-preview | Default (false)     | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

## servers/vulnerabilityAssessments

![cleanliness](https://img.shields.io/badge/cleanliness-12.50%25%20(1%20/%208)-orange) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%207)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.State

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.isStorageSecondaryKeyInUse

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.recurringScans.emails

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.retentionDays

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.storageContainerPath

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

## servers

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-96.55%25%20(28%20/%2029)-brightgreen)

### \$.identity

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Put-as-patch          |
| 2019-06-01-preview | Unknown             | Put-as-patch          |

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |

### \$.properties

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2014-04-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2014-04-01) |
| 2014-04-01         | Unknown             | Put-as-patch                                          |
| 2015-05-01-preview | Unknown             | Put-as-patch                                          |
| 2019-06-01-preview | Unknown             | Put-as-patch                                          |

### \$.properties.administratorLogin

| API version        | Detected noise type | Determined noise type                                         |
| ------------------ | ------------------- | ------------------------------------------------------------- |
| 2014-04-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-05-01-preview) |
| 2015-05-01-preview | Unknown             | Put-as-patch                                                  |

### \$.properties.administratorLoginPassword

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2014-04-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2014-04-01) |
| 2014-04-01         | Unknown             | Put-as-patch                                          |

### \$.properties.comments

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Put-as-patch          |

### \$.properties.mode

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Put-as-patch          |

### \$.properties.publicNetworkAccess

| API version        | Detected noise type | Determined noise type                                         |
| ------------------ | ------------------- | ------------------------------------------------------------- |
| 2018-06-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-06-01-preview) |
| 2019-06-01-preview | Unknown             | Put-as-patch                                                  |

### \$.properties.version

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2014-04-01-preview | Default (12)        | No Swagger, Put-as-patch (inheritted from 2014-04-01) |
| 2014-04-01         | Default (12)        | Put-as-patch                                          |

### \$.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Put-as-patch          |

### \$.tags

| API version        | Detected noise type | Determined noise type                                         |
| ------------------ | ------------------- | ------------------------------------------------------------- |
| 2014-04-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2014-04-01)         |
| 2014-04-01         | Unknown             | Put-as-patch                                                  |
| 2015-05-01-preview | Unknown             | Put-as-patch                                                  |
| 2018-06-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-06-01-preview) |
| 2019-06-01-preview | Unknown             | Put-as-patch                                                  |

### \$.tags.*

| API version        | Detected noise type | Determined noise type                                         |
| ------------------ | ------------------- | ------------------------------------------------------------- |
| 2014-04-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2014-04-01)         |
| 2014-04-01         | Unknown             | Put-as-patch                                                  |
| 2015-05-01-preview | Unknown             | Put-as-patch                                                  |
| 2017-10-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-06-01-preview) |
| 2018-06-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-06-01-preview) |
| 2019-06-01-preview | Unknown             | Put-as-patch                                                  |
