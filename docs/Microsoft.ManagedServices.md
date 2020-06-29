# Microsoft.ManagedServices

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## registrationDefinitions

![cleanliness](https://img.shields.io/badge/cleanliness-92.31%25%20(12%20/%2013)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties.authorizations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |
