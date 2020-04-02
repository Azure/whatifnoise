# Microsoft.AnalysisServices

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## servers

![6.25%25](https://img.shields.io/badge/6.25%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-red)

### \$.properties.asAdministrators.members[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-05-16  | Unknown             | No Swagger            |
| 2017-08-01  | Unknown             | No Swagger            |

### \$.properties.backupBlobContainerUri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | Unknown               |

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

### \$.properties.managedMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-05-16  | Default* (1)        | No Swagger            |
| 2017-07-14  | Default* (1)        | No Swagger            |
| 2017-08-01  | Default* (1)        | No Swagger            |

### \$.properties.serverMonitorMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-05-16  | Default (1)         | No Swagger            |
| 2017-07-14  | Default (1)         | No Swagger            |
| 2017-08-01  | Default (1)         | No Swagger            |

### \$.sku.capacity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Default* (1)        | Default (1)           |

### \$.sku.tier

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-05-16  | Unknown             | Unknown               |
| 2017-08-01  | Unknown             | Unknown               |
