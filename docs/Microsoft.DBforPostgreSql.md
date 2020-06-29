# Microsoft.DBforPostgreSql

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## serverGroups

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties.Mode

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |

### \$.properties.mode

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |

## servers/configurations

![cleanliness](https://img.shields.io/badge/cleanliness-0.00%25%20(0%20/%207)-red) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%207)-red)

### \$.properties.isConfigPendingRestart

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

### \$.properties.isDynamicConfig

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

### \$.properties.source

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

## servers/databases

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%206)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

### \$.properties.charset

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

## servers/firewallRules

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%205)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.endIpAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.startIpAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

## servers/securityAlertPolicies

![cleanliness](https://img.shields.io/badge/cleanliness-50.00%25%20(4%20/%208)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%204)-red)

### \$.properties.creationTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.disabledAlerts

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.retentionDays

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Default* (0)        | No Swagger            |

### \$.properties.storageAccountAccessKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

## servers/virtualNetworkRules

![cleanliness](https://img.shields.io/badge/cleanliness-25.00%25%20(1%20/%204)-orange) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%203)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.ignoreMissingVnetServiceEndpoint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Default* (false)    | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

## servers

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2043)-red)

### \$.properties.administratorLoginPassword

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

### \$.properties.byokEnforcement

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

### \$.properties.createMode

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

### \$.properties.infrastructureEncryption

| API version | Detected noise type   | Determined noise type |
| ----------- | --------------------- | --------------------- |
| 2017-12-01  | Default* ("Disabled") | No Swagger            |

### \$.properties.minimalTlsVersion

| API version        | Detected noise type                | Determined noise type |
| ------------------ | ---------------------------------- | --------------------- |
| 2017-12-01-preview | Default ("TLSEnforcementDisabled") | No Swagger            |
| 2017-12-01         | Default ("TLSEnforcementDisabled") | No Swagger            |

### \$.properties.minimumTlsVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.mode

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |

### \$.properties.previewFeature

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |

### \$.properties.publicNetworkAccess

| API version | Detected noise type  | Determined noise type |
| ----------- | -------------------- | --------------------- |
| 2017-12-01  | Default* ("Enabled") | No Swagger            |

### \$.properties.restorePointInTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |

### \$.properties.sourceServerId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

### \$.properties.sslEnforcement

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

### \$.properties.storageMB

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.storageProfile

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

### \$.properties.storageProfile.backupRetentionDays

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Default* (7)        | No Swagger            |
| 2017-12-01         | Default* (7)        | No Swagger            |

### \$.properties.storageProfile.geoRedundantBackup

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

### \$.properties.storageProfile.storageAutoGrow

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

### \$.properties.storageProfile.storageAutogrow

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

### \$.properties.version

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |

### \$.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |

### \$.sku.capacity

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

### \$.sku.family

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

### \$.sku.size

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

### \$.sku.tier

| API version        | Detected noise type         | Determined noise type |
| ------------------ | --------------------------- | --------------------- |
| 2017-12-01-preview | Default* ("GeneralPurpose") | No Swagger            |
| 2017-12-01         | Default* ("GeneralPurpose") | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

### \$.tags.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

## serversv2/firewallRules

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties.endIpAddress

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |

### \$.properties.startIpAddress

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |

## serversv2

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2012)-red)

### \$.properties.Role

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |

### \$.properties.VCores

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |

### \$.properties.administratorLoginPassword

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |

### \$.properties.displayName

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |

### \$.properties.fullyQualifiedDomainName

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |

### \$.properties.publicIpAddressRequested

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |

### \$.properties.role

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |

### \$.properties.standbyCount

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Default (0)         | No Swagger            |

### \$.properties.userVisibleHAState

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |

### \$.properties.userVisibleState

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |

### \$.properties.vCores

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Default* (4)        | No Swagger            |

### \$.sku

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-03-29-privatepreview | Unknown             | No Swagger            |

## singleservers

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2016)-red)

### \$.properties.administratorLogin

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2020-02-14-privatepreview | Unknown             | No Swagger            |

### \$.properties.backupRetentionDays

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2020-02-14-privatepreview | Default* (35)       | No Swagger            |

### \$.properties.createMode

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2020-02-14-privatepreview | Unknown             | No Swagger            |

### \$.properties.displayName

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2020-02-14-privatepreview | Unknown             | No Swagger            |

### \$.properties.fullyQualifiedDomainName

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2020-02-14-privatepreview | Unknown             | No Swagger            |

### \$.properties.logBackupStorageSku

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2020-02-14-privatepreview | Unknown             | No Swagger            |

### \$.properties.pointInTimeUTC

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2020-02-14-privatepreview | Unknown             | No Swagger            |

### \$.properties.publicIpAddressRequested

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2020-02-14-privatepreview | Default* (true)     | No Swagger            |

### \$.properties.serverEdition

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2020-02-14-privatepreview | Unknown             | No Swagger            |

### \$.properties.sourceServerName

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2020-02-14-privatepreview | Unknown             | No Swagger            |

### \$.properties.standbyCount

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2020-02-14-privatepreview | Default* (0)        | No Swagger            |

### \$.properties.storageQuotaInMb

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2020-02-14-privatepreview | Default* (32768)    | No Swagger            |

### \$.properties.userVisibleHAState

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2020-02-14-privatepreview | Unknown             | No Swagger            |

### \$.properties.userVisibleState

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2020-02-14-privatepreview | Unknown             | No Swagger            |

### \$.properties.vCores

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2020-02-14-privatepreview | Default* (4)        | No Swagger            |

### \$.properties.version

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2020-02-14-privatepreview | Unknown             | No Swagger            |
