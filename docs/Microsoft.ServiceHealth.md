# Microsoft.ServiceHealth

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## healthChecks

!> No Swagger.

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.initialMonitoringWaitTimeInMinutes

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-11-01-preview | Default* (1)        | No Swagger            |

### \$.properties.maxElasticDurationInMinutes

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2016-03-01-privatepreview | Default (0)         | No Swagger            |
| 2017-11-01-preview        | Default (0)         | No Swagger            |

### \$.properties.monitorPollingIntervalInSeconds

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-11-01-preview | Default* (30)       | No Swagger            |

### \$.properties.monitorProviderType

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2016-03-01-privatepreview | Default (2)         | No Swagger            |
| 2017-11-01-preview        | Default (2)         | No Swagger            |

### \$.properties.monitoringDurationInMinutes

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-11-01-preview | Default* (3)        | No Swagger            |

### \$.properties.successPercentage

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2016-03-01-privatepreview | Default (0)         | No Swagger            |
| 2017-11-01-preview        | Default (0)         | No Swagger            |
