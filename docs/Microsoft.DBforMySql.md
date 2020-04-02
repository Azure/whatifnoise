# Microsoft.DBforMySql

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## servers/configurations

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.isConfigPendingRestart

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.isDynamicConfig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

## servers/databases

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | Unknown               |

### \$.properties.apiVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.charset

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Unknown               |

### \$.properties.collation

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Unknown               |

### \$.properties.dependsOn

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

## servers/firewallrules

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |

## servers

![26.47%25](https://img.shields.io/badge/26.47%25-%E2%98%85★★%E2%98%86☆☆☆☆☆☆-orange)

### \$.properties.administratorLoginPassword

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

### \$.properties.byokEnforcement

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | Read-only             |
| 2017-12-01         | Unknown             | Read-only             |

### \$.properties.createMode

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | Unknown               |
| 2017-12-01         | Unknown             | Unknown               |

### \$.properties.infrastructureEncryption

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | Read-only             |
| 2017-12-01         | Unknown             | Read-only             |

### \$.properties.minimalTlsVersion

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | Unknown               |
| 2017-12-01         | Unknown             | Read-only             |

### \$.properties.previewFeature

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.publicNetworkAccess

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | Read-only             |
| 2017-12-01         | Unknown             | Read-only             |

### \$.properties.restorePointInTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

### \$.properties.sourceServerId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

### \$.properties.sslEnforcement

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Default ("Enabled") | Default ("Enabled")   |
| 2017-12-01         | Default ("Enabled") | Default ("Enabled")   |

### \$.properties.storageProfile

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | Unknown               |

### \$.properties.storageProfile.backupRetentionDays

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Default* (7)        | Unknown               |

### \$.properties.storageProfile.storageAutoGrow

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | Unknown               |

### \$.properties.storageProfile.storageAutogrow

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | Unknown               |
| 2017-12-01         | Unknown             | Unknown               |

### \$.properties.version

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | Unknown               |
| 2017-12-01         | Unknown             | Unknown               |

### \$.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | Unknown               |

### \$.sku.capacity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Default* (2)        | Unknown               |

### \$.sku.family

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Unknown               |

### \$.sku.size

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | Unknown               |
| 2017-12-01         | Unknown             | Unknown               |

### \$.sku.tier

| API version | Detected noise type         | Determined noise type |
| ----------- | --------------------------- | --------------------- |
| 2017-12-01  | Default* ("GeneralPurpose") | Unknown               |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-12-01-preview | Unknown             | Unknown               |
| 2017-12-01         | Unknown             | Unknown               |
