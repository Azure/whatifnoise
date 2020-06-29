# Microsoft.Devices

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## iotHubs/eventhubEndpoints/consumerGroups

![cleanliness](https://img.shields.io/badge/cleanliness-0.00%25%20(0%20/%202)-red) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |
| 2019-03-22  | Unknown             | No Swagger            |

## iotHubs

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%20155)-red)

### \$.identity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.authorizationPolicies

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-02-03  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.cloudToDevice

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-02-03         | Unknown             | No Swagger            |
| 2017-01-19         | Unknown             | No Swagger            |
| 2017-07-01         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2019-03-22         | Unknown             | No Swagger            |
| 2019-07-01-preview | Unknown             | No Swagger            |
| 2019-11-04         | Unknown             | No Swagger            |
| 2020-03-01         | Unknown             | No Swagger            |

### \$.properties.cloudToDevice.feedback.lockDurationAsIso8601

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-15-preview | Unknown             | No Swagger            |
| 2016-02-03         | Unknown             | No Swagger            |

### \$.properties.deviceStreams

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-07-01-preview | Unknown             | No Swagger            |
| 2020-03-01         | Unknown             | No Swagger            |

### \$.properties.enableFileUploadNotifications

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-02-03         | Default (false)     | No Swagger            |
| 2017-01-19         | Default (false)     | No Swagger            |
| 2018-04-01         | Default (false)     | No Swagger            |
| 2019-03-22         | Default (false)     | No Swagger            |
| 2019-07-01-preview | Default (false)     | No Swagger            |
| 2020-03-01         | Default (false)     | No Swagger            |

### \$.properties.eventHubEndpoints

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-15-preview | Unknown             | No Swagger            |
| 2016-02-03         | Unknown             | No Swagger            |
| 2017-01-19         | Unknown             | No Swagger            |
| 2017-07-01         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2019-11-04         | Unknown             | No Swagger            |
| 2020-03-01         | Unknown             | No Swagger            |

### \$.properties.eventHubEndpoints.events.endpoint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-02-03         | Unknown             | No Swagger            |
| 2017-07-01         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2019-03-22         | Unknown             | No Swagger            |
| 2019-07-01-preview | Unknown             | No Swagger            |
| 2019-11-04         | Unknown             | No Swagger            |
| 2020-03-01         | Unknown             | No Swagger            |

### \$.properties.eventHubEndpoints.events.partitionCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-02-03  | Default* (32)       | No Swagger            |

### \$.properties.eventHubEndpoints.events.partitionIds

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-02-03         | Unknown             | No Swagger            |
| 2017-07-01         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2019-03-22         | Unknown             | No Swagger            |
| 2019-07-01-preview | Unknown             | No Swagger            |
| 2019-11-04         | Unknown             | No Swagger            |
| 2020-03-01         | Unknown             | No Swagger            |

### \$.properties.eventHubEndpoints.events.path

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-02-03         | Unknown             | No Swagger            |
| 2017-07-01         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2019-03-22         | Unknown             | No Swagger            |
| 2019-07-01-preview | Unknown             | No Swagger            |
| 2019-11-04         | Unknown             | No Swagger            |
| 2020-03-01         | Unknown             | No Swagger            |

### \$.properties.eventHubEndpoints.operationsMonitoringEvents

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.eventHubEndpoints.operationsMonitoringEvents.endpoint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-02-03  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.eventHubEndpoints.operationsMonitoringEvents.partitionCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-02-03  | Default* (32)       | No Swagger            |

### \$.properties.eventHubEndpoints.operationsMonitoringEvents.partitionIds

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-02-03  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.eventHubEndpoints.operationsMonitoringEvents.path

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-02-03  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.features

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-02-03  | Default* ("None")   | No Swagger            |
| 2018-04-01  | Default* ("None")   | No Swagger            |

### \$.properties.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-15-preview | Unknown             | No Swagger            |
| 2016-02-03         | Unknown             | No Swagger            |
| 2017-07-01         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |

### \$.properties.messagingEndpoints

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-15-preview | Unknown             | No Swagger            |
| 2016-02-03         | Unknown             | No Swagger            |
| 2017-01-19         | Unknown             | No Swagger            |
| 2017-07-01         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2019-03-22         | Unknown             | No Swagger            |
| 2019-07-01-preview | Unknown             | No Swagger            |
| 2019-11-04         | Unknown             | No Swagger            |
| 2020-03-01         | Unknown             | No Swagger            |

### \$.properties.messagingEndpoints.fileNotifications.lockDuration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-22  | Unknown             | No Swagger            |

### \$.properties.messagingEndpoints.fileNotifications.lockDurationAsIso8601

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-22  | Unknown             | No Swagger            |

