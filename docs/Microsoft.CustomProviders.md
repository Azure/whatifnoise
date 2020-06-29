# Microsoft.CustomProviders

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## associations

![cleanliness](https://img.shields.io/badge/cleanliness-0.00%25%20(0%20/%203)-red) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%203)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-01-preview | Unknown             | No Swagger            |

### \$.properties.myDynamicProperty

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-01-preview | Unknown             | No Swagger            |

### \$.properties.targetResourceId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-01-preview | Unknown             | No Swagger            |

## resourceProviders/consulClusters

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%209)-red)

### \$.properties.blobContainerName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-01-preview | Unknown             | No Swagger            |

### \$.properties.consulCaFile

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-01-preview | Unknown             | No Swagger            |

### \$.properties.consulClusterId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-01-preview | Unknown             | No Swagger            |

### \$.properties.consulClusterMode

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-01-preview | Unknown             | No Swagger            |

### \$.properties.consulConfigFile

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-01-preview | Unknown             | No Swagger            |

### \$.properties.consulExternalEndpointUrl

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-01-preview | Unknown             | No Swagger            |

### \$.properties.consulPrivateEndpointUrl

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-01-preview | Unknown             | No Swagger            |

### \$.properties.state

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-01-preview | Unknown             | No Swagger            |

### \$.properties.storageAccountName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-01-preview | Unknown             | No Swagger            |

## resourceProviders

![cleanliness](https://img.shields.io/badge/cleanliness-78.57%25%20(11%20/%2014)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%203)-red)

### \$.properties.actions[*].endpoint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-01-preview | Unknown             | No Swagger            |

### \$.properties.resourceTypes[*].endpoint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-01-preview | Unknown             | No Swagger            |

### \$.properties.resourceTypes[*].routingType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-01-preview | Unknown             | No Swagger            |
