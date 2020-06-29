# Microsoft.HybridCompute

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## machines/extensions

![cleanliness](https://img.shields.io/badge/cleanliness-81.82%25%20(18%20/%2022)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%204)-red)

### \$.properties.autoUpgradeMinorVersion

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-08-02-preview | Default* (false)    | No Swagger            |

### \$.properties.instanceView

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-08-02-preview | Unknown             | No Swagger            |

### \$.properties.protectedSettings

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-08-02-preview | Unknown             | No Swagger            |

### \$.properties.typeHandlerVersion

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-08-02-preview | Unknown             | No Swagger            |
