# Microsoft.Digitaltwins

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## digitaltwinsinstances/endpoints

![cleanliness](https://img.shields.io/badge/cleanliness-66.67%25%20(4%20/%206)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties.connectionString-PrimaryKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2020-03-01-preview | Unknown             | No Swagger            |

### \$.properties.connectionString-SecondaryKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2020-03-01-preview | Unknown             | No Swagger            |

## digitaltwinsinstances

![cleanliness](https://img.shields.io/badge/cleanliness-85.71%25%20(6%20/%207)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2020-03-01-preview | Unknown             | No Swagger            |
