# Microsoft.DataLakeStore

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

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-10-01-preview | Unknown             | No Swagger            |
| 2016-11-01         | Unknown             | Unknown               |

### \$.properties.dataLakePerformanceTierState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.encryptionConfig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | Unknown               |

### \$.properties.encryptionState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | Unknown               |

### \$.properties.firewallAllowAzureIps

| API version | Detected noise type   | Determined noise type |
| ----------- | --------------------- | --------------------- |
| 2016-11-01  | Default* ("Disabled") | Unknown               |

### \$.properties.firewallAllowDataLakeAnalytics

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.firewallState

| API version | Detected noise type   | Determined noise type |
| ----------- | --------------------- | --------------------- |
| 2016-11-01  | Default* ("Disabled") | Unknown               |

### \$.properties.initialUser

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.newTier

| API version | Detected noise type      | Determined noise type |
| ----------- | ------------------------ | --------------------- |
| 2016-11-01  | Default* ("Consumption") | Unknown               |

### \$.properties.trustedIdProviderState

| API version | Detected noise type   | Determined noise type |
| ----------- | --------------------- | --------------------- |
| 2016-11-01  | Default* ("Disabled") | Unknown               |

### \$.properties.virtualNetworkRules[*].properties.state

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | Unknown               |
