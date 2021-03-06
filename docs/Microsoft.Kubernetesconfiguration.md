# Microsoft.Kubernetesconfiguration

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## sourcecontrolconfigurations

![cleanliness](https://img.shields.io/badge/cleanliness-72.22%25%20(13%20/%2018)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%205)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-11-01-preview | Unknown             | No Swagger            |

### \$.properties.complianceStatus

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-11-01-preview | Unknown             | No Swagger            |

### \$.properties.configKind

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-11-01-preview | Default* (0)        | No Swagger            |

### \$.properties.operatorParams

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-11-01-preview | Unknown             | No Swagger            |

### \$.properties.timeCreated

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-11-01-preview | Unknown             | No Swagger            |
