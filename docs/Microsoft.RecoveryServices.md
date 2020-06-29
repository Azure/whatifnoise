# Microsoft.RecoveryServices

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## vaults/backupFabrics/backupProtectionIntent

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2015)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.backupManagementType

| API version | Detected noise type     | Determined noise type |
| ----------- | ----------------------- | --------------------- |
| 2017-07-01  | Default ("AzureIaasVM") | No Swagger            |

### \$.properties.friendlyName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |
| 2018-01-10  | Unknown             | No Swagger            |

### \$.properties.itemId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parentName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.policyId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |
| 2018-01-10  | Unknown             | No Swagger            |

### \$.properties.protectionIntentItemType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |
| 2018-01-10  | Unknown             | No Swagger            |

### \$.properties.protectionState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.sourceResourceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |
| 2018-01-10  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |

## vaults/backupFabrics/protectionContainers/protectedItems

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2091)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2016-12-01  | Unknown             | No Swagger            |
| 2019-06-15  | Unknown             | No Swagger            |

### \$.properties.backupManagementType

| API version | Detected noise type     | Determined noise type |
| ----------- | ----------------------- | --------------------- |
| 2016-06-01  | Default ("AzureIaasVM") | No Swagger            |
| 2016-12-01  | Default ("AzureIaasVM") | No Swagger            |

### \$.properties.containerName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2016-12-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |
| 2018-07-10  | Unknown             | No Swagger            |
| 2019-05-13  | Unknown             | No Swagger            |
| 2019-06-15  | Unknown             | No Swagger            |

### \$.properties.createMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-15  | Unknown             | No Swagger            |

### \$.properties.extendedInfo

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.friendlyName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2016-12-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |
| 2018-07-10  | Unknown             | No Swagger            |
| 2019-05-13  | Unknown             | No Swagger            |
| 2019-06-15  | Unknown             | No Swagger            |

### \$.properties.healthDetails

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2016-12-01  | Unknown             | No Swagger            |
| 2018-07-10  | Unknown             | No Swagger            |
| 2019-05-13  | Unknown             | No Swagger            |
| 2019-06-15  | Unknown             | No Swagger            |

### \$.properties.healthStatus

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2016-12-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |
| 2018-07-10  | Unknown             | No Swagger            |
| 2019-05-13  | Unknown             | No Swagger            |
| 2019-06-15  | Unknown             | No Swagger            |

### \$.properties.lastBackupErrorDetail

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.lastBackupStatus

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2016-12-01  | Unknown             | No Swagger            |
| 2018-07-10  | Unknown             | No Swagger            |
| 2019-05-13  | Unknown             | No Swagger            |
| 2019-06-15  | Unknown             | No Swagger            |

### \$.properties.lastBackupTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2016-12-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |
| 2018-07-10  | Unknown             | No Swagger            |
| 2019-05-13  | Unknown             | No Swagger            |
| 2019-06-15  | Unknown             | No Swagger            |

### \$.properties.lastRecoveryPoint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2016-12-01  | Unknown             | No Swagger            |
| 2018-07-10  | Unknown             | No Swagger            |
| 2019-05-13  | Unknown             | No Swagger            |
| 2019-06-15  | Unknown             | No Swagger            |

### \$.properties.parentName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parentType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.policyId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2016-12-01  | Unknown             | No Swagger            |
| 2019-06-15  | Unknown             | No Swagger            |

### \$.properties.policyName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2016-12-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |
| 2018-07-10  | Unknown             | No Swagger            |
| 2019-05-13  | Unknown             | No Swagger            |
| 2019-06-15  | Unknown             | No Swagger            |

### \$.properties.protectedItemDataId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2016-12-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |
| 2018-07-10  | Unknown             | No Swagger            |
| 2019-05-13  | Unknown             | No Swagger            |
| 2019-06-15  | Unknown             | No Swagger            |

### \$.properties.protectedItemDataSourceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.protectedItemHealthStatus

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.protectedItemType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2016-12-01  | Unknown             | No Swagger            |

### \$.properties.protectionState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2016-12-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |
| 2018-07-10  | Unknown             | No Swagger            |
| 2019-05-13  | Unknown             | No Swagger            |
| 2019-06-15  | Unknown             | No Swagger            |