### \$.properties.operationsMonitoringProperties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-02-03  | Unknown             | No Swagger            |
| 2017-01-19  | Unknown             | No Swagger            |
| 2017-07-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.operationsMonitoringProperties.events.FileUploadOperations

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-15-preview | Unknown             | No Swagger            |
| 2016-02-03         | Unknown             | No Swagger            |

### \$.properties.operationsMonitoringProperties.events.None

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-15-preview | Unknown             | No Swagger            |
| 2016-02-03         | Unknown             | No Swagger            |

### \$.properties.operationsMonitoringProperties.events.Routes

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-15-preview | Unknown             | No Swagger            |
| 2016-02-03         | Unknown             | No Swagger            |

### \$.properties.routing

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-15-preview | Unknown             | No Swagger            |
| 2016-02-03         | Unknown             | No Swagger            |
| 2017-01-19         | Unknown             | No Swagger            |
| 2017-07-01         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2019-03-22         | Unknown             | No Swagger            |
| 2019-07-01-preview | Unknown             | No Swagger            |
| 2019-11-04         | Unknown             | No Swagger            |
| 2020-03-01         | Unknown             | No Swagger            |

### \$.properties.routing.endpoints.eventHubs[*].connectionString

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-02-03  | Unknown             | No Swagger            |
| 2017-01-19  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2019-03-22  | Unknown             | No Swagger            |

### \$.properties.routing.endpoints.eventHubs[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-01-19  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2019-03-22  | Unknown             | No Swagger            |

### \$.properties.routing.endpoints.serviceBusQueues[*].connectionString

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |
| 2019-03-22  | Unknown             | No Swagger            |
| 2019-11-04  | Unknown             | No Swagger            |

### \$.properties.routing.endpoints.serviceBusQueues[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |
| 2019-03-22  | Unknown             | No Swagger            |
| 2019-11-04  | Unknown             | No Swagger            |

### \$.properties.routing.endpoints.serviceBusTopics[*].connectionString

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-22  | Unknown             | No Swagger            |
| 2019-11-04  | Unknown             | No Swagger            |

### \$.properties.routing.endpoints.serviceBusTopics[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-22  | Unknown             | No Swagger            |
| 2019-11-04  | Unknown             | No Swagger            |

### \$.properties.routing.endpoints.storageContainers[*].batchFrequencyInSeconds

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Default* (300)      | No Swagger            |

### \$.properties.routing.endpoints.storageContainers[*].connectionString

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2019-03-22  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.routing.endpoints.storageContainers[*].encoding

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.routing.endpoints.storageContainers[*].fileNameFormat

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.routing.endpoints.storageContainers[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2019-03-22  | Unknown             | No Swagger            |
| 2019-11-04  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.routing.endpoints.storageContainers[*].maxChunkSizeInBytes

| API version | Detected noise type  | Determined noise type |
| ----------- | -------------------- | --------------------- |
| 2017-07-01  | Default* (314572800) | No Swagger            |
| 2018-04-01  | Default* (314572800) | No Swagger            |

### \$.properties.routing.fallbackRoute

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2019-03-22  | Unknown             | No Swagger            |

### \$.properties.routing.fallbackRoute.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |
| 2019-03-22  | Unknown             | No Swagger            |

### \$.properties.routing.routes[*].condition

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.state

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-15-preview | Unknown             | No Swagger            |
| 2016-02-03         | Unknown             | No Swagger            |
| 2017-01-19         | Unknown             | No Swagger            |
| 2017-07-01         | Unknown             | No Swagger            |

### \$.properties.storageEndpoints

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-15-preview | Unknown             | No Swagger            |
| 2016-02-03         | Unknown             | No Swagger            |
| 2017-01-19         | Unknown             | No Swagger            |
| 2017-07-01         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2019-03-22         | Unknown             | No Swagger            |
| 2019-07-01-preview | Unknown             | No Swagger            |
| 2019-11-04         | Unknown             | No Swagger            |
| 2020-03-01         | Unknown             | No Swagger            |

### \$.properties.storageEndpoints.$default.connectionString

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2019-03-22  | Unknown             | No Swagger            |
| 2019-11-04  | Unknown             | No Swagger            |

### \$.properties.storageEndpoints.$default.sasTtlAsIso8601

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-07-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |

## provisioningServices

![cleanliness](https://img.shields.io/badge/cleanliness-68.18%25%20(15%20/%2022)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%207)-red)

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-08-21-preview | Unknown             | No Swagger            |

### \$.properties.allocationPolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-11-15  | Default* ("Hashed") | No Swagger            |

### \$.properties.iotHubs[*].connectionString

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-11-15  | Unknown             | No Swagger            |
| 2018-01-22  | Unknown             | No Swagger            |

### \$.properties.state

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-11-15  | Default* ("Active") | No Swagger            |
| 2018-01-22  | Default* ("Active") | No Swagger            |

### \$.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-08-21-preview | Unknown             | No Swagger            |
