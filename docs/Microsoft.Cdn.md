# Microsoft.Cdn

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## cdnWebApplicationFirewallPolicies

![cleanliness](https://img.shields.io/badge/cleanliness-96.15%25%20(50%20/%2052)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties.managedRules.managedRuleSets[*].anomalyScore

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-15-preview | Default* (0)        | No Swagger            |

### \$.properties.rateLimitRules

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-15-preview | Unknown             | No Swagger            |

## profiles/endpoints/customdomains

![cleanliness](https://img.shields.io/badge/cleanliness-81.82%25%20(9%20/%2011)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties.customHttpsParameters

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-12-31  | Unknown             | No Swagger            |

### \$.properties.hostName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-15  | Unknown             | No Swagger            |

## profiles/endpoints/origins

![cleanliness](https://img.shields.io/badge/cleanliness-66.67%25%20(4%20/%206)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties.hostName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-02  | Unknown             | No Swagger            |
| 2017-10-12  | Unknown             | No Swagger            |

## profiles/endpoints

![cleanliness](https://img.shields.io/badge/cleanliness-22.41%25%20(13%20/%2058)-orange) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2045)-red)

### \$.properties.customDomains

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-12  | Unknown             | No Swagger            |
| 2018-04-02  | Unknown             | No Swagger            |
| 2019-04-15  | Unknown             | No Swagger            |
| 2019-12-31  | Unknown             | No Swagger            |

### \$.properties.deliveryPolicy.rules[*].conditions[*].parameters.negateCondition

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-15  | Default* (false)    | No Swagger            |

### \$.properties.isCompressionEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-02  | Default* (false)    | No Swagger            |
| 2017-10-12  | Default* (false)    | No Swagger            |
| 2018-04-02  | Default* (false)    | No Swagger            |

### \$.properties.isHttpAllowed

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-02  | Default* (true)     | No Swagger            |
| 2019-04-15  | Default* (true)     | No Swagger            |

### \$.properties.isHttpsAllowed

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-02  | Default* (true)     | No Swagger            |
| 2019-04-15  | Default* (true)     | No Swagger            |

### \$.properties.originHostHeader

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-02         | Unknown             | No Swagger            |
| 2017-10-12         | Unknown             | No Swagger            |
| 2018-04-02         | Unknown             | No Swagger            |
| 2019-04-15         | Unknown             | No Swagger            |
| 2019-06-15-preview | Unknown             | No Swagger            |
| 2019-12-31         | Unknown             | No Swagger            |

### \$.properties.origins

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-12  | Unknown             | No Swagger            |

### \$.properties.origins[*].name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-02         | Unknown             | No Swagger            |
| 2019-04-15         | Unknown             | No Swagger            |
| 2019-06-15-preview | Unknown             | No Swagger            |
| 2019-12-31         | Unknown             | No Swagger            |

### \$.properties.origins[*].properties.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-12-31  | Default* (true)     | No Swagger            |

### \$.properties.origins[*].properties.hostName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-02         | Unknown             | No Swagger            |
| 2017-10-12         | Unknown             | No Swagger            |
| 2018-04-02         | Unknown             | No Swagger            |
| 2019-04-15         | Unknown             | No Swagger            |
| 2019-06-15-preview | Unknown             | No Swagger            |
| 2019-12-31         | Unknown             | No Swagger            |

### \$.properties.origins[*].properties.httpPort

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-02  | Default* (80)       | No Swagger            |

### \$.properties.origins[*].properties.httpsPort

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-02  | Default* (443)      | No Swagger            |

### \$.properties.origins[*].properties.originHostHeader

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-12-31  | Unknown             | No Swagger            |

### \$.properties.origins[*].properties.priority

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-12-31  | Default* (1)        | No Swagger            |

### \$.properties.origins[*].properties.weight

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-12-31  | Default* (1000)     | No Swagger            |

### \$.properties.queryStringCachingBehavior

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-02  | Unknown             | No Swagger            |
| 2017-10-12  | Unknown             | No Swagger            |
| 2018-04-02  | Unknown             | No Swagger            |
| 2019-04-15  | Unknown             | No Swagger            |
| 2019-12-31  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-02  | Unknown             | No Swagger            |
| 2018-04-02  | Unknown             | No Swagger            |
| 2019-04-15  | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-02  | Unknown             | No Swagger            |
| 2019-04-15  | Unknown             | No Swagger            |

## profiles

![cleanliness](https://img.shields.io/badge/cleanliness-60.00%25%20(3%20/%205)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-15  | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-02  | Unknown             | No Swagger            |
