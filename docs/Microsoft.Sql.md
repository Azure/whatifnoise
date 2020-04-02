# Microsoft.Sql

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## locations/instanceFailoverGroups

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | Unknown               |

### \$.properties.managedInstancePairs[*].primaryManagedInstanceId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | No Swagger            |

### \$.properties.readOnlyEndpoint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | Unknown               |

## managedInstances/databases

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.collation

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | Unknown               |

### \$.properties.createMode

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | Unknown               |

### \$.properties.recoverableDatabaseId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | Unknown               |

### \$.properties.restorePointInTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | Unknown               |

### \$.properties.sourceDatabaseId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | Unknown               |

## managedInstances/vulnerabilityAssessments

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.storageContainerPath

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | Unknown               |

## managedInstances

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.collation

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |

### \$.properties.dnsZonePartner

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |

### \$.properties.hardwareFamily

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.publicDataEndpointEnabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | Unknown               |

### \$.properties.timezoneId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | Unknown               |

### \$.properties.vCores

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Default* (8)        | Unknown               |

### \$.sku.capacity

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | Unknown               |

### \$.sku.family

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | Unknown               |

### \$.sku.tier

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | Unknown               |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |

## servers/administrators

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | No Swagger            |

### \$.properties.tenantId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | Unknown               |

## servers/advisors

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.autoExecuteValue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | Unknown               |

## servers/auditingPolicies

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

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

