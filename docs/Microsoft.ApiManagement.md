# Microsoft.Apimanagement

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## service/apiVersionSets

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |

### \$.properties.displayName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |

## service/apis/releases

![cleanliness](https://img.shields.io/badge/cleanliness-80.00%25%20(4%20/%205)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties.apiId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | Unknown               |

## service/caches

![cleanliness](https://img.shields.io/badge/cleanliness-75.00%25%20(3%20/%204)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties.connectionString

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | Unknown               |

## service/namedvalues

![cleanliness](https://img.shields.io/badge/cleanliness-80.00%25%20(4%20/%205)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-12-01  | Unknown             | Unknown               |

## service/notifications

![cleanliness](https://img.shields.io/badge/cleanliness-83.33%25%20(5%20/%206)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

## service/products/policies

![cleanliness](https://img.shields.io/badge/cleanliness-40.00%25%20(2%20/%205)-yellow) ![progress](https://img.shields.io/badge/progress-40.00%25%20(2%20/%205)-yellow)

### \$.properties.contentFormat

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Default* ("xml")    | Default ("xml")       |

### \$.properties.format

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Default* ("xml")    | Default ("xml")       |

### \$.properties.policyContent

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | Unknown               |

### \$.properties.value

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-01-01         | Unknown             | No Swagger            |
| 2019-12-01-preview | Unknown             | No Swagger            |

## service/templates

![cleanliness](https://img.shields.io/badge/cleanliness-90.00%25%20(9%20/%2010)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties.description

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-01-preview | Unknown             | No Swagger            |

## service/apis/diagnostics

![cleanliness](https://img.shields.io/badge/cleanliness-66.67%25%20(18%20/%2027)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%209)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.enableHttpCorrelationHeaders

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Default* (true)     | No Swagger            |

### \$.properties.enabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.httpCorrelationProtocol

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Default ("Legacy")  | No Swagger            |

### \$.properties.logClientIp

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Default (true)      | No Swagger            |
| 2019-01-01         | Default (true)      | No Swagger            |

### \$.properties.loggerId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

## service/apis/operations/policies

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2012)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | No Swagger            |

### \$.properties.contentFormat

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Default* ("xml")    | No Swagger            |
| 2018-06-01-preview | Default* ("xml")    | No Swagger            |

### \$.properties.format

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Default ("xml")     | No Swagger            |

### \$.properties.policyContent

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | No Swagger            |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.value

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-01-01         | Unknown             | No Swagger            |
| 2019-12-01-preview | Unknown             | No Swagger            |
| 2019-12-01         | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |

## service/apis/operations

![cleanliness](https://img.shields.io/badge/cleanliness-38.10%25%20(24%20/%2063)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2039)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | No Swagger            |

### \$.properties.apiVersionSetId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | No Swagger            |

### \$.properties.method

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-12-01         | Unknown             | No Swagger            |

### \$.properties.request

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | No Swagger            |
| 2018-01-01         | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |
| 2019-12-01-preview | Unknown             | No Swagger            |

### \$.properties.request.headers[*].required

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | No Swagger            |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |

### \$.properties.request.in

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.request.name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.request.queryParameters[*].in

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.request.queryParameters[*].required

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | No Swagger            |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |

### \$.properties.request.queryParameters[*].schema

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.request.representations[*].description

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |

### \$.properties.request.representations[*].formParameters[*].required

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.request.representations[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |

### \$.properties.responses[*].headers[*].required

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.responses[*].representations[*].generatedSample

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | No Swagger            |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |

### \$.properties.responses[*].respresentations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | No Swagger            |

### \$.properties.templateParameters[*].in

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.templateParameters[*].required

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Default* (true)     | No Swagger            |
| 2019-01-01  | Default* (true)     | No Swagger            |

### \$.properties.urlTemplate

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |
| 2019-12-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |

## service/apis/policies

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2011)-red)

### \$.properties.contentFormat

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Default* ("xml")    | No Swagger            |
| 2018-06-01-preview | Default* ("xml")    | No Swagger            |

### \$.properties.format

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Default ("xml")     | No Swagger            |

### \$.properties.policyContent

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | No Swagger            |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.value

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-01-01         | Unknown             | No Swagger            |
| 2019-12-01-preview | Unknown             | No Swagger            |
| 2019-12-01         | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |

## service/apis/schemas

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%207)-red)

### \$.properties.document

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | Unknown               |

### \$.properties.document.definitions

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |

### \$.properties.document.value

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |

## service/apis/tags

![cleanliness](https://img.shields.io/badge/cleanliness-0.00%25%20(0%20/%202)-red) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

## service/apis

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2075)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |

### \$.properties.apiBackendId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.apiRevision

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | No Swagger            |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |
| 2019-12-01-preview | Unknown             | No Swagger            |
| 2019-12-01         | Unknown             | No Swagger            |

### \$.properties.apiRevisionDescription

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.apiType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.apiVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.apiVersionDescription

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.apiVersionName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |

### \$.properties.apiVersionSet

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | No Swagger            |

### \$.properties.apiVersionSetId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | No Swagger            |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |

### \$.properties.authenticationSettings

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |

### \$.properties.authenticationSettings.subscriptionKeyRequired

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |
| 2019-12-01         | Unknown             | No Swagger            |

### \$.properties.contentFormat

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | No Swagger            |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-12-01         | Unknown             | No Swagger            |

### \$.properties.contentValue

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | No Swagger            |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-12-01         | Unknown             | No Swagger            |

### \$.properties.decription

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.description

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.displayName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | No Swagger            |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |
| 2019-12-01-preview | Unknown             | No Swagger            |

### \$.properties.format

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.isCurrent

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-01-01         | Default (true)      | No Swagger            |
| 2019-12-01-preview | Default (true)      | No Swagger            |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | No Swagger            |

### \$.properties.path

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |
| 2019-12-01  | Unknown             | No Swagger            |

### \$.properties.protocols

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | No Swagger            |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |
| 2019-12-01-preview | Unknown             | No Swagger            |

### \$.properties.protocols[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.serviceUrl

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | No Swagger            |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |

### \$.properties.subscriptionKeyParameterNames

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | No Swagger            |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |
| 2019-12-01-preview | Unknown             | No Swagger            |
| 2019-12-01         | Unknown             | No Swagger            |

### \$.properties.subscriptionKeyParameterNames.query

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.subscriptionRequired

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | No Swagger            |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |

### \$.properties.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |

## service/authorizationServers

![cleanliness](https://img.shields.io/badge/cleanliness-94.74%25%20(18%20/%2019)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties.supportState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Default* (false)    | Unknown               |

## service/backends

![cleanliness](https://img.shields.io/badge/cleanliness-83.87%25%20(26%20/%2031)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%205)-red)

### \$.properties.credentials.header.x-functions-key[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.url

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |
| 2019-12-01         | Unknown             | No Swagger            |

## service/certificates

![cleanliness](https://img.shields.io/badge/cleanliness-50.00%25%20(3%20/%206)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%203)-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.data

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |

## service/diagnostics

![cleanliness](https://img.shields.io/badge/cleanliness-70.37%25%20(19%20/%2027)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%208)-red)

### \$.properties.backend

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.enableHttpCorrelationHeaders

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Default (true)      | No Swagger            |

### \$.properties.frontend

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.httpCorrelationProtocol

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Default* ("Legacy") | No Swagger            |

### \$.properties.logClientIp

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Default (true)      | No Swagger            |
| 2019-01-01         | Default (true)      | No Swagger            |

### \$.properties.loggerId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |

## service/identityProviders

![cleanliness](https://img.shields.io/badge/cleanliness-54.55%25%20(6%20/%2011)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%205)-red)

### \$.properties.authority

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | No Swagger            |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | Unknown               |
| 2019-01-01         | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

## service/loggers

![cleanliness](https://img.shields.io/badge/cleanliness-36.84%25%20(7%20/%2019)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2012)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.credentials.connectionString

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.credentials.instrumentationKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |

### \$.properties.isBuffered

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Default (true)      | No Swagger            |
| 2018-06-01-preview | Default (true)      | No Swagger            |
| 2019-01-01         | Default (true)      | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |

## service/policies

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%207)-red)

### \$.properties.contentFormat

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | No Swagger            |

### \$.properties.format

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Default* ("xml")    | No Swagger            |

### \$.properties.policyContent

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | No Swagger            |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.value

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-01-01         | Unknown             | No Swagger            |
| 2019-12-01-preview | Unknown             | No Swagger            |

## service/portalSettings

![cleanliness](https://img.shields.io/badge/cleanliness-85.71%25%20(18%20/%2021)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%203)-red)

### \$.properties.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | Unknown               |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.termsOfService

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |

## service/products

![cleanliness](https://img.shields.io/badge/cleanliness-60.00%25%20(6%20/%2010)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%204)-red)

### \$.properties.approvalRequired

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | Unknown               |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |

### \$.properties.state

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | No Swagger            |

## service/properties

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2011)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |

### \$.properties.mode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |

### \$.properties.secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.value

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | No Swagger            |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | Unknown               |
| 2019-01-01         | Unknown             | Unknown               |

## service/subscriptions

![cleanliness](https://img.shields.io/badge/cleanliness-21.05%25%20(4%20/%2019)-orange) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2015)-red)

### \$.properties.allowTracing

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | Unknown               |

### \$.properties.createdDate

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |

### \$.properties.primaryKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | No Swagger            |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |

### \$.properties.productId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |

### \$.properties.scope

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-06-01-preview | Unknown             | No Swagger            |

### \$.properties.secondaryKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-01         | Unknown             | No Swagger            |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |

### \$.properties.state

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Default* ("active") | No Swagger            |

### \$.properties.userId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |

## service/tags

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%204)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.displayName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

## service/users

![cleanliness](https://img.shields.io/badge/cleanliness-82.35%25%20(28%20/%2034)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%206)-red)

### \$.properties.confirmation

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | Unknown               |
| 2018-01-01  | Unknown             | No Swagger            |

### \$.properties.identities

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |
| 2019-12-01-preview | Unknown             | No Swagger            |

### \$.properties.password

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |

## service

![cleanliness](https://img.shields.io/badge/cleanliness-44.54%25%20(53%20/%20119)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2066)-red)

### \$.properties.addresserEmail

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-07-07  | Unknown             | Unknown               |

### \$.properties.apiVersionConstraint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-01-preview | Unknown             | Unknown               |

### \$.properties.certificates[*].certificate

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-01-01         | Unknown             | No Swagger            |
| 2019-12-01-preview | Unknown             | No Swagger            |

### \$.properties.certificates[*].certificate.expiry

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
| 2016-07-07         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | No Swagger            |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |
| 2019-12-01-preview | Unknown             | No Swagger            |
| 2019-12-01         | Unknown             | No Swagger            |

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

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |
| 2019-12-01-preview | Unknown             | No Swagger            |

### \$.properties.disableGateway

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-12-01-preview | Default* (false)    | No Swagger            |

### \$.properties.hostnameConfigurations

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-07-07         | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |
| 2019-12-01-preview | Unknown             | No Swagger            |
| 2019-12-01         | Unknown             | No Swagger            |

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

### \$.properties.hostnameConfigurations[*].hostName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |
| 2019-12-01  | Unknown             | No Swagger            |

### \$.properties.hostnameConfigurations[*].keyVaultId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
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
| 2016-07-07         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | No Swagger            |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-06-01-preview | Unknown             | No Swagger            |
| 2019-01-01         | Unknown             | No Swagger            |
| 2019-12-01-preview | Unknown             | No Swagger            |
| 2019-12-01         | Unknown             | No Swagger            |

### \$.properties.parameters

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.publisherEmail

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-07-07  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.publisherName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.properties.vpnType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-07-07  | Default* (0)        | No Swagger            |

### \$.sku.capacity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Unknown             | No Swagger            |
| 2019-01-01  | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-01-01  | Unknown             | No Swagger            |
