# Microsoft.TimeSeriesInsights

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## environments/accessPolicies

![cleanliness](https://img.shields.io/badge/cleanliness-75.00%25%20(3%20/%204)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-02-28-preview | Unknown             | No Swagger            |

## environments/eventSources

![cleanliness](https://img.shields.io/badge/cleanliness-73.33%25%20(11%20/%2015)-yellowgreen) ![progress](https://img.shields.io/badge/progress-33.33%25%20(2%20/%206)-yellow)

### \$.properties.creationTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-02-28-preview | Unknown             | Read-only             |
| 2017-11-15         | Unknown             | Read-only             |
| 2018-08-15-preview | Unknown             | No Swagger            |

### \$.properties.sharedAccessKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-02-28-preview | Unknown             | No Swagger            |
| 2017-11-15         | Unknown             | No Swagger            |
| 2018-08-15-preview | Unknown             | No Swagger            |

## environments/referenceDataSets

![cleanliness](https://img.shields.io/badge/cleanliness-85.71%25%20(6%20/%207)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties.dataStringComparisonBehavior

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-02-28-preview | Unknown             | No Swagger            |

## environments

![cleanliness](https://img.shields.io/badge/cleanliness-75.76%25%20(25%20/%2033)-yellowgreen) ![progress](https://img.shields.io/badge/progress-27.27%25%20(3%20/%2011)-orange)

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
| 2018-08-15-preview | Unknown             | No Swagger            |

### \$.properties.storageLimitExceededBehavior

| API version        | Detected noise type       | Determined noise type |
| ------------------ | ------------------------- | --------------------- |
| 2017-02-28-preview | Default* ("PurgeOldData") | No Swagger            |
| 2017-11-15         | Default* ("PurgeOldData") | No Swagger            |
