# Microsoft.OffAzure

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## hyperVSites/hosts

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.createdTimestamp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-06  | Unknown             | No Swagger            |

### \$.properties.updatedTimestamp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-06  | Unknown             | No Swagger            |

### \$.properties.version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-06  | Unknown             | No Swagger            |

## hyperVSites

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.agentDetails.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-06  | Unknown             | No Swagger            |

### \$.properties.serviceEndpoint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-06  | Unknown             | No Swagger            |

## serverSites/machines

!> No Swagger.

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.OperatingSystemDetails

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |

### \$.properties.biosGuid

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |

### \$.properties.biosSerialNumber

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |

### \$.properties.createdTimestamp

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |

### \$.properties.disks

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |

### \$.properties.displayName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |

### \$.properties.firmware

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |

### \$.properties.hydratedFqdn

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |

### \$.properties.isDeleted

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Default* (false)    | No Swagger            |

### \$.properties.networkAdapters

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |

### \$.properties.numberOfProcessorCore

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Default* (1)        | No Swagger            |

### \$.properties.operatingSystemDetails

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |

### \$.properties.updatedTimestamp

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |

## vMwareSites/vcenters

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.createdTimestamp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-06  | Unknown             | No Swagger            |

### \$.properties.instanceUuid

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-06  | Unknown             | No Swagger            |

### \$.properties.perfStatisticsLevel

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-06  | Unknown             | No Swagger            |

### \$.properties.updatedTimestamp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-06  | Unknown             | No Swagger            |

### \$.properties.version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-06  | Unknown             | No Swagger            |

## vMwareSites

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.agentDetails.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-06  | Unknown             | No Swagger            |

### \$.properties.serviceEndpoint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-06  | Unknown             | No Swagger            |

## importsites

!> No Swagger.

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.serviceEndpoint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |

## serversites

!> No Swagger.

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.agentDetails.id

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |

### \$.properties.serviceEndpoint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |
