# Microsoft.VirtualMachineImages

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## imageTemplates

![cleanliness](https://img.shields.io/badge/cleanliness-84.00%25%20(42%20/%2050)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%208)-red)

### \$.properties.buildTimeoutInMinutes

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Default* (0)        | Unknown               |

### \$.properties.customize[*].runElevated

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Default* (false)    | No Swagger            |

### \$.properties.customize[*].sha256Checksum

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |

### \$.properties.distribute[*].aritfactTags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |

### \$.properties.distribute[*].excludeFromLatest

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-14  | Default* (false)    | No Swagger            |

### \$.properties.source.version

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Unknown             | No Swagger            |
| 2020-02-14         | Unknown             | No Swagger            |

### \$.properties.vmProfile.osDiskSizeGB

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-05-01-preview | Default* (0)        | No Swagger            |
