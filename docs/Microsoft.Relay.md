# Microsoft.Relay

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## namespaces/authorizationRules

![cleanliness](https://img.shields.io/badge/cleanliness-0.00%25%20(0%20/%202)-red) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.location

| API version | Detected noise type  | Determined noise type |
| ----------- | -------------------- | --------------------- |
| 2017-04-01  | Default* ("West US") | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

## namespaces/hybridConnections/authorizationRules

![cleanliness](https://img.shields.io/badge/cleanliness-50.00%25%20(1%20/%202)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.location

| API version | Detected noise type  | Determined noise type |
| ----------- | -------------------- | --------------------- |
| 2017-04-01  | Default* ("West US") | No Swagger            |

## namespaces/hybridConnections

![cleanliness](https://img.shields.io/badge/cleanliness-50.00%25%20(3%20/%206)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%203)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.requiresClientAuthorization

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Default* (true)     | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

## namespaces/wcfRelays/authorizationRules

![cleanliness](https://img.shields.io/badge/cleanliness-50.00%25%20(1%20/%202)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

## namespaces/wcfRelays

![cleanliness](https://img.shields.io/badge/cleanliness-55.56%25%20(5%20/%209)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%204)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.path

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.requiresClientAuthorization

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.requiresTransportSecurity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

## namespaces

![cleanliness](https://img.shields.io/badge/cleanliness-11.11%25%20(1%20/%209)-orange) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%208)-red)

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-07-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.namespaceType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.properties.status

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-07-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

### \$.sku.tier

| API version | Detected noise type   | Determined noise type |
| ----------- | --------------------- | --------------------- |
| 2017-04-01  | Default* ("Standard") | No Swagger            |
