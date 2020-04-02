# Microsoft.CognitiveServices

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## accounts

![13.33%25](https://img.shields.io/badge/13.33%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-orange)

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-02-01-preview | Unknown             | Unknown               |
| 2017-04-18         | Unknown             | Unknown               |

### \$.properties.callRateLimit

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-02-01-preview | Unknown             | No Swagger            |
| 2017-04-18         | Unknown             | No Swagger            |

### \$.properties.customSubDomainName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-02-01-preview | Unknown             | No Swagger            |
| 2017-04-18         | Unknown             | Unknown               |

### \$.properties.dateCreated

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-02-01-preview | Unknown             | Read-only             |
| 2017-04-18         | Unknown             | Read-only             |

### \$.properties.internalId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-02-01-preview | Unknown             | No Swagger            |

### \$.properties.quotaLimit

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-02-01-preview | Unknown             | No Swagger            |
| 2017-04-18         | Unknown             | No Swagger            |

### \$.properties.statisticsEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-18  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-18  | Unknown             | Unknown               |

### \$.tags.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-02-01-preview | Unknown             | Unknown               |
| 2017-04-18         | Unknown             | Unknown               |
