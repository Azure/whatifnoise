# Microsoft.Datalakeanalytics

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## accounts/storageaccounts

![cleanliness](https://img.shields.io/badge/cleanliness-66.67%25%20(2%20/%203)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties.suffix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | Unknown               |

## accounts

![cleanliness](https://img.shields.io/badge/cleanliness-65.31%25%20(32%20/%2049)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2017)-red)

### \$.properties.dataLakeStoreAccounts[*].properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.debugDataAccessLevel

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.firewallAllowAzureIps

| API version | Detected noise type   | Determined noise type |
| ----------- | --------------------- | --------------------- |
| 2016-11-01  | Default* ("Disabled") | No Swagger            |

### \$.properties.firewallRules[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.firewallRules[*].properties.endIpAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.firewallRules[*].properties.startIpAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.firewallState

| API version | Detected noise type   | Determined noise type |
| ----------- | --------------------- | --------------------- |
| 2016-11-01  | Default* ("Disabled") | No Swagger            |

### \$.properties.maxDegreeOfParallelism

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.maxDegreeOfParallelismPerJob

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.maxJobCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.minPriorityPerJob

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Default (1)         | No Swagger            |

### \$.properties.newTier

| API version | Detected noise type      | Determined noise type |
| ----------- | ------------------------ | --------------------- |
| 2016-11-01  | Default* ("Consumption") | No Swagger            |

### \$.properties.publicDataLakeStoreAccounts

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.queryStoreRetention

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Default* (30)       | No Swagger            |

### \$.properties.storageAccounts

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.storageAccounts[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.storageAccounts[*].properties.suffix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |
