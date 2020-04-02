# Microsoft.Resources

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## deploymentScripts

![15.38%25](https://img.shields.io/badge/15.38%25-%E2%98%85★%E2%98%86☆☆☆☆☆☆☆-orange)

### \$.properties.Arguments

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-10-01-preview | Unknown             | Unknown               |

### \$.properties.arguments

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-10-01-preview | Unknown             | Unknown               |

### \$.properties.cleanupPreference

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-10-01-preview | Unknown             | Unknown               |

### \$.properties.containerSettings

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-10-01-preview | Unknown             | Unknown               |

### \$.properties.containerSettings.restartPolicy

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-10-01-preview | Unknown             | No Swagger            |

### \$.properties.environmentVariables

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-10-01-preview | Unknown             | Unknown               |

### \$.properties.environmentVariables[*].SecureValue

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-10-01-preview | Unknown             | No Swagger            |

### \$.properties.environmentVariables[*].secureValue

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-10-01-preview | Unknown             | No Swagger            |

### \$.properties.forceUpdateTag

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-10-01-preview | Unknown             | Unknown               |

### \$.properties.outputs

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-10-01-preview | Unknown             | Read-only             |

### \$.properties.retentionInterval

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-10-01-preview | Unknown             | Unknown               |

### \$.properties.status

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-10-01-preview | Unknown             | Read-only             |

### \$.properties.timeout

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-10-01-preview | Unknown             | Unknown               |

## links

!> No Swagger.

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.sourceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-01-01  | Unknown             | No Swagger            |
| 2016-06-01  | Unknown             | No Swagger            |
| 2017-05-01  | Unknown             | No Swagger            |

### \$.properties.targetId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-01-01  | Unknown             | No Swagger            |
| 2016-06-01  | Unknown             | No Swagger            |
| 2017-05-01  | Unknown             | No Swagger            |

## subscriptions/resourcegroups

!> No Swagger.

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-05-01  | Unknown             | No Swagger            |
| 2019-05-01  | Unknown             | No Swagger            |
