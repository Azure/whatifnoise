# Microsoft.DataLakeAnalytics

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## accounts

![23.08%25](https://img.shields.io/badge/23.08%25-%E2%98%85★%E2%98%86☆☆☆☆☆☆☆-orange)

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
| 2016-11-01  | Default* ("Disabled") | Unknown               |

### \$.properties.firewallState

| API version | Detected noise type   | Determined noise type |
| ----------- | --------------------- | --------------------- |
| 2016-11-01  | Default* ("Disabled") | Unknown               |

### \$.properties.maxDegreeOfParallelism

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | Default (30)          |

### \$.properties.maxDegreeOfParallelismPerJob

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | Unknown               |

### \$.properties.maxJobCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Default* (20)       | Default (3)           |

### \$.properties.minPriorityPerJob

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Default* (1)        | Unknown               |

### \$.properties.newTier

| API version | Detected noise type      | Determined noise type |
| ----------- | ------------------------ | --------------------- |
| 2016-11-01  | Default* ("Consumption") | Unknown               |

### \$.properties.publicDataLakeStoreAccounts

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.queryStoreRetention

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Default* (30)       | Default (30)          |

### \$.properties.storageAccounts[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.storageAccounts[*].properties.suffix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |
