# Microsoft.SignalRService

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## signalR

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Unknown               |

### \$.properties.cors

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-03-01-preview | Unknown             | No Swagger            |
| 2018-10-01         | Unknown             | Unknown               |

### \$.properties.domainLabel

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-03-01-preview | Unknown             | No Swagger            |

### \$.properties.features

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Unknown               |

### \$.properties.features[*]

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-03-01-preview | Unknown             | No Swagger            |
| 2018-10-01         | Unknown             | No Swagger            |

### \$.properties.features[*].condition

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-03-01-preview | Unknown             | No Swagger            |

### \$.properties.features[*].value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.hostNamePrefix

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-03-01-preview | Unknown             | Unknown               |
| 2018-10-01         | Unknown             | Unknown               |

### \$.properties.mode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.networkACLs

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-03-01-preview | Unknown             | No Swagger            |
| 2018-10-01         | Unknown             | No Swagger            |

### \$.properties.siteConfig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.sku.size

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-03-01-preview | Unknown             | Unknown               |
| 2018-10-01         | Unknown             | Unknown               |

### \$.sku.tier

| API version        | Detected noise type   | Determined noise type |
| ------------------ | --------------------- | --------------------- |
| 2018-03-01-preview | Default* ("Standard") | Unknown               |
| 2018-10-01         | Default* ("Standard") | Unknown               |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-03-01-preview | Unknown             | Unknown               |
| 2018-10-01         | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Unknown               |
