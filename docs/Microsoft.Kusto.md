# Microsoft.Kusto

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## clusters/databases/principalassignments

![cleanliness](https://img.shields.io/badge/cleanliness-75.00%25%20(6%20/%208)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties.principalId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-15  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-11-09  | Unknown             | No Swagger            |

## clusters/databases

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2019)-red)

### \$.kind

| API version | Detected noise type    | Determined noise type |
| ----------- | ---------------------- | --------------------- |
| 2019-09-07  | Default* ("ReadWrite") | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-15  | Unknown             | No Swagger            |

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
| 2020-02-15  | Unknown             | No Swagger            |

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
| 2019-05-15         | Unknown             | No Swagger            |

### \$.properties.softDeletePeriodInDays

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-15  | Unknown             | No Swagger            |
| 2019-09-07  | Unknown             | No Swagger            |
| 2020-02-15  | Unknown             | No Swagger            |

### \$.properties.statistics

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-07  | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-07-preview | Unknown             | No Swagger            |
| 2019-09-07         | Unknown             | No Swagger            |

## clusters/principalassignments

![cleanliness](https://img.shields.io/badge/cleanliness-75.00%25%20(6%20/%208)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties.principalId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-15  | Unknown             | No Swagger            |

### \$.properties.tenantId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-15  | Unknown             | No Swagger            |

## clusters

![cleanliness](https://img.shields.io/badge/cleanliness-71.74%25%20(33%20/%2046)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2013)-red)

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-07-preview | Unknown             | No Swagger            |
| 2019-01-21         | Unknown             | No Swagger            |

### \$.properties.enableDiskEncryption

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-15  | Default* (false)    | Unknown               |
| 2019-11-09  | Default* (false)    | No Swagger            |
| 2020-02-15  | Default* (false)    | No Swagger            |

### \$.properties.enablePurge

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-15  | Unknown             | No Swagger            |

### \$.properties.enableStreamingIngest

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-15  | Default* (false)    | No Swagger            |

### \$.properties.trustedExternalTenants

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-15  | Unknown             | No Swagger            |
| 2020-02-15  | Unknown             | No Swagger            |

### \$.sku.capacity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-15  | Unknown             | No Swagger            |
| 2019-11-09  | Unknown             | No Swagger            |
| 2020-02-15  | Unknown             | No Swagger            |

### \$.sku.name

| API version        | Detected noise type          | Determined noise type |
| ------------------ | ---------------------------- | --------------------- |
| 2018-09-07-preview | Default* ("Standard_D13_v2") | No Swagger            |
