# Microsoft.VMwareCloudSimple

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## dedicatedCloudNodes

![cleanliness](https://img.shields.io/badge/cleanliness-72.73%25%20(16%20/%2022)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%206)-red)

### \$.properties.billingHoursLeftInMonth

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Default* (730)      | No Swagger            |

### \$.properties.nodesCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Default* (0)        | No Swagger            |

### \$.properties.purchaseType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.skuDescription.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.sku.name

| API version | Detected noise type                  | Determined noise type |
| ----------- | ------------------------------------ | --------------------- |
| 2019-04-01  | Default* ("VMware_CloudSimple_CS28") | No Swagger            |

## dedicatedcloudservices

![cleanliness](https://img.shields.io/badge/cleanliness-40.00%25%20(2%20/%205)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%203)-red)

### \$.properties.gatewaySubnet

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Unknown               |

### \$.properties.privateCloud

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.purchaseId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |
