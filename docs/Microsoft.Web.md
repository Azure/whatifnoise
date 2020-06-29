# Microsoft.Web

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## certificates

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-brightgreen) ![progress](https://img.shields.io/badge/progress-100.00%25%20(67%20/%2067)-brightgreen)

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | Put-as-patch          |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | Put-as-patch          |

### \$.properties.expirationDate

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2014-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.friendlyName

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2014-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.hostNames

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2014-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.hostNames[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | Put-as-patch          |

### \$.properties.issueDate

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2014-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.issuer

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2014-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.keyVaultSecretName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-03-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.keyVaultSecretStatus

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2014-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.password

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2014-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |

### \$.properties.pfxBlob

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | Put-as-patch          |

### \$.properties.serverFarmId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.subjectName

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2014-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.tags

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.thumbprint

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2014-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.webSpace

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2014-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-03-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.tags.*

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |

## connectionGateways

![cleanliness](https://img.shields.io/badge/cleanliness-10.53%25%20(2%20/%2019)-orange) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2017)-red)

### \$.properties.backendUri

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01-preview | Unknown             | No Swagger            |
| 2016-06-01         | Unknown             | Unknown               |

### \$.properties.connectionGatewayInstallation.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01-preview | Unknown             | No Swagger            |
| 2016-06-01         | Unknown             | No Swagger            |

### \$.properties.connectionGatewayInstallation.name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01-preview | Unknown             | No Swagger            |
| 2016-06-01         | Unknown             | No Swagger            |

### \$.properties.connectionGatewayInstallation.type

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01-preview | Unknown             | No Swagger            |
| 2016-06-01         | Unknown             | No Swagger            |

### \$.properties.contactInformation

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01-preview | Unknown             | No Swagger            |
| 2016-06-01         | Unknown             | No Swagger            |

### \$.properties.description

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.displayName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01-preview | Unknown             | No Swagger            |
| 2016-06-01         | Unknown             | No Swagger            |

### \$.properties.machineName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01-preview | Unknown             | No Swagger            |
| 2016-06-01         | Unknown             | No Swagger            |

### \$.properties.status

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

## connections

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-44.78%25%20(30%20/%2067)-yellow)

### \$.properties.ParameterValues

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.api.brandColor

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01-preview | Unknown             | Put-as-patch          |
| 2016-06-01         | Unknown             | Put-as-patch          |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.api.category

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01-preview | Unknown             | Put-as-patch          |
| 2016-06-01         | Unknown             | Put-as-patch          |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.api.description

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01-preview | Unknown             | Put-as-patch          |
| 2016-06-01         | Unknown             | Put-as-patch          |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.api.displayName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01-preview | Unknown             | Put-as-patch          |
| 2016-06-01         | Unknown             | Put-as-patch          |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.api.iconUri

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01-preview | Unknown             | Put-as-patch          |
| 2016-06-01         | Unknown             | Put-as-patch          |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.api.id

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01-preview | Unknown             | Put-as-patch          |
| 2016-06-01         | Unknown             | Put-as-patch          |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.api.integrationServiceEnvironment

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-06-01         | Unknown             | Put-as-patch          |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.api.name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01-preview | Unknown             | Put-as-patch          |
| 2016-06-01         | Unknown             | Put-as-patch          |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.api.type

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01-preview | Unknown             | Put-as-patch          |
| 2016-06-01         | Unknown             | Put-as-patch          |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.authenticatedUser

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-06-01         | Unknown             | Put-as-patch          |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.changedTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-06-01         | Unknown             | Put-as-patch          |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.createdTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-06-01         | Unknown             | Put-as-patch          |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.customParameterValues

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.displayName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-06-01         | Unknown             | Put-as-patch          |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.nonSecretParameterValues

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-06-01         | Unknown             | Put-as-patch          |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.nonSecretParameterValues.salesforceApiVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Put-as-patch          |

### \$.properties.parameterValues

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
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

### \$.properties.parameterValues.endpoint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-07-01-preview | Unknown             | No Swagger            |

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
| 2016-06-01         | Unknown             | Put-as-patch          |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.testLinks

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-06-01         | Unknown             | Put-as-patch          |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.testLinks[*].requestUri

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-08-01-preview | Unknown             | Put-as-patch          |
| 2016-06-01         | Unknown             | Put-as-patch          |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.tags.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-06-01         | Unknown             | Put-as-patch          |
| 2018-07-01-preview | Unknown             | No Swagger            |

## customApis

![cleanliness](https://img.shields.io/badge/cleanliness-77.61%25%20(52%20/%2067)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2015)-red)

### \$.properties.apiDefinitions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Unknown               |

### \$.properties.apiType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Default ("Rest")    | No Swagger            |

### \$.properties.backendService

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.connectionParameters

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.connectionParameters.token.oAuthSettings.clientSecret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.connectionParameters.token.oAuthSettings.properties.AzureActiveDirectoryResourceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.connectionParameters.token.oAuthSettings.redirectUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.description

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.displayName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.iconUri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

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
| 2016-06-01  | Unknown             | No Swagger            |

### \$.properties.swagger

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |

## hostingEnvironments

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%20157)-red)

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.allowedMultiSizes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.allowedWorkerSizes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.clusterSettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.databaseEdition

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.databaseServiceObjective

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.defaultFrontEndScaleFactor

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Default* (15)       | No Swagger            |
| 2015-08-01  | Default* (15)       | No Swagger            |

### \$.properties.dnsSuffix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.dynamicCacheEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.environmentCapacities

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |

### \$.properties.environmentIsHealthy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Default* (true)     | No Swagger            |
| 2015-08-01  | Default* (true)     | No Swagger            |

### \$.properties.environmentStatus

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.frontEndScaleFactor

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Default (15)        | No Swagger            |
| 2015-08-01  | Default (15)        | No Swagger            |
| 2016-09-01  | Default (15)        | No Swagger            |
| 2017-08-01  | Default (15)        | No Swagger            |
| 2018-02-01  | Default (15)        | No Swagger            |
| 2019-01-01  | Default (15)        | No Swagger            |
| 2019-02-01  | Default (15)        | No Swagger            |
| 2019-08-01  | Default (15)        | No Swagger            |

### \$.properties.hasLinuxWorkers

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

### \$.properties.internalLoadBalancingMode

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

### \$.properties.ipsslAddressCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.lastAction

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.lastActionResult

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.maximumNumberOfMachines

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.multiRoleCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | No Swagger            |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.multiSize

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | No Swagger            |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.osPreference

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2017-08-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

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
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.status

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.subscriptionId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.suspended

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Default (false)     | No Swagger            |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2016-09-01  | Default (false)     | No Swagger            |
| 2017-08-01  | Default (false)     | No Swagger            |
| 2018-02-01  | Default (false)     | No Swagger            |
| 2019-01-01  | Default (false)     | No Swagger            |
| 2019-02-01  | Default (false)     | No Swagger            |
| 2019-08-01  | Default (false)     | No Swagger            |

### \$.properties.upgradeDomains

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Default* (20)       | No Swagger            |
| 2015-08-01  | Default* (20)       | No Swagger            |

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

### \$.properties.virtualNetwork

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.virtualNetwork.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | No Swagger            |

### \$.properties.virtualNetwork.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.virtualNetwork.subnet

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | No Swagger            |

### \$.properties.virtualNetwork.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.vnetName

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

### \$.properties.vnetResourceGroupName

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

### \$.properties.vnetSubnetName

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

### \$.properties.workerPools[*].isLinux

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Default (false)     | No Swagger            |
| 2015-08-01  | Default (false)     | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | No Swagger            |

### \$.zones

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

## serverFarms

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-93.54%25%20(304%20/%20325)-brightgreen)

