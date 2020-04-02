# Microsoft.MachineLearningServices

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## workspaces/computes

![54.55%25](https://img.shields.io/badge/54.55%25-%E2%98%85★★★★%E2%98%86☆☆☆☆-yellow)

### \$.properties.isNestedCompute

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Default* (false)    | No Swagger            |

### \$.properties.properties.agentVmSize

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | Unknown               |

### \$.properties.properties.allocationState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | Read-only             |

### \$.properties.properties.allocationStateTransitionTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | Read-only             |

### \$.properties.properties.clusterFqdn

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | Unknown               |

### \$.properties.properties.clusterPurpose

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | No Swagger            |

### \$.properties.properties.currentNodeCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Default* (0)        | Read-only             |

### \$.properties.properties.nodeStateCounts

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | Read-only             |

### \$.properties.properties.systemServices

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | Read-only             |

### \$.properties.properties.targetNodeCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Default* (1)        | Read-only             |

### \$.properties.resourceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | Unknown               |

## workspaces

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.adbWorkspace

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.allowPublicAccessWhenBehindVnet

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-10-01  | Default (false)     | No Swagger            |
| 2019-11-01  | Default (false)     | No Swagger            |

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
| 2018-03-01-preview | Unknown             | Unknown               |
| 2018-11-19         | Unknown             | Unknown               |
| 2019-10-01         | Unknown             | No Swagger            |
| 2019-11-01         | Unknown             | Unknown               |

### \$.properties.enableDataActions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-10-01  | Default (false)     | No Swagger            |
| 2019-11-01  | Default (false)     | No Swagger            |

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

### \$.properties.hbiWorkspace

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-03-01-preview | Unknown             | No Swagger            |
| 2018-11-19         | Unknown             | No Swagger            |
| 2019-10-01         | Unknown             | No Swagger            |
| 2019-11-01         | Unknown             | No Swagger            |

### \$.properties.keyVault

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | Unknown               |
| 2019-10-01  | Unknown             | No Swagger            |

### \$.properties.privateLinkCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Default (0)         | No Swagger            |
| 2019-10-01  | Default (0)         | No Swagger            |
| 2019-11-01  | Default (0)         | No Swagger            |

### \$.properties.storageAccount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-10-01  | Unknown             | No Swagger            |

### \$.properties.subscriptionState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | No Swagger            |

### \$.properties.subscriptionStatusChangeTimeStampUtc

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | No Swagger            |

### \$.properties.tenantId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-03-01-preview | Unknown             | No Swagger            |
| 2018-11-19         | Unknown             | No Swagger            |
| 2019-10-01         | Unknown             | No Swagger            |
| 2019-11-01         | Unknown             | No Swagger            |

### \$.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-03-01-preview | Unknown             | No Swagger            |
| 2018-11-19         | Unknown             | No Swagger            |
| 2019-11-01         | Unknown             | Unknown               |

### \$.sku.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | No Swagger            |
| 2019-10-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | Unknown               |

### \$.sku.tier

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-19  | Unknown             | No Swagger            |
| 2019-10-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-10-01  | Unknown             | No Swagger            |
