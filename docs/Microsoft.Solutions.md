# Microsoft.Solutions

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## applicationDefinitions

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.artifacts

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | Unknown               |

### \$.properties.isEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Default* (true)     | Unknown               |
| 2019-07-01  | Default* (true)     | Unknown               |

### \$.properties.packageFileUri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | Unknown               |

## applications

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.authorizations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |

### \$.properties.customerSupport

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |

### \$.properties.parameters.azureZoneName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |

### \$.properties.parameters.baseUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |

### \$.properties.parameters.baseUrl.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |

### \$.properties.parameters.fusionGroupName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |

### \$.properties.parameters.location.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.merakiAuthToken.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |

### \$.properties.parameters.nodeCount.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |

### \$.properties.parameters.storageAccessKey.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |

### \$.properties.parameters.storageAccount.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |

### \$.properties.parameters.storageAccountName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.storageAccountNamePrefix.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |

### \$.properties.parameters.storageAccountType.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.parameters.storageContainer.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |

### \$.properties.parameters.subnetAddressPrefix.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |

### \$.properties.parameters.subnetName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |

### \$.properties.parameters.userAssignedIdentities

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |

### \$.properties.parameters.virtualMachineSize.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |

### \$.properties.parameters.virtualNetwork.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |

### \$.properties.parameters.virtualNetworkAddressPrefix.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |

### \$.properties.parameters.virtualNetworkName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |

### \$.properties.parameters.virtualNetworkNewOrExisting.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |

### \$.properties.parameters.virtualNetworkResourceGroup.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |

### \$.properties.parameters.vmName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |

### \$.properties.parameters.vmSize.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |

### \$.properties.publisherPackageId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |

### \$.properties.publisherTenantId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |

### \$.properties.supportUrls

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |
