# Microsoft.HdInsight

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## clusters/applications

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.computeProfile.roles[*].encryptDataDisks

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Default* (false)    | No Swagger            |
| 2018-06-01-preview | Default* (false)    | No Swagger            |

### \$.properties.computeProfile.roles[*].hardwareProfile.vmSize

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.httpsEndpoints[*].accessModes[*]

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.httpsEndpoints[*].disableGatewayAuth

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.httpsEndpoints[*].location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.httpsEndpoints[*].publicPort

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Default* (443)      | No Swagger            |

### \$.properties.httpsEndpoints[*].subDomainSuffix

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.installScriptActions[*].parameters

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.sshEndpoints

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | Unknown               |

## clusters

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.identity.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |

### \$.properties.clusterDefinition.blueprint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | Unknown               |

### \$.properties.clusterDefinition.componentVersion

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | Unknown               |

### \$.properties.clusterDefinition.configurations

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | Unknown               |

### \$.properties.clusterHdpVersion

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.clusterVersion

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | Unknown               |

### \$.properties.computeProfile.roles

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | Unknown               |

### \$.properties.computeProfile.roles[*]

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.computeProfile.roles[*].encryptDataDisks

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Default (false)     | No Swagger            |
| 2018-06-01-preview | Default (false)     | No Swagger            |

### \$.properties.computeProfile.roles[*].hardwareProfile.vmSize

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.computeProfile.roles[*].minInstanceCount

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.computeProfile.roles[*].osProfile.linuxOperatingSystemProfile.disablePasswordAuthentication

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |

### \$.properties.computeProfile.roles[*].osProfile.linuxOperatingSystemProfile.sshProfile

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |

### \$.properties.computeProfile.roles[*].scriptActions

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.securityProfile.organizationalUnitDN

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | Unknown               |

### \$.properties.storageProfile.storageaccounts[*].key

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.storageProfile.storageaccounts[*].name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.tier

| API version        | Detected noise type   | Determined noise type |
| ------------------ | --------------------- | --------------------- |
| 2015-03-01-preview | Default* ("standard") | Unknown               |
| 2018-06-01-preview | Default* ("standard") | Unknown               |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | Unknown               |