### \$.identity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | Put-as-patch          |
| 2017-08-01  | Unknown             | No Swagger            |

### \$.kind

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.location

| API version | Detected noise type    | Determined noise type |
| ----------- | ---------------------- | --------------------- |
| 2018-02-01  | Default* ("East US 2") | Put-as-patch          |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |

### \$.properties.alwaysOn

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |

### \$.properties.computeMode

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger                                            |

### \$.properties.currentNumberOfWorkers

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.currentWorkerSize

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger                                            |

### \$.properties.currentWorkerSizeId

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.detailedErrorLoggingEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | Put-as-patch          |
| 2017-08-01  | Unknown             | No Swagger            |

### \$.properties.enableEventGrid

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Default (false)     | No Swagger            |
| 2015-02-01  | Default (false)     | No Swagger            |
| 2015-04-01  | Default (false)     | No Swagger            |

### \$.properties.freeOfferExpirationTime

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.ftpsState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-09-01  | Unknown             | Put-as-patch          |
| 2017-08-01  | Unknown             | No Swagger            |

### \$.properties.homeStamp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.properties.hostingEnvironment

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.hostingEnvironmentId

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.hostingEnvironmentProfile

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.hostingEnvironmentProfile.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | Put-as-patch          |

### \$.properties.hostingEnvironmentProfile.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |

