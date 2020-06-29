# Microsoft.ImportExport

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## jobs

![cleanliness](https://img.shields.io/badge/cleanliness-86.89%25%20(53%20/%2061)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%208)-red)

### \$.identity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.backupDriveManifest

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Default* (false)    | No Swagger            |

### \$.properties.cancelRequested

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Default* (false)    | No Swagger            |

### \$.properties.diagnosticsPath

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.driveList[*].state

| API version | Detected noise type    | Determined noise type |
| ----------- | ---------------------- | --------------------- |
| 2016-11-01  | Default* ("Specified") | No Swagger            |

### \$.properties.encryptionKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.shippingInformation

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |

### \$.properties.state

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-11-01  | Unknown             | No Swagger            |
