# Microsoft.Dbformariadb

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## servers/firewallrules

![cleanliness](https://img.shields.io/badge/cleanliness-0.00%25%20(0%20/%203)-red) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%203)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.endIpAddress

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.startIpAddress

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

## servers

![cleanliness](https://img.shields.io/badge/cleanliness-41.67%25%20(15%20/%2036)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2021)-red)

### \$.properties.administratorLoginPassword

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.byokEnforcement

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |

### \$.properties.createMode

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.infrastructureEncryption

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |

### \$.properties.minimalTlsVersion

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |

### \$.properties.publicNetworkAccess

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |

### \$.properties.restorePointInTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.sourceServerId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.sslEnforcement

| API version        | Detected noise type  | Determined noise type |
| ------------------ | -------------------- | --------------------- |
| 2018-06-01-preview | Default* ("Enabled") | No Swagger            |

### \$.properties.storageProfile

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.storageProfile.storageAutogrow

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.version

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Default* (10.2)     | No Swagger            |

### \$.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.sku.capacity

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Default* (2)        | No Swagger            |

### \$.sku.family

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.sku.size

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.sku.tier

| API version        | Detected noise type         | Determined noise type |
| ------------------ | --------------------------- | --------------------- |
| 2018-06-01-preview | Default* ("GeneralPurpose") | No Swagger            |
