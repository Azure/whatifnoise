# Microsoft.KeyVault

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## vaults/secrets

![41.67%25](https://img.shields.io/badge/41.67%25-%E2%98%85★★★%E2%98%86☆☆☆☆☆-yellow)

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | No Swagger            |

### \$.properties.attributes.created

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | Read-only             |
| 2018-02-14  | Unknown             | Read-only             |

### \$.properties.attributes.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Default (true)      | Default (true)        |

### \$.properties.attributes.exp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | Unknown               |

### \$.properties.attributes.nbf

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | Unknown               |

### \$.properties.attributes.updated

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | Read-only             |
| 2018-02-14  | Unknown             | Read-only             |

### \$.properties.contentType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | Unknown               |

### \$.properties.recoveryLevel

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | No Swagger            |

### \$.properties.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |

## vaults

![13.45%25](https://img.shields.io/badge/13.45%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-orange)

### \$.properties.accessPolicies

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | Unknown               |
| 2016-10-01  | Unknown             | Unknown               |
| 2018-02-14  | Unknown             | Unknown               |

### \$.properties.accessPolicies[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |
| 2016-10-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*]._id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*].comment

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |
| 2016-10-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*].comments

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*].condition

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |
| 2016-10-01  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*].metadata

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*].objectId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-01         | Unknown             | No Swagger            |
| 2016-10-01         | Unknown             | No Swagger            |
| 2018-02-14-preview | Unknown             | No Swagger            |
| 2018-02-14         | Unknown             | No Swagger            |
| 2019-09-01         | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*].objectIdName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*].permissions.certificates[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*].permissions.keys

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*].permissions.keys[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |
| 2016-10-01  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*].permissions.secrets[*]

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-01         | Unknown             | No Swagger            |
| 2016-10-01         | Unknown             | No Swagger            |
| 2018-02-14-preview | Unknown             | No Swagger            |
| 2018-02-14         | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*].tenantId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |
| 2016-10-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.createMode

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-01         | Unknown             | No Swagger            |
| 2016-10-01         | Unknown             | Unknown               |
| 2018-02-14-preview | Unknown             | Unknown               |
| 2018-02-14         | Unknown             | Unknown               |

### \$.properties.createmode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | Unknown               |

### \$.properties.dependsOn

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.enablePurgeProtection

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Default* (true)     | Unknown               |
| 2018-02-14  | Default* (true)     | Unknown               |
| 2019-09-01  | Default* (true)     | Unknown               |

### \$.properties.enableRbacAuthorization

| API version        | Detected noise type | Determined noise type                                    |
| ------------------ | ------------------- | -------------------------------------------------------- |
| 2015-06-01         | Default (false)     | No Swagger, Default (false) (inheritted from 2019-09-01) |
| 2016-10-01         | Default (false)     | No Swagger, Default (false) (inheritted from 2019-09-01) |
| 2018-02-14-preview | Default (false)     | No Swagger, Default (false) (inheritted from 2019-09-01) |
| 2018-02-14         | Default (false)     | No Swagger, Default (false) (inheritted from 2019-09-01) |
| 2019-09-01         | Default (false)     | Default (false)                                          |

### \$.properties.enableSoftDelete

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | Unknown               |
| 2016-10-01  | Unknown             | Unknown               |
| 2018-02-14  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Default (true)        |

### \$.properties.enabledForDeployment

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | Default (false)       |
| 2016-10-01  | Unknown             | Default (false)       |
| 2018-02-14  | Unknown             | Default (false)       |

### \$.properties.enabledForDiskEncryption

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | Default (false)       |
| 2016-10-01  | Unknown             | Default (false)       |
| 2018-02-14  | Unknown             | Default (false)       |

### \$.properties.enabledForTemplateDeployment

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | Default (false)       |
| 2016-10-01  | Unknown             | Default (false)       |
| 2018-02-14  | Unknown             | Default (false)       |

### \$.properties.enabledForVolumeEncryption

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |
| 2016-10-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.enabledSoftDelete

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.enabledforTemplateDeployment

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | Default (false)       |

### \$.properties.firewallState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.mode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.networkAcls

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |
| 2016-10-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Unknown               |

### \$.properties.networkAcls.bypass

| API version | Detected noise type        | Determined noise type |
| ----------- | -------------------------- | --------------------- |
| 2018-02-14  | Default* ("AzureServices") | Unknown               |
| 2019-09-01  | Default* ("AzureServices") | Unknown               |

### \$.properties.networkAcls.defaultAction

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Default* ("Deny")   | Unknown               |

### \$.properties.networkAcls.ipRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |
| 2016-10-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | Unknown               |

### \$.properties.networkAcls.ipRules[*].action

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | No Swagger            |

### \$.properties.networkAcls.ipRules[*].value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |
| 2016-10-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.networkAcls.iprules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | Unknown               |

### \$.properties.networkAcls.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.networkAcls.virtualNetworkRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | Unknown               |

### \$.properties.networkAcls.virtualNetworkRules[*].action

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.networkAcls.virtualNetworkRules[*].ignoreMissingVnetServiceEndpoint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Default* (false)    | No Swagger            |

### \$.properties.networkAcls.virtualNetworkRules[*].resourceGroup

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |

### \$.properties.networkAcls.virtualNetworkRules[*].state

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.objectId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.permissions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.resources

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |
| 2016-10-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.secrets

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.settings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.softDeleteRetentionInDays

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Default* (90)       | No Swagger            |
| 2016-10-01  | Default* (90)       | No Swagger            |

### \$.properties.supportsHttpsTrafficOnly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.tenantId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | Unknown               |
| 2016-10-01  | Unknown             | Unknown               |
| 2018-02-14  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | Unknown               |
| 2016-10-01  | Unknown             | Unknown               |
| 2018-02-14  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Unknown               |

### \$.tags.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-01         | Unknown             | Unknown               |
| 2016-10-01         | Unknown             | Unknown               |
| 2018-02-14-preview | Unknown             | Unknown               |
| 2018-02-14         | Unknown             | Unknown               |
