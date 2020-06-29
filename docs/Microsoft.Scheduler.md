# Microsoft.Scheduler

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## jobCollections/jobs

![cleanliness](https://img.shields.io/badge/cleanliness-92.50%25%20(148%20/%20160)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2012)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.action.errorAction

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.action.request.authentication

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-08-01-preview | Unknown             | No Swagger            |

### \$.properties.action.request.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.action.request.retryPolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.action.request.uri

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-08-01-preview | Unknown             | No Swagger            |
| 2016-03-01         | Unknown             | No Swagger            |

### \$.properties.action.retryPolicy.retryInterval

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-08-01-preview | Unknown             | No Swagger            |

### \$.properties.action.serviceBusQueueMessage.authentication.sasKeyName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-01-01  | Unknown             | No Swagger            |

### \$.properties.recurrence.schedule.weekDays[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.startTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-01-01  | Unknown             | No Swagger            |

### \$.properties.state

| API version | Detected noise type  | Determined noise type |
| ----------- | -------------------- | --------------------- |
| 2016-03-01  | Default* ("enabled") | No Swagger            |

## jobCollections

![cleanliness](https://img.shields.io/badge/cleanliness-81.82%25%20(9%20/%2011)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties.state

| API version | Detected noise type  | Determined noise type |
| ----------- | -------------------- | --------------------- |
| 2016-01-01  | Default* ("Enabled") | No Swagger            |
| 2016-03-01  | Default* ("Enabled") | No Swagger            |
