# Microsoft.PowerBiDedicated

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## capacities

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.administration.members[*]

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-01-01-preview | Unknown             | No Swagger            |
| 2017-10-01         | Unknown             | No Swagger            |

### \$.sku.capacity

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-01-01-preview | Default* (1)        | No Swagger            |
| 2017-10-01         | Default* (1)        | No Swagger            |

### \$.sku.tier

| API version        | Detected noise type     | Determined noise type |
| ------------------ | ----------------------- | --------------------- |
| 2017-01-01-preview | Default* ("PBIE_Azure") | No Swagger            |
| 2017-10-01         | Default* ("PBIE_Azure") | Unknown               |
