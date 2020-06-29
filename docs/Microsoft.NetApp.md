# Microsoft.NetApp

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## netAppAccounts/capacityPools/volumes

![cleanliness](https://img.shields.io/badge/cleanliness-40.91%25%20(27%20/%2066)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2039)-red)

### \$.properties.dataProtection.replication.endPointType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-10-01  | Unknown             | Unknown               |

### \$.properties.dataProtection.replication.remoteVolumeRegion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-10-01  | Unknown             | No Swagger            |

### \$.properties.dataProtection.replication.replicationId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-10-01  | Unknown             | No Swagger            |

### \$.properties.dataProtection.replication.replicationPolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-10-01  | Unknown             | No Swagger            |

### \$.properties.exportPolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.exportPolicy.rules[*].cifs

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-10-01  | Default* (false)    | No Swagger            |
| 2020-02-01  | Default* (false)    | No Swagger            |
| 2020-05-01  | Default* (false)    | No Swagger            |

### \$.properties.exportPolicy.rules[*].hasRootAccess

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-05-01  | Default* (true)     | No Swagger            |

### \$.properties.exportPolicy.rules[*].nfsv4

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-10-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.exportPolicy.rules[*].nfsv41

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Default* (false)    | No Swagger            |

### \$.properties.mountTargets

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-10-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |
| 2020-05-01  | Unknown             | No Swagger            |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-10-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |
| 2020-05-01  | Unknown             | No Swagger            |

### \$.properties.ownerId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.protocolTypes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.serviceLevel

| API version | Detected noise type   | Determined noise type |
| ----------- | --------------------- | --------------------- |
| 2019-11-01  | Default* ("Standard") | No Swagger            |

### \$.properties.snapshotId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.usageThreshold

| API version | Detected noise type     | Determined noise type |
| ----------- | ----------------------- | --------------------- |
| 2019-07-01  | Default* (107374182400) | No Swagger            |
| 2019-11-01  | Default* (107374182400) | No Swagger            |

### \$.properties.usedBytes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Default (0)         | No Swagger            |
| 2019-10-01  | Default (0)         | No Swagger            |
| 2019-11-01  | Default (0)         | No Swagger            |
| 2020-02-01  | Default (0)         | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-10-01  | Unknown             | No Swagger            |

## netAppAccounts/capacityPools

![cleanliness](https://img.shields.io/badge/cleanliness-16.67%25%20(1%20/%206)-orange) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%205)-red)

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.size

| API version | Detected noise type      | Determined noise type |
| ----------- | ------------------------ | --------------------- |
| 2019-07-01  | Default* (4398046511104) | No Swagger            |
| 2019-11-01  | Default* (4398046511104) | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | No Swagger            |

## netAppAccounts

![cleanliness](https://img.shields.io/badge/cleanliness-84.62%25%20(11%20/%2013)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |
