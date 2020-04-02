# Microsoft.ContainerInstance

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## containerGroups

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.containers

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-08-01-preview | Unknown             | Unknown               |
| 2018-04-01         | Unknown             | Unknown               |

### \$.properties.containers[*].properties.command[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.containers[*].properties.environmentVariables[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.containers[*].properties.environmentVariables[*].secureValue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.containers[*].properties.environmentVariables[*].securevalue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.containers[*].properties.environmentVariables[*].value

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-02-01-preview | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |
| 2018-07-01         | Unknown             | No Swagger            |
| 2018-10-01         | Unknown             | No Swagger            |

### \$.properties.containers[*].properties.resources.requests.memoryInGb

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-08-01-preview | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |
| 2018-10-01         | Unknown             | No Swagger            |

### \$.properties.diagnostics.logAnalytics.workspaceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Unknown               |

### \$.properties.imageRegistryCredentials[*].server

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.imageRegistryCredentials[*].username

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.ipAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | Unknown               |
| 2019-12-01  | Unknown             | No Swagger            |

### \$.properties.ipAddress.ports[*].protocol

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.networkProfile.Id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.networkProfile.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.volumes[*].secret

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-02-01-preview | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |
| 2018-07-01         | Unknown             | No Swagger            |
| 2018-10-01         | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | Unknown               |
| 2018-07-01  | Unknown             | No Swagger            |
