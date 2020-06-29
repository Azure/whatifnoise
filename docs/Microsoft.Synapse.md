# Microsoft.Synapse

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## workspaces/bigdatapools

![cleanliness](https://img.shields.io/badge/cleanliness-95.24%25%20(20%20/%2021)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties.creationDate

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

## workspaces/firewallrules

![cleanliness](https://img.shields.io/badge/cleanliness-75.00%25%20(3%20/%204)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

## workspaces/managedIdentitySqlControlSettings

![cleanliness](https://img.shields.io/badge/cleanliness-75.00%25%20(3%20/%204)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

## workspaces/sqlPools/metadataSync

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%205)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.Enabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.isPreExistingEntity

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Default* (true)     | No Swagger            |

### \$.properties.result

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.syncIntervalInMinutes

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Default* (1)        | No Swagger            |

## workspaces/sqlPools

![cleanliness](https://img.shields.io/badge/cleanliness-53.85%25%20(7%20/%2013)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%206)-red)

### \$.properties.createMode

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.creationDate

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.maxSizeBytes

| API version        | Detected noise type        | Determined noise type |
| ------------------ | -------------------------- | --------------------- |
| 2019-06-01-preview | Default* (263882790666240) | No Swagger            |

### \$.properties.restorePointInTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.status

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

## workspaces

![cleanliness](https://img.shields.io/badge/cleanliness-89.66%25%20(26%20/%2029)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%203)-red)

### \$.properties.connectivityEndpoints

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.privateEndpointConnections

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |
