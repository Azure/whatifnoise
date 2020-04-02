# Microsoft.StreamAnalytics

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## streamingjobs/inputs

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.datasource.properties.authenticationMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.datasource.properties.password

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.datasource.properties.sharedAccessPolicyKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.datasource.properties.storageAccounts[*].accountKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

## streamingjobs/outputs

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.datasource.properties.accountKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.datasource.properties.sharedAccessPolicyKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-01-preview | Unknown             | No Swagger            |

## streamingjobs

![3.45%25](https://img.shields.io/badge/3.45%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.compatibilityLevel

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Default (1)         | Default (1)           |
| 2019-06-01  | Default (1)         | No Swagger            |

### \$.properties.contentStoragePolicy

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-03-01         | Unknown             | No Swagger            |
| 2017-04-01-preview | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |

### \$.properties.dataLocale

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-03-01         | Unknown             | Unknown               |
| 2017-04-01-preview | Unknown             | No Swagger            |

### \$.properties.eventsLateArrivalMaxDelayInSeconds

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-03-01         | Default* (5)        | Unknown               |
| 2017-04-01-preview | Default* (5)        | No Swagger            |

### \$.properties.functions

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-03-01         | Unknown             | Unknown               |
| 2017-04-01-preview | Unknown             | No Swagger            |

### \$.properties.inputs

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-03-01         | Unknown             | Unknown               |
| 2017-04-01-preview | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |

### \$.properties.jobStorageAccount.accountKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-01-preview | Unknown             | No Swagger            |

### \$.properties.jobType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-03-01         | Unknown             | No Swagger            |
| 2017-04-01-preview | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |

### \$.properties.outputErrorPolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Default* ("Stop")   | Unknown               |

### \$.properties.outputStartTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-03-01         | Unknown             | Unknown               |
| 2017-04-01-preview | Unknown             | No Swagger            |

### \$.properties.outputs

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-03-01         | Unknown             | Unknown               |
| 2017-04-01-preview | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |

### \$.properties.transformation

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-03-01         | Unknown             | Unknown               |
| 2017-04-01-preview | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-03-01         | Unknown             | Unknown               |
| 2017-04-01-preview | Unknown             | No Swagger            |