### \$.properties.hostingEnvironmentProfile.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |

### \$.properties.httpLoggingEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | Put-as-patch          |
| 2017-08-01  | Unknown             | No Swagger            |

### \$.properties.hyperV

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Default (false)     | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Default (false)     | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Default (false)     | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Default (false)     | Put-as-patch                                          |
| 2016-03-01  | Default (false)     | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Default (false)     | Put-as-patch                                          |
| 2017-08-01  | Default (false)     | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Default (false)     | Put-as-patch                                          |
| 2018-11-01  | Default (false)     | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Default (false)     | Put-as-patch                                          |

### \$.properties.isSpot

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Default (false)     | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Default (false)     | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Default (false)     | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Default (false)     | Put-as-patch                                          |
| 2016-03-01  | Default (false)     | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Default (false)     | Put-as-patch                                          |
| 2017-08-01  | Default (false)     | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Default (false)     | Put-as-patch                                          |
| 2018-11-01  | Default (false)     | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Default (false)     | Put-as-patch                                          |

### \$.properties.isXenon

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.kind

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.lastModifiedTimeUtc

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.properties.maximumElasticWorkerCount

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.maximumNumberOfWorkers

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.mdmId

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.name

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.netFrameworkVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | Put-as-patch          |
| 2017-08-01  | Unknown             | No Swagger            |

### \$.properties.numberOfWorkers

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.perSiteScaling

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.planName

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.requestTracingEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | Put-as-patch          |
| 2017-08-01  | Unknown             | No Swagger            |

### \$.properties.reserved

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.serverFarmId

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteConfig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |

### \$.properties.siteMode

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.properties.tags

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.targetWorkerCount

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.targetWorkerSizeId

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.webSpace

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.workerSize

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger                                            |

### \$.properties.workerSizeId

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.sku.capacity

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.sku.family

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.sku.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | Put-as-patch          |

### \$.sku.size

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.sku.tier

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.tags

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.tags.*

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-09-01) |
| 2016-09-01  | Unknown             | Put-as-patch                                          |
| 2017-08-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2019-08-01) |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

## sites/config

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-98.83%25%20(421%20/%20426)-brightgreen)

### \$.identity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

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
| 2018-02-01  | Unknown             | Put-as-patch          |

### \$.properties.APPLICATIONINSIGHTS_CONNECTION_STRING

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |

### \$.properties.AlwaysOn

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.ApplicationInsightsAgent_EXTENSION_VERSION

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |

### \$.properties.IpSecurityRestrictions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.MSDEPLOY_RENAME_LOCKED_FILES

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |

### \$.properties.NetFrameworkVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.Use32BitWorkerProcess

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.WEBSITE_RUN_FROM_PACKAGE

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.XDT_MicrosoftApplicationInsights_Mode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |

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
| 2018-11-01  | Unknown             | Put-as-patch          |

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
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.applicationLogs.azureBlobStorage.retentionInMb

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |

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
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.applicationLogs.fileSystem.retentionInDays

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |

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
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.azureMonitorLogCategories

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.connectionStrings

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |

