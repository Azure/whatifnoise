# Microsoft.Kubernetesconfiguration

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## sourcecontrolconfigurations

!> No Swagger.

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

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
