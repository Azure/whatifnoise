# Microsoft.Databricks

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## workspaces

![3.45%25](https://img.shields.io/badge/3.45%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.ManagedResourceGroupId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | Unknown               |

### \$.properties.authorizations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-03-15  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | Unknown               |

### \$.properties.authorizations[*].principalId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.authorizations[*].roleDefinitionId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.createdBy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | Read-only             |

### \$.properties.createdDateTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-03-15  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.managedResourceGroupId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | Unknown               |

### \$.properties.parameters

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-15  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | Unknown               |

### \$.properties.parameters.amlWorkspaceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | Unknown               |

### \$.properties.parameters.customPrivateSubnetName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.parameters.customPrivateSubnetName.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | Unknown               |

### \$.properties.parameters.customPublicSubnetName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.parameters.customPublicSubnetName.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | Unknown               |

### \$.properties.parameters.customVirtualNetworkId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.parameters.customVirtualNetworkId.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | Unknown               |

### \$.properties.parameters.enableFedRampCertification

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-03-15  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.parameters.enableNoPublicIp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-15  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | Unknown               |

### \$.properties.parameters.loadBalancerBackendPoolName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | Unknown               |

### \$.properties.parameters.loadBalancerId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | Unknown               |

### \$.properties.parameters.relayNamespaceName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-03-15  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | Unknown               |

### \$.properties.parameters.resourceTags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-03-15  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | Unknown               |

### \$.properties.parameters.resourceTags.value.application

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.parameters.resourceTags.value.databricks-environment

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.parameters.storageAccountName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-03-15  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | Unknown               |

### \$.properties.parameters.storageAccountSkuName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-03-15  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | Unknown               |

### \$.properties.parameters.vnetAddressPrefix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-03-15  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | Unknown               |

### \$.properties.updatedBy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | Read-only             |

### \$.properties.workspaceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-03-15  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.workspaceUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-03-15  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | Unknown               |
