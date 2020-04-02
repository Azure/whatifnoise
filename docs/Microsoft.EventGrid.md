# Microsoft.EventGrid

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## domains/topics

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

## domains

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.publicNetworkAccess

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2020-04-01-preview | Unknown             | Unknown               |

### \$.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2020-04-01-preview | Unknown             | Unknown               |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2020-01-01-preview | Unknown             | Unknown               |

## eventSubscriptions

![20.00%25](https://img.shields.io/badge/20.00%25-%E2%98%85★%E2%98%86☆☆☆☆☆☆☆-orange)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-05-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |
| 2020-01-01-preview | Unknown             | No Swagger            |
| 2020-04-01-preview | Unknown             | No Swagger            |

### \$.properties.deadLetterDestination

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |

### \$.properties.destination.properties.endpointBaseUrl

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | Read-only             |
| 2018-05-01-preview | Unknown             | Read-only             |
| 2018-09-15-preview | Unknown             | Read-only             |
| 2019-01-01         | Unknown             | Read-only             |
| 2019-06-01         | Unknown             | Read-only             |
| 2020-04-01-preview | Unknown             | Read-only             |

### \$.properties.destination.properties.endpointUrl

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | Unknown               |
| 2018-05-01-preview | Unknown             | Unknown               |
| 2018-09-15-preview | Unknown             | Unknown               |
| 2019-01-01         | Unknown             | Unknown               |
| 2019-06-01         | Unknown             | Unknown               |
| 2020-04-01-preview | Unknown             | Unknown               |

### \$.properties.destination.properties.maxEventsPerBatch

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2020-01-01-preview | Default* (1)        | Unknown               |
| 2020-04-01-preview | Default* (1)        | Unknown               |

### \$.properties.destination.properties.preferredBatchSizeInKilobytes

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2020-01-01-preview | Default* (64)       | Unknown               |
| 2020-04-01-preview | Default* (64)       | Unknown               |

### \$.properties.destination.properties.topic

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.eventDeliverySchema

| API version        | Detected noise type          | Determined noise type |
| ------------------ | ---------------------------- | --------------------- |
| 2018-09-15-preview | Default* ("EventGridSchema") | Unknown               |
| 2020-01-01-preview | Default* ("EventGridSchema") | Unknown               |
| 2020-04-01-preview | Default* ("EventGridSchema") | Unknown               |

### \$.properties.filter

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | Unknown               |
| 2018-05-01-preview | Unknown             | Unknown               |
| 2018-09-15-preview | Unknown             | Unknown               |
| 2019-06-01         | Unknown             | Unknown               |

### \$.properties.filter.advancedFilters

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.filter.eventDeliverySchema

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.filter.includedEventTypes

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | Unknown               |
| 2018-05-01-preview | Unknown             | Unknown               |
| 2019-01-01         | Unknown             | Unknown               |

### \$.properties.filter.includedEventTypes[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |

### \$.properties.filter.isSubjectCaseSensitive

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | Default (false)       |
| 2018-05-01-preview | Unknown             | Default (false)       |
| 2019-01-01         | Unknown             | Default (false)       |
| 2019-06-01         | Unknown             | Default (false)       |
| 2020-01-01-preview | Unknown             | Default (false)       |

### \$.properties.retryPolicy

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-05-01-preview | Unknown             | Unknown               |
| 2018-09-15-preview | Unknown             | Unknown               |
| 2019-01-01         | Unknown             | Unknown               |
| 2019-06-01         | Unknown             | Unknown               |
| 2020-01-01-preview | Unknown             | Unknown               |
| 2020-04-01-preview | Unknown             | Unknown               |

### \$.properties.retryPolicy.eventTimeToLiveInMinutes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Default* (1440)     | Unknown               |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-05-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |

## topics

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | Unknown               |

### \$.properties.publicNetworkAccess

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2020-04-01-preview | Unknown             | Unknown               |

### \$.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2020-04-01-preview | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | Unknown               |
