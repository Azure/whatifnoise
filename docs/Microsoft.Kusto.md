# Microsoft.Kusto

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## clusters/databases/principalassignments

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-11-09  | Unknown             | No Swagger            |

## clusters/databases

![6.25%25](https://img.shields.io/badge/6.25%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-red)

### \$.kind

| API version | Detected noise type    | Determined noise type |
| ----------- | ---------------------- | --------------------- |
| 2019-09-07  | Default* ("ReadWrite") | Unknown               |

### \$.properties.hotCachePeriod

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-07-preview | Unknown             | No Swagger            |
| 2019-05-15         | Unknown             | Unknown               |

### \$.properties.hotCachePeriodInDays

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-15  | Unknown             | No Swagger            |
| 2019-09-07  | Unknown             | No Swagger            |

### \$.properties.isFollowed

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-07-preview | Unknown             | No Swagger            |
| 2019-01-21         | Unknown             | No Swagger            |
| 2019-05-15         | Unknown             | No Swagger            |
| 2019-09-07         | Unknown             | No Swagger            |

### \$.properties.softDeletePeriod

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-07-preview | Unknown             | No Swagger            |
| 2019-05-15         | Unknown             | Unknown               |

### \$.properties.softDeletePeriodInDays

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-15  | Unknown             | No Swagger            |
| 2019-09-07  | Unknown             | No Swagger            |

### \$.properties.statistics

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-07  | Unknown             | Read-only             |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-07-preview | Unknown             | Unknown               |
| 2019-09-07         | Unknown             | No Swagger            |

## clusters

![9.09%25](https://img.shields.io/badge/9.09%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-red)

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-07-preview | Unknown             | Unknown               |
| 2019-01-21         | Unknown             | Unknown               |

### \$.properties.enableDiskEncryption

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-15  | Default* (false)    | Unknown               |
| 2019-11-09  | Default* (false)    | Unknown               |
| 2020-02-15  | Default* (false)    | Unknown               |

### \$.properties.enableStreamingIngest

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-15  | Default* (false)    | Default (false)       |

### \$.properties.trustedExternalTenants

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-15  | Unknown             | Unknown               |

### \$.sku.capacity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-15  | Default* (2)        | Unknown               |
| 2019-11-09  | Default* (2)        | Unknown               |
| 2020-02-15  | Default* (2)        | Unknown               |

### \$.sku.name

| API version        | Detected noise type          | Determined noise type |
| ------------------ | ---------------------------- | --------------------- |
| 2018-09-07-preview | Default* ("Standard_D13_v2") | Unknown               |
