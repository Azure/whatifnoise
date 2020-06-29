# Microsoft.OffAzure

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## hyperVSites/hosts

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%203)-red)

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

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

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

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2018)-red)

### \$.properties.OperatingSystemDetails

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |

### \$.properties.allocatedMemoryInMB

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
| 2019-05-01-preview | Unknown             | No Swagger            |

### \$.properties.operatingSystemDetails

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |

### \$.properties.operatingSystemDetails.osArchitecture

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |

### \$.properties.operatingSystemDetails.osName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |

### \$.properties.operatingSystemDetails.osType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |

### \$.properties.operatingSystemDetails.osVersion

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |

### \$.properties.updatedTimestamp

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |

## vMwareSites/vcenters

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%205)-red)

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

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

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

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties.serviceEndpoint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |

## serversites

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties.agentDetails.id

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |

### \$.properties.serviceEndpoint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |
