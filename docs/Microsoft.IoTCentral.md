# Microsoft.IoTCentral

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## ioTApps

![cleanliness](https://img.shields.io/badge/cleanliness-37.50%25%20(3%20/%208)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%205)-red)

### \$.properties.capabilities

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-09-01  | Unknown             | No Swagger            |

### \$.properties.geography

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-09-01  | Unknown             | No Swagger            |

### \$.properties.state

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-09-01  | Unknown             | No Swagger            |

### \$.properties.tenant

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-09-01  | Unknown             | No Swagger            |

### \$.sku.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-09-01  | Default* ("ST2")    | No Swagger            |
