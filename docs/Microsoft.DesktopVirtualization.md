# Microsoft.DesktopVirtualization

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## applicationgroups/applications

![cleanliness](https://img.shields.io/badge/cleanliness-60.00%25%20(9%20/%2015)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%206)-red)

### \$.properties.commandLineSetting

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-01-23-preview | Unknown             | Unknown               |

### \$.properties.friendlyName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-10-preview | Unknown             | No Swagger            |

### \$.properties.iconContent

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-01-23-preview | Unknown             | No Swagger            |
| 2019-12-10-preview | Unknown             | No Swagger            |

### \$.properties.iconHash

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-01-23-preview | Unknown             | No Swagger            |
| 2019-12-10-preview | Unknown             | No Swagger            |

## applicationgroups

![cleanliness](https://img.shields.io/badge/cleanliness-0.00%25%20(0%20/%207)-red) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%207)-red)

### \$.kind

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-01-23-preview | Unknown             | No Swagger            |
| 2019-12-10-preview | Unknown             | No Swagger            |

### \$.properties.applicationGroupType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-10-preview | Unknown             | No Swagger            |

### \$.properties.friendlyName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-10-preview | Unknown             | No Swagger            |

### \$.properties.workspaceArmPath

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-01-23-preview | Unknown             | No Swagger            |
| 2019-12-10-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-10-preview | Unknown             | No Swagger            |

## hostPools

![cleanliness](https://img.shields.io/badge/cleanliness-25.00%25%20(5%20/%2020)-orange) ![progress](https://img.shields.io/badge/progress-6.25%25%20(1%20/%2016)-red)

### \$.properties.applicationGroupReferences

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-01-23-preview | Unknown             | Read-only             |
| 2019-12-10-preview | Unknown             | No Swagger            |

### \$.properties.customRdpProperty

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-10-preview | Unknown             | No Swagger            |

### \$.properties.enableUserProfileDisk

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-01-23-preview | Unknown             | No Swagger            |

### \$.properties.hostPoolType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-01-23-preview | Unknown             | No Swagger            |

### \$.properties.maxSessionLimit

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-01-23-preview | Default (999999)    | No Swagger            |
| 2019-12-10-preview | Default (999999)    | No Swagger            |

### \$.properties.personalDesktopAssignmentType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-01-23-preview | Unknown             | No Swagger            |

### \$.properties.preferredAppGroupType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-10-preview | Unknown             | No Swagger            |

### \$.properties.registrationInfo.expirationTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-10-preview | Unknown             | No Swagger            |

### \$.properties.registrationInfo.registrationTokenOperation

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-10-preview | Default ("None")    | No Swagger            |

### \$.properties.registrationInfo.resetToken

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-10-preview | Default (false)     | No Swagger            |

### \$.properties.registrationInfo.token

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-10-preview | Unknown             | No Swagger            |

### \$.properties.validationEnviroment

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-10-preview | Unknown             | No Swagger            |

### \$.properties.validationEnvironment

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-10-preview | Default* (true)     | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-10-preview | Unknown             | No Swagger            |

## workspaces

![cleanliness](https://img.shields.io/badge/cleanliness-40.00%25%20(2%20/%205)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%203)-red)

### \$.properties.applicationGroupReferences[*]

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-10-preview | Unknown             | No Swagger            |

### \$.properties.description

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-10-preview | Unknown             | No Swagger            |

### \$.properties.friendlyName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-10-preview | Unknown             | No Swagger            |
