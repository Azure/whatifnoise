# Microsoft.ContainerRegistry

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## registries/taskRuns

![28.57%25](https://img.shields.io/badge/28.57%25-%E2%98%85★★%E2%98%86☆☆☆☆☆☆-orange)

### \$.identity

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | Unknown               |

### \$.properties.forceUpdateTag

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | Unknown               |

### \$.properties.runRequest.credentials.apiVersion

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.runRequest.credentials.customRegistries.acrcieus2euapdeployment.azurecr.io

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.runRequest.isArchiveEnabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Default* (true)     | Default (false)       |

### \$.properties.runRequest.noCache

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Default* (false)    | Default (false)       |

### \$.properties.runRequest.values[*].isSecret

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Default* (false)    | No Swagger            |

## registries/tokens

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.credentials

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | Unknown               |

## registries/webhooks

![50.00%25](https://img.shields.io/badge/50.00%25-%E2%98%85★★★★%E2%98%86☆☆☆☆-yellow)

### \$.properties.serviceUri

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01         | Unknown             | Unknown               |
| 2019-12-01-preview | Unknown             | Unknown               |

### \$.properties.status

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01         | Default ("enabled") | Default ("enabled")   |
| 2019-12-01-preview | Default ("enabled") | Default ("enabled")   |

## registries

![21.43%25](https://img.shields.io/badge/21.43%25-%E2%98%85★%E2%98%86☆☆☆☆☆☆☆-orange)

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |

### \$.properties.adminUserEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | Default (false)       |
| 2019-05-01  | Unknown             | Default (false)       |

### \$.properties.dataEndpointEnabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-01-preview | Default* (false)    | Unknown               |

### \$.properties.dataEndpointHostNames

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-01-preview | Unknown             | Read-only             |

### \$.properties.encryption

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-01-preview | Unknown             | Unknown               |

### \$.properties.encryption.status

| API version        | Detected noise type   | Determined noise type |
| ------------------ | --------------------- | --------------------- |
| 2019-12-01-preview | Default* ("disabled") | Unknown               |

### \$.properties.networkRuleSet.ipRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | Unknown               |

### \$.properties.networkRuleSet.ipRules[*].description

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.networkRuleSet.virtualNetworkRules[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.publicNetworkAccess

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-01-preview | Unknown             | No Swagger            |

### \$.properties.supportsHttpsTrafficOnly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Unknown               |