### \$.properties.cors

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.cors.allowedHeaders

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.cors.allowedMethods

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.cors.allowedOrigins

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.cors.allowedOrigins[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.cors.exposedHeaders

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

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

### \$.properties.httpLogs.azureBlobStorage.level

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |

### \$.properties.httpLogs.azureBlobStorage.retentionInDays

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.httpLogs.azureBlobStorage.retentionInMb

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |

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
| 2018-02-01  | Unknown             | Put-as-patch          |

### \$.properties.httpsOnly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-01  | Unknown             | No Swagger            |

### \$.properties.httpsonly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.ipSecurityRestrictions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |

### \$.properties.ipSecurityRestrictions[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.ipSecurityRestrictions[*].Priority

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.ipSecurityRestrictions[*].action

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.ipSecurityRestrictions[*].description

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.ipSecurityRestrictions[*].ipAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.ipSecurityRestrictions[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.ipSecurityRestrictions[*].priority

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.ipSecurityRestrictions[*].tag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.isHttpAllowed

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |

### \$.properties.isSwift

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |

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

### \$.properties.publishingUserpassword

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.push.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Put-as-patch          |

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

### \$.properties.reserved

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Put-as-patch          |

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

### \$.properties.retentionInDays

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.scmIpSecurityRestrictions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |

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

### \$.properties.siteAuthSettings.aadClientId

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteAuthSettings.clientId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.siteAuthSettings.clientSecret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.siteAuthSettings.defaultProvider

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.siteAuthSettings.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.siteAuthSettings.facebookOAuthScopes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.siteAuthSettings.isAadAutoProvisioned

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Default (false)     | Put-as-patch          |
| 2018-11-01  | Default (false)     | Put-as-patch          |

### \$.properties.siteAuthSettings.issuer

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.siteAuthSettings.microsoftAccountOAuthScopes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.siteAuthSettings.openIdIssuer

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |

### \$.properties.siteAuthSettings.tokenStoreEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteAuthSettings.unauthenticatedClientAction

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

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
| 2019-08-01  | Unknown             | Put-as-patch          |

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

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

## sites/deployments

![cleanliness](https://img.shields.io/badge/cleanliness-10.00%25%20(1%20/%2010)-orange) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%209)-red)

### \$.properties.complete

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Default* (true)     | No Swagger            |

### \$.properties.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.is_readonly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Default* (true)     | No Swagger            |

### \$.properties.is_temp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Default* (false)    | No Swagger            |

### \$.properties.last_success_end_time

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.log_url

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.received_time

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.site_name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.url

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

## sites/domainOwnershipIdentifiers

![cleanliness](https://img.shields.io/badge/cleanliness-50.00%25%20(1%20/%202)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

## sites/extensions

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2023)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.dbType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.packageUri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.setParameters

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-02-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2015-02-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |

## sites/functions

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2040)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.config_href

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.files

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.href

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.invoke_url_template

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.isDisabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default* (false)    | No Swagger            |
| 2016-08-01  | Default* (false)    | No Swagger            |
| 2018-02-01  | Default* (false)    | No Swagger            |
| 2018-11-01  | Default* (false)    | No Swagger            |
| 2019-08-01  | Default* (false)    | No Swagger            |

### \$.properties.language

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.script_href

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.script_root_path_href

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.secrets_file_href

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.test_data

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.test_data_href

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

## sites/hostnameBindings

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2047)-red)

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.appName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.azureResourceName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.azureResourceType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.customHostNameDnsRecordType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.hostNameType

| API version | Detected noise type  | Determined noise type |
| ----------- | -------------------- | --------------------- |
| 2015-08-01  | Default ("Verified") | No Swagger            |
| 2016-03-01  | Default ("Verified") | No Swagger            |
| 2016-08-01  | Default ("Verified") | No Swagger            |
| 2018-02-01  | Default ("Verified") | No Swagger            |
| 2018-11-01  | Default ("Verified") | No Swagger            |

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
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.sslState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.thumbprint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.toUpdate

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

## sites/hybridConnectionNamespaces/relays

![cleanliness](https://img.shields.io/badge/cleanliness-60.00%25%20(9%20/%2015)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%206)-red)

### \$.properties.hostname

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Unknown               |

### \$.properties.port

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.relayName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.sendKeyValue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.serviceBusNamespace

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.serviceBusSuffix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

## sites/networkConfig

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%205)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.swiftSupported

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Default* (true)     | No Swagger            |
| 2018-11-01  | Default* (true)     | No Swagger            |

## sites/publicCertificates

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%207)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.blob

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

## sites/siteextensions

![cleanliness](https://img.shields.io/badge/cleanliness-61.76%25%20(21%20/%2034)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2013)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

## sites/slots/config

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%20268)-red)

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.acrUseManagedIdentityCreds

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2016-08-01  | Default (false)     | No Swagger            |
| 2018-11-01  | Default (false)     | No Swagger            |
| 2019-08-01  | Default (false)     | No Swagger            |

### \$.properties.alwaysOn

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.appCommandLine

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.applicationLogs

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.applicationLogs.azureBlobStorage

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.applicationLogs.azureBlobStorage.sasUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.applicationLogs.azureTableStorage

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.applicationLogs.fileSystem.retentionInDays

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.applicationLogs.fileSystem.retentionInMb

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.autoHealEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2016-03-01  | Default (false)     | No Swagger            |
| 2016-08-01  | Default (false)     | No Swagger            |
| 2018-11-01  | Default (false)     | No Swagger            |

