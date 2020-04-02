# Microsoft.Cache

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## redis/linkedServers

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.linkedRedisCacheLocation

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | Unknown               |

## redis/patchSchedules

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.scheduleEntries[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.scheduleEntries[*].dayOfWeek

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Default* ("Sunday") | No Swagger            |

## redis

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.enableNonSslPort

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-04-01  | Unknown             | Unknown               |
| 2017-10-01  | Unknown             | Unknown               |
| 2018-03-01  | Unknown             | Unknown               |

### \$.properties.minimumTlsVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Default* (1.2)      | Unknown               |

### \$.properties.redisConfiguration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-04-01  | Unknown             | Unknown               |
| 2017-02-01  | Unknown             | Unknown               |
| 2017-10-01  | Unknown             | Unknown               |
| 2018-03-01  | Unknown             | Unknown               |
| 2019-07-01  | Unknown             | Unknown               |

### \$.properties.redisConfiguration.aof-backup-enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.redisConfiguration.aof-storage-connection-string-0

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.redisConfiguration.aof-storage-connection-string-1

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.redisConfiguration.maxclients

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-04-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-03-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.redisConfiguration.maxfragmentationmemory-reserved

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-04-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-03-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.redisConfiguration.maxmemory-delta

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-04-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-03-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.redisConfiguration.maxmemory-policy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |

### \$.properties.redisConfiguration.maxmemory-reserved

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-04-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-03-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.redisConfiguration.rdb-storage-connection-string

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |

### \$.properties.redisVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.staticIP

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2017-02-01  | Unknown             | Unknown               |
| 2017-10-01  | Unknown             | Unknown               |
| 2018-03-01  | Unknown             | Unknown               |
| 2019-07-01  | Unknown             | Unknown               |

### \$.properties.subnet

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.subnetId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |

### \$.properties.virtualNetwork

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | Unknown               |
| 2019-07-01  | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | Unknown               |
