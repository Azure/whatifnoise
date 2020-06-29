# Microsoft.Cache

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## redis/linkedServers

![cleanliness](https://img.shields.io/badge/cleanliness-80.00%25%20(4%20/%205)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties.linkedRedisCacheLocation

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | Unknown               |

## redis/patchSchedules

![cleanliness](https://img.shields.io/badge/cleanliness-20.00%25%20(1%20/%205)-orange) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%204)-red)

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

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2070)-red)

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |

### \$.properties.enableNonSslPort

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-04-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-03-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.minimumTlsVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-04-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-03-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-01  | Unknown             | No Swagger            |
| 2018-03-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.redisConfiguration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-04-01  | Unknown             | No Swagger            |
| 2017-02-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-03-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.redisConfiguration.aof-backup-enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |
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
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-04-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

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
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.shardCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |

### \$.properties.staticIP

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-04-01  | Unknown             | No Swagger            |
| 2017-02-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-03-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.subnet

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.subnetId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-01  | Unknown             | No Swagger            |

### \$.properties.virtualNetwork

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-04-01  | Unknown             | No Swagger            |
| 2018-03-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-01  | Unknown             | No Swagger            |
| 2018-03-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