![13.33%25](https://img.shields.io/badge/13.33%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-orange)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.IsAzureMonitorTargetEnabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | Unknown               |

### \$.properties.State

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | Unknown               |

### \$.properties.auditActionsAndGroups

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | Unknown               |
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
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | Unknown               |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.isStorageSecondaryKeyInUse

| API version        | Detected noise type | Determined noise type                                            |
| ------------------ | ------------------- | ---------------------------------------------------------------- |
| 2015-05-01-preview | Default (false)     | No Swagger, Default (false) (inheritted from 2017-03-01-preview) |
| 2017-03-01-preview | Default (false)     | Default (false)                                                  |

### \$.properties.retentionDays

| API version        | Detected noise type | Determined noise type                                        |
| ------------------ | ------------------- | ------------------------------------------------------------ |
| 2015-05-01-preview | Default (0)         | No Swagger, Default (0) (inheritted from 2017-03-01-preview) |
| 2017-03-01-preview | Default (0)         | Default (0)                                                  |

### \$.properties.state

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | Unknown               |

### \$.properties.storageAccountAccessKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.storageAccountName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.properties.storageAccountResourceGroupName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.properties.storageAccountSubscriptionId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | Unknown               |

### \$.properties.storageEndpoint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | Unknown               |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

## servers/databases/advisors

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.autoExecuteValue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |

## servers/databases/auditingPolicies

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.auditLogsTableName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | Unknown               |

### \$.properties.auditingState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | Unknown               |

### \$.properties.eventTypesToAudit

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | Unknown               |

### \$.properties.fullAuditLogsTableName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | Unknown               |

### \$.properties.retentionDays

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | Unknown               |

### \$.properties.useServerDefault

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |

## servers/databases/auditingSettings

![11.76%25](https://img.shields.io/badge/11.76%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-orange)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.properties.State

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |

### \$.properties.auditActionsAndGroups

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |
| 2017-03-01-preview | Unknown             | Unknown               |

### \$.properties.isAzureMonitorTargetEnabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Default (false)     | Default (false)       |
| 2017-03-01-preview | Default (false)     | Default (false)       |

### \$.properties.isStorageSecondaryKeyInUse

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Default* (false)    | Unknown               |
| 2017-03-01-preview | Default* (false)    | Unknown               |

### \$.properties.retentionDays

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Default* (0)        | Unknown               |

### \$.properties.state

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |

### \$.properties.storageAccountAccessKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |
| 2017-03-01-preview | Unknown             | Unknown               |

### \$.properties.storageAccountSubscriptionId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | Unknown               |

### \$.properties.storageEndpoint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |
| 2017-03-01-preview | Unknown             | Unknown               |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

## servers/databases/backupLongTermRetentionPolicies

![14.29%25](https://img.shields.io/badge/14.29%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-orange)

### \$.properties.monthlyRetention

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | Unknown               |
| 2017-10-01-preview | Unknown             | No Swagger            |

### \$.properties.weekOfYear

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Default (0)         | Default (0)           |

### \$.properties.weeklyRetention

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | Unknown               |

### \$.properties.yearlyRetention

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | Unknown               |
| 2017-10-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

## servers/databases/backupshorttermretentionpolicies

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | No Swagger            |

## servers/databases/datamaskingpolicies

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |

## servers/databases/extendedauditingsettings

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

## servers/databases/extensions

!> No Swagger.

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

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

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | Unknown               |

### \$.properties.disabledAlerts

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | Unknown               |

### \$.properties.emailAddresses

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | Unknown               |

### \$.properties.retentionDays

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Default* (0)        | No Swagger            |
| 2014-04-01         | Default* (0)        | Unknown               |
| 2018-06-01-preview | Default* (0)        | Unknown               |

### \$.properties.storageAccountAccessKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |

### \$.properties.useServerDefault

| API version        | Detected noise type   | Determined noise type |
| ------------------ | --------------------- | --------------------- |
| 2014-04-01-preview | Default* ("Disabled") | No Swagger            |
| 2014-04-01         | Default* ("Disabled") | Unknown               |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

## servers/databases/syncGroups/syncMembers

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.password

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |

### \$.properties.skipInitSync

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Default* (false)    | No Swagger            |

## servers/databases/transparentDataEncryption

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | No Swagger            |

## servers/databases/vulnerabilityAssessments

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

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
| 2017-03-01-preview | Unknown             | Unknown               |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

## servers/databases

![9.48%25](https://img.shields.io/badge/9.48%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-red)

### \$.managedBy

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | No Swagger            |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | Unknown               |
| 2017-10-01-preview | Unknown             | Unknown               |

### \$.properties.autoPauseDelay

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Default* (60)       | Unknown               |

### \$.properties.catalogCollation

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | Unknown               |
| 2017-10-01-preview | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | Unknown               |

### \$.properties.collation

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | Unknown               |
| 2015-01-01         | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | Unknown               |
| 2017-10-01-preview | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | Unknown               |

### \$.properties.containmentState

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01         | Default (2)         | No Swagger            |
| 2015-05-01-preview | Default (2)         | No Swagger            |

### \$.properties.createMode

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | Unknown               |
| 2017-03-01-preview | Unknown             | Unknown               |
| 2017-10-01-preview | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | Unknown               |

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

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | Unknown               |

### \$.properties.elasticPoolName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01         | Unknown             | Unknown               |
| 2017-10-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.isUpgradeRequested

| API version        | Detected noise type | Determined noise type                              |
| ------------------ | ------------------- | -------------------------------------------------- |
| 2014-04-01-preview | Default (false)     | No Swagger, Read-only (inheritted from 2014-04-01) |
| 2014-04-01         | Default (false)     | Read-only                                          |
| 2015-01-01         | Default (false)     | No Swagger                                         |
| 2015-05-01-preview | Default (false)     | No Swagger                                         |

### \$.properties.licenseType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.maxSizeBytes

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | Unknown               |
| 2017-10-01-preview | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | Unknown               |

### \$.properties.maxSizeGB

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | No Swagger            |

### \$.properties.minCapacity

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | Unknown               |

### \$.properties.mode

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | No Swagger            |

### \$.properties.readReplicaCount

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | Unknown               |

### \$.properties.readScale

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | Unknown               |
| 2017-10-01-preview | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | Unknown               |

### \$.properties.recoverableDatabaseId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | Unknown               |
| 2017-10-01-preview | Unknown             | Unknown               |

### \$.properties.requestedServiceObjectiveId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | Unknown               |
| 2015-01-01         | Unknown             | No Swagger            |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.properties.requestedServiceObjectiveName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | Unknown               |

### \$.properties.restorePointInTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | Unknown               |

### \$.properties.sampleName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | Unknown               |
| 2017-10-01-preview | Unknown             | Unknown               |

### \$.properties.serviceLevelObjective

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01         | Unknown             | No Swagger            |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | No Swagger            |

### \$.properties.sourceDatabaseDeletionDate

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | Unknown               |

### \$.properties.sourceDatabaseId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | Unknown               |
| 2017-10-01-preview | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | Unknown               |

### \$.properties.storageAccountType

| API version        | Detected noise type | Determined noise type                                            |
| ------------------ | ------------------- | ---------------------------------------------------------------- |
| 2018-06-01-preview | Default ("GRS")     | No Swagger, Default ("GRS") (inheritted from 2019-06-01-preview) |
| 2019-06-01-preview | Default ("GRS")     | Default ("GRS")                                                  |

### \$.properties.zoneRedundant

| API version        | Detected noise type | Determined noise type                                            |
| ------------------ | ------------------- | ---------------------------------------------------------------- |
| 2014-04-01-preview | Unknown             | No Swagger, Default (false) (inheritted from 2014-04-01)         |
| 2014-04-01         | Unknown             | Default (false)                                                  |
| 2015-01-01         | Unknown             | No Swagger, Default (false) (inheritted from 2017-03-01-preview) |
| 2015-05-01-preview | Unknown             | No Swagger, Default (false) (inheritted from 2017-03-01-preview) |
| 2017-03-01-preview | Unknown             | Default (false)                                                  |
| 2017-10-01-preview | Unknown             | Default (false)                                                  |
| 2019-06-01-preview | Unknown             | Default (false)                                                  |

### \$.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | Unknown               |
| 2017-10-01-preview | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | Unknown               |

### \$.sku.capacity

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | Unknown               |

### \$.sku.family

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.sku.name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | Unknown               |

### \$.sku.tier

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | Unknown               |
| 2017-10-01-preview | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | Unknown               |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | Unknown               |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | Unknown               |
| 2017-10-01-preview | Unknown             | Unknown               |
| 2019-06-01-preview | Unknown             | Unknown               |

### \$.tags.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | Unknown               |
| 2015-01-01         | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | Unknown               |
| 2017-10-01-preview | Unknown             | Unknown               |

## servers/elasticPools

![17.39%25](https://img.shields.io/badge/17.39%25-%E2%98%85★%E2%98%86☆☆☆☆☆☆☆-orange)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | Unknown               |

### \$.properties.dtu

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | Unknown               |

### \$.properties.licenseType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | Unknown               |

### \$.properties.maxSizeBytes

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | Unknown               |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.perDatabaseSettings

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | Unknown               |

### \$.properties.storageMB

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | Unknown               |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.zone,Redundant

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | No Swagger            |

### \$.properties.zoneRedundant

| API version        | Detected noise type | Determined noise type                                            |
| ------------------ | ------------------- | ---------------------------------------------------------------- |
| 2014-04-01-preview | Default (false)     | No Swagger, Default (false) (inheritted from 2014-04-01)         |
| 2014-04-01         | Default (false)     | Default (false)                                                  |
| 2015-05-01-preview | Default (false)     | No Swagger, Default (false) (inheritted from 2017-10-01-preview) |
| 2017-10-01-preview | Default (false)     | Default (false)                                                  |
| 2019-06-01-preview | Default (false)     | No Swagger                                                       |

### \$.sku.capacity

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Default* (2)        | Unknown               |

### \$.sku.family

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | Unknown               |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.sku.tier

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01-preview | Unknown             | Unknown               |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01         | Unknown             | Unknown               |
| 2017-10-01-preview | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | Unknown               |

## servers/encryptionProtector

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.serverKeyName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

## servers/failoverGroups

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.kind

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.databases

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.databases[*]

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.readOnlyEndpoint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |

### \$.properties.serverName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

## servers/firewallRules

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

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
| 2015-05-01-preview | Unknown             | Unknown               |

### \$.properties.startIpAddress

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |

## servers/jobAgents

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | Unknown               |

## servers/keys

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.kind

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |

### \$.properties.creationDate

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |

### \$.properties.thumbprint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |

### \$.properties.uri

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |

## servers/securityAlertPolicies

![13.33%25](https://img.shields.io/badge/13.33%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-orange)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

### \$.properties.disabledAlerts

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | Unknown               |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.emailAccountAdmins

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | Unknown               |

### \$.properties.emailAddresses

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | Unknown               |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.retentionDays

| API version        | Detected noise type | Determined noise type                                        |
| ------------------ | ------------------- | ------------------------------------------------------------ |
| 2015-05-01-preview | Default (0)         | No Swagger, Default (0) (inheritted from 2017-03-01-preview) |
| 2017-03-01-preview | Default (0)         | Default (0)                                                  |

### \$.properties.storageAccountAccessKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | Unknown               |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.storageAccountSubscriptionId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.storageEndpoint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-03-01-preview | Unknown             | Unknown               |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01-preview | Unknown             | No Swagger            |

## servers/virtualNetworkRules

![25.00%25](https://img.shields.io/badge/25.00%25-%E2%98%85★★%E2%98%86☆☆☆☆☆☆-orange)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.ignoreMissingVnetServiceEndpoint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Default (false)     | Default (false)       |
| 2019-06-01-preview | Default (false)     | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

## servers/vulnerabilityAssessments

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.recurringScans.emails

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | Unknown               |

### \$.properties.storageContainerPath

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | Unknown               |

## servers

![9.09%25](https://img.shields.io/badge/9.09%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-red)

### \$.identity

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | Unknown               |
| 2015-05-01-preview | Unknown             | Unknown               |
| 2019-06-01-preview | Unknown             | Unknown               |

### \$.properties.administratorLoginPassword

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | Unknown               |

### \$.properties.networkAcls

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.publicNetworkAccess

| API version        | Detected noise type  | Determined noise type |
| ------------------ | -------------------- | --------------------- |
| 2019-06-01-preview | Default* ("Enabled") | Unknown               |

### \$.properties.timezoneId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.version

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2014-04-01-preview | Default (12)        | No Swagger, Default (12) (inheritted from 2014-04-01) |
| 2014-04-01         | Default (12)        | Default (12)                                          |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | Unknown               |
| 2015-05-01-preview | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | Unknown               |

### \$.tags.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-04-01-preview | Unknown             | No Swagger            |
| 2014-04-01         | Unknown             | Unknown               |
| 2015-05-01-preview | Unknown             | Unknown               |
| 2017-10-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
