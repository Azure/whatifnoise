# Microsoft.Containerregistry

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## registries/pipelineruns

![cleanliness](https://img.shields.io/badge/cleanliness-90.91%25%20(30%20/%2033)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%203)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-01-preview | Unknown             | No Swagger            |

### \$.properties.request.pipelineResourceId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-01-preview | Unknown             | No Swagger            |

### \$.properties.response

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-01-preview | Unknown             | No Swagger            |

## registries/taskRuns

![cleanliness](https://img.shields.io/badge/cleanliness-93.10%25%20(108%20/%20116)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%208)-red)

### \$.identity

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.forceUpdateTag

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.runRequest.credentials.apiVersion

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.runRequest.credentials.customRegistries

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
| 2019-06-01-preview | Default* (true)     | No Swagger            |

### \$.properties.runRequest.noCache

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Default* (false)    | No Swagger            |

### \$.properties.runRequest.values[*].isSecret

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Default* (false)    | No Swagger            |

## registries/tokens

![cleanliness](https://img.shields.io/badge/cleanliness-94.74%25%20(18%20/%2019)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties.credentials

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |

## registries/webhooks

![cleanliness](https://img.shields.io/badge/cleanliness-44.44%25%20(4%20/%209)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%205)-red)

### \$.properties.serviceUri

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01         | Unknown             | Unknown               |
| 2019-12-01-preview | Unknown             | No Swagger            |

### \$.properties.status

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01         | Default ("enabled") | No Swagger            |
| 2019-12-01-preview | Default ("enabled") | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-01-preview | Unknown             | No Swagger            |

## registries

![cleanliness](https://img.shields.io/badge/cleanliness-73.33%25%20(44%20/%2060)-yellowgreen) ![progress](https://img.shields.io/badge/progress-11.11%25%20(2%20/%2018)-orange)

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |

### \$.properties.adminUserEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.dataEndpointEnabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-01-preview | Default (false)     | Default (false)       |

### \$.properties.dataEndpointHostNames

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-01-preview | Unknown             | Read-only             |

### \$.properties.encryption

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-01-preview | Unknown             | No Swagger            |

### \$.properties.encryption.status

| API version        | Detected noise type   | Determined noise type |
| ------------------ | --------------------- | --------------------- |
| 2019-12-01-preview | Default* ("disabled") | No Swagger            |

### \$.properties.networkRuleSet.ipRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |

### \$.properties.networkRuleSet.ipRules[*].description

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.networkRuleSet.ipRules[*].value

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

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01         | Unknown             | No Swagger            |
| 2019-12-01-preview | Unknown             | No Swagger            |

### \$.tags.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-10-01         | Unknown             | No Swagger            |
| 2019-05-01         | Unknown             | No Swagger            |
| 2019-12-01-preview | Unknown             | No Swagger            |
