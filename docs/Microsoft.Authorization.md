# Microsoft.Authorization

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## denyassignments

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%205)-red)

### \$.properties.createdBy

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.createdOn

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.doNotApplyToChildScopes

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-07-01-preview | Default* (false)    | No Swagger            |

### \$.properties.updatedBy

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-07-01-preview | Unknown             | No Swagger            |

### \$.properties.updatedOn

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-07-01-preview | Unknown             | No Swagger            |

## locks

![cleanliness](https://img.shields.io/badge/cleanliness-80.00%25%20(4%20/%205)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | No Swagger            |

## policyAssignments

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-brightgreen) ![progress](https://img.shields.io/badge/progress-100.00%25%20(8%20/%208)-brightgreen)

### \$.properties.enforcementMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Default ("Default") | Put-as-patch          |
| 2019-09-01  | Default ("Default") | Put-as-patch          |

### \$.properties.scope

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-05-01  | Unknown             | Put-as-patch          |

### \$.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | Put-as-patch          |
| 2018-05-01  | Unknown             | Put-as-patch          |
| 2019-01-01  | Unknown             | Put-as-patch          |
| 2019-06-01  | Unknown             | Put-as-patch          |
| 2019-09-01  | Unknown             | Put-as-patch          |

## policyDefinitions

![cleanliness](https://img.shields.io/badge/cleanliness-60.00%25%20(12%20/%2020)-yellowgreen) ![progress](https://img.shields.io/badge/progress-11.11%25%20(1%20/%209)-orange)

### \$.properties.mode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | Default ("Indexed")   |

### \$.properties.parameters.effect.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-05-01  | Unknown             | No Swagger            |

### \$.properties.parameters.eventHubAuthorizationRuleId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-05-01  | Unknown             | No Swagger            |

### \$.properties.parameters.eventHubName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-05-01  | Unknown             | No Swagger            |

### \$.properties.parameters.logAnalytics.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-05-01  | Unknown             | No Swagger            |

### \$.properties.parameters.logAnalyticsWorkspaceId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-05-01  | Unknown             | No Swagger            |

### \$.properties.parameters.storageAccountId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-05-01  | Unknown             | No Swagger            |

### \$.properties.policyType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-05-01  | Default ("Custom")  | No Swagger            |
| 2019-09-01  | Default ("Custom")  | No Swagger            |

## policySetDefinitions

![cleanliness](https://img.shields.io/badge/cleanliness-70.97%25%20(22%20/%2031)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%209)-red)

### \$.properties.parameters.eventHubAuthorizationRuleId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-05-01  | Unknown             | No Swagger            |

### \$.properties.parameters.eventHubName.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-05-01  | Unknown             | No Swagger            |

### \$.properties.parameters.logAnalytics.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-05-01  | Unknown             | No Swagger            |

### \$.properties.parameters.logAnalyticsWorkspaceId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-05-01  | Unknown             | No Swagger            |

### \$.properties.parameters.storageAccountId.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-05-01  | Unknown             | No Swagger            |

### \$.properties.policyDefinitions[*].policyDefinitionReferenceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-05-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.policyType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-05-01  | Default* ("Custom") | No Swagger            |

## roleAssignments

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2076)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-01-preview | Unknown             | No Swagger            |
| 2019-04-01-preview | Unknown             | No Swagger            |

### \$.properties.canDelegate

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-01-preview | Unknown             | No Swagger            |

### \$.properties.createdBy

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-07-01-preview | Unknown             | No Swagger            |
| 2015-06-01         | Unknown             | No Swagger            |
| 2015-07-01         | Unknown             | No Swagger            |
| 2017-05-01         | Unknown             | No Swagger            |
| 2017-09-01         | Unknown             | No Swagger            |
| 2017-10-01-preview | Unknown             | No Swagger            |
| 2018-01-01-preview | Unknown             | No Swagger            |
| 2018-07-01         | Unknown             | No Swagger            |
| 2018-09-01-preview | Unknown             | No Swagger            |
| 2018-12-01-preview | Unknown             | No Swagger            |
| 2019-04-01-preview | Unknown             | No Swagger            |

### \$.properties.createdOn

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-07-01-preview | Unknown             | No Swagger            |
| 2015-06-01         | Unknown             | No Swagger            |
| 2015-07-01         | Unknown             | No Swagger            |
| 2017-05-01         | Unknown             | No Swagger            |
| 2017-09-01         | Unknown             | No Swagger            |
| 2017-10-01-preview | Unknown             | No Swagger            |
| 2018-01-01-preview | Unknown             | No Swagger            |
| 2018-07-01         | Unknown             | No Swagger            |
| 2018-09-01-preview | Unknown             | No Swagger            |
| 2018-12-01-preview | Unknown             | No Swagger            |
| 2019-04-01-preview | Unknown             | No Swagger            |

### \$.properties.principalId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-07-01         | Unknown             | No Swagger            |
| 2017-05-01         | Unknown             | No Swagger            |
| 2017-09-01         | Unknown             | No Swagger            |
| 2017-10-01-preview | Unknown             | No Swagger            |
| 2018-01-01-preview | Unknown             | No Swagger            |
| 2018-07-01         | Unknown             | No Swagger            |
| 2018-09-01-preview | Unknown             | No Swagger            |
| 2018-12-01-preview | Unknown             | No Swagger            |
| 2019-04-01-preview | Unknown             | No Swagger            |
| 2020-03-01-preview | Unknown             | No Swagger            |

### \$.properties.principalType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-07-01         | Unknown             | No Swagger            |
| 2018-09-01-preview | Unknown             | No Swagger            |
| 2018-12-01-preview | Unknown             | No Swagger            |
| 2019-04-01-preview | Unknown             | No Swagger            |
| 2020-03-01-preview | Unknown             | No Swagger            |

### \$.properties.roleDefinitionId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-10-01-preview | Unknown             | No Swagger            |
| 2015-07-01         | Unknown             | No Swagger            |
| 2017-09-01         | Unknown             | No Swagger            |
| 2017-10-01-preview | Unknown             | No Swagger            |
| 2018-01-01-preview | Unknown             | No Swagger            |
| 2018-07-01         | Unknown             | No Swagger            |
| 2018-09-01-preview | Unknown             | No Swagger            |
| 2018-12-01-preview | Unknown             | No Swagger            |
| 2019-04-01-preview | Unknown             | No Swagger            |
| 2020-03-01-preview | Unknown             | No Swagger            |

### \$.properties.updatedBy

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-07-01-preview | Unknown             | No Swagger            |
| 2015-06-01         | Unknown             | No Swagger            |
| 2015-07-01         | Unknown             | No Swagger            |
| 2017-05-01         | Unknown             | No Swagger            |
| 2017-09-01         | Unknown             | No Swagger            |
| 2017-10-01-preview | Unknown             | No Swagger            |
| 2018-01-01-preview | Unknown             | No Swagger            |
| 2018-07-01         | Unknown             | No Swagger            |
| 2018-09-01-preview | Unknown             | No Swagger            |
| 2018-12-01-preview | Unknown             | No Swagger            |
| 2019-04-01-preview | Unknown             | No Swagger            |

### \$.properties.updatedOn

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-07-01-preview | Unknown             | No Swagger            |
| 2015-06-01         | Unknown             | No Swagger            |
| 2015-07-01         | Unknown             | No Swagger            |
| 2017-05-01         | Unknown             | No Swagger            |
| 2017-09-01         | Unknown             | No Swagger            |
| 2017-10-01-preview | Unknown             | No Swagger            |
| 2018-01-01-preview | Unknown             | No Swagger            |
| 2018-07-01         | Unknown             | No Swagger            |
| 2018-09-01-preview | Unknown             | No Swagger            |
| 2018-12-01-preview | Unknown             | No Swagger            |
| 2019-04-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-01         | Unknown             | No Swagger            |
| 2017-09-01         | Unknown             | No Swagger            |
| 2018-01-01-preview | Unknown             | No Swagger            |
| 2018-09-01-preview | Unknown             | No Swagger            |

## roleDefinitions

![cleanliness](https://img.shields.io/badge/cleanliness-21.43%25%20(3%20/%2014)-orange) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2011)-red)

### \$.properties.IsCustom

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Unknown             | No Swagger            |

### \$.properties.createdBy

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Unknown             | No Swagger            |
| 2018-07-01         | Unknown             | No Swagger            |

### \$.properties.createdOn

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Unknown             | No Swagger            |
| 2018-07-01         | Unknown             | No Swagger            |

### \$.properties.isCustom

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Unknown             | No Swagger            |

### \$.properties.type

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Unknown             | No Swagger            |

### \$.properties.updatedBy

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Unknown             | No Swagger            |
| 2018-07-01         | Unknown             | No Swagger            |

### \$.properties.updatedOn

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Unknown             | No Swagger            |
| 2018-07-01         | Unknown             | No Swagger            |