### \$.properties.autoHealRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.autoHealRules.actions.minProcessExecutionTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.autoSwapSlotName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.azureMonitorLogCategories

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.clientAffinityEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.clientCertEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.cors

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.cors.supportCredentials

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Default* (false)    | No Swagger            |
| 2018-11-01  | Default* (false)    | No Swagger            |
| 2019-08-01  | Default* (false)    | No Swagger            |

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
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.detailedErrorLoggingEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.detailedErrorMessages

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.experiments

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.failedRequestsTracing

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

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
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.functionsRuntimeScaleMonitoringEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2016-03-01  | Default (false)     | No Swagger            |
| 2016-08-01  | Default (false)     | No Swagger            |
| 2018-11-01  | Default (false)     | No Swagger            |
| 2019-08-01  | Default (false)     | No Swagger            |

### \$.properties.http20Enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.httpLoggingEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.httpLogs

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.httpLogs.azureBlobStorage

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.httpLogs.azureBlobStorage.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default* (false)    | No Swagger            |

### \$.properties.httpLogs.azureBlobStorage.retentionInDays

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.httpLogs.azureBlobStorage.sasUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.httpLogs.fileSystem

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.httpLogs.fileSystem.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default* (true)     | No Swagger            |

### \$.properties.ipSecurityRestrictions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.ipSecurityRestrictions[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.ipSecurityRestrictions[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.ipSecurityRestrictions[*].priority

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.ipSecurityRestrictions[*].tag

| API version | Detected noise type  | Determined noise type |
| ----------- | -------------------- | --------------------- |
| 2018-11-01  | Default* ("Default") | No Swagger            |
| 2019-08-01  | Default* ("Default") | No Swagger            |

### \$.properties.linuxFxVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.loadBalancing

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.localMySqlEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2016-08-01  | Default (false)     | No Swagger            |
| 2018-11-01  | Default (false)     | No Swagger            |

### \$.properties.logsDirectorySizeLimit

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.managedPipelineMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.managedServiceIdentityId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.minTlsVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.minimumElasticInstanceCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (0)         | No Swagger            |
| 2016-08-01  | Default (0)         | No Swagger            |
| 2018-11-01  | Default (0)         | No Swagger            |
| 2019-08-01  | Default (0)         | No Swagger            |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.netFrameworkVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.nodeVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.numberOfWorkers

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.phpVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.preWarmedInstanceCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Default* (0)        | No Swagger            |

### \$.properties.publishingUsername

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.remoteDebuggingEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2016-03-01  | Default (false)     | No Swagger            |
| 2016-08-01  | Default (false)     | No Swagger            |
| 2018-11-01  | Default (false)     | No Swagger            |

### \$.properties.remoteDebuggingVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.requestTracingEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.requestTracingExpirationTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.reservedInstanceCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (0)         | No Swagger            |
| 2016-03-01  | Default (0)         | No Swagger            |
| 2016-08-01  | Default (0)         | No Swagger            |
| 2018-11-01  | Default (0)         | No Swagger            |

### \$.properties.retentionInDays

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.scmIpSecurityRestrictions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.scmIpSecurityRestrictionsUseMain

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Default (false)     | No Swagger            |
| 2019-08-01  | Default (false)     | No Swagger            |

### \$.properties.scmIpSecurityRestrictions[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.scmType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

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
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.virtualApplications

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

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
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.webSocketsEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.websiteTimeZone

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

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

### \$.properties.windowsFxVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.xManagedServiceIdentityId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
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

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2018)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.AppOffline

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.SkipAppData

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.addOnPackages

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.dbType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.mode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.packageUri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.setParameters

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |

## sites/slots/hostNameBindings

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2022)-red)

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.app

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.hostNameType

| API version | Detected noise type  | Determined noise type |
| ----------- | -------------------- | --------------------- |
| 2016-03-01  | Default ("Verified") | No Swagger            |
| 2016-08-01  | Default ("Verified") | No Swagger            |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.siteName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.slot

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.sslState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.thumbprint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.toUpdate

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

## sites/slots/hybridConnectionNamespaces/relays

