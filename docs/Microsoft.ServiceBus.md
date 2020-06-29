# Microsoft.ServiceBus

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## namespaces/authorizationRules

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%205)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.Rights

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.rights

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

## namespaces/disasterRecoveryConfigs

![cleanliness](https://img.shields.io/badge/cleanliness-83.33%25%20(5%20/%206)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

## namespaces/networkruleset

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%204)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-01         | Unknown             | No Swagger            |
| 2018-01-01-preview | Unknown             | No Swagger            |

### \$.properties.virtualNetworkRules

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Unknown             | No Swagger            |

### \$.properties.virtualNetworkRules[*].subnet.id

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Unknown             | No Swagger            |

## namespaces/queues/authorizationRules

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2010)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.PrimaryKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.SecondaryKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.claimType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.claimValue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.keyName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.revision

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.rights[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

## namespaces/queues

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2045)-red)

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.autoDeleteOnIdle

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.deadLetteringOnMessageExpiration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.defaultMessageTimeToLive

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.duplicateDetectionHistoryTimeWindow

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.enableBatchedOperations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (true)      | No Swagger            |
| 2017-04-01  | Default (true)      | No Swagger            |

### \$.properties.enableExpress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2017-04-01  | Default (false)     | No Swagger            |

### \$.properties.enablePartitioning

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2017-04-01  | Default (false)     | No Swagger            |

### \$.properties.entityAvailabilityStatus

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.filteringMessagesBeforePublishing

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.isAnonymousAccessible

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2017-04-01  | Default (false)     | No Swagger            |

### \$.properties.lockDuration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.lockDuration 

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.maxDeliveryCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (10)        | No Swagger            |
| 2017-04-01  | Default (10)        | No Swagger            |

### \$.properties.maxDeliveryCount 

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.maxSizeInMegabytes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.messageOrder

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.path

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.requiresDuplicateDetection

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.requiresSession

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2017-04-01  | Default (false)     | No Swagger            |

### \$.properties.scopes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.status

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default ("Active")  | No Swagger            |
| 2017-04-01  | Default ("Active")  | No Swagger            |

### \$.properties.supportOrdering

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

## namespaces/topics/authorizationRules

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2012)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.PrimaryKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.Rights

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.SecondaryKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.claimType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.claimValue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.keyName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.revision

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.rights

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.rights[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

## namespaces/topics/subscriptions/rules

![cleanliness](https://img.shields.io/badge/cleanliness-31.82%25%20(7%20/%2022)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2015)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.action.compatibilityLevel

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Default (20)        | No Swagger            |

### \$.properties.correlationFilter.requiresPreprocessing

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.createdAt

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.filter

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.filter.compatibilityLevel

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (20)        | No Swagger            |

### \$.properties.filterType

| API version | Detected noise type    | Determined noise type |
| ----------- | ---------------------- | --------------------- |
| 2017-04-01  | Default* ("SqlFilter") | No Swagger            |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.sqlFilter

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.sqlFilter.compatibilityLevel

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Default (20)        | No Swagger            |

### \$.properties.sqlFilter.requiresPreprocessing

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.sqlFilter.requiresSession

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.sqlFilter.sqlExpression

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

## namespaces/topics/subscriptions

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2053)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.accessedAt

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.authorizationRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.autoDeleteOnIdle

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.countDetails

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.createdAt

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.deadLetteringOnFilterEvaluationExceptions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (true)      | No Swagger            |
| 2017-04-01  | Default (true)      | No Swagger            |

### \$.properties.deadLetteringOnMessageExpiration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.defaultMessageTimeToLive

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.duplicateDetectionHistoryTimeWindow

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.enableBatchedOperations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.enableDeadLetteringOnFilterEvaluationExceptions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.enableDeadLetteringOnMessageExpiration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.enableExpress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.enablePartitioning

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.entityAvailabilityStatus

| API version | Detected noise type    | Determined noise type |
| ----------- | ---------------------- | --------------------- |
| 2015-08-01  | Default* ("Available") | No Swagger            |

### \$.properties.filterType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.forwardTo

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.lockDuration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.maxDeliveryCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (10)        | No Swagger            |
| 2017-04-01  | Default (10)        | No Swagger            |

### \$.properties.maxSizeInMegabytes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.messageCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.path

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.requiresDuplicateDetection

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.requiresSession

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2017-04-01  | Default (false)     | No Swagger            |

### \$.properties.sqlFilter

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.status

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default ("Active")  | No Swagger            |
| 2017-04-01  | Default ("Active")  | No Swagger            |

### \$.properties.subscriptionName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.supportOrdering

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.topicPath

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.updatedAt

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.userMetadata

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

## namespaces/topics

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2042)-red)

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.autoDeleteOnIdle

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.deadLetteringOnFilterEvaluationExceptions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.deadLetteringOnMessageExpiration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.defaultMessageTimeToLive

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.duplicateDetectionHistoryTimeWindow

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.enableBatchedOperations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.enableExpress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.enablePartitioning

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.enableSubscriptionPartitioning

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2017-04-01  | Default (false)     | No Swagger            |

