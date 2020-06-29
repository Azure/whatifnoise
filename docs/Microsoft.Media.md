# Microsoft.Media

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## mediaservices

![cleanliness](https://img.shields.io/badge/cleanliness-87.50%25%20(7%20/%208)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties.storageAccounts[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-01  | Unknown             | No Swagger            |
