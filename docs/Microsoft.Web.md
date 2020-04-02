# Microsoft.Web

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## certificates

![4.23%25](https://img.shields.io/badge/4.23%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.expirationDate

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2014-11-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.friendlyName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2014-11-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.hostNames

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2014-11-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.hostNames[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.issueDate

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2014-11-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.issuer

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2014-11-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.keyVaultSecretName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.keyVaultSecretStatus

| API version | Detected noise type | Determined noise type                              |
| ----------- | ------------------- | -------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2014-11-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Read-only                                          |

### \$.properties.mode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.password

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2014-11-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |

### \$.properties.pfxBlob

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2014-11-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |

### \$.properties.serverFarmId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.subjectName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2014-11-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.thumbprint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2014-11-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.webSpace

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2014-11-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |

## connectionGateways

![6.67%25](https://img.shields.io/badge/6.67%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-red)

### \$.properties.backendUri

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01-preview | Unknown             | No Swagger            |
| 2016-06-01         | Unknown             | Unknown               |

### \$.properties.connectionGatewayInstallation.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01-preview | Unknown             | No Swagger            |
| 2016-06-01         | Unknown             | Unknown               |

### \$.properties.connectionGatewayInstallation.name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01-preview | Unknown             | No Swagger            |
| 2016-06-01         | Unknown             | Unknown               |

### \$.properties.connectionGatewayInstallation.type

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01-preview | Unknown             | No Swagger            |
| 2016-06-01         | Unknown             | Unknown               |

### \$.properties.contactInformation

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01-preview | Unknown             | No Swagger            |
| 2016-06-01         | Unknown             | Unknown               |

### \$.properties.displayName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01-preview | Unknown             | No Swagger            |
| 2016-06-01         | Unknown             | Unknown               |

### \$.properties.machineName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01-preview | Unknown             | No Swagger            |
| 2016-06-01         | Unknown             | Unknown               |

### \$.properties.status

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Read-only             |

## connections

![5.66%25](https://img.shields.io/badge/5.66%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-red)

### \$.properties.api.brandColor

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-06-01         | Unknown             | Unknown               |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.api.category

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-06-01         | Unknown             | No Swagger            |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.api.description

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-06-01         | Unknown             | Unknown               |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.api.displayName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-06-01         | Unknown             | Unknown               |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.api.iconUri

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-06-01         | Unknown             | Unknown               |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.api.id

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-06-01         | Unknown             | Unknown               |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.api.integrationServiceEnvironment

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-06-01         | Unknown             | No Swagger            |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.api.name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-06-01         | Unknown             | Unknown               |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.api.type

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-06-01         | Unknown             | Unknown               |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.changedTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-06-01         | Unknown             | Read-only             |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.createdTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-06-01         | Unknown             | Read-only             |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.displayName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-06-01         | Unknown             | Unknown               |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.nonSecretParameterValues

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-06-01         | Unknown             | Unknown               |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.nonSecretParameterValues.salesforceApiVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.parameterValues

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-06-01         | Unknown             | Unknown               |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameterValues.accessKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameterValues.api_key

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameterValues.authType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameterValues.disableUploadFilesResumeCapability

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-07-01-preview | Default* (false)    | No Swagger            |

### \$.properties.parameterValues.gateway.name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameterValues.gateway.type

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameterValues.giveUpSecurityAndAcceptAnySshHostKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-07-01-preview | Default* (true)     | No Swagger            |

### \$.properties.parameterValues.hostName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameterValues.integrationAccountUrl

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameterValues.password

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameterValues.sharedkey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameterValues.sqlConnectionString

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameterValues.sshPrivateKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameterValues.sshPrivateKeyPassphrase

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameterValues.token:clientSecret

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameterValues.username

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.statuses

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-06-01         | Unknown             | Read-only             |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.testLinks

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-06-01         | Unknown             | Unknown               |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.testLinks[*].requestUri

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-06-01         | Unknown             | Unknown               |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Unknown               |

## customApis

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.apiDefinitions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Unknown               |

### \$.properties.apiType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Default* ("Rest")   | Unknown               |

### \$.properties.backendService

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Unknown               |

### \$.properties.connectionParameters

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Unknown               |

### \$.properties.connectionParameters.token.oAuthSettings.clientSecret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.connectionParameters.token.oAuthSettings.properties.AzureActiveDirectoryResourceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.description

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Unknown               |

### \$.properties.integrationServiceEnvironment.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.integrationServiceEnvironment.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.runtimeUrls

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Unknown               |

### \$.properties.swagger

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Unknown               |

## hostingEnvironments

![12.68%25](https://img.shields.io/badge/12.68%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-orange)

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.allowedMultiSizes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.allowedWorkerSizes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.clusterSettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-09-01  | Unknown             | Unknown               |

### \$.properties.databaseEdition

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.databaseServiceObjective

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.defaultFrontEndScaleFactor

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Default* (15)       | No Swagger            |
| 2015-08-01  | Default* (15)       | No Swagger            |

### \$.properties.dnsSuffix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.environmentCapacities

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |

### \$.properties.environmentIsHealthy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Default* (true)     | No Swagger            |
| 2015-08-01  | Default* (true)     | Unknown               |

### \$.properties.environmentStatus

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.frontEndScaleFactor

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-02-01  | Default (15)        | No Swagger, Default (15) (inheritted from 2016-09-01) |
| 2015-08-01  | Default (15)        | No Swagger, Default (15) (inheritted from 2016-09-01) |
| 2016-09-01  | Default (15)        | Default (15)                                          |
| 2017-08-01  | Default (15)        | No Swagger, Default (15) (inheritted from 2018-02-01) |
| 2018-02-01  | Default (15)        | Default (15)                                          |
| 2019-01-01  | Default (15)        | No Swagger, Default (15) (inheritted from 2019-08-01) |
| 2019-02-01  | Default (15)        | No Swagger, Default (15) (inheritted from 2019-08-01) |
| 2019-08-01  | Default (15)        | Default (15)                                          |

### \$.properties.hasLinuxWorkers

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | No Swagger            |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | Unknown               |
| 2019-01-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.internalLoadBalancingMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-09-01  | Unknown             | Unknown               |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | Unknown               |
| 2019-01-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.ipsslAddressCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2017-08-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |

### \$.properties.lastAction

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.lastActionResult

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-09-01  | Unknown             | Unknown               |
| 2019-01-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.maximumNumberOfMachines

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.multiRoleCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-09-01  | Unknown             | Unknown               |
| 2017-08-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.multiSize

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-09-01  | Unknown             | Unknown               |
| 2017-08-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | Unknown               |
| 2019-01-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |

### \$.properties.publicHost

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | No Swagger            |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.resourceGroup

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.status

| API version | Detected noise type | Determined noise type                              |
| ----------- | ------------------- | -------------------------------------------------- |
| 2015-02-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Read-only                                          |

### \$.properties.subscriptionId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.suspended

| API version | Detected noise type | Determined noise type                                    |
| ----------- | ------------------- | -------------------------------------------------------- |
| 2015-02-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2015-08-01) |
| 2015-08-01  | Default (false)     | Default (false)                                          |
| 2016-09-01  | Default (false)     | Default (false)                                          |
| 2017-08-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2018-02-01) |
| 2018-02-01  | Default (false)     | Default (false)                                          |
| 2019-01-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2019-08-01) |
| 2019-02-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2019-08-01) |
| 2019-08-01  | Default (false)     | Default (false)                                          |

### \$.properties.upgradeDomains

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Default* (20)       | No Swagger            |
| 2015-08-01  | Default* (20)       | Unknown               |

### \$.properties.upgradePreference

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | No Swagger            |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.vipMappings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |

### \$.properties.virtualNetwork.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | Unknown               |

### \$.properties.virtualNetwork.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.virtualNetwork.subnet

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | Unknown               |

### \$.properties.virtualNetwork.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.vnetName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-09-01  | Unknown             | Unknown               |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | Unknown               |
| 2019-01-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.vnetResourceGroupName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-09-01  | Unknown             | Unknown               |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | Unknown               |
| 2019-01-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.vnetSubnetName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-09-01  | Unknown             | Unknown               |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | Unknown               |
| 2019-01-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.workerPools[*].isLinux

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Default (false)     | No Swagger            |
| 2015-08-01  | Default (false)     | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | Unknown               |

## serverFarms

![35.65%25](https://img.shields.io/badge/35.65%25-%E2%98%85★★★%E2%98%86☆☆☆☆☆-yellow)

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | Unknown               |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.appServicePlanWorkerSize

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.capacity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.clusterSetting

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.computeMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.currentNumberOfWorkers

| API version | Detected noise type | Determined noise type                              |
| ----------- | ------------------- | -------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Read-only                                          |
| 2016-03-01  | Unknown             | No Swagger, Read-only (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Read-only                                          |
| 2017-08-01  | Unknown             | No Swagger, Read-only (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Read-only                                          |
| 2018-11-01  | Unknown             | No Swagger, Read-only (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Read-only                                          |

### \$.properties.currentWorkerSize

| API version | Detected noise type | Determined noise type                              |
| ----------- | ------------------- | -------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Read-only                                          |
| 2016-03-01  | Unknown             | No Swagger                                         |

### \$.properties.currentWorkerSizeId

| API version | Detected noise type | Determined noise type                              |
| ----------- | ------------------- | -------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Read-only                                          |
| 2016-03-01  | Unknown             | No Swagger, Read-only (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Read-only                                          |
| 2017-08-01  | Unknown             | No Swagger, Read-only (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Read-only                                          |
| 2018-11-01  | Unknown             | No Swagger, Read-only (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Read-only                                          |

### \$.properties.enableEventGrid

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Default (false)     | No Swagger            |
| 2015-02-01  | Default (false)     | No Swagger            |
| 2015-04-01  | Default (false)     | No Swagger            |

### \$.properties.environment

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.family

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.freeOfferExpirationTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.homeStamp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.properties.hostingEnvironment

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.hostingEnvironmentId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | No Swagger            |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.hostingEnvironmentProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | Unknown               |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.hostingEnvironmentProfile.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | Unknown               |

### \$.properties.hostingEnvironmentProfile.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.hostingEnvironmentProfile.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.hyperV

| API version | Detected noise type | Determined noise type                                    |
| ----------- | ------------------- | -------------------------------------------------------- |
| 2014-06-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2018-02-01) |
| 2015-02-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2018-02-01) |
| 2015-04-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2018-02-01) |
| 2015-08-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2018-02-01) |
| 2016-03-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2018-02-01) |
| 2016-09-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2018-02-01) |
| 2017-08-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2018-02-01) |
| 2018-02-01  | Default (false)     | Default (false)                                          |
| 2018-11-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2019-08-01) |
| 2019-08-01  | Default (false)     | Default (false)                                          |