### \$.properties.entityAvailabilityStatus

| API version | Detected noise type   | Determined noise type |
| ----------- | --------------------- | --------------------- |
| 2015-08-01  | Default ("Available") | No Swagger            |

### \$.properties.filteringMessagesBeforePublishing

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2017-04-01  | Default (false)     | No Swagger            |

### \$.properties.isAnonymousAccessible

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2017-04-01  | Default (false)     | No Swagger            |

### \$.properties.isExpress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.lockDuration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.maxDeliveryCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.maxSizeInMegabytes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.path

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.requiresDuplicateDetection

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2017-04-01  | Default (false)     | No Swagger            |

### \$.properties.requiresSession

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.status

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default ("Active")  | No Swagger            |
| 2017-04-01  | Default ("Active")  | No Swagger            |

### \$.properties.supportOrdering

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

## namespaces/virtualNetworkRules

![cleanliness](https://img.shields.io/badge/cleanliness-0.00%25%20(0%20/%202)-red) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Unknown             | No Swagger            |

### \$.properties.ignoreMissingVnetServiceEndpoint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Default* (false)    | No Swagger            |

## namespaces

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-brightgreen) ![progress](https://img.shields.io/badge/progress-100.00%25%20(48%20/%2048)-brightgreen)

### \$.identity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | Put-as-patch          |

### \$.kind

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-01         | Unknown             | Put-as-patch          |
| 2018-01-01-preview | Unknown             | Put-as-patch          |

### \$.location

| API version        | Detected noise type    | Determined noise type |
| ------------------ | ---------------------- | --------------------- |
| 2018-01-01-preview | Default* ("East US 2") | Put-as-patch          |

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01         | Unknown             | Put-as-patch          |
| 2017-04-01         | Unknown             | Put-as-patch          |
| 2018-01-01-preview | Unknown             | Put-as-patch          |

### \$.properties.Enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | Put-as-patch          |

### \$.properties.MessagingSKUPlan

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | Put-as-patch          |

### \$.properties.MessagingSku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | Put-as-patch          |

### \$.properties.createACSNamespace

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-09-01  | Unknown             | Put-as-patch          |
| 2017-04-01  | Unknown             | Put-as-patch          |

### \$.properties.critical

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-09-01  | Default (false)     | Put-as-patch          |
| 2015-08-01  | Default (false)     | Put-as-patch          |

### \$.properties.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-09-01  | Default (true)      | Put-as-patch          |
| 2015-08-01  | Default (true)      | Put-as-patch          |

### \$.properties.eventHubEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-09-01  | Unknown             | Put-as-patch          |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2017-04-01  | Unknown             | Put-as-patch          |

### \$.properties.messagingSku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-09-01  | Unknown             | Put-as-patch          |
| 2015-08-01  | Unknown             | Put-as-patch          |

### \$.properties.messagingSkuPlan

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-09-01  | Unknown             | Put-as-patch          |

### \$.properties.messagingSkuPlan.MessagingUnits

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-09-01  | Unknown             | Put-as-patch          |

### \$.properties.messagingSkuPlan.selectedEventHubUnit

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-09-01  | Default (0)         | Put-as-patch          |

### \$.properties.metricId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-09-01  | Unknown             | Put-as-patch          |
| 2015-08-01  | Unknown             | Put-as-patch          |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |

### \$.properties.namespaceType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2017-04-01  | Unknown             | Put-as-patch          |

### \$.properties.status

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-09-01  | Default ("Active")  | Put-as-patch          |

### \$.properties.zoneRedundant

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-01         | Unknown             | Put-as-patch          |
| 2018-01-01-preview | Unknown             | Put-as-patch          |

### \$.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-09-01         | Unknown             | Put-as-patch          |
| 2015-08-01         | Unknown             | Put-as-patch          |
| 2017-04-01         | Unknown             | Put-as-patch          |
| 2018-01-01-preview | Unknown             | Put-as-patch          |

### \$.sku.capacity

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01         | Unknown             | Put-as-patch          |
| 2017-04-01         | Unknown             | Put-as-patch          |
| 2018-01-01-preview | Unknown             | Put-as-patch          |

### \$.sku.name

| API version | Detected noise type  | Determined noise type |
| ----------- | -------------------- | --------------------- |
| 2015-08-01  | Default ("Standard") | Put-as-patch          |

### \$.sku.tier

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01         | Unknown             | Put-as-patch          |
| 2017-04-01         | Unknown             | Put-as-patch          |
| 2018-01-01-preview | Unknown             | Put-as-patch          |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01         | Unknown             | Put-as-patch          |
| 2017-04-01         | Unknown             | Put-as-patch          |
| 2018-01-01-preview | Unknown             | Put-as-patch          |

### \$.tags.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-01         | Unknown             | Put-as-patch          |
| 2018-01-01-preview | Unknown             | Put-as-patch          |

## namespaces/networkrulesets

![cleanliness](https://img.shields.io/badge/cleanliness-77.78%25%20(7%20/%209)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-01         | Unknown             | No Swagger            |
| 2018-01-01-preview | Unknown             | No Swagger            |
