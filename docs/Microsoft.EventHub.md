# Microsoft.EventHub

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## clusters

![cleanliness](https://img.shields.io/badge/cleanliness-87.50%25%20(7%20/%208)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Unknown             | No Swagger            |

## namespaces/authorizationRules

![cleanliness](https://img.shields.io/badge/cleanliness-50.00%25%20(1%20/%202)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

## namespaces/disasterrecoveryconfigs

![cleanliness](https://img.shields.io/badge/cleanliness-83.33%25%20(5%20/%206)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

## namespaces/eventhubs/authorizationRules

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%203)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.rights[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

## namespaces/eventHubs/consumerGroups

![cleanliness](https://img.shields.io/badge/cleanliness-40.00%25%20(2%20/%205)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%203)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

## namespaces/eventhubs

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2023)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.MessageRetentionInDays

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.PartitionCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.captureDescription.destination.properties.BlobContainer

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.captureDescription.destination.properties.StorageAccountResourceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.captureDescription.destination.properties.archiveNameFormat

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.captureDescription.destination.properties.blobContainer

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.captureDescription.destination.properties.storageAccountResourceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.captureDescription.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.captureDescription.intervalInSeconds

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Default (300)       | No Swagger            |

### \$.properties.captureDescription.invervallInSeconds

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.captureDescription.sizeLimitInBytes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Default (104857600) | No Swagger            |

### \$.properties.captureDescription.skipEmptyArchives

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.messageRetentionInDays

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.partitionCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.path

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.status

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default ("Active")  | No Swagger            |
| 2017-04-01  | Default ("Active")  | No Swagger            |

### \$.properties.userMetadata

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

## namespaces/networkruleset

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%203)-red)

### \$.location

| API version        | Detected noise type        | Determined noise type |
| ------------------ | -------------------------- | --------------------- |
| 2018-01-01-preview | Default ("Australia East") | No Swagger            |

### \$.properties.trustedServiceAccessEnabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Unknown             | No Swagger            |

## namespaces/networkRuleSets

![cleanliness](https://img.shields.io/badge/cleanliness-55.56%25%20(5%20/%209)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%204)-red)

### \$.location

| API version        | Detected noise type      | Determined noise type |
| ------------------ | ------------------------ | --------------------- |
| 2018-01-01-preview | Default* ("West Europe") | No Swagger            |

### \$.properties.defaultAction

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Default* ("Allow")  | No Swagger            |

### \$.properties.virtualNetworkRules[*]

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Unknown             | No Swagger            |

## namespaces/virtualnetworkrules

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%204)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Unknown             | No Swagger            |

### \$.properties.ignoreMissingVnetServiceEndpoint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Default* (false)    | No Swagger            |

### \$.properties.mode

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Unknown             | No Swagger            |

## namespaces

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2052)-red)

### \$.kind

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-01         | Unknown             | No Swagger            |
| 2018-01-01-preview | Unknown             | No Swagger            |

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01         | Unknown             | No Swagger            |
| 2017-04-01         | Unknown             | No Swagger            |
| 2018-01-01-preview | Unknown             | No Swagger            |

### \$.properties.MessagingSKUPlan

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.MessagingSku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.createACSNamespace

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.createdAt

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.critical

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-09-01  | Default (false)     | No Swagger            |
| 2015-08-01  | Default (false)     | No Swagger            |

### \$.properties.dataCenter

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-09-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.encryption.keyVaultProperties[*].keyVaultUri

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Unknown             | No Swagger            |

### \$.properties.eventHubEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-09-01  | Default (true)      | No Swagger            |
| 2015-08-01  | Default (true)      | No Swagger            |

### \$.properties.isAutoInflateEnabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-09-01         | Unknown             | No Swagger            |
| 2017-04-01         | Unknown             | No Swagger            |
| 2018-01-01-preview | Unknown             | No Swagger            |

### \$.properties.kafkaEnabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-01         | Unknown             | No Swagger            |
| 2018-01-01-preview | Unknown             | No Swagger            |

### \$.properties.maximumThroughputUnits

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-09-01         | Unknown             | No Swagger            |
| 2017-04-01         | Unknown             | No Swagger            |
| 2018-01-01-preview | Unknown             | No Swagger            |

### \$.properties.messagingSku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-09-01  | Default (2)         | No Swagger            |
| 2015-08-01  | Default (2)         | No Swagger            |

### \$.properties.messagingSkuPlan

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-09-01  | Unknown             | No Swagger            |

### \$.properties.namespaceType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-09-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.scaleUnit

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.serviceBusEndpoint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-09-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.status

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default ("Active")  | No Swagger            |

### \$.properties.updatedAt

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.zoneRedundant

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-01         | Unknown             | No Swagger            |
| 2018-01-01-preview | Unknown             | No Swagger            |

### \$.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01         | Unknown             | No Swagger            |
| 2017-04-01         | Unknown             | No Swagger            |
| 2018-01-01-preview | Unknown             | No Swagger            |

### \$.sku.capacity

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01         | Unknown             | No Swagger            |
| 2017-04-01         | Unknown             | No Swagger            |
| 2018-01-01-preview | Unknown             | No Swagger            |

### \$.sku.name

| API version | Detected noise type   | Determined noise type |
| ----------- | --------------------- | --------------------- |
| 2015-08-01  | Default* ("Standard") | No Swagger            |
| 2017-04-01  | Default* ("Standard") | No Swagger            |

### \$.sku.tier

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-01         | Unknown             | No Swagger            |
| 2018-01-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.tags.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-01         | Unknown             | No Swagger            |
| 2018-01-01-preview | Unknown             | No Swagger            |

## namespaces/ipfilterrules

![cleanliness](https://img.shields.io/badge/cleanliness-75.00%25%20(3%20/%204)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.location

| API version        | Detected noise type  | Determined noise type |
| ------------------ | -------------------- | --------------------- |
| 2018-01-01-preview | Default* ("West US") | No Swagger            |
