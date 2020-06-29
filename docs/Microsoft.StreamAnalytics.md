# Microsoft.StreamAnalytics

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## streamingjobs/inputs

![cleanliness](https://img.shields.io/badge/cleanliness-50.00%25%20(5%20/%2010)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%205)-red)

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

![cleanliness](https://img.shields.io/badge/cleanliness-45.45%25%20(5%20/%2011)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%206)-red)

### \$.properties.datasource.properties.accountKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.datasource.properties.consumerGroupName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-01-preview | Unknown             | No Swagger            |

### \$.properties.datasource.properties.sharedAccessPolicyKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-01-preview | Unknown             | No Swagger            |

### \$.properties.serialization.properties.format

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-03-01         | Unknown             | No Swagger            |
| 2017-04-01-preview | Unknown             | No Swagger            |

### \$.properties.type

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-01-preview | Unknown             | No Swagger            |

## streamingjobs

![cleanliness](https://img.shields.io/badge/cleanliness-32.26%25%20(20%20/%2062)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2042)-red)

### \$.identity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.compatibilityLevel

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.contentStoragePolicy

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-04-01         | Unknown             | No Swagger            |
| 2016-03-01         | Unknown             | No Swagger            |
| 2017-04-01-preview | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |

### \$.properties.dataLocale

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-03-01         | Unknown             | No Swagger            |
| 2017-04-01-preview | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |

### \$.properties.eventsLateArrivalMaxDelayInSeconds

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-03-01         | Default* (5)        | No Swagger            |
| 2017-04-01-preview | Default* (5)        | No Swagger            |

### \$.properties.externals.storageAccount.accountKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-01-preview | Unknown             | No Swagger            |

### \$.properties.functions

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-03-01         | Unknown             | No Swagger            |
| 2017-04-01-preview | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |

### \$.properties.inputs

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-04-01         | Unknown             | No Swagger            |
| 2016-03-01         | Unknown             | No Swagger            |
| 2017-04-01-preview | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |

### \$.properties.jobStorageAccount.accountKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-01-preview | Unknown             | No Swagger            |

### \$.properties.jobStorageAccount.authenticationMode

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
| 2015-04-01  | Default* ("Stop")   | No Swagger            |
| 2016-03-01  | Default* ("Stop")   | No Swagger            |

### \$.properties.outputStartTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-03-01         | Unknown             | No Swagger            |
| 2017-04-01-preview | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |

### \$.properties.outputs

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-04-01         | Unknown             | No Swagger            |
| 2016-03-01         | Unknown             | No Swagger            |
| 2017-04-01-preview | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |

### \$.properties.resources

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-01-preview | Unknown             | No Swagger            |

### \$.properties.transformation

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-04-01         | Unknown             | No Swagger            |
| 2016-03-01         | Unknown             | No Swagger            |
| 2017-04-01-preview | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-03-01         | Unknown             | No Swagger            |
| 2017-04-01-preview | Unknown             | No Swagger            |
