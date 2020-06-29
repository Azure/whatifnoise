# Microsoft.Security

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## automations

![cleanliness](https://img.shields.io/badge/cleanliness-78.26%25%20(18%20/%2023)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%205)-red)

### \$.properties.actions[*].connectionString

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-01-01-preview | Unknown             | No Swagger            |

### \$.properties.actions[*].sasPolicyName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-01-01-preview | Unknown             | No Swagger            |

### \$.properties.actions[*].uri

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-01-01-preview | Unknown             | No Swagger            |

### \$.properties.metadata

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-01-01-preview | Unknown             | No Swagger            |

### \$.properties.sources[*].eventVersionType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-01-01-preview | Unknown             | No Swagger            |

## ioTSecuritySolutions

![cleanliness](https://img.shields.io/badge/cleanliness-90.91%25%20(20%20/%2022)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties.recommendationsConfiguration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.userDefinedResources

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

## locations/jitNetworkAccessPolicies

![cleanliness](https://img.shields.io/badge/cleanliness-96.00%25%20(24%20/%2025)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties.appendMode

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-01-preview | Default* (false)    | No Swagger            |

## servervulnerabilityassessments

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-01-preview | Unknown             | No Swagger            |

## workspaceSettings

![cleanliness](https://img.shields.io/badge/cleanliness-66.67%25%20(2%20/%203)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties.workspaceId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-08-01-preview | Unknown             | No Swagger            |
