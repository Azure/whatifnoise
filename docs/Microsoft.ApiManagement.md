# Microsoft.ApiManagement

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## service/apis/diagnostics

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.httpCorrelationProtocol

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Default* ("Legacy") | Unknown               |

### \$.properties.logClientIp

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Default* (true)     | No Swagger            |
| 2019-01-01         | Default* (true)     | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

## service/apis/operations/policies

![20.00%25](https://img.shields.io/badge/20.00%25-%E2%98%85★%E2%98%86☆☆☆☆☆☆☆-orange)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | No Swagger            |

### \$.properties.contentFormat

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Default* ("xml")    | Default ("xml")       |

### \$.properties.format

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Default* ("xml")    | Default ("xml")       |

### \$.properties.policyContent

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | Unknown               |
| 2018-01-01         | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | Unknown               |

### \$.properties.value

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-01-01         | Unknown             | Unknown               |
| 2019-12-01-preview | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |

## service/apis/operations

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | No Swagger            |

### \$.properties.request

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | Unknown               |
| 2018-01-01         | Unknown             | Unknown               |
| 2019-01-01         | Unknown             | Unknown               |
| 2019-12-01-preview | Unknown             | Unknown               |

### \$.properties.request.in

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.request.name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.request.queryParameters[*].required

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.responses[*].representations[*].generatedSample

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.templateParameters[*].required

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Default* (true)     | No Swagger            |

### \$.properties.urlTemplate

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |

## service/apis/policies

![25.00%25](https://img.shields.io/badge/25.00%25-%E2%98%85★★%E2%98%86☆☆☆☆☆☆-orange)

### \$.properties.contentFormat

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Default* ("xml")    | Default ("xml")       |

### \$.properties.format

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Default* ("xml")    | Default ("xml")       |

### \$.properties.policyContent

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | Unknown               |
| 2018-01-01         | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | Unknown               |

### \$.properties.value

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-01-01         | Unknown             | Unknown               |
| 2019-12-01-preview | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |

## service/apis/schemas

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.document

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | Unknown               |

## service/apis/tags

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

## service/apis

![3.08%25](https://img.shields.io/badge/3.08%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.apiRevision

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | Unknown               |
| 2018-01-01         | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | Unknown               |
| 2019-01-01         | Unknown             | Unknown               |
| 2019-12-01-preview | Unknown             | Unknown               |

### \$.properties.apiRevisionDescription

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | Unknown               |

### \$.properties.apiType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | Unknown               |

### \$.properties.apiVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | Unknown               |

### \$.properties.apiVersionDescription

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | Unknown               |

### \$.properties.apiVersionName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | No Swagger            |

### \$.properties.apiVersionSet

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | Unknown               |

### \$.properties.apiVersionSetId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | Unknown               |
| 2019-01-01         | Unknown             | Unknown               |

### \$.properties.authenticationSettings

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | Unknown               |
| 2018-01-01         | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | Unknown               |
| 2019-01-01         | Unknown             | Unknown               |
| 2019-12-01-preview | Unknown             | Unknown               |

### \$.properties.authenticationSettings.subscriptionKeyRequired

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.contentFormat

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | Unknown               |
| 2018-01-01         | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | Unknown               |

### \$.properties.contentValue

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | Unknown               |
| 2018-01-01         | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | Unknown               |

### \$.properties.description

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | Unknown               |
| 2018-01-01         | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | Unknown               |
| 2019-01-01         | Unknown             | Unknown               |

### \$.properties.displayName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | Unknown               |
| 2018-01-01         | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | Unknown               |
| 2019-01-01         | Unknown             | Unknown               |

### \$.properties.format

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | Unknown               |

### \$.properties.isCurrent

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-01-01         | Default (true)      | Read-only             |
| 2019-12-01-preview | Default (true)      | Read-only             |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | No Swagger            |

### \$.properties.path

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | Unknown               |
| 2018-01-01  | Unknown             | Unknown               |
| 2019-01-01  | Unknown             | Unknown               |

### \$.properties.protocols

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | Unknown               |
| 2018-01-01         | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | Unknown               |
| 2019-01-01         | Unknown             | Unknown               |
| 2019-12-01-preview | Unknown             | Unknown               |

### \$.properties.protocols[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.serviceUrl

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | Unknown               |
| 2018-01-01         | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | Unknown               |
| 2019-01-01         | Unknown             | Unknown               |

### \$.properties.subscriptionKeyParameterNames

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | Unknown               |
| 2018-01-01         | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | Unknown               |
| 2019-01-01         | Unknown             | Unknown               |
| 2019-12-01-preview | Unknown             | Unknown               |

### \$.properties.subscriptionRequired

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | Unknown               |
| 2019-01-01         | Unknown             | Unknown               |

### \$.properties.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | Unknown               |

### \$.properties.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | Unknown               |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |

## service/authorizationServers

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.supportState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Default* (false)    | Unknown               |

## service/backends

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.credentials.header.x-functions-key[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.url

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | Unknown               |
| 2019-01-01         | Unknown             | Unknown               |

## service/certificates

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | Unknown               |
| 2019-01-01  | Unknown             | Unknown               |

## service/diagnostics

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.enableHttpCorrelationHeaders

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Default* (true)     | Unknown               |

### \$.properties.httpCorrelationProtocol

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Default* ("Legacy") | Unknown               |

### \$.properties.logClientIp

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Default* (true)     | No Swagger            |
| 2019-01-01         | Default* (true)     | No Swagger            |

### \$.properties.loggerId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | Unknown               |

## service/identityProviders

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.authority

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | Unknown               |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

## service/loggers

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |

### \$.properties.credentials.connectionString

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.credentials.instrumentationKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.isBuffered

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Default* (true)     | Unknown               |
| 2019-01-01  | Default* (true)     | Unknown               |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |

## service/policies

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.policyContent

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | Unknown               |

### \$.properties.value

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-01-01         | Unknown             | Unknown               |
| 2019-12-01-preview | Unknown             | Unknown               |

## service/portalSettings

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | Unknown               |

### \$.properties.termsOfService

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | Unknown               |

## service/products

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.approvalRequired

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Default* (false)    | Unknown               |

## service/properties

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.mode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |

### \$.properties.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | Unknown               |
| 2018-01-01  | Unknown             | Unknown               |
| 2019-01-01  | Unknown             | Unknown               |

### \$.properties.value

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | Unknown               |
| 2018-01-01         | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | Unknown               |
| 2019-01-01         | Unknown             | Unknown               |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |

## service/subscriptions

![28.57%25](https://img.shields.io/badge/28.57%25-%E2%98%85★★%E2%98%86☆☆☆☆☆☆-orange)

### \$.properties.allowTracing

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Default* (false)    | Unknown               |

### \$.properties.createdDate

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | Read-only             |
| 2019-01-01         | Unknown             | Read-only             |

### \$.properties.primaryKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | Unknown               |
| 2019-01-01  | Unknown             | Unknown               |

### \$.properties.secondaryKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | Unknown               |
| 2019-01-01  | Unknown             | Unknown               |

## service/tags

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

## service/users

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.confirmation

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | Unknown               |

### \$.properties.identities

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | Unknown               |
| 2019-01-01  | Unknown             | Unknown               |

### \$.properties.password

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | Unknown               |

## service

![10.71%25](https://img.shields.io/badge/10.71%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-orange)

### \$.properties.addresserEmail

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-07-07  | Unknown             | Unknown               |

### \$.properties.apiVersionConstraint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-01-preview | Unknown             | Unknown               |

### \$.properties.certificates[*].certificate

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.certificates[*].encodedCertificate

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.customProperties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-07-07         | Unknown             | Unknown               |
| 2017-03-01         | Unknown             | Unknown               |
| 2018-01-01         | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | Unknown               |
| 2019-01-01         | Unknown             | Unknown               |
| 2019-12-01-preview | Unknown             | Unknown               |

### \$.properties.customProperties.Microsoft.WindowsAzure.ApiManagement.Gateway.Protocols.Server.Http2

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |

### \$.properties.customProperties.Microsoft.WindowsAzure.ApiManagement.Gateway.Security.Backend.Protocols.Ssl30

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.customProperties.Microsoft.WindowsAzure.ApiManagement.Gateway.Security.Backend.Protocols.Tls10

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.customProperties.Microsoft.WindowsAzure.ApiManagement.Gateway.Security.Backend.Protocols.Tls11

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.customProperties.Microsoft.WindowsAzure.ApiManagement.Gateway.Security.Ciphers.TripleDes168

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.customProperties.Microsoft.WindowsAzure.ApiManagement.Gateway.Security.Protocols.Ssl30

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.customProperties.Microsoft.WindowsAzure.ApiManagement.Gateway.Security.Protocols.Tls10

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.customProperties.Microsoft.WindowsAzure.ApiManagement.Gateway.Security.Protocols.Tls11

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.developerPortalUrl

| API version        | Detected noise type | Determined noise type                              |
| ------------------ | ------------------- | -------------------------------------------------- |
| 2018-01-01         | Unknown             | No Swagger, Read-only (inheritted from 2019-01-01) |
| 2018-06-01-preview | Unknown             | No Swagger, Read-only (inheritted from 2019-01-01) |
| 2019-01-01         | Unknown             | Read-only                                          |
| 2019-12-01-preview | Unknown             | Read-only                                          |

### \$.properties.disableGateway

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-01-preview | Default* (false)    | Default (false)       |

### \$.properties.hostnameConfigurations

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-01-01         | Unknown             | Unknown               |
| 2019-12-01-preview | Unknown             | Unknown               |

### \$.properties.hostnameConfigurations[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.hostnameConfigurations[*].certificate

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.hostnameConfigurations[*].certificate.expiry

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.hostnameConfigurations[*].certificate.subject

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.hostnameConfigurations[*].certificate.thumbprint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.hostnameConfigurations[*].defaultSslBinding

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.hostnameConfigurations[*].encodedCertificate

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.hostnameConfigurations[*].hostName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.hostnameConfigurations[*].keyVaultId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.hostnameConfigurations[*].negotiateClientCertificate

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.hostnameConfigurations[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Default* ("Proxy")  | No Swagger            |

### \$.properties.notificationSenderEmail

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | Unknown               |
| 2018-01-01         | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | Unknown               |
| 2019-01-01         | Unknown             | Unknown               |
| 2019-12-01-preview | Unknown             | Unknown               |

### \$.properties.parameters

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.publisherName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | Unknown               |

### \$.properties.vpnType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-07-07  | Default* (0)        | Default ("None")      |

### \$.sku.capacity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | Unknown               |

## service/products/policies

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | Unknown               |
