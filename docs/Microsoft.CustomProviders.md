# Microsoft.CustomProviders

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## associations

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

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
| 2018-09-01-preview | Unknown             | Unknown               |

## resourceProviders/consulClusters

!> No Swagger.

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.blobContainerName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-01-preview | Unknown             | No Swagger            |

### \$.properties.consulCaFile

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

### \$.properties.state

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-01-preview | Unknown             | No Swagger            |

### \$.properties.storageAccountName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-01-preview | Unknown             | No Swagger            |

## resourceProviders

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.actions[*].endpoint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-01-preview | Unknown             | No Swagger            |

### \$.properties.resourceTypes[*].endpoint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-01-preview | Unknown             | No Swagger            |

### \$.properties.resourceTypes[*].routingType

| API version        | Detected noise type                    | Determined noise type |
| ------------------ | -------------------------------------- | --------------------- |
| 2018-09-01-preview | Default* ("Extension, Cache, Webhook") | No Swagger            |
