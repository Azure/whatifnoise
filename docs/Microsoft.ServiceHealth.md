# Microsoft.ServiceHealth

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## healthChecks

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2017)-red)

### \$.properties.healthyStateDuration

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-11-01-preview | Unknown             | No Swagger            |

### \$.properties.initialMonitoringWaitTimeInMinutes

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-11-01-preview | Unknown             | No Swagger            |

### \$.properties.maxElasticDuration

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-11-01-preview | Unknown             | No Swagger            |

### \$.properties.maxElasticDurationInMinutes

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2016-03-01-privatepreview | Default (0)         | No Swagger            |
| 2017-11-01-preview        | Default (0)         | No Swagger            |

### \$.properties.monitorParameters.healthChecks[*].request.authentication.in

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-11-01-preview | Default* (0)        | No Swagger            |

### \$.properties.monitorParameters.healthChecks[*].request.authentication.type

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-11-01-preview | Default* (0)        | No Swagger            |

### \$.properties.monitorParameters.healthChecks[*].request.method

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-11-01-preview | Default* (0)        | No Swagger            |

### \$.properties.monitorParameters.healthChecks[*].response.successStatusCodes[*]

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-11-01-preview | Unknown             | No Swagger            |

### \$.properties.monitorPollingIntervalInSeconds

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-11-01-preview | Default* (30)       | No Swagger            |

### \$.properties.monitorProviderType

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2016-03-01-privatepreview | Unknown             | No Swagger            |
| 2017-11-01-preview        | Unknown             | No Swagger            |

### \$.properties.monitoringDurationInMinutes

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-11-01-preview | Unknown             | No Swagger            |

### \$.properties.pollingInterval

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-11-01-preview | Unknown             | No Swagger            |

### \$.properties.successPercentage

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2016-03-01-privatepreview | Default (0)         | No Swagger            |
| 2017-11-01-preview        | Default (0)         | No Swagger            |

### \$.properties.waitDuration

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-11-01-preview | Unknown             | No Swagger            |
