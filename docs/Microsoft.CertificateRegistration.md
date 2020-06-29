# Microsoft.CertificateRegistration

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## certificateOrders/certificates

![cleanliness](https://img.shields.io/badge/cleanliness-80.00%25%20(4%20/%205)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties.keyVaultSecretName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |

## certificateOrders

![cleanliness](https://img.shields.io/badge/cleanliness-94.82%25%20(183%20/%20193)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2010)-red)

### \$.properties.DistinguishedName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.ProductType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.ValidityInYears

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.autoRenew

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default* (true)     | No Swagger            |

### \$.properties.certificates

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.csr

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.distinguishedName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.keySize

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default* (2048)     | No Swagger            |

### \$.properties.productType

| API version | Detected noise type                     | Determined noise type |
| ----------- | --------------------------------------- | --------------------- |
| 2015-08-01  | Default* ("StandardDomainValidatedSsl") | No Swagger            |

### \$.properties.validityInYears

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default* (1)        | No Swagger            |
