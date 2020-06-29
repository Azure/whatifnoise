# Microsoft.HdInsight

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## clusters/applications

![cleanliness](https://img.shields.io/badge/cleanliness-80.00%25%20(56%20/%2070)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2014)-red)

### \$.properties.computeProfile.roles[*].VMGroupName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |

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
| 2015-03-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.sshEndpoints

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |

## clusters

![cleanliness](https://img.shields.io/badge/cleanliness-61.22%25%20(60%20/%2098)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2038)-red)

### \$.identity.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |

### \$.location

| API version        | Detected noise type         | Determined noise type |
| ------------------ | --------------------------- | --------------------- |
| 2015-03-01-preview | Default* ("Southeast Asia") | No Swagger            |

### \$.properties.clusterDefinition.blueprint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.clusterDefinition.componentVersion

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.clusterDefinition.configurations

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.clusterHdpVersion

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.clusterLoginPassword

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |

### \$.properties.clusterVersion

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.computeProfile.roles

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |

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

### \$.properties.computeProfile.roles[*].osProfile.linuxOperatingSystemProfile.disablePasswordAuthentication

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |

### \$.properties.computeProfile.roles[*].osProfile.linuxOperatingSystemProfile.sshProfile

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.computeProfile.roles[*].scriptActions

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |

### \$.properties.computeProfile.roles[*].targetInstanceCount

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Default* (2)        | No Swagger            |

### \$.properties.computeProfile.roles[*].virtualNetworkProfile.id

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |

### \$.properties.computeProfile.roles[*].virtualNetworkProfile.subnet

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |

### \$.properties.securityProfile.isHibEnabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |

### \$.properties.securityProfile.organizationalUnitDN

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |

### \$.properties.sshPassword

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |

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

| API version        | Detected noise type  | Determined noise type |
| ------------------ | -------------------- | --------------------- |
| 2015-03-01-preview | Default ("standard") | No Swagger            |
| 2018-06-01-preview | Default ("standard") | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-01-preview | Unknown             | No Swagger            |