### \$.properties.protectionStatus

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2016-12-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |
| 2018-07-10  | Unknown             | No Swagger            |
| 2019-05-13  | Unknown             | No Swagger            |
| 2019-06-15  | Unknown             | No Swagger            |

### \$.properties.serverName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.sourceResourceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.virtualMachineId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2016-12-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |
| 2018-07-10  | Unknown             | No Swagger            |
| 2019-05-13  | Unknown             | No Swagger            |
| 2019-06-15  | Unknown             | No Swagger            |

### \$.properties.workloadType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Default ("VM")      | No Swagger            |
| 2016-12-01  | Default ("VM")      | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-12-01  | Unknown             | No Swagger            |

## vaults/backupFabrics/protectionContainers

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2012)-red)

### \$.properties.extendedInfo

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.friendlyName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.healthStatus

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2016-12-01  | Unknown             | Unknown               |

### \$.properties.lastUpdatedTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.operationType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.protectableObjectType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2016-12-01  | Unknown             | No Swagger            |

### \$.properties.protectedItemCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-12-01  | Default* (1)        | No Swagger            |

### \$.properties.registrationStatus

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2016-12-01  | Unknown             | No Swagger            |

### \$.properties.workloadType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

## vaults/backupPolicies

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2072)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2016-12-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |
| 2019-05-13  | Unknown             | No Swagger            |

### \$.properties.WorkloadType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |

### \$.properties.instantRpRetentionRangeInDays

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-11-10  | Default (2)         | No Swagger            |
| 2016-06-01  | Default (2)         | No Swagger            |
| 2016-12-01  | Default (2)         | No Swagger            |
| 2017-07-01  | Default (2)         | No Swagger            |
| 2018-01-10  | Default (2)         | No Swagger            |

### \$.properties.protectedItemsCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-11-10  | Unknown             | No Swagger            |
| 2016-06-01  | Unknown             | No Swagger            |
| 2016-12-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |
| 2018-01-10  | Unknown             | No Swagger            |
| 2019-05-13  | Unknown             | No Swagger            |
| 2019-06-15  | Unknown             | No Swagger            |

### \$.properties.retentionPolicy.dailySchedule.retentionTimes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.retentionPolicy.dailySchedule.retentionTimes[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2016-12-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |
| 2018-01-10  | Unknown             | No Swagger            |

### \$.properties.retentionPolicy.isDailyEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.retentionPolicy.isMonthlyEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.retentionPolicy.isWeeklyEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.retentionPolicy.isYearlyEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.retentionPolicy.monthlySchedule.retentionTimes[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2018-01-10  | Unknown             | No Swagger            |

### \$.properties.retentionPolicy.weeklySchedule.retentionTimes[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2018-01-10  | Unknown             | No Swagger            |

### \$.properties.retentionPolicy.yearlySchedule.retentionTimes[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.schedulePolicy.scheduleRunTimes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.schedulePolicy.scheduleRunTimes[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2016-12-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |
| 2018-01-10  | Unknown             | No Swagger            |

### \$.properties.schedulePolicy.scheduleWeeklyFrequency

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-11-10  | Default (0)         | No Swagger            |
| 2016-06-01  | Default (0)         | No Swagger            |
| 2016-12-01  | Default (0)         | No Swagger            |
| 2017-07-01  | Default (0)         | No Swagger            |
| 2018-01-10  | Default (0)         | No Swagger            |
| 2019-05-13  | Default (0)         | No Swagger            |
| 2019-06-15  | Default (0)         | No Swagger            |

### \$.properties.settings.isCompression

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-11-10  | Default* (false)    | No Swagger            |
| 2016-06-01  | Default* (false)    | No Swagger            |

