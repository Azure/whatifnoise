# Microsoft.Authorization

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## locks

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |

## policyAssignments

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.enforcementMode

| API version | Detected noise type  | Determined noise type |
| ----------- | -------------------- | --------------------- |
| 2019-06-01  | Default* ("Default") | Unknown               |
| 2019-09-01  | Default* ("Default") | Unknown               |

### \$.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | Unknown               |
| 2018-05-01  | Unknown             | Unknown               |
| 2019-01-01  | Unknown             | Unknown               |
| 2019-06-01  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Unknown               |

## policyDefinitions

![28.57%25](https://img.shields.io/badge/28.57%25-%E2%98%85★★%E2%98%86☆☆☆☆☆☆-orange)

### \$.properties.mode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | Default ("Indexed")   |

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
| 2018-05-01  | Default ("Custom")  | Default ("Custom")    |

## policySetDefinitions

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

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
| 2018-05-01  | Default* ("Custom") | Unknown               |

## roleAssignments

![50.00%25](https://img.shields.io/badge/50.00%25-%E2%98%85★★★★%E2%98%86☆☆☆☆-yellow)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-01         | Unknown             | No Swagger            |
| 2017-05-01         | Unknown             | No Swagger            |
| 2017-10-01-preview | Unknown             | No Swagger            |
| 2018-07-01         | Unknown             | No Swagger            |
| 2018-09-01-preview | Unknown             | No Swagger            |

### \$.properties.canDelegate

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-01-preview | Unknown             | Unknown               |

### \$.properties.createdBy

| API version        | Detected noise type | Determined noise type                                      |
| ------------------ | ------------------- | ---------------------------------------------------------- |
| 2014-07-01-preview | Unknown             | No Swagger, Read-only (inheritted from 2015-07-01)         |
| 2015-06-01         | Unknown             | No Swagger, Read-only (inheritted from 2015-07-01)         |
| 2015-07-01         | Unknown             | Read-only                                                  |
| 2017-05-01         | Unknown             | No Swagger, Read-only (inheritted from 2017-10-01-preview) |
| 2017-09-01         | Unknown             | No Swagger, Read-only (inheritted from 2017-10-01-preview) |
| 2017-10-01-preview | Unknown             | Read-only                                                  |
| 2018-01-01-preview | Unknown             | Read-only                                                  |
| 2018-07-01         | Unknown             | No Swagger, Read-only (inheritted from 2018-09-01-preview) |
| 2018-09-01-preview | Unknown             | Read-only                                                  |
| 2018-12-01-preview | Unknown             | No Swagger                                                 |
| 2019-04-01-preview | Unknown             | No Swagger                                                 |

### \$.properties.createdOn

| API version        | Detected noise type | Determined noise type                                      |
| ------------------ | ------------------- | ---------------------------------------------------------- |
| 2014-07-01-preview | Unknown             | No Swagger, Read-only (inheritted from 2015-07-01)         |
| 2015-06-01         | Unknown             | No Swagger, Read-only (inheritted from 2015-07-01)         |
| 2015-07-01         | Unknown             | Read-only                                                  |
| 2017-05-01         | Unknown             | No Swagger, Read-only (inheritted from 2017-10-01-preview) |
| 2017-09-01         | Unknown             | No Swagger, Read-only (inheritted from 2017-10-01-preview) |
| 2017-10-01-preview | Unknown             | Read-only                                                  |
| 2018-01-01-preview | Unknown             | Read-only                                                  |
| 2018-07-01         | Unknown             | No Swagger, Read-only (inheritted from 2018-09-01-preview) |
| 2018-09-01-preview | Unknown             | Read-only                                                  |
| 2018-12-01-preview | Unknown             | No Swagger                                                 |
| 2019-04-01-preview | Unknown             | No Swagger                                                 |

### \$.properties.principalId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-07-01         | Unknown             | Unknown               |
| 2017-05-01         | Unknown             | No Swagger            |
| 2017-09-01         | Unknown             | No Swagger            |
| 2017-10-01-preview | Unknown             | Unknown               |
| 2018-01-01-preview | Unknown             | Unknown               |
| 2018-07-01         | Unknown             | No Swagger            |
| 2018-09-01-preview | Unknown             | Unknown               |
| 2018-12-01-preview | Unknown             | No Swagger            |

### \$.properties.principalType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-07-01         | Unknown             | No Swagger            |
| 2018-09-01-preview | Unknown             | Unknown               |
| 2018-12-01-preview | Unknown             | No Swagger            |
| 2019-04-01-preview | Unknown             | No Swagger            |

### \$.properties.roleDefinitionId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-07-01         | Unknown             | Unknown               |
| 2017-09-01         | Unknown             | No Swagger            |
| 2017-10-01-preview | Unknown             | Unknown               |
| 2018-01-01-preview | Unknown             | Unknown               |
| 2018-07-01         | Unknown             | No Swagger            |
| 2018-09-01-preview | Unknown             | Unknown               |

### \$.properties.updatedBy

| API version        | Detected noise type | Determined noise type                                      |
| ------------------ | ------------------- | ---------------------------------------------------------- |
| 2014-07-01-preview | Unknown             | No Swagger, Read-only (inheritted from 2015-07-01)         |
| 2015-06-01         | Unknown             | No Swagger, Read-only (inheritted from 2015-07-01)         |
| 2015-07-01         | Unknown             | Read-only                                                  |
| 2017-05-01         | Unknown             | No Swagger, Read-only (inheritted from 2017-10-01-preview) |
| 2017-09-01         | Unknown             | No Swagger, Read-only (inheritted from 2017-10-01-preview) |
| 2017-10-01-preview | Unknown             | Read-only                                                  |
| 2018-01-01-preview | Unknown             | Read-only                                                  |
| 2018-07-01         | Unknown             | No Swagger, Read-only (inheritted from 2018-09-01-preview) |
| 2018-09-01-preview | Unknown             | Read-only                                                  |
| 2018-12-01-preview | Unknown             | No Swagger                                                 |
| 2019-04-01-preview | Unknown             | No Swagger                                                 |

### \$.properties.updatedOn

| API version        | Detected noise type | Determined noise type                                      |
| ------------------ | ------------------- | ---------------------------------------------------------- |
| 2014-07-01-preview | Unknown             | No Swagger, Read-only (inheritted from 2015-07-01)         |
| 2015-06-01         | Unknown             | No Swagger, Read-only (inheritted from 2015-07-01)         |
| 2015-07-01         | Unknown             | Read-only                                                  |
| 2017-05-01         | Unknown             | No Swagger, Read-only (inheritted from 2017-10-01-preview) |
| 2017-09-01         | Unknown             | No Swagger, Read-only (inheritted from 2017-10-01-preview) |
| 2017-10-01-preview | Unknown             | Read-only                                                  |
| 2018-01-01-preview | Unknown             | Read-only                                                  |
| 2018-07-01         | Unknown             | No Swagger, Read-only (inheritted from 2018-09-01-preview) |
| 2018-09-01-preview | Unknown             | Read-only                                                  |
| 2018-12-01-preview | Unknown             | No Swagger                                                 |
| 2019-04-01-preview | Unknown             | No Swagger                                                 |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-01         | Unknown             | No Swagger            |
| 2017-09-01         | Unknown             | No Swagger            |
| 2018-01-01-preview | Unknown             | No Swagger            |
| 2018-09-01-preview | Unknown             | No Swagger            |

## roleDefinitions

![40.00%25](https://img.shields.io/badge/40.00%25-%E2%98%85★★★%E2%98%86☆☆☆☆☆-yellow)

### \$.properties.IsCustom

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Unknown             | No Swagger            |

### \$.properties.createdBy

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Unknown             | Read-only             |
| 2018-07-01         | Unknown             | No Swagger            |

### \$.properties.createdOn

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Unknown             | Read-only             |
| 2018-07-01         | Unknown             | No Swagger            |

### \$.properties.type

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Unknown             | Unknown               |

### \$.properties.updatedBy

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Unknown             | Read-only             |
| 2018-07-01         | Unknown             | No Swagger            |

### \$.properties.updatedOn

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-01-01-preview | Unknown             | Read-only             |
| 2018-07-01         | Unknown             | No Swagger            |
