# Microsoft.Batch

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## batchAccounts/certificates

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.data

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |

### \$.properties.password

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |

### \$.properties.thumbprint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |

### \$.properties.thumbprintAlgorithm

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |

## batchAccounts/pools

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.deploymentConfiguration.cloudServiceConfiguration.currentOSVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | Unknown               |

### \$.properties.deploymentConfiguration.cloudServiceConfiguration.targetOSVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | Unknown               |

### \$.properties.displayName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.interNodeCommunication

| API version | Detected noise type   | Determined noise type |
| ----------- | --------------------- | --------------------- |
| 2019-04-01  | Default* ("Disabled") | Unknown               |
| 2019-08-01  | Default* ("Disabled") | Unknown               |

### \$.properties.maxTasksPerNode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Default* (1)        | Unknown               |
| 2018-12-01  | Default* (1)        | Unknown               |
| 2019-04-01  | Default* (1)        | Unknown               |

### \$.properties.scaleSettings.fixedScale.resizeTimeout

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |

### \$.properties.scaleSettings.fixedScale.targetLowPriorityNodes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Default* (0)        | Unknown               |
| 2019-04-01  | Default* (0)        | Unknown               |

### \$.properties.taskSchedulingPolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.vmSize

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-12-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

## batchAccounts

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Unknown               |

### \$.properties.poolAllocationMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-05-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Unknown               |