### \$.properties.isLinux

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |

### \$.properties.isSpot

| API version | Detected noise type | Determined noise type                                    |
| ----------- | ------------------- | -------------------------------------------------------- |
| 2014-06-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2016-09-01) |
| 2015-02-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2016-09-01) |
| 2015-04-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2016-09-01) |
| 2015-08-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2016-09-01) |
| 2016-03-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2016-09-01) |
| 2016-09-01  | Default (false)     | Default (false)                                          |
| 2017-08-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2018-02-01) |
| 2018-02-01  | Default (false)     | Default (false)                                          |
| 2018-11-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2019-08-01) |
| 2019-08-01  | Default (false)     | Default (false)                                          |

### \$.properties.isXenon

| API version | Detected noise type | Determined noise type                                    |
| ----------- | ------------------- | -------------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Default (false) (inheritted from 2018-02-01) |
| 2015-02-01  | Unknown             | No Swagger, Default (false) (inheritted from 2018-02-01) |
| 2015-04-01  | Unknown             | No Swagger, Default (false) (inheritted from 2018-02-01) |
| 2015-08-01  | Unknown             | No Swagger, Default (false) (inheritted from 2018-02-01) |
| 2016-03-01  | Unknown             | No Swagger, Default (false) (inheritted from 2018-02-01) |
| 2016-09-01  | Unknown             | No Swagger, Default (false) (inheritted from 2018-02-01) |
| 2017-08-01  | Unknown             | No Swagger, Default (false) (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Default (false)                                          |
| 2018-11-01  | Unknown             | No Swagger, Default (false) (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Default (false)                                          |

### \$.properties.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | No Swagger            |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.lastModifiedTimeUtc

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.properties.maximumElasticWorkerCount

| API version | Detected noise type | Determined noise type                              |
| ----------- | ------------------- | -------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Read-only                                          |
| 2016-03-01  | Unknown             | No Swagger, Read-only (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Read-only                                          |
| 2017-08-01  | Unknown             | No Swagger, Read-only (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Read-only                                          |
| 2018-11-01  | Unknown             | No Swagger, Read-only (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Read-only                                          |

### \$.properties.maximumNumberOfWorkers

| API version | Detected noise type | Determined noise type                              |
| ----------- | ------------------- | -------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Read-only                                          |

### \$.properties.mdmId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | No Swagger            |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.mode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-09-01  | Unknown             | Unknown               |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.numberOfWorkers

| API version | Detected noise type | Determined noise type                              |
| ----------- | ------------------- | -------------------------------------------------- |
| 2015-02-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Read-only                                          |
| 2016-03-01  | Unknown             | No Swagger, Read-only (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Read-only                                          |
| 2017-08-01  | Unknown             | No Swagger, Read-only (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Read-only                                          |
| 2018-11-01  | Unknown             | No Swagger, Read-only (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Read-only                                          |

### \$.properties.perSiteScaling

| API version | Detected noise type | Determined noise type                                    |
| ----------- | ------------------- | -------------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger                                               |
| 2015-04-01  | Unknown             | No Swagger                                               |
| 2015-08-01  | Unknown             | Unknown                                                  |
| 2016-03-01  | Unknown             | No Swagger, Default (false) (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Default (false)                                          |
| 2017-08-01  | Unknown             | No Swagger, Default (false) (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Default (false)                                          |
| 2018-11-01  | Unknown             | No Swagger, Default (false) (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Default (false)                                          |

### \$.properties.planName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | No Swagger            |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.reserved

| API version | Detected noise type | Determined noise type                                    |
| ----------- | ------------------- | -------------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger                                               |
| 2015-02-01  | Unknown             | No Swagger                                               |
| 2015-04-01  | Unknown             | No Swagger                                               |
| 2015-08-01  | Unknown             | Unknown                                                  |
| 2016-03-01  | Unknown             | No Swagger, Default (false) (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Default (false)                                          |
| 2017-08-01  | Unknown             | No Swagger, Default (false) (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Default (false)                                          |
| 2018-11-01  | Unknown             | No Swagger, Default (false) (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Default (false)                                          |

### \$.properties.serverFarmId

| API version | Detected noise type | Determined noise type                              |
| ----------- | ------------------- | -------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Read-only                                          |
| 2016-03-01  | Unknown             | No Swagger, Read-only (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Read-only                                          |
| 2017-08-01  | Unknown             | No Swagger, Read-only (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Read-only                                          |
| 2018-11-01  | Unknown             | No Swagger, Read-only (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Read-only                                          |

### \$.properties.siteMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.size

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.properties.spotExpirationTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | Unknown               |

### \$.properties.supportsHttpsTrafficOnly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | No Swagger            |

### \$.properties.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | No Swagger            |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.targetWorkerCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | Unknown               |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.targetWorkerSizeId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | Unknown               |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.use32BitWorkerProcess

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.properties.webSpace

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | No Swagger            |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.workerSize

| API version | Detected noise type | Determined noise type                              |
| ----------- | ------------------- | -------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Read-only                                          |
| 2016-03-01  | Unknown             | No Swagger                                         |

### \$.properties.workerSizeId

| API version | Detected noise type | Determined noise type                              |
| ----------- | ------------------- | -------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Read-only (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Read-only                                          |
| 2016-03-01  | Unknown             | No Swagger, Read-only (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Read-only                                          |
| 2017-08-01  | Unknown             | No Swagger, Read-only (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Read-only                                          |
| 2018-11-01  | Unknown             | No Swagger, Read-only (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Read-only                                          |

### \$.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.sku.capacity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | Unknown               |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | Unknown               |

### \$.sku.family

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | Unknown               |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | Unknown               |

### \$.sku.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | Unknown               |

### \$.sku.size

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | Unknown               |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | Unknown               |

### \$.sku.tier

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | Unknown               |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | Unknown               |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | Unknown               |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | Unknown               |

## sites/config

![98.77%25](https://img.shields.io/badge/98.77%25-%E2%98%85★★★★★★★★★-brightgreen)

### \$.identity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.location

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.APPINSIGHTS_INSTRUMENTATIONKEY

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.AlwaysOn

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.IpSecurityRestrictions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.NetFrameworkVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.Use32BitWorkerProcess

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.alwaysOn

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.apiDefinition

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.apiManagementConfig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |

### \$.properties.appCommandLine

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.appSettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |

### \$.properties.applicationLogs

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |

### \$.properties.applicationLogs.azureBlobStorage

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.applicationLogs.azureBlobStorage.level

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |

### \$.properties.applicationLogs.azureBlobStorage.retentionInDays

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.applicationLogs.azureBlobStorage.sasUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.applicationLogs.azureTableStorage

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.applicationLogs.fileSystem

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |

### \$.properties.applicationLogs.fileSystem.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.applicationLogs.fileSystem.retentionInDays

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |

### \$.properties.applicationLogs.fileSystem.retentionInMb

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |

### \$.properties.autoHealEnabled

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.autoHealRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.azureMonitorLogCategories

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.connectionStrings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |

### \$.properties.cors

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.cors.allowedOrigins

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.cors.supportCredentials

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Default (false)     | Put-as-patch          |
| 2018-02-01  | Default (false)     | Put-as-patch          |
| 2019-08-01  | Default (false)     | Put-as-patch          |

### \$.properties.customAppPoolIdentityAdminState

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.customAppPoolIdentityTenantState

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Default (false)     | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-06-01  | Default (false)     | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Default (false)     | Put-as-patch                                          |
| 2016-03-01  | Default (false)     | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Default (false)     | Put-as-patch                                          |
| 2018-02-01  | Default (false)     | Put-as-patch                                          |
| 2018-11-01  | Default (false)     | Put-as-patch                                          |
| 2019-08-01  | Default (false)     | Put-as-patch                                          |

### \$.properties.defaultDocuments

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.detailedErrorLoggingEnabled

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.detailedErrorMessages

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.detailedErrorMessages.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Default* (true)     | Put-as-patch          |

### \$.properties.experiments

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.failedRequestsTracing

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.failedRequestsTracing.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Default* (true)     | Put-as-patch          |

### \$.properties.fileChangeAuditEnabled

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Default (false)     | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-06-01  | Default (false)     | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Default (false)     | Put-as-patch                                          |
| 2016-03-01  | Default (false)     | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Default (false)     | Put-as-patch                                          |
| 2018-02-01  | Default (false)     | Put-as-patch                                          |
| 2018-11-01  | Default (false)     | Put-as-patch                                          |
| 2019-08-01  | Default (false)     | Put-as-patch                                          |

### \$.properties.ftpsState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.functionsRuntimeScaleMonitoringEnabled

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Default (false)     | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-06-01  | Default (false)     | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Default (false)     | Put-as-patch                                          |
| 2016-03-01  | Default (false)     | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Default (false)     | Put-as-patch                                          |
| 2018-02-01  | Default (false)     | Put-as-patch                                          |
| 2018-11-01  | Default (false)     | Put-as-patch                                          |
| 2019-08-01  | Default (false)     | Put-as-patch                                          |

### \$.properties.http20Enabled

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.httpLoggingEnabled

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.httpLogs

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.httpLogs.azureBlobStorage

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.httpLogs.azureBlobStorage.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default* (false)    | Put-as-patch          |

### \$.properties.httpLogs.azureBlobStorage.retentionInDays

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.httpLogs.azureBlobStorage.sasUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.httpLogs.fileSystem

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.httpLogs.fileSystem.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default* (true)     | Put-as-patch          |
| 2016-08-01  | Default* (true)     | Put-as-patch          |

### \$.properties.httpLogs.fileSystem.retentionInDays

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |

### \$.properties.httpsOnly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |

### \$.properties.ipSecurityRestrictions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.ipSecurityRestrictions[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.ipSecurityRestrictions[*].Priority

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.ipSecurityRestrictions[*].action

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.ipSecurityRestrictions[*].description

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.ipSecurityRestrictions[*].ipAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.ipSecurityRestrictions[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.ipSecurityRestrictions[*].priority

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Default* (65000)    | Put-as-patch          |

### \$.properties.ipSecurityRestrictions[*].tag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Default ("Default") | Put-as-patch          |
| 2018-11-01  | Default ("Default") | Put-as-patch          |
| 2019-08-01  | Default ("Default") | Put-as-patch          |

### \$.properties.javaVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.limits

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.linuxFxVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.loadBalancing

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.localMySqlEnabled

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.logsDirectorySizeLimit

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.managedPipelineMode

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.managedServiceIdentityId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.minTlsVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.netFrameworkVersion

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.numberOfWorkers

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.phpVersion

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.preWarmedInstanceCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Default* (0)        | Put-as-patch          |

### \$.properties.publishingUsername

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.pythonVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.remoteDebuggingEnabled

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.remoteDebuggingVersion

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.requestTracingEnabled

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.requestTracingExpirationTime

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |

### \$.properties.reservedInstanceCount

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |

### \$.properties.scmIpSecurityRestrictions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.scmIpSecurityRestrictionsUseMain

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.scmIpSecurityRestrictions[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.scmIpSecurityRestrictions[*].tag

| API version | Detected noise type  | Determined noise type |
| ----------- | -------------------- | --------------------- |
| 2018-11-01  | Default* ("Default") | Put-as-patch          |
| 2019-08-01  | Default* ("Default") | Put-as-patch          |

### \$.properties.scmType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteAuthEnabled

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteAuthSettings

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteAuthSettings.clientId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.siteAuthSettings.clientSecret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteAuthSettings.defaultProvider

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteAuthSettings.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteAuthSettings.isAadAutoProvisioned

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Default (false)     | Put-as-patch          |
| 2018-11-01  | Default (false)     | Put-as-patch          |

### \$.properties.siteAuthSettings.issuer

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.siteAuthSettings.tokenStoreEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteAuthSettings.unauthenticatedClientAction

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.use32BitWorkerProcess

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.virtualApplications

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.virtualApplications[*].physicalPath

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualApplications[*].preloadEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualApplications[*].virtualPath

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.vnetName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.webSocketsEnabled

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.websiteTimeZone

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.winAuthAdminState

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Default (0)         | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-06-01  | Default (0)         | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Default (0)         | Put-as-patch                                          |
| 2016-03-01  | Default (0)         | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Default (0)         | Put-as-patch                                          |
| 2018-02-01  | Default (0)         | Put-as-patch                                          |
| 2018-11-01  | Default (0)         | Put-as-patch                                          |
| 2019-08-01  | Default (0)         | Put-as-patch                                          |

### \$.properties.winAuthTenantState

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Default (0)         | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-06-01  | Default (0)         | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Default (0)         | Put-as-patch                                          |
| 2016-03-01  | Default (0)         | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Default (0)         | Put-as-patch                                          |
| 2018-02-01  | Default (0)         | Put-as-patch                                          |
| 2018-11-01  | Default (0)         | Put-as-patch                                          |
| 2019-08-01  | Default (0)         | Put-as-patch                                          |

### \$.properties.xManagedServiceIdentityId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.tags

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

## sites/domainOwnershipIdentifiers

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Unknown               |

## sites/extensions

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |

## sites/functions

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.config_href

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | Unknown               |

### \$.properties.files

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |

### \$.properties.href

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |

### \$.properties.invoke_url_template

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.isDisabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Default* (false)    | No Swagger            |
| 2018-02-01  | Default* (false)    | Unknown               |
| 2018-11-01  | Default* (false)    | No Swagger            |

### \$.properties.language

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.script_href

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | Unknown               |

### \$.properties.script_root_path_href

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | Unknown               |

### \$.properties.test_data

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.test_data_href

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

## sites/hostnameBindings

![12.82%25](https://img.shields.io/badge/12.82%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-orange)

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Unknown               |

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | Unknown               |

### \$.properties.appName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.hostNameType

| API version | Detected noise type  | Determined noise type                                         |
| ----------- | -------------------- | ------------------------------------------------------------- |
| 2015-08-01  | Default ("Verified") | Default ("Verified")                                          |
| 2016-03-01  | Default ("Verified") | No Swagger, Default ("Verified") (inheritted from 2016-08-01) |
| 2016-08-01  | Default ("Verified") | Default ("Verified")                                          |
| 2018-02-01  | Default ("Verified") | Default ("Verified")                                          |
| 2018-11-01  | Default ("Verified") | Default ("Verified")                                          |

### \$.properties.minTlsVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.siteName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.sslState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |

### \$.properties.thumbprint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.toUpdate

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

## sites/hybridConnectionNamespaces/relays

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.hostname

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Unknown               |

### \$.properties.port

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Unknown               |

### \$.properties.relayName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Unknown               |

### \$.properties.sendKeyValue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.serviceBusNamespace

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Unknown               |

### \$.properties.serviceBusSuffix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Unknown               |

## sites/networkConfig

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type  | Determined noise type |
| ----------- | -------------------- | --------------------- |
| 2019-08-01  | Default* ("West US") | No Swagger            |

### \$.properties.swiftSupported

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Default* (true)     | No Swagger            |

## sites/publicCertificates

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.blob

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

## sites/siteextensions

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

## sites/slots/config

![11.97%25](https://img.shields.io/badge/11.97%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-orange)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.alwaysOn

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.appCommandLine

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Unknown               |

### \$.properties.applicationLogs

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.applicationLogs.azureBlobStorage

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.applicationLogs.azureBlobStorage.sasUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |

### \$.properties.applicationLogs.azureTableStorage

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | Unknown               |

### \$.properties.applicationLogs.fileSystem.retentionInDays

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.applicationLogs.fileSystem.retentionInMb

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.autoHealEnabled

| API version | Detected noise type | Determined noise type                                    |
| ----------- | ------------------- | -------------------------------------------------------- |
| 2015-08-01  | Default (false)     | Default (false)                                          |
| 2016-03-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2016-08-01) |
| 2016-08-01  | Default (false)     | Default (false)                                          |
| 2018-11-01  | Default (false)     | Default (false)                                          |

### \$.properties.autoHealRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Unknown               |

### \$.properties.azureMonitorLogCategories

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.clientAffinityEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.cors

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.cors.supportCredentials

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Default* (false)    | No Swagger            |

### \$.properties.customAppPoolIdentityAdminState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2016-03-01  | Default (false)     | No Swagger            |
| 2016-08-01  | Default (false)     | No Swagger            |
| 2018-11-01  | Default (false)     | No Swagger            |
| 2019-08-01  | Default (false)     | No Swagger            |

### \$.properties.customAppPoolIdentityTenantState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2016-03-01  | Default (false)     | No Swagger            |
| 2016-08-01  | Default (false)     | No Swagger            |
| 2018-11-01  | Default (false)     | No Swagger            |
| 2019-08-01  | Default (false)     | No Swagger            |

### \$.properties.defaultDocuments

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.detailedErrorLoggingEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.detailedErrorMessages

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.experiments

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |

### \$.properties.failedRequestsTracing

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.fileChangeAuditEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2016-03-01  | Default (false)     | No Swagger            |
| 2016-08-01  | Default (false)     | No Swagger            |
| 2018-11-01  | Default (false)     | No Swagger            |
| 2019-08-01  | Default (false)     | No Swagger            |

### \$.properties.ftpsState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.functionsRuntimeScaleMonitoringEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2016-03-01  | Default (false)     | No Swagger            |
| 2016-08-01  | Default (false)     | No Swagger            |
| 2018-11-01  | Default (false)     | No Swagger            |
| 2019-08-01  | Default (false)     | No Swagger            |

### \$.properties.http20Enabled

| API version | Detected noise type | Determined noise type                                   |
| ----------- | ------------------- | ------------------------------------------------------- |
| 2015-08-01  | Unknown             | No Swagger, Default (true) (inheritted from 2016-08-01) |
| 2016-03-01  | Unknown             | No Swagger, Default (true) (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Default (true)                                          |
| 2018-11-01  | Unknown             | Default (true)                                          |
| 2019-08-01  | Unknown             | Default (true)                                          |

### \$.properties.httpLoggingEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.httpLogs

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.httpLogs.azureBlobStorage

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.httpLogs.azureBlobStorage.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default* (false)    | Unknown               |

### \$.properties.httpLogs.azureBlobStorage.retentionInDays

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.httpLogs.azureBlobStorage.sasUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |

### \$.properties.httpLogs.fileSystem

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.httpLogs.fileSystem.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default* (true)     | Unknown               |

### \$.properties.ipSecurityRestrictions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.ipSecurityRestrictions[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.ipSecurityRestrictions[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.ipSecurityRestrictions[*].priority

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.ipSecurityRestrictions[*].tag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.linuxFxVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Unknown               |

### \$.properties.loadBalancing

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.localMySqlEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | Default (false)       |
| 2016-08-01  | Default (false)     | Default (false)       |
| 2018-11-01  | Default (false)     | Default (false)       |

### \$.properties.logsDirectorySizeLimit

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.managedPipelineMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.managedServiceIdentityId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.minTlsVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.netFrameworkVersion

| API version | Detected noise type | Determined noise type                                     |
| ----------- | ------------------- | --------------------------------------------------------- |
| 2015-08-01  | Unknown             | Unknown                                                   |
| 2016-03-01  | Unknown             | No Swagger, Default ("v4.6") (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Default ("v4.6")                                          |
| 2018-11-01  | Unknown             | Default ("v4.6")                                          |
| 2019-08-01  | Unknown             | Default ("v4.6")                                          |

### \$.properties.numberOfWorkers

| API version | Detected noise type | Determined noise type                                |
| ----------- | ------------------- | ---------------------------------------------------- |
| 2015-08-01  | Default (1)         | Default (1)                                          |
| 2016-03-01  | Default (1)         | No Swagger, Default (1) (inheritted from 2016-08-01) |
| 2016-08-01  | Default (1)         | Default (1)                                          |
| 2018-11-01  | Default (1)         | Default (1)                                          |

### \$.properties.phpVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.preWarmedInstanceCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Default* (0)        | Unknown               |

### \$.properties.publishingUsername

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.remoteDebuggingEnabled

| API version | Detected noise type | Determined noise type                                    |
| ----------- | ------------------- | -------------------------------------------------------- |
| 2015-08-01  | Default (false)     | Default (false)                                          |
| 2016-03-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2016-08-01) |
| 2016-08-01  | Default (false)     | Default (false)                                          |
| 2018-11-01  | Default (false)     | Default (false)                                          |

### \$.properties.remoteDebuggingVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.requestTracingEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.requestTracingExpirationTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-08-01  | Unknown             | Unknown               |

### \$.properties.reservedInstanceCount

| API version | Detected noise type | Determined noise type                                |
| ----------- | ------------------- | ---------------------------------------------------- |
| 2015-08-01  | Default (0)         | No Swagger, Default (0) (inheritted from 2018-11-01) |
| 2016-03-01  | Default (0)         | No Swagger, Default (0) (inheritted from 2018-11-01) |
| 2016-08-01  | Default (0)         | No Swagger, Default (0) (inheritted from 2018-11-01) |
| 2018-11-01  | Default (0)         | Default (0)                                          |

### \$.properties.scmIpSecurityRestrictions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.scmIpSecurityRestrictionsUseMain

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Default* (false)    | Unknown               |
| 2019-08-01  | Default* (false)    | Unknown               |

### \$.properties.scmType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.serverFarmId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.siteAuthEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2016-03-01  | Default (false)     | No Swagger            |
| 2016-08-01  | Default (false)     | No Swagger            |
| 2018-11-01  | Default (false)     | No Swagger            |
| 2019-08-01  | Default (false)     | No Swagger            |

### \$.properties.siteAuthSettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.siteAuthSettings.isAadAutoProvisioned

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Default* (false)    | No Swagger            |

### \$.properties.siteConfig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.use32BitWorkerProcess

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.virtualApplications

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.virtualApplications[*].PhysicalPath

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.virtualApplications[*].PreloadEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.virtualApplications[*].VirtualPath

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.virtualApplications[*].physicalPath

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.virtualApplications[*].preloadEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.virtualApplications[*].virtualPath

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.vnetName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-08-01  | Unknown             | Unknown               |

### \$.properties.webSocketsEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.websiteTimeZone

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.winAuthAdminState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (0)         | No Swagger            |
| 2016-03-01  | Default (0)         | No Swagger            |
| 2016-08-01  | Default (0)         | No Swagger            |
| 2018-11-01  | Default (0)         | No Swagger            |
| 2019-08-01  | Default (0)         | No Swagger            |

### \$.properties.winAuthTenantState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (0)         | No Swagger            |
| 2016-03-01  | Default (0)         | No Swagger            |
| 2016-08-01  | Default (0)         | No Swagger            |
| 2018-11-01  | Default (0)         | No Swagger            |
| 2019-08-01  | Default (0)         | No Swagger            |

### \$.properties.xManagedServiceIdentityId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

## sites/slots/extensions

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

## sites/slots/hostNameBindings

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Unknown               |

### \$.properties.app

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.hostNameType

| API version | Detected noise type   | Determined noise type |
| ----------- | --------------------- | --------------------- |
| 2016-03-01  | Default* ("Verified") | No Swagger            |
| 2016-08-01  | Default* ("Verified") | Unknown               |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.siteName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.slot

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.sslState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | Unknown               |

### \$.properties.thumbprint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |

### \$.properties.toUpdate

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

## sites/slots/hybridConnectionNamespaces/relays

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.hostname

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Unknown               |

### \$.properties.port

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Default* (80)       | Unknown               |

### \$.properties.relayName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Unknown               |

### \$.properties.sendKeyValue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Unknown               |

### \$.properties.serviceBusSuffix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Unknown               |

## sites/slots/publicCertificates

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.blob

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Unknown               |

## sites/slots/siteextensions

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |

## sites/slots/virtualNetworkConnections

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.certBlob

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Unknown               |

### \$.properties.isSwift

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Default* (false)    | No Swagger            |
| 2018-02-01  | Default* (false)    | Unknown               |

## sites/slots

![14.24%25](https://img.shields.io/badge/14.24%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-orange)

### \$.identity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |

### \$.identity.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.adminEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Default (true)      | No Swagger            |
| 2015-08-01  | Default (true)      | No Swagger            |
| 2016-03-01  | Default (true)      | No Swagger            |
| 2016-08-01  | Default (true)      | No Swagger            |
| 2018-02-01  | Default (true)      | No Swagger            |
| 2018-11-01  | Default (true)      | No Swagger            |
| 2019-08-01  | Default (true)      | No Swagger            |

### \$.properties.alwaysOn

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.appSettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.authType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.buildVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.clientAffinityEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.clientCertEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.clientCertExclusionPaths

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | Unknown               |

### \$.properties.containerSize

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.contentAvailabilityState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Default (0)         | No Swagger            |
| 2015-08-01  | Default (0)         | No Swagger            |
| 2016-03-01  | Default (0)         | No Swagger            |

### \$.properties.customDomainVerificationId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.dailyMemoryTimeQuota

| API version | Detected noise type | Determined noise type                                |
| ----------- | ------------------- | ---------------------------------------------------- |
| 2015-04-01  | Default (0)         | No Swagger, Default (0) (inheritted from 2016-08-01) |
| 2015-08-01  | Default (0)         | No Swagger, Default (0) (inheritted from 2016-08-01) |
| 2016-08-01  | Default (0)         | Default (0)                                          |
| 2018-02-01  | Default (0)         | Default (0)                                          |
| 2018-11-01  | Default (0)         | Default (0)                                          |
| 2019-08-01  | Default (0)         | Default (0)                                          |

### \$.properties.dbType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.deploymentId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (true)      | Default (true)        |
| 2016-08-01  | Default (true)      | Default (true)        |
| 2018-02-01  | Default (true)      | Default (true)        |
| 2018-11-01  | Default (true)      | Default (true)        |
| 2019-08-01  | Default (true)      | Default (true)        |

### \$.properties.homeStamp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.hostNameSslStates

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.hostNameSslStates[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.hostNameSslStates[*].hostType

| API version | Detected noise type     | Determined noise type |
| ----------- | ----------------------- | --------------------- |
| 2016-08-01  | Default* ("Repository") | No Swagger            |

### \$.properties.hostNameSslStates[*].ipBasedSslState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.hostNameSslStates[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.hostNameSslStates[*].sslState

| API version | Detected noise type   | Determined noise type |
| ----------- | --------------------- | --------------------- |
| 2016-08-01  | Default* ("Disabled") | No Swagger            |

### \$.properties.hostNamesDisabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | Default (false)       |
| 2016-08-01  | Default (false)     | Default (false)       |
| 2018-02-01  | Default (false)     | Default (false)       |
| 2018-11-01  | Default (false)     | Default (false)       |
| 2019-08-01  | Default (false)     | Default (false)       |

### \$.properties.hostingEnvironment

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.hostingEnvironmentId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.hostingEnvironmentProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.hostingEnvironmentProfile.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.hostingEnvironmentProfile.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.hostingEnvironmentsId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.http20Enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.httpsOnly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.hyperV

| API version | Detected noise type | Determined noise type                                    |
| ----------- | ------------------- | -------------------------------------------------------- |
| 2015-04-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2018-02-01) |
| 2015-08-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2018-02-01) |
| 2016-03-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2018-02-01) |
| 2016-08-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2018-02-01) |
| 2018-02-01  | Default (false)     | Default (false)                                          |
| 2018-11-01  | Default (false)     | Default (false)                                          |
| 2019-08-01  | Default (false)     | Default (false)                                          |

### \$.properties.inboundIpAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.ipSecurityRestrictions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.isXenon

| API version | Detected noise type | Determined noise type                                    |
| ----------- | ------------------- | -------------------------------------------------------- |
| 2015-04-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2018-02-01) |
| 2015-08-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2018-02-01) |
| 2016-03-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2018-02-01) |
| 2016-08-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2018-02-01) |
| 2018-02-01  | Default (false)     | Default (false)                                          |
| 2018-11-01  | Default (false)     | Default (false)                                          |
| 2019-08-01  | Default (false)     | Default (false)                                          |

### \$.properties.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.localCacheOption

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.minTlsVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.mode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.phpVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.possibleInboundIpAddresses

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.possibleOutboundIpAddresses

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.redundancyMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.reserved

| API version | Detected noise type | Determined noise type                                    |
| ----------- | ------------------- | -------------------------------------------------------- |
| 2015-04-01  | Unknown             | No Swagger, Default (false) (inheritted from 2016-08-01) |
| 2015-08-01  | Unknown             | No Swagger, Default (false) (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Default (false)                                          |
| 2018-02-01  | Unknown             | Default (false)                                          |
| 2018-11-01  | Unknown             | Default (false)                                          |
| 2019-08-01  | Unknown             | Default (false)                                          |

### \$.properties.runtimeAvailabilityState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Default (0)         | No Swagger            |
| 2015-08-01  | Default (0)         | No Swagger            |
| 2016-03-01  | Default (0)         | No Swagger            |

### \$.properties.scmSiteAlsoStopped

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | Default (false)       |
| 2016-08-01  | Default (false)     | Default (false)       |
| 2018-02-01  | Default (false)     | Default (false)       |
| 2018-11-01  | Default (false)     | Default (false)       |
| 2019-08-01  | Default (false)     | Default (false)       |

### \$.properties.selfLink

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.serverFarmId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.setParameters

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.siteDisabledReason

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Default (0)         | No Swagger            |
| 2015-08-01  | Default (0)         | No Swagger            |
| 2016-03-01  | Default (0)         | No Swagger            |
| 2016-08-01  | Default (0)         | No Swagger            |
| 2018-02-01  | Default (0)         | No Swagger            |
| 2018-11-01  | Default (0)         | No Swagger            |
| 2019-08-01  | Default (0)         | No Swagger            |

### \$.properties.siteProperties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.slotSwapStatus

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.storageRecoveryDefaultState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.targetBuildVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.webSpace

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.websiteDynamicCache

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

## sites/sourcecontrols

![13.33%25](https://img.shields.io/badge/13.33%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-orange)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.IsManualIntegration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |

### \$.properties.RepoUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |

### \$.properties.branch

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Unknown               |

### \$.properties.deploymentRollbackEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | Default (false)       |
| 2018-11-01  | Default (false)     | Default (false)       |

### \$.properties.isGitHubAction

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2016-03-01  | Default (false)     | No Swagger            |
| 2016-08-01  | Default (false)     | No Swagger            |
| 2018-02-01  | Default (false)     | No Swagger            |
| 2018-11-01  | Default (false)     | No Swagger            |

### \$.properties.isManualIntegration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |

### \$.properties.isMercurial

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | Default (false)       |
| 2018-11-01  | Default (false)     | Default (false)       |

### \$.properties.repoUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |

## sites/virtualNetworkConnections

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.certBlob

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |

### \$.properties.certThumbprint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Unknown               |

### \$.properties.isSwift

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default* (false)    | No Swagger            |
| 2016-08-01  | Default* (false)    | No Swagger            |
| 2018-11-01  | Default* (false)    | Unknown               |

### \$.properties.resyncRequired

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default* (false)    | Unknown               |

### \$.properties.swiftSupported

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

## sites

![98.50%25](https://img.shields.io/badge/98.50%25-%E2%98%85★★★★★★★★★-brightgreen)

### \$.identity

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.identity.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.kind

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |

### \$.properties.Enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.HttpsOnly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.InstrumentationKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.TableStorage

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.WEBSITE_RUN_FROM_PACKAGE

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.adminEnabled

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Default (true)      | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Default (true)      | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Default (true)      | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Default (true)      | Put-as-patch                                          |
| 2016-03-01  | Default (true)      | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Default (true)      | Put-as-patch                                          |
| 2017-08-01  | Default (true)      | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Default (true)      | Put-as-patch                                          |
| 2018-11-01  | Default (true)      | Put-as-patch                                          |
| 2019-08-01  | Default (true)      | Put-as-patch                                          |

### \$.properties.buildVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.clientAffinityEnabled

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.clientCertEnabled

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.cloningInfo

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.containerSize

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.contentAvailabilityState

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Default (0)         | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Default (0)         | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Default (0)         | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Default (0)         | Put-as-patch                                          |
| 2016-03-01  | Default (0)         | No Swagger                                            |

### \$.properties.customDomainVerificationId

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.dailyMemoryTimeQuota

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Default (0)         | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Default (0)         | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Default (0)         | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Default (0)         | Put-as-patch                                          |
| 2016-03-01  | Default (0)         | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Default (0)         | Put-as-patch                                          |
| 2018-02-01  | Default (0)         | Put-as-patch                                          |
| 2018-11-01  | Default (0)         | Put-as-patch                                          |
| 2019-08-01  | Default (0)         | Put-as-patch                                          |

### \$.properties.deploymentId

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.enabled

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Default (true)      | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Default (true)      | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Default (true)      | Put-as-patch                                          |
| 2016-03-01  | Default (true)      | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Default (true)      | Put-as-patch                                          |
| 2018-02-01  | Default (true)      | Put-as-patch                                          |
| 2018-11-01  | Default (true)      | Put-as-patch                                          |
| 2019-08-01  | Default (true)      | Put-as-patch                                          |

### \$.properties.environment

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.homeStamp

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.hostNameSslStates

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.hostNameSslStates[*]

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |

### \$.properties.hostNameSslStates[*].hostType

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.hostNameSslStates[*].ipBasedSslState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (0)         | Put-as-patch          |
| 2016-03-01  | Default (0)         | No Swagger            |

### \$.properties.hostNameSslStates[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.hostNameSslStates[*].sslState

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |

### \$.properties.hostNameSslStates[*].thumbprint

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |

### \$.properties.hostNameSslStates[*].toUpdate

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.hostNamesDisabled

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Default (false)     | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Default (false)     | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Default (false)     | Put-as-patch                                          |
| 2016-03-01  | Default (false)     | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Default (false)     | Put-as-patch                                          |
| 2018-02-01  | Default (false)     | Put-as-patch                                          |
| 2018-11-01  | Default (false)     | Put-as-patch                                          |
| 2019-08-01  | Default (false)     | Put-as-patch                                          |

### \$.properties.hostingEnvironment

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.hostingEnvironmentId

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.hostingEnvironmentProfile

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |

### \$.properties.hostingEnvironmentProfile.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |

### \$.properties.hostingEnvironmentProfile.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |

### \$.properties.hostingEnvironmentProfile.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |

### \$.properties.httpsOnly

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.hyperV

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.identity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.inboundIpAddress

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.ipSecurityRestrictions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.isXenon

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.kind

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.localMySqlEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.managedPipelineMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.name

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.netFrameworkVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.possibleInboundIpAddresses

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.possibleOutboundIpAddresses

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.redundancyMode

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.remoteDebuggingVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.reserved

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.runtimeAvailabilityState

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Default (0)         | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Default (0)         | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Default (0)         | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Default (0)         | Put-as-patch                                          |
| 2016-03-01  | Default (0)         | No Swagger                                            |

### \$.properties.scmIpSecurityRestrictions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.scmIpSecurityRestrictionsUseMain

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.scmSiteAlsoStopped

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Default (false)     | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Default (false)     | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Default (false)     | Put-as-patch                                          |
| 2016-03-01  | Default (false)     | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Default (false)     | Put-as-patch                                          |
| 2018-02-01  | Default (false)     | Put-as-patch                                          |
| 2018-11-01  | Default (false)     | Put-as-patch                                          |
| 2019-08-01  | Default (false)     | Put-as-patch                                          |

### \$.properties.selfLink

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.serverFarmId

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteConfig

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteDisabledReason

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Default (0)         | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Default (0)         | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Default (0)         | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Default (0)         | Put-as-patch                                          |
| 2016-03-01  | Default (0)         | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Default (0)         | Put-as-patch                                          |
| 2017-08-01  | Default (0)         | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Default (0)         | Put-as-patch                                          |
| 2018-11-01  | Default (0)         | Put-as-patch                                          |
| 2019-08-01  | Default (0)         | Put-as-patch                                          |

### \$.properties.siteProperties

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteconfig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.sku

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.slotSwapStatus

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.sourcePlatform

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |

### \$.properties.storageRecoveryDefaultState

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.tags

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.targetBuildVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.targetPlatform

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualApplications

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.webSpace

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.tags

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.tags.*

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |
