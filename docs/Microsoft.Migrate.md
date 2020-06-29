# Microsoft.Migrate

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## assessmentProjects/servercollectors

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%205)-red)

### \$.properties.agentProperties.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.agentProperties.lastHeartbeatUtc

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.agentProperties.version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.createdTimestamp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.updatedTimestamp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

## assessmentprojects

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%204)-red)

### \$.properties.ProjectStatus

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.assessmentSolutionId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.numberOfImportMachines

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.projectStatus

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Default* ("Active") | No Swagger            |

## migrateProjects/solutions

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%205)-red)

### \$.properties.cleanupState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.details

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.details.assessmentCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Default* (0)        | No Swagger            |

### \$.properties.details.groupCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Default* (0)        | No Swagger            |

### \$.properties.summary

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

## migrateProjects

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

## movecollections/moveresources

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%205)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-10-01-preview | Unknown             | No Swagger            |

### \$.properties.isResolveRequired

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-10-01-preview | Unknown             | No Swagger            |

### \$.properties.moveStatus

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-10-01-preview | Unknown             | No Swagger            |

### \$.properties.resourceSettings.resourceType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-10-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-10-01-preview | Unknown             | No Swagger            |
