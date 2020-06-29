# Microsoft.DataBox

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## jobs

![cleanliness](https://img.shields.io/badge/cleanliness-88.54%25%20(85%20/%2096)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2011)-red)

### \$.identity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |
| 2020-04-01  | Unknown             | No Swagger            |

### \$.properties.deliveryInfo

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |
| 2020-04-01  | Unknown             | No Swagger            |

### \$.properties.deliveryType

| API version | Detected noise type       | Determined noise type |
| ----------- | ------------------------- | --------------------- |
| 2020-04-01  | Default* ("NonScheduled") | No Swagger            |

### \$.properties.details

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |
| 2020-04-01  | Unknown             | No Swagger            |

### \$.properties.isCancellableWithoutFee

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Default (true)      | No Swagger            |

### \$.properties.isPrepareToShipEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Default (false)     | No Swagger            |
| 2020-04-01  | Default (false)     | No Swagger            |

### \$.properties.transferType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |
