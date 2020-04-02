# Microsoft.OperationsManagement

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## solutions

![5.88%25](https://img.shields.io/badge/5.88%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-red)

### \$.plan.name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | Unknown               |

### \$.plan.version

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.properties.ETag

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.properties.configurations[*].Name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.properties.configurations[*].Value

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.properties.configurations[*].name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.properties.configurations[*].value

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.properties.containedResources

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | Unknown               |

### \$.properties.containedResources[*]

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.properties.creationTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.properties.lastModifiedTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | Read-only             |

### \$.properties.referencedResources

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | Unknown               |

### \$.properties.referencedResources[*]

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.properties.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.properties.workbookTemplates

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | Unknown               |

### \$.tags.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | Unknown               |
