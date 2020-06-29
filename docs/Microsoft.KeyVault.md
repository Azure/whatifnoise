# Microsoft.KeyVault

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## vaults/secrets

![cleanliness](https://img.shields.io/badge/cleanliness-16.67%25%20(2%20/%2012)-orange) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2010)-red)

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | No Swagger            |

### \$.properties.attributes.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Default (true)      | No Swagger            |

### \$.properties.attributes.exp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.attributes.nbf

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.contentType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.description

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |

### \$.properties.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | No Swagger            |

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
| 2016-10-01  | Unknown             | No Swagger            |

## vaults

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%20139)-red)

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | No Swagger            |

### \$.properties.accessPolicies

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |
| 2016-10-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*]._description

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*]._id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*].clientId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*].comment

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*].comments

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |
| 2016-10-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*].condition

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |
| 2016-10-01  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*].description

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*].enableSoftDelete

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*].enabledForTemplateDeployment

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*].friendlyName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*].metadata

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | No Swagger            |
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

### \$.properties.accessPolicies[*].objectName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*].permissions.certificates[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |
| 2016-10-01  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*].permissions.keys

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*].permissions.keys[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*].permissions.secrets[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |

### \$.properties.accessPolicies[*].tenantId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |
| 2016-10-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.createMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.createmode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | No Swagger            |

### \$.properties.dependsOn

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.enablePurgeProtection

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Default* (true)     | No Swagger            |
| 2016-10-01  | Default* (true)     | No Swagger            |
| 2018-02-14  | Default* (true)     | No Swagger            |
| 2019-09-01  | Default* (true)     | No Swagger            |

### \$.properties.enableRbacAuthorization

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-01         | Default (false)     | No Swagger            |
| 2016-10-01         | Default (false)     | No Swagger            |
| 2018-02-14-preview | Default (false)     | No Swagger            |
| 2018-02-14         | Default (false)     | No Swagger            |
| 2019-09-01         | Default (false)     | No Swagger            |

### \$.properties.enableSoftDelete

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |
| 2016-10-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.enabledForDeployment

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |
| 2016-10-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.enabledForDiskEncryption

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |
| 2016-10-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.enabledForTemplateDeployment

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |
| 2016-10-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

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
| 2016-10-01  | Unknown             | No Swagger            |

### \$.properties.firewallState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.keyVaultEnableSoftDelete

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |

### \$.properties.keyVaultEnabledForDeployment

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |

### \$.properties.keyVaultEnabledForDiskEncryption

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |

### \$.properties.keyVaultEnabledForTemplateDeployment

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |

### \$.properties.keyVaultSoftDelete

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | No Swagger            |

### \$.properties.mode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | No Swagger            |

### \$.properties.networkAcls

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |
| 2016-10-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.networkAcls.bypass

| API version | Detected noise type       | Determined noise type |
| ----------- | ------------------------- | --------------------- |
| 2018-02-14  | Default ("AzureServices") | No Swagger            |
| 2019-09-01  | Default ("AzureServices") | No Swagger            |

### \$.properties.networkAcls.defaultAction

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Default* ("Deny")   | No Swagger            |

### \$.properties.networkAcls.ipRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |
| 2016-10-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.networkAcls.ipRules[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.networkAcls.ipRules[*].action

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | No Swagger            |

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
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.networkAcls.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.networkAcls.virtualNetworkRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.networkAcls.virtualNetworkRules[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.networkAcls.virtualNetworkRules[*].action

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.networkAcls.virtualNetworkRules[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.networkAcls.virtualNetworkRules[*].ignoreMissingVnetServiceEndpoint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Default* (false)    | No Swagger            |

### \$.properties.networkAcls.virtualNetworkRules[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.networkAcls.virtualNetworkRules[*].resourceGroup

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |
| 2016-10-01  | Unknown             | No Swagger            |

### \$.properties.networkAcls.virtualNetworkRules[*].state

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-10-01  | Unknown             | No Swagger            |
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
| 2015-06-01  | Unknown             | No Swagger            |
| 2016-10-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.supportsHttpsTrafficOnly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | No Swagger            |

### \$.properties.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-14  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.tenantId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |
| 2016-10-01  | Unknown             | No Swagger            |
| 2018-02-14  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.tags.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-01         | Unknown             | No Swagger            |
| 2016-10-01         | Unknown             | No Swagger            |
| 2018-02-14-preview | Unknown             | No Swagger            |
| 2018-02-14         | Unknown             | No Swagger            |
| 2019-09-01         | Unknown             | No Swagger            |
