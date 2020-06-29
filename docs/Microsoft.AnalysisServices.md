# Microsoft.AnalysisServices

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## servers

![cleanliness](https://img.shields.io/badge/cleanliness-9.09%25%20(2%20/%2022)-red) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2020)-red)

### \$.properties.asAdministrators.members[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | No Swagger            |

### \$.properties.backupBlobContainerUri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | No Swagger            |

### \$.properties.gatewayDetails

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | No Swagger            |

### \$.properties.ipV4FirewallSettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | No Swagger            |

### \$.properties.ipV4FirewallSettings.firewallRules[*].firewallRuleName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | No Swagger            |

### \$.properties.ipV4FirewallSettings.firewallRules[*].rangeEnd

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | No Swagger            |

### \$.properties.ipV4FirewallSettings.firewallRules[*].rangeStart

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | No Swagger            |

### \$.properties.manageMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | No Swagger            |

### \$.properties.managedMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-05-16  | Default (1)         | No Swagger            |
| 2017-07-14  | Default (1)         | No Swagger            |
| 2017-08-01  | Default (1)         | No Swagger            |

### \$.properties.resources

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | No Swagger            |

### \$.properties.serverMonitorMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-05-16  | Default (1)         | No Swagger            |
| 2017-07-14  | Default (1)         | No Swagger            |
| 2017-08-01  | Default (1)         | No Swagger            |

### \$.sku.capacity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Default* (1)        | No Swagger            |

### \$.sku.tier

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-05-16  | Unknown             | No Swagger            |
| 2017-08-01  | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | No Swagger            |
