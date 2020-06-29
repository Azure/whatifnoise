# Microsoft.GuestConfiguration

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## guestConfigurationAssignments

![cleanliness](https://img.shields.io/badge/cleanliness-91.30%25%20(21%20/%2023)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties.IsVisibleToARM

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-20  | Default* (true)     | No Swagger            |

### \$.properties.parameterHash

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-20  | Unknown             | No Swagger            |
