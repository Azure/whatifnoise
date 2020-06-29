# Microsoft.MachineLearningServices

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## workspaces/computes

![cleanliness](https://img.shields.io/badge/cleanliness-78.87%25%20(112%20/%20142)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2030)-red)

### \$.properties.computeLocation

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | Unknown               |
| 2020-04-01  | Unknown             | No Swagger            |

### \$.properties.computeType

| API version | Detected noise type          | Determined noise type |
| ----------- | ---------------------------- | --------------------- |
| 2020-01-01  | Default* ("ComputeInstance") | No Swagger            |

### \$.properties.isNestedCompute

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Default* (false)    | No Swagger            |

### \$.properties.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-01-01  | Unknown             | No Swagger            |

### \$.properties.properties.address

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | No Swagger            |

### \$.properties.properties.administratorAccount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | No Swagger            |

### \$.properties.properties.agentVmSize

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | No Swagger            |

### \$.properties.properties.allocationState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | No Swagger            |

### \$.properties.properties.allocationStateTransitionTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | No Swagger            |

### \$.properties.properties.applicationSharingPolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-04-01  | Unknown             | No Swagger            |

### \$.properties.properties.applications

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-04-01  | Unknown             | No Swagger            |

### \$.properties.properties.clusterFqdn

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | No Swagger            |

### \$.properties.properties.clusterPurpose

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | No Swagger            |

### \$.properties.properties.connectivityEndpoints

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-04-01  | Unknown             | No Swagger            |

### \$.properties.properties.createdBy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-04-01  | Unknown             | No Swagger            |

### \$.properties.properties.currentNodeCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Default* (0)        | No Swagger            |

### \$.properties.properties.ipAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | No Swagger            |

### \$.properties.properties.nodeStateCounts

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | No Swagger            |

### \$.properties.properties.scaleSettings.nodeIdleTimeBeforeScaleDown

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | No Swagger            |

### \$.properties.properties.sshSettings.sshPort

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-04-01  | Default* (50000)    | No Swagger            |

### \$.properties.properties.state

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-04-01  | Unknown             | No Swagger            |

### \$.properties.properties.subnet.action

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | No Swagger            |

### \$.properties.properties.systemServices

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | No Swagger            |

### \$.properties.properties.targetNodeCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Default* (1)        | No Swagger            |

### \$.properties.properties.vmPriority

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | No Swagger            |

### \$.properties.properties.vmSize

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | No Swagger            |
| 2020-04-01  | Unknown             | No Swagger            |

### \$.properties.resourceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | No Swagger            |

## workspaces

![cleanliness](https://img.shields.io/badge/cleanliness-9.46%25%20(7%20/%2074)-red) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2067)-red)

### \$.properties.adbWorkspace

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.allowPublicAccessWhenBehindVnet

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Default (false)     | No Swagger            |
| 2019-10-01  | Default (false)     | No Swagger            |
| 2019-11-01  | Default (false)     | No Swagger            |
| 2020-01-01  | Default (false)     | No Swagger            |

### \$.properties.applicationInsights

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-10-01  | Unknown             | No Swagger            |

### \$.properties.batchaiWorkspace

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-03-01-preview | Unknown             | Unknown               |

### \$.properties.customerManagedCosmosDb

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-10-01  | Default* (false)    | No Swagger            |

### \$.properties.discoveryUrl

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-03-01-preview | Unknown             | No Swagger            |
| 2018-11-19         | Unknown             | No Swagger            |
| 2019-10-01         | Unknown             | No Swagger            |
| 2019-11-01         | Unknown             | No Swagger            |
| 2020-01-01         | Unknown             | No Swagger            |
| 2020-03-01         | Unknown             | No Swagger            |
| 2020-04-01         | Unknown             | No Swagger            |

### \$.properties.enableDataActions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Default (false)     | No Swagger            |
| 2019-10-01  | Default (false)     | No Swagger            |
| 2019-11-01  | Default (false)     | No Swagger            |
| 2020-01-01  | Default (false)     | No Swagger            |

### \$.properties.enableFineGrainAccessControl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Default (false)     | No Swagger            |
| 2019-10-01  | Default (false)     | No Swagger            |
| 2019-11-01  | Default (false)     | No Swagger            |

### \$.properties.encryption

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-10-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |
| 2020-04-01  | Unknown             | No Swagger            |

### \$.properties.encryption.keyVaultProperties.keyIdentifier

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-01-01  | Unknown             | No Swagger            |

### \$.properties.hbiWorkspace

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-03-01-preview | Unknown             | No Swagger            |
| 2018-11-19         | Unknown             | No Swagger            |
| 2019-10-01         | Unknown             | No Swagger            |
| 2019-11-01         | Unknown             | No Swagger            |

### \$.properties.hbi_workspace

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-01-01  | Unknown             | No Swagger            |

### \$.properties.keyVault

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | No Swagger            |
| 2019-10-01  | Unknown             | No Swagger            |

### \$.properties.notebookInfo

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | No Swagger            |
| 2019-10-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |
| 2020-01-01  | Unknown             | No Swagger            |
| 2020-04-01  | Unknown             | No Swagger            |

### \$.properties.privateLinkCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Default (0)         | No Swagger            |
| 2019-10-01  | Default (0)         | No Swagger            |
| 2019-11-01  | Default (0)         | No Swagger            |
| 2020-01-01  | Default (0)         | No Swagger            |

### \$.properties.sharedPrivateLinkResources

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-04-01  | Unknown             | No Swagger            |

### \$.properties.storageAccount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-10-01  | Unknown             | No Swagger            |

### \$.properties.subscriptionState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | No Swagger            |
| 2020-01-01  | Unknown             | No Swagger            |

### \$.properties.subscriptionStatusChangeTimeStampUtc

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | No Swagger            |
| 2020-01-01  | Unknown             | No Swagger            |

### \$.properties.tenantId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-03-01-preview | Unknown             | No Swagger            |
| 2018-11-19         | Unknown             | No Swagger            |
| 2019-10-01         | Unknown             | No Swagger            |
| 2019-11-01         | Unknown             | No Swagger            |
| 2020-01-01         | Unknown             | No Swagger            |
| 2020-03-01         | Unknown             | No Swagger            |
| 2020-04-01         | Unknown             | No Swagger            |

### \$.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-03-01-preview | Unknown             | No Swagger            |
| 2018-11-19         | Unknown             | No Swagger            |
| 2019-11-01         | Unknown             | No Swagger            |
| 2020-03-01         | Unknown             | No Swagger            |

### \$.sku.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | No Swagger            |
| 2019-10-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.sku.tier

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | No Swagger            |
| 2019-10-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-10-01  | Unknown             | No Swagger            |
| 2020-04-01  | Unknown             | No Swagger            |
