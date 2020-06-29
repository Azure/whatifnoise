# Microsoft.EventGrid

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## domains/topics

![cleanliness](https://img.shields.io/badge/cleanliness-0.00%25%20(0%20/%202)-red) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

## domains

![cleanliness](https://img.shields.io/badge/cleanliness-91.84%25%20(45%20/%2049)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%204)-red)

### \$.properties.privateEndpointConnections

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2020-04-01-preview | Unknown             | No Swagger            |

### \$.properties.publicNetworkAccess

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2020-04-01-preview | Unknown             | No Swagger            |

### \$.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2020-04-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2020-01-01-preview | Unknown             | No Swagger            |

## eventSubscriptions

![cleanliness](https://img.shields.io/badge/cleanliness-23.19%25%20(16%20/%2069)-orange) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2053)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |
| 2020-01-01-preview | Unknown             | No Swagger            |
| 2020-04-01-preview | Unknown             | No Swagger            |

### \$.properties.deadLetterDestination

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |

### \$.properties.deadletterdestination

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |

### \$.properties.destination.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.destination.properties.endpointBaseUrl

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-05-01-preview | Unknown             | No Swagger            |
| 2018-09-15-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |
| 2020-04-01-preview | Unknown             | No Swagger            |

### \$.properties.destination.properties.endpointUrl

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2020-01-01-preview | Unknown             | No Swagger            |
| 2020-04-01-preview | Unknown             | No Swagger            |

### \$.properties.destination.properties.maxEventsPerBatch

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2020-01-01-preview | Default (1)         | No Swagger            |
| 2020-04-01-preview | Default (1)         | No Swagger            |

### \$.properties.destination.properties.preferredBatchSizeInKilobytes

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2020-01-01-preview | Default (64)        | No Swagger            |
| 2020-04-01-preview | Default (64)        | No Swagger            |

### \$.properties.destination.properties.topic

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.destination.topic

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2020-04-01-preview | Unknown             | No Swagger            |

### \$.properties.eventDeliverySchema

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-09-15-preview | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |
| 2020-01-01-preview | Unknown             | No Swagger            |
| 2020-04-01-preview | Unknown             | No Swagger            |

### \$.properties.filter

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.filter.advancedFilters

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.filter.advancedFilters[*].value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.filter.eventDeliverySchema

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.filter.includedEventTypes

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-05-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |

### \$.properties.filter.includedEventTypes[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |

### \$.properties.filter.isSubjectCaseSensitive

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |
| 2020-04-01-preview | Unknown             | No Swagger            |

### \$.properties.filter.subjectIsCaseSensitive

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-15-preview | Unknown             | No Swagger            |

### \$.properties.mode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |

### \$.properties.retryPolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |

### \$.properties.retryPolicy.eventTimeToLiveInMinutes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Default* (1440)     | No Swagger            |

### \$.properties.tenantId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-05-01-preview | Unknown             | No Swagger            |
| 2018-09-15-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |

## topics

![cleanliness](https://img.shields.io/badge/cleanliness-85.71%25%20(42%20/%2049)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%207)-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.publicNetworkAccess

| API version        | Detected noise type  | Determined noise type |
| ------------------ | -------------------- | --------------------- |
| 2020-04-01-preview | Default* ("Enabled") | No Swagger            |

### \$.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2020-04-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | No Swagger            |
| 2020-04-01-preview | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

## systemtopics/eventsubscriptions

![cleanliness](https://img.shields.io/badge/cleanliness-92.75%25%20(64%20/%2069)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%205)-red)

### \$.properties.destination.properties.endpointUrl

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2020-04-01-preview | Unknown             | No Swagger            |

### \$.properties.destination.properties.maxEventsPerBatch

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2020-04-01-preview | Default* (1)        | No Swagger            |

### \$.properties.destination.properties.preferredBatchSizeInKilobytes

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2020-04-01-preview | Default* (64)       | No Swagger            |

### \$.properties.eventDeliverySchema

| API version        | Detected noise type          | Determined noise type |
| ------------------ | ---------------------------- | --------------------- |
| 2020-04-01-preview | Default* ("EventGridSchema") | No Swagger            |

### \$.properties.retryPolicy

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2020-04-01-preview | Unknown             | No Swagger            |
