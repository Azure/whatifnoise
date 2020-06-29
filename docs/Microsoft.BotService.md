# Microsoft.BotService

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## botServices/channels

![cleanliness](https://img.shields.io/badge/cleanliness-73.56%25%20(64%20/%2087)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2023)-red)

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Unknown               |
| 2018-07-12  | Unknown             | No Swagger            |

### \$.properties.etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |
| 2018-07-12  | Unknown             | No Swagger            |

### \$.properties.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |
| 2018-07-12  | Unknown             | No Swagger            |

### \$.properties.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-12  | Unknown             | No Swagger            |

### \$.properties.properties.callingWebhook

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-12  | Unknown             | No Swagger            |

### \$.properties.properties.deploymentEnvironment

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-12  | Default* (0)        | No Swagger            |

### \$.properties.properties.enableCalling

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-12  | Default* (false)    | No Swagger            |

### \$.properties.properties.sites[*].disablev1

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.properties.sites[*].disablev3

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.properties.sites[*].enablePreview

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-12  | Unknown             | No Swagger            |

### \$.properties.properties.sites[*].isBlockUserUploadEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Default* (false)    | No Swagger            |
| 2018-07-12  | Default* (false)    | No Swagger            |

### \$.properties.properties.sites[*].isEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Default* (true)     | No Swagger            |

### \$.properties.properties.sites[*].isSecureSiteEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Default* (false)    | No Swagger            |

### \$.properties.properties.sites[*].isV1Enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Default* (true)     | No Swagger            |

### \$.properties.properties.sites[*].isV3Enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Default* (true)     | No Swagger            |

### \$.properties.properties.sites[*].isWebchatPreviewEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-12  | Default* (true)     | No Swagger            |

### \$.properties.properties.sites[*].siteId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |
| 2018-07-12  | Unknown             | No Swagger            |

### \$.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-12  | Unknown             | No Swagger            |

## botServices/connections

![cleanliness](https://img.shields.io/badge/cleanliness-46.15%25%20(6%20/%2013)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%207)-red)

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-12  | Unknown             | No Swagger            |

### \$.properties.clientId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-12  | Unknown             | No Swagger            |

### \$.properties.clientSecret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-12  | Unknown             | No Swagger            |

### \$.properties.parameters[*].key

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-12  | Unknown             | No Swagger            |

### \$.properties.serviceProviderDisplayName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-12  | Unknown             | No Swagger            |

### \$.properties.serviceProviderId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-12  | Unknown             | No Swagger            |

### \$.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-12  | Unknown             | No Swagger            |

## botServices

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2023)-red)

### \$.properties.allSettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.developerAppInsightKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |
| 2018-07-12  | Unknown             | No Swagger            |

### \$.properties.developerAppInsightsApplicationId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |
| 2018-07-12  | Unknown             | No Swagger            |

### \$.properties.displayName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.endpoint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-12  | Unknown             | No Swagger            |

### \$.properties.iconUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |
| 2018-07-12  | Unknown             | No Swagger            |

### \$.properties.isDeveloperAppInsightsApiKeySet

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |
| 2018-07-12  | Unknown             | No Swagger            |

### \$.properties.isStreamingSupported

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Default (false)     | No Swagger            |
| 2018-07-12  | Default (false)     | No Swagger            |

### \$.properties.msaAppId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |
| 2018-07-12  | Unknown             | No Swagger            |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.parameters

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.publishingCredentials

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.storageResourceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |
| 2018-07-12  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-12  | Unknown             | No Swagger            |
