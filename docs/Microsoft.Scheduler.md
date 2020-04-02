# Microsoft.Scheduler

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## jobCollections/jobs

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.action.errorAction

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | Unknown               |

### \$.properties.action.request.authentication

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-08-01-preview | Unknown             | Unknown               |

### \$.properties.action.request.authentication.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.action.request.uri

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-08-01-preview | Unknown             | Unknown               |

### \$.properties.action.retryPolicy.retryInterval

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-08-01-preview | Unknown             | Unknown               |

### \$.properties.action.serviceBusQueueMessage.authentication.sasKeyName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-01-01  | Unknown             | Unknown               |

### \$.properties.state

| API version | Detected noise type  | Determined noise type |
| ----------- | -------------------- | --------------------- |
| 2016-03-01  | Default* ("enabled") | Unknown               |

## jobCollections

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.state

| API version | Detected noise type  | Determined noise type |
| ----------- | -------------------- | --------------------- |
| 2016-01-01  | Default* ("Enabled") | Unknown               |
| 2016-03-01  | Default* ("Enabled") | Unknown               |
