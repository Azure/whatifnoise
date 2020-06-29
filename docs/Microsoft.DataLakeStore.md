# Microsoft.Datalakestore

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## accounts/firewallrules

![cleanliness](https://img.shields.io/badge/cleanliness-33.33%25%20(1%20/%203)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

## accounts

![cleanliness](https://img.shields.io/badge/cleanliness-61.36%25%20(27%20/%2044)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2017)-red)

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-10-01-preview | Unknown             | No Swagger            |
| 2016-11-01         | Unknown             | No Swagger            |

### \$.properties.dataLakePerformanceTierState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.encryptionConfig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.encryptionState

| API version | Detected noise type  | Determined noise type |
| ----------- | -------------------- | --------------------- |
| 2016-11-01  | Default* ("Enabled") | No Swagger            |

### \$.properties.firewallAllowAzureIps

| API version | Detected noise type  | Determined noise type |
| ----------- | -------------------- | --------------------- |
| 2016-11-01  | Default ("Disabled") | No Swagger            |

### \$.properties.firewallAllowDataLakeAnalytics

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.firewallRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

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

### \$.properties.initialUser

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.newTier

| API version | Detected noise type      | Determined noise type |
| ----------- | ------------------------ | --------------------- |
| 2016-11-01  | Default* ("Consumption") | No Swagger            |

### \$.properties.trustedIdProviderState

| API version | Detected noise type  | Determined noise type |
| ----------- | -------------------- | --------------------- |
| 2016-11-01  | Default ("Disabled") | No Swagger            |

### \$.properties.virtualNetworkRules[*].properties.state

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |
