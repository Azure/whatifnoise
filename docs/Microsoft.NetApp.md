# Microsoft.NetApp

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## netAppAccounts/capacityPools/volumes

![10.53%25](https://img.shields.io/badge/10.53%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-orange)

### \$.properties.exportPolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Unknown               |

### \$.properties.exportPolicy.rules[*].cifs

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-10-01  | Default* (false)    | No Swagger            |

### \$.properties.exportPolicy.rules[*].nfsv4

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-10-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.exportPolicy.rules[*].nfsv41

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Default* (false)    | No Swagger            |

### \$.properties.mountTargets

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Unknown               |
| 2019-10-01  | Unknown             | Unknown               |
| 2019-11-01  | Unknown             | Unknown               |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |
| 2019-10-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.ownerId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.protocolTypes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Unknown               |
| 2019-11-01  | Unknown             | Unknown               |

### \$.properties.serviceLevel

| API version | Detected noise type   | Determined noise type |
| ----------- | --------------------- | --------------------- |
| 2019-11-01  | Default* ("Standard") | Default ("Premium")   |

### \$.properties.usageThreshold

| API version | Detected noise type     | Determined noise type  |
| ----------- | ----------------------- | ---------------------- |
| 2019-11-01  | Default* (107374182400) | Default (107374182400) |

### \$.properties.usedBytes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Default (0)         | No Swagger            |
| 2019-10-01  | Default (0)         | No Swagger            |
| 2019-11-01  | Default (0)         | No Swagger            |

## netAppAccounts/capacityPools

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.size

| API version | Detected noise type      | Determined noise type |
| ----------- | ------------------------ | --------------------- |
| 2019-07-01  | Default* (4398046511104) | Unknown               |
| 2019-11-01  | Default* (4398046511104) | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | Unknown               |

## netAppAccounts

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | Unknown               |
| 2019-11-01  | Unknown             | Unknown               |
