# Microsoft.TimeSeriesInsights

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## environments/accessPolicies

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-02-28-preview | Unknown             | No Swagger            |

## environments/eventSources

![50.00%25](https://img.shields.io/badge/50.00%25-%E2%98%85★★★★%E2%98%86☆☆☆☆-yellow)

### \$.properties.creationTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-02-28-preview | Unknown             | Read-only             |
| 2017-11-15         | Unknown             | Read-only             |
| 2018-08-15-preview | Unknown             | Read-only             |

### \$.properties.sharedAccessKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-02-28-preview | Unknown             | Unknown               |
| 2017-11-15         | Unknown             | Unknown               |
| 2018-08-15-preview | Unknown             | Unknown               |

## environments/referenceDataSets

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.dataStringComparisonBehavior

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-02-28-preview | Unknown             | No Swagger            |

## environments

![27.27%25](https://img.shields.io/badge/27.27%25-%E2%98%85★★%E2%98%86☆☆☆☆☆☆-orange)

### \$.kind

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-02-28-preview | Unknown             | No Swagger            |
| 2017-11-15         | Unknown             | No Swagger            |

### \$.properties.creationTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-08-15-preview | Unknown             | Read-only             |

### \$.properties.dataAccessFqdn

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-08-15-preview | Unknown             | Read-only             |

### \$.properties.dataAccessId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-08-15-preview | Unknown             | Read-only             |

### \$.properties.requestApiVersion

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-02-28-preview | Unknown             | No Swagger            |
| 2017-11-15         | Unknown             | No Swagger            |
| 2018-08-15-preview | Unknown             | No Swagger            |

### \$.properties.storageConfiguration.managementKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-08-15-preview | Unknown             | Unknown               |

### \$.properties.storageLimitExceededBehavior

| API version        | Detected noise type       | Determined noise type |
| ------------------ | ------------------------- | --------------------- |
| 2017-02-28-preview | Default* ("PurgeOldData") | Unknown               |
| 2017-11-15         | Default* ("PurgeOldData") | Unknown               |