### \$.properties.settings.isSqlCompression

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.settings.issqlcompression

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.subProtectionPolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.subProtectionPolicy[*].policyType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.subProtectionPolicy[*].retentionPolicy.dailySchedule

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.subProtectionPolicy[*].retentionPolicy.dailySchedule.retentionTimes[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.subProtectionPolicy[*].retentionPolicy.monthlySchedule

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.subProtectionPolicy[*].retentionPolicy.monthlySchedule.retentionTimes[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.subProtectionPolicy[*].retentionPolicy.retentionDuration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.subProtectionPolicy[*].retentionPolicy.retentionPolicyType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.subProtectionPolicy[*].retentionPolicy.weeklySchedule

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.subProtectionPolicy[*].retentionPolicy.weeklySchedule.retentionTimes[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.subProtectionPolicy[*].retentionPolicy.yearlySchedule

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.subProtectionPolicy[*].retentionPolicy.yearlySchedule.retentionTimes[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.subProtectionPolicy[*].schedulePolicy.scheduleFrequencyInMins

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.subProtectionPolicy[*].schedulePolicy.schedulePolicyType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.subProtectionPolicy[*].schedulePolicy.scheduleRunFrequency

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.subProtectionPolicy[*].schedulePolicy.scheduleRunTimes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.subProtectionPolicy[*].schedulePolicy.scheduleRunTimes[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.subProtectionPolicy[*].schedulePolicy.scheduleWeeklyFrequency

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Default (0)         | No Swagger            |

### \$.properties.timeZone

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.workLoadType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2018-01-10  | Unknown             | No Swagger            |

### \$.properties.workloadType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-13  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |

## vaults/backupstorageconfig

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2012)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-12-01  | Unknown             | No Swagger            |

### \$.properties.crossRegionRestoreFlag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-12-01  | Default* (false)    | No Swagger            |
| 2018-01-10  | Default* (false)    | No Swagger            |

### \$.properties.dedupState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-12-01  | Unknown             | No Swagger            |
| 2018-01-10  | Unknown             | No Swagger            |

### \$.properties.storageType

| API version | Detected noise type           | Determined noise type |
| ----------- | ----------------------------- | --------------------- |
| 2016-12-01  | Default* ("LocallyRedundant") | No Swagger            |
| 2018-01-10  | Default* ("LocallyRedundant") | No Swagger            |

### \$.properties.storageTypeState

| API version | Detected noise type   | Determined noise type |
| ----------- | --------------------- | --------------------- |
| 2016-12-01  | Default* ("Unlocked") | No Swagger            |
| 2018-01-10  | Default* ("Unlocked") | No Swagger            |

### \$.properties.xcoolState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-12-01  | Unknown             | No Swagger            |
| 2018-01-10  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-12-01  | Unknown             | No Swagger            |

## vaults/replicationFabrics/replicationNetworks/replicationNetworkMappings

![cleanliness](https://img.shields.io/badge/cleanliness-90.91%25%20(20%20/%2022)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties.fabricSpecificDetails

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-10  | Unknown             | Unknown               |

### \$.properties.recoveryFabricName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-10  | Unknown             | No Swagger            |

## vaults/replicationFabrics/replicationProtectionContainers/replicationMigrationItems

![cleanliness](https://img.shields.io/badge/cleanliness-92.48%25%20(123%20/%20133)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2010)-red)

### \$.properties.providerSpecificDetails.disksToInclude

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-10  | Unknown             | Unknown               |

### \$.properties.providerSpecificDetails.osType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.protectedDisks

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.resyncRequired

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.resyncState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.targetLocation

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.targetSubnetName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.targetVmSize

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.vmNics

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-10  | Unknown             | No Swagger            |

### \$.properties.recoveryServicesProviderId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-10  | Unknown             | No Swagger            |

## vaults/replicationFabrics/replicationProtectionContainers/replicationProtectionContainerMappings

![cleanliness](https://img.shields.io/badge/cleanliness-98.28%25%20(57%20/%2058)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties.providerSpecificInput

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-10  | Unknown             | Unknown               |

## vaults/replicationFabrics/replicationProtectionContainers

![cleanliness](https://img.shields.io/badge/cleanliness-90.91%25%20(10%20/%2011)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-10  | Unknown             | No Swagger            |

## vaults/replicationFabrics/replicationRecoveryServicesProviders

![cleanliness](https://img.shields.io/badge/cleanliness-97.70%25%20(85%20/%2087)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties.authenticationIdentityInput

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-10  | Unknown             | Unknown               |

### \$.properties.resourceAccessIdentityInput

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-10  | Unknown             | No Swagger            |

## vaults/replicationFabrics

![cleanliness](https://img.shields.io/badge/cleanliness-92.59%25%20(225%20/%20243)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2018)-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2018-01-10  | Unknown             | No Swagger            |

### \$.properties.customDetails

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-10  | Unknown             | No Swagger            |

### \$.properties.customDetails.containerIds

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-10  | Unknown             | No Swagger            |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.customDetails.controlPlaneUri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-10  | Unknown             | No Swagger            |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.customDetails.dataPlaneUri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-10  | Unknown             | No Swagger            |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.customDetails.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.customDetails.serviceContainerId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-10  | Unknown             | No Swagger            |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.customDetails.serviceEndpoint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-10  | Unknown             | No Swagger            |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.customDetails.serviceResourceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-10  | Unknown             | No Swagger            |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.customDetails.srsServiceEndpoint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-10  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

## vaults/replicationPolicies

![cleanliness](https://img.shields.io/badge/cleanliness-95.83%25%20(46%20/%2048)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-10  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-10  | Unknown             | No Swagger            |

## vaults

![cleanliness](https://img.shields.io/badge/cleanliness-55.17%25%20(16%20/%2029)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2013)-red)

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-10         | Unknown             | No Swagger            |
| 2016-06-01         | Unknown             | No Swagger            |
| 2016-12-01         | Unknown             | No Swagger            |
| 2018-01-10         | Unknown             | No Swagger            |
| 2018-07-10         | Unknown             | No Swagger            |
| 2019-06-15         | Unknown             | No Swagger            |
| 2020-02-02-preview | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2018-01-10  | Unknown             | No Swagger            |
| 2018-07-10  | Unknown             | No Swagger            |
| 2019-06-15  | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2018-01-10  | Unknown             | No Swagger            |

## vaults/replicationFabrics/replicationProtectionContainers/replicationProtectedItems

![cleanliness](https://img.shields.io/badge/cleanliness-78.68%25%20(299%20/%20380)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2081)-red)

### \$.properties.eventCorrelationId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.agentExpiryDate

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.agentVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.azureVmDiskDetails

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.azureVmGeneration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.datastores

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.discoveryType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.diskResized

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.diskType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.disksToInclude

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.encryption

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.firmwareType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.infrastructureVmId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.initialPrimaryFabricLocation

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.initialPrimaryZone

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.initialRecoveryFabricLocation

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.initialReplicationDetails

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.ipAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.isAgentUpdateRequired

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.isRebootAfterUpdateRequired

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.isReplicationAgentCertificateUpdateRequired

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Default* (false)    | No Swagger            |

### \$.properties.providerSpecificDetails.isReplicationAgentUpdateRequired

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Default (false)     | No Swagger            |

### \$.properties.providerSpecificDetails.lastHeartbeat

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.lastRpoCalculatedTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.lastUpdateReceivedTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.licenseType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.logStorageAccountId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.managementId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.multiVmGroupCreateOption

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.multiVmGroupId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.multiVmGroupName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.multiVmSyncStatus

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.oSDetails

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.osDiskId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.osType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.osVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.primaryAvailabilityZone

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.primaryFabricLocation

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.processServerName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.protectedDisks

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.protectedManagedDisks

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.protectionStage

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.recoveryAvailabilitySet

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.recoveryAvailabilitySetId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.recoveryAzureGeneration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.recoveryAzureLogStorageAccountId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.recoveryAzureNetworkId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.recoveryAzureResourceGroupId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.recoveryAzureStorageAccount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.recoveryAzureVMName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.recoveryAzureVMSize

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.recoveryAzureVmName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.recoveryContainerId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.recoveryFabricLocation

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.recoveryResourceGroupId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.replicaId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.resyncProgressPercentage

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Default (0)         | No Swagger            |

### \$.properties.providerSpecificDetails.rpoInSeconds

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.runAsAccountId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.sourceVmCpuCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.sourceVmRamSizeInMB

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.targetAvailabilitySetId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.targetAzureNetworkId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.targetAzureSubnetId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.targetAzureV2ResourceGroupId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.targetAzureVmName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.targetStorageAccountId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.targetVmId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.targetVmSize

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.tfoAzureVMName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.useManagedDisks

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.vCenterInfrastructureId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.validationErrors

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.vhdId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.vhdName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.vmEncryptionType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.vmId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.vmManagedDisks

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.vmProtectionState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.vmProtectionStateDescription

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |

### \$.properties.providerSpecificDetails.vmSyncedConfigDetails

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-10  | Unknown             | No Swagger            |
