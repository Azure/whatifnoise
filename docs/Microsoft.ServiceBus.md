# Microsoft.ServiceBus

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## namespaces/authorizationRules

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.Rights

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | Unknown               |

### \$.properties.rights

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

## namespaces/disasterRecoveryConfigs

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

## namespaces/networkruleset

!> No Swagger.

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version        | Detected noise type   | Determined noise type |
| ------------------ | --------------------- | --------------------- |
| 2018-01-01-preview | Default* ("UK South") | No Swagger            |

### \$.properties.virtualNetworkRules

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Unknown             | No Swagger            |

## namespaces/queues/authorizationRules

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
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
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.claimValue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.keyName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.revision

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

## namespaces/queues

![35.00%25](https://img.shields.io/badge/35.00%25-%E2%98%85★★★%E2%98%86☆☆☆☆☆-yellow)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | Unknown               |

### \$.properties.autoDeleteOnIdle

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | Unknown               |

### \$.properties.deadLetteringOnMessageExpiration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | Unknown               |

### \$.properties.defaultMessageTimeToLive

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | Unknown               |

### \$.properties.duplicateDetectionHistoryTimeWindow

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | Unknown               |

### \$.properties.enableBatchedOperations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (true)      | Default (true)        |
| 2017-04-01  | Default (true)      | Default (true)        |

### \$.properties.enableExpress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | Default (false)       |
| 2017-04-01  | Default (false)     | Default (false)       |

### \$.properties.enablePartitioning

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | Default (false)       |
| 2017-04-01  | Default (false)     | Default (false)       |

### \$.properties.entityAvailabilityStatus

| API version | Detected noise type   | Determined noise type |
| ----------- | --------------------- | --------------------- |
| 2015-08-01  | Default ("Available") | Read-only             |

### \$.properties.filteringMessagesBeforePublishing

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.isAnonymousAccessible

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | Default (false)       |

### \$.properties.lockDuration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | Unknown               |

### \$.properties.lockDuration 

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.maxDeliveryCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (10)        | Default (10)          |
| 2017-04-01  | Default (10)        | Default (10)          |

### \$.properties.maxDeliveryCount 

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.maxSizeInMegabytes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | Unknown               |

### \$.properties.messageOrder

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.path

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.requiresDuplicateDetection

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | Unknown               |

### \$.properties.requiresSession

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | Default (false)       |
| 2017-04-01  | Default (false)     | Default (false)       |

### \$.properties.status

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default ("Active")  | Default ("Active")    |
| 2017-04-01  | Default ("Active")  | Default ("Active")    |

### \$.properties.supportOrdering

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

## namespaces/topics/authorizationRules

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.PrimaryKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.Rights

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | Unknown               |

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
| 2017-04-01  | Unknown             | Unknown               |

## namespaces/topics/subscriptions/rules

![23.08%25](https://img.shields.io/badge/23.08%25-%E2%98%85★%E2%98%86☆☆☆☆☆☆☆-orange)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.action.compatibilityLevel

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Default* (20)       | Unknown               |

### \$.properties.correlationFilter.requiresPreprocessing

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | Default (true)        |

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
| 2017-04-01  | Default* ("SqlFilter") | Unknown               |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.sqlFilter

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | Unknown               |

### \$.properties.sqlFilter.compatibilityLevel

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Default (20)        | Default (20)          |

### \$.properties.sqlFilter.requiresPreprocessing

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | Default (true)        |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

## namespaces/topics/subscriptions

![36.73%25](https://img.shields.io/badge/36.73%25-%E2%98%85★★★%E2%98%86☆☆☆☆☆-yellow)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | Unknown               |

### \$.properties.accessedAt

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Read-only             |
| 2017-04-01  | Unknown             | Read-only             |

### \$.properties.authorizationRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.autoDeleteOnIdle

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | Unknown               |

### \$.properties.countDetails

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Read-only             |
| 2017-04-01  | Unknown             | Read-only             |

### \$.properties.createdAt

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Read-only             |
| 2017-04-01  | Unknown             | Read-only             |

### \$.properties.deadLetteringOnFilterEvaluationExceptions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (true)      | Default (true)        |
| 2017-04-01  | Default (true)      | Default (true)        |

### \$.properties.deadLetteringOnMessageExpiration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | Unknown               |

### \$.properties.defaultMessageTimeToLive

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | Unknown               |

### \$.properties.duplicateDetectionHistoryTimeWindow

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | Unknown               |

### \$.properties.enableBatchedOperations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | Unknown               |

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
| 2015-08-01  | Default* ("Available") | Unknown               |

### \$.properties.forwardTo

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | Unknown               |

### \$.properties.lockDuration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | Unknown               |

### \$.properties.maxDeliveryCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (10)        | Default (10)          |
| 2017-04-01  | Default (10)        | Default (10)          |

### \$.properties.maxSizeInMegabytes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.messageCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Read-only             |
| 2017-04-01  | Unknown             | Read-only             |

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
| 2015-08-01  | Default (false)     | Default (false)       |
| 2017-04-01  | Default (false)     | Default (false)       |

### \$.properties.status

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default ("Active")  | Default ("Active")    |
| 2017-04-01  | Default ("Active")  | Default ("Active")    |

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
| 2015-08-01  | Unknown             | Read-only             |
| 2017-04-01  | Unknown             | Read-only             |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

## namespaces/topics

![21.05%25](https://img.shields.io/badge/21.05%25-%E2%98%85★%E2%98%86☆☆☆☆☆☆☆-orange)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | Unknown               |

### \$.properties.autoDeleteOnIdle

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | Unknown               |

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
| 2015-08-01  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | Unknown               |

### \$.properties.duplicateDetectionHistoryTimeWindow

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | Unknown               |

### \$.properties.enableBatchedOperations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | Unknown               |

### \$.properties.enableExpress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | Unknown               |

### \$.properties.enablePartitioning

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | Unknown               |

### \$.properties.enableSubscriptionPartitioning

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | No Swagger            |

### \$.properties.entityAvailabilityStatus

| API version | Detected noise type   | Determined noise type |
| ----------- | --------------------- | --------------------- |
| 2015-08-01  | Default ("Available") | Read-only             |

### \$.properties.filteringMessagesBeforePublishing

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | Default (false)       |

### \$.properties.isAnonymousAccessible

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | Default (false)       |

### \$.properties.isExpress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | Default (false)       |

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
| 2015-08-01  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | Unknown               |

### \$.properties.path

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.requiresDuplicateDetection

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | Default (false)       |
| 2017-04-01  | Default (false)     | Default (false)       |

### \$.properties.requiresSession

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.status

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default ("Active")  | Default ("Active")    |
| 2017-04-01  | Default ("Active")  | Default ("Active")    |

### \$.properties.supportOrdering

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

## namespaces/virtualNetworkRules

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Unknown             | No Swagger            |

### \$.properties.ignoreMissingVnetServiceEndpoint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Default* (false)    | No Swagger            |

## namespaces

![8.70%25](https://img.shields.io/badge/8.70%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-red)

### \$.kind

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-09-01         | Unknown             | No Swagger            |
| 2015-08-01         | Unknown             | No Swagger            |
| 2017-04-01         | Unknown             | No Swagger            |
| 2018-01-01-preview | Unknown             | No Swagger            |

### \$.location

| API version        | Detected noise type    | Determined noise type |
| ------------------ | ---------------------- | --------------------- |
| 2018-01-01-preview | Default* ("East US 2") | Unknown               |

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01         | Unknown             | Unknown               |
| 2017-04-01         | Unknown             | Unknown               |
| 2018-01-01-preview | Unknown             | Unknown               |

### \$.properties.Enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.createACSNamespace

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-09-01  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.critical

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-09-01  | Default (false)     | No Swagger            |
| 2015-08-01  | Default (false)     | No Swagger            |

### \$.properties.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-09-01  | Default* (true)     | Unknown               |
| 2015-08-01  | Default* (true)     | Unknown               |

### \$.properties.eventHubEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-09-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.messagingSku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-09-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.messagingSkuPlan

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-09-01  | Unknown             | No Swagger            |

### \$.properties.messagingSkuPlan.MessagingUnits

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-09-01  | Unknown             | No Swagger            |

### \$.properties.messagingSkuPlan.selectedEventHubUnit

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-09-01  | Default* (0)        | No Swagger            |

### \$.properties.metricId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-09-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.mode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.namespaceType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.resources

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.status

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-09-01  | Default ("Active")  | Read-only             |

### \$.properties.zoneRedundant

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Default* (false)    | Unknown               |

### \$.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-09-01         | Unknown             | Unknown               |
| 2015-08-01         | Unknown             | Unknown               |
| 2017-04-01         | Unknown             | Unknown               |
| 2018-01-01-preview | Unknown             | Unknown               |

### \$.sku.capacity

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01         | Default (1)         | Default (1)           |
| 2017-04-01         | Default (1)         | Default (1)           |
| 2018-01-01-preview | Default (1)         | Default (1)           |

### \$.sku.name

| API version | Detected noise type   | Determined noise type |
| ----------- | --------------------- | --------------------- |
| 2015-08-01  | Default* ("Standard") | Unknown               |

### \$.sku.tier

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01         | Unknown             | Unknown               |
| 2017-04-01         | Unknown             | Unknown               |
| 2018-01-01-preview | Unknown             | Unknown               |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01         | Unknown             | Unknown               |
| 2017-04-01         | Unknown             | Unknown               |
| 2018-01-01-preview | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | Unknown               |
