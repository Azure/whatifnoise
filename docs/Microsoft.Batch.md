# Microsoft.Batch

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## batchaccounts/applications

![cleanliness](https://img.shields.io/badge/cleanliness-60.00%25%20(3%20/%205)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties.allowUpdates

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Default* (true)     | Unknown               |

### \$.properties.defaultVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

## batchAccounts/certificates

![cleanliness](https://img.shields.io/badge/cleanliness-65.00%25%20(13%20/%2020)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%207)-red)

### \$.properties.data

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.password

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.thumbprint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.thumbprintAlgorithm

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |

## batchAccounts/pools

![cleanliness](https://img.shields.io/badge/cleanliness-84.21%25%20(144%20/%20171)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2027)-red)

### \$.properties.certificates[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.deploymentConfiguration.cloudServiceConfiguration.currentOSVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | Unknown               |

### \$.properties.deploymentConfiguration.cloudServiceConfiguration.targetOSVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |

### \$.properties.displayName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.interNodeCommunication

| API version | Detected noise type   | Determined noise type |
| ----------- | --------------------- | --------------------- |
| 2017-09-01  | Default* ("Disabled") | No Swagger            |
| 2019-04-01  | Default* ("Disabled") | No Swagger            |
| 2019-08-01  | Default* ("Disabled") | No Swagger            |

### \$.properties.maxTasksPerNode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Default* (1)        | No Swagger            |
| 2018-12-01  | Default* (1)        | No Swagger            |
| 2019-04-01  | Default* (1)        | No Swagger            |

### \$.properties.networkConfiguration.publicIPs[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.scaleSettings.fixedScale.resizeTimeout

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.scaleSettings.fixedScale.targetLowPriorityNodes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Default* (0)        | No Swagger            |
| 2019-04-01  | Default* (0)        | No Swagger            |

### \$.properties.startTask.maxTaskRetryCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Default* (0)        | No Swagger            |
| 2019-08-01  | Default* (0)        | No Swagger            |

### \$.properties.startTask.waitForSuccess

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Default* (true)     | No Swagger            |

### \$.properties.taskSchedulingPolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.vmSize

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

## batchAccounts

![cleanliness](https://img.shields.io/badge/cleanliness-80.49%25%20(33%20/%2041)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%208)-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.encryption

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-03-01  | Unknown             | No Swagger            |
| 2020-05-01  | Unknown             | No Swagger            |

### \$.properties.poolAllocationMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-05-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-12-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
