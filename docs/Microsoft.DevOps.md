# Microsoft.DevOps

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## pipelines

![cleanliness](https://img.shields.io/badge/cleanliness-85.00%25%20(34%20/%2040)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%206)-red)

### \$.properties.bootstrapConfiguration.repository.authorization

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-07-01-preview | Unknown             | Unknown               |

### \$.properties.bootstrapConfiguration.template.parameters.azureAuth

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-07-01-preview | Unknown             | No Swagger            |

### \$.properties.organization

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-07-01-preview | Unknown             | No Swagger            |

### \$.properties.organization.name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-07-01-preview | Unknown             | No Swagger            |

### \$.properties.project

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-07-01-preview | Unknown             | No Swagger            |

### \$.properties.project.name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-07-01-preview | Unknown             | No Swagger            |
