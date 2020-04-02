# Microsoft.Cdn

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## cdnWebApplicationFirewallPolicies

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.managedRules.managedRuleSets[*].anomalyScore

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-15-preview | Default* (0)        | No Swagger            |

### \$.properties.rateLimitRules

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-15-preview | Unknown             | Unknown               |

## profiles/endpoints/origins

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.hostName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-02  | Unknown             | Unknown               |

## profiles/endpoints

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.customDomains

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-12  | Unknown             | No Swagger            |
| 2019-04-15  | Unknown             | No Swagger            |

### \$.properties.deliveryPolicy.rules[*].conditions[*].parameters.negateCondition

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-15  | Default* (false)    | No Swagger            |

### \$.properties.isCompressionEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-02  | Default* (false)    | Unknown               |
| 2017-10-12  | Default* (false)    | Unknown               |

### \$.properties.isHttpAllowed

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-02  | Default* (true)     | Unknown               |
| 2019-04-15  | Default* (true)     | Unknown               |

### \$.properties.isHttpsAllowed

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-02  | Default* (true)     | Unknown               |
| 2019-04-15  | Default* (true)     | Unknown               |

### \$.properties.originHostHeader

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-02  | Unknown             | Unknown               |
| 2017-10-12  | Unknown             | Unknown               |
| 2019-04-15  | Unknown             | Unknown               |

### \$.properties.origins

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-12  | Unknown             | Unknown               |

### \$.properties.origins[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-02  | Unknown             | No Swagger            |
| 2019-04-15  | Unknown             | No Swagger            |

### \$.properties.origins[*].properties.hostName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-02  | Unknown             | No Swagger            |
| 2019-04-15  | Unknown             | No Swagger            |

### \$.properties.origins[*].properties.httpPort

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-02  | Default* (80)       | No Swagger            |

### \$.properties.origins[*].properties.httpsPort

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-02  | Default* (443)      | No Swagger            |

### \$.properties.queryStringCachingBehavior

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-12  | Unknown             | Unknown               |
| 2018-04-02  | Unknown             | No Swagger            |
| 2019-04-15  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-02  | Unknown             | No Swagger            |
| 2019-04-15  | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-15  | Unknown             | Unknown               |

## profiles

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-15  | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-02  | Unknown             | Unknown               |