![cleanliness](https://img.shields.io/badge/cleanliness-44.44%25%20(4%20/%209)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%205)-red)

### \$.properties.hostname

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.port

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Default* (80)       | No Swagger            |

### \$.properties.relayName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.sendKeyValue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.serviceBusSuffix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

## sites/slots/networkconfig

![cleanliness](https://img.shields.io/badge/cleanliness-33.33%25%20(1%20/%203)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.location

| API version | Detected noise type             | Determined noise type |
| ----------- | ------------------------------- | --------------------- |
| 2019-08-01  | Default* ("South Africa North") | No Swagger            |

### \$.properties.swiftSupported

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Default* (true)     | No Swagger            |

## sites/slots/publicCertificates

![cleanliness](https://img.shields.io/badge/cleanliness-25.00%25%20(1%20/%204)-orange) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%203)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.blob

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

## sites/slots/siteextensions

![cleanliness](https://img.shields.io/badge/cleanliness-76.47%25%20(26%20/%2034)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%208)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

## sites/slots/virtualNetworkConnections

![cleanliness](https://img.shields.io/badge/cleanliness-84.00%25%20(21%20/%2025)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%204)-red)

### \$.properties.certBlob

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.isSwift

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Default* (false)    | No Swagger            |
| 2018-02-01  | Default* (false)    | No Swagger            |

## sites/slots

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%20474)-red)

### \$.identity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.identity.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.AlwaysOn

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.adminEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Default (true)      | No Swagger            |
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
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.appSettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.authType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.autoSwapSlotName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.buildVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.clientAffinityEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.clientCertEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.clientCertExclusionPaths

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.clientCertMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Default (0)         | No Swagger            |
| 2015-08-01  | Default (0)         | No Swagger            |
| 2016-03-01  | Default (0)         | No Swagger            |

### \$.properties.connectionStrings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.containerSize

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.contentAvailabilityState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Default (0)         | No Swagger            |
| 2015-04-01  | Default (0)         | No Swagger            |
| 2015-08-01  | Default (0)         | No Swagger            |
| 2016-03-01  | Default (0)         | No Swagger            |

### \$.properties.customDomainVerificationId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.dailyMemoryTimeQuota

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Default (0)         | No Swagger            |
| 2015-04-01  | Default (0)         | No Swagger            |
| 2015-08-01  | Default (0)         | No Swagger            |
| 2016-08-01  | Default (0)         | No Swagger            |
| 2018-02-01  | Default (0)         | No Swagger            |
| 2018-11-01  | Default (0)         | No Swagger            |
| 2019-08-01  | Default (0)         | No Swagger            |

### \$.properties.dbType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.deploymentId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
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
| 2015-08-01  | Default (true)      | No Swagger            |
| 2016-08-01  | Default (true)      | No Swagger            |
| 2018-02-01  | Default (true)      | No Swagger            |
| 2018-11-01  | Default (true)      | No Swagger            |
| 2019-08-01  | Default (true)      | No Swagger            |

### \$.properties.ftpUsername

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.ftpsHostName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.homeStamp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
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
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.hostNameSslStates[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.hostNameSslStates[*].hostType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.hostNameSslStates[*].ipBasedSslState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Default* (0)        | No Swagger            |
| 2015-08-01  | Default* (0)        | No Swagger            |

### \$.properties.hostNameSslStates[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.hostNameSslStates[*].sslState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.hostNameSslStates[*].thumbprint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.hostNameSslStates[*].toUpdate

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.hostingEnvironment

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

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
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.hostingEnvironmentProfile.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.hostingEnvironmentProfile.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.hostingEnvironmentsId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.http20Enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.httpsOnly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.httpsOnly 

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.hyperV

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Default (false)     | No Swagger            |
| 2015-04-01  | Default (false)     | No Swagger            |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2016-03-01  | Default (false)     | No Swagger            |
| 2016-08-01  | Default (false)     | No Swagger            |
| 2018-02-01  | Default (false)     | No Swagger            |
| 2018-11-01  | Default (false)     | No Swagger            |
| 2019-08-01  | Default (false)     | No Swagger            |

### \$.properties.inProgressOperationId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.inboundIpAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
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

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Default (false)     | No Swagger            |
| 2015-04-01  | Default (false)     | No Swagger            |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2016-03-01  | Default (false)     | No Swagger            |
| 2016-08-01  | Default (false)     | No Swagger            |
| 2018-02-01  | Default (false)     | No Swagger            |
| 2018-11-01  | Default (false)     | No Swagger            |
| 2019-08-01  | Default (false)     | No Swagger            |

### \$.properties.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
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

### \$.properties.metadata

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.minTlsVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.mode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
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
| 2014-04-01  | Unknown             | No Swagger            |
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
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.redundancyMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.remoteDebuggingEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.reserved

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.runtimeAvailabilityState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Default (0)         | No Swagger            |
| 2015-04-01  | Default (0)         | No Swagger            |
| 2015-08-01  | Default (0)         | No Swagger            |
| 2016-03-01  | Default (0)         | No Swagger            |

### \$.properties.selfLink

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.serverFarm

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |

### \$.properties.serverFarmId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.setParameters

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.acrUseManagedIdentityCreds

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2016-03-01  | Default (false)     | No Swagger            |
| 2016-08-01  | Default (false)     | No Swagger            |
| 2018-02-01  | Default (false)     | No Swagger            |
| 2018-11-01  | Default (false)     | No Swagger            |
| 2019-08-01  | Default (false)     | No Swagger            |

### \$.properties.siteConfig.alwaysOn

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.apiDefinition

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.appCommandLine

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.appSettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.autoHealEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.autoSwapSlotName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.clientAffinityEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.clientCertEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.connectionStrings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.containerSize

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.cors

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.dailyMemoryTimeQuota

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.defaultDocuments

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.detailedErrorLoggingEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.detailedErrorLoggingEnabled 

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.ftpsState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.healthCheckPath

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.hostNamesDisabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.http20Enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.httpLoggingEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.httpsOnly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.ipSecurityRestrictions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.javaContainer

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.javaContainerVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.javaVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.linuxFxVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.localMySqlEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.logsDirectorySizeLimit

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.managedPipelineMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.metadata

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.minTlsVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.minimumElasticInstanceCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (0)         | No Swagger            |
| 2016-03-01  | Default (0)         | No Swagger            |
| 2016-08-01  | Default (0)         | No Swagger            |
| 2018-02-01  | Default (0)         | No Swagger            |
| 2018-11-01  | Default (0)         | No Swagger            |
| 2019-08-01  | Default (0)         | No Swagger            |

### \$.properties.siteConfig.netFrameworkVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.nodeVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.numberOfWorkers

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.phpVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.pythonVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.remoteDebuggingEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.remoteDebuggingVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.requestTracingEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.requestTracingExpirationTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.scmIpSecurityRestrictions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.scmIpSecurityRestrictionsUseMain

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.scmSiteAlsoStopped

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.scmType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.siteAuthSettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.use32BitWorkerProcess

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.virtualApplications

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.webSocketsEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.websiteTimeZone

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.siteDisabledReason

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Default (0)         | No Swagger            |
| 2015-04-01  | Default (0)         | No Swagger            |
| 2015-08-01  | Default (0)         | No Swagger            |
| 2016-03-01  | Default (0)         | No Swagger            |
| 2016-08-01  | Default (0)         | No Swagger            |
| 2018-02-01  | Default (0)         | No Swagger            |
| 2018-11-01  | Default (0)         | No Swagger            |
| 2019-08-01  | Default (0)         | No Swagger            |

### \$.properties.siteName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.siteProperties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-04-01  | Unknown             | No Swagger            |
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
| 2014-04-01  | Unknown             | No Swagger            |
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
| 2014-04-01  | Unknown             | No Swagger            |
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
| 2016-03-01  | Unknown             | No Swagger            |
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
| 2014-04-01  | Unknown             | No Swagger            |
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

### \$.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-01  | Unknown             | No Swagger            |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

## sites/sourcecontrols

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2033)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-03-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.IsManualIntegration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.RepoUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.branch

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.deploymentRollbackEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2018-11-01  | Default (false)     | No Swagger            |

### \$.properties.isGitHubAction

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2016-03-01  | Default (false)     | No Swagger            |
| 2016-08-01  | Default (false)     | No Swagger            |
| 2018-02-01  | Default (false)     | No Swagger            |
| 2018-11-01  | Default (false)     | No Swagger            |
| 2019-08-01  | Default (false)     | No Swagger            |

### \$.properties.isManualIntegration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.isMercurial

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2018-11-01  | Default (false)     | No Swagger            |

### \$.properties.repoUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

## sites/virtualNetworkConnections

![cleanliness](https://img.shields.io/badge/cleanliness-47.62%25%20(10%20/%2021)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2011)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.certBlob

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |
| 2016-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.properties.certThumbprint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | No Swagger            |

### \$.properties.isSwift

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default (false)     | No Swagger            |
| 2016-08-01  | Default (false)     | No Swagger            |
| 2018-11-01  | Default (false)     | No Swagger            |

### \$.properties.resyncRequired

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Default* (false)    | No Swagger            |

### \$.properties.swiftSupported

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |

## sites

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-98.75%25%20(632%20/%20640)-brightgreen)

### \$.identity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

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

### \$.location

| API version | Detected noise type    | Determined noise type |
| ----------- | ---------------------- | --------------------- |
| 2019-08-01  | Default* ("East US 2") | Put-as-patch          |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.Enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.FUNCTIONS_EXTENSION_VERSION

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |

### \$.properties.FUNCTIONS_WORKER_RUNTIME

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |

### \$.properties.HttpsOnly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.InstrumentationKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.NumberOfWorkers

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

### \$.properties.apiManagementConfig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.applicationLogs

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.autoSwapSlotName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

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

### \$.properties.defaultDocuments

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

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

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Default* (false)    | Put-as-patch          |

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

### \$.properties.httpsOnly 

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2014-06-01  | Unknown             | No Swagger            |

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
| 2015-08-01  | Unknown             | Put-as-patch          |

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

### \$.properties.javaVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

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
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.logsDirectorySizeLimit

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.managedPipelineMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.managedServiceIdentityId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

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
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.networkAcls

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.numberOfWorkers

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
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

### \$.properties.pythonVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

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

### \$.properties.requestTracingEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Put-as-patch          |

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

### \$.properties.reservedInstanceCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

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

### \$.properties.scmType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-08-01  | Unknown             | Put-as-patch          |

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
| 2015-02-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-04-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteConfig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.ApplicationInsights

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.DOCKER_CUSTOM_IMAGE_NAME

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.MSDEPLOY_RENAME_LOCKED_FILES

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.alwaysOn

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteConfig.appCommandLine

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.appSettings

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2016-09-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteConfig.applicationLogs

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.autoHealEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.autoHealRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.clientAffinityEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.comments

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.connectionStrings

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteConfig.cors

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteConfig.customAppPoolIdentityAdminState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.customAppPoolIdentityTenantState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.dailyMemoryTimeQuota

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.defaultDocuments

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.detailedErrorLoggingEnabled

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteConfig.enableHttp2

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.ftpState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-01  | Unknown             | No Swagger            |

### \$.properties.siteConfig.ftpsState

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteConfig.handlerMappings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.healthCheckPath

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.hostNameSslStates

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.http20Enabled

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2016-09-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteConfig.httpLoggingEnabled

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteConfig.httpsOnly

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteConfig.ipSecurityRestrictions

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteConfig.isHttpAllowed

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.javaContainer

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.javaContainerVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.javaVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.linuxFxVersion

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteConfig.loadBalancing

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.localMySqlEnabled

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2016-09-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteConfig.logsDirectorySizeLimit

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteConfig.managedPipelineMode

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteConfig.metadata

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.minTlsVersion

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteConfig.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.netFrameworkVersion

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2016-09-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-02-01) |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteConfig.nodeVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.numberOfWorkers

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.phpVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.preWarmedInstanceCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.publishingPassword

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.publishingUsername

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.pythonVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.remoteDebuggingEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.remoteDebuggingVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.requestTracingEnabled

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteConfig.requestTracingExpirationTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.reservedInstanceCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.scmIpSecurityRestrictions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.scmIpSecurityRestrictionsUseMain

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.scmSiteAlsoStopped

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.scmType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.serverFarmId

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2018-11-01) |
| 2018-11-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteConfig.siteAuthEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.siteAuthSettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.use32BitWorkerProcess

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteConfig.virtualApplications

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteConfig.vnetName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-08-01  | Unknown             | Put-as-patch          |
| 2018-02-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.web

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.webSocketsEnabled

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2014-06-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-08-01) |
| 2015-08-01  | Unknown             | Put-as-patch                                          |
| 2016-03-01  | Unknown             | No Swagger, Put-as-patch (inheritted from 2016-08-01) |
| 2016-08-01  | Unknown             | Put-as-patch                                          |
| 2018-02-01  | Unknown             | Put-as-patch                                          |
| 2018-11-01  | Unknown             | Put-as-patch                                          |
| 2019-08-01  | Unknown             | Put-as-patch                                          |

### \$.properties.siteConfig.websiteTimeZone

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.winAuthAdminState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.winAuthTenantState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-08-01  | Unknown             | Put-as-patch          |

### \$.properties.siteConfig.windowsFxVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

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
| 2019-08-01  | Unknown             | Put-as-patch          |

### \$.properties.vnetName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

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

### \$.properties.xManagedServiceIdentityId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Put-as-patch          |

### \$.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Put-as-patch          |
| 2018-11-01  | Unknown             | Put-as-patch          |

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

## staticsites

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties.buildProperties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-01-preview | Unknown             | No Swagger            |

### \$.properties.createOrUpdateWorkflow

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-01-preview | Unknown             | No Swagger            |
