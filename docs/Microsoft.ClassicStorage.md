# Microsoft.Classicstorage

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## storageaccounts/disks

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%205)-red)

### \$.properties.createdTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |

### \$.properties.diskSize

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Default* (31)       | No Swagger            |

### \$.properties.inUse

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Default* (false)    | No Swagger            |

### \$.properties.ioType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |

### \$.properties.storageAccount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |

## storageAccounts

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2024)-red)

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.accountType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-12-01  | Unknown             | No Swagger            |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.creationTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-12-01  | Unknown             | No Swagger            |
| 2016-04-01  | Unknown             | No Swagger            |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.endpoints

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-12-01  | Unknown             | No Swagger            |
| 2016-04-01  | Unknown             | No Swagger            |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.geoPrimaryRegion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-12-01  | Unknown             | No Swagger            |
| 2016-04-01  | Unknown             | No Swagger            |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.geoSecondaryRegion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-01  | Unknown             | No Swagger            |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.secondaryEndpoints

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-01  | Unknown             | No Swagger            |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.status

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-12-01  | Unknown             | No Swagger            |
| 2016-04-01  | Unknown             | No Swagger            |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.statusOfPrimaryRegion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-12-01  | Unknown             | No Swagger            |
| 2016-04-01  | Unknown             | No Swagger            |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.statusOfSecondaryRegion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-01  | Unknown             | No Swagger            |
| 2016-11-01  | Unknown             | No Swagger            |
