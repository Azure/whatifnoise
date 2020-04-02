# Microsoft.OperationalInsights

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## workspaces/configurationScopes

!> No Swagger.

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

## workspaces/dataSources

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.kind

| API version        | Detected noise type                   | Determined noise type |
| ------------------ | ------------------------------------- | --------------------- |
| 2015-11-01-preview | Default* ("ChangeTrackingCustomPath") | Unknown               |

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.properties.Enabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.properties.LastUpdate

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.properties.collectorType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.properties.customLogName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.properties.enabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.properties.inputs[*].recordDelimiter.regexDelimiter.matchIndexSpecified

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.properties.maxContentsReturnable

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Default* (0)        | No Swagger            |

### \$.properties.maxOutputSize

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Default* (0)        | No Swagger            |

### \$.properties.recurse

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.properties.tier

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.properties.tierSetMethod

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.properties.useSudo

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | Unknown               |

## workspaces/linkedServices

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

## workspaces/storageInsightConfigs

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.containers

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-03-20  | Unknown             | Unknown               |

### \$.properties.workspaceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-03-20  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-03-20  | Unknown             | Unknown               |

## workspaces/views

!> No Swagger.

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-03-preview | Unknown             | No Swagger            |

### \$.properties.Description

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-03-preview | Unknown             | No Swagger            |

### \$.properties.Id

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-03-preview | Unknown             | No Swagger            |

### \$.properties.Name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-03-preview | Unknown             | No Swagger            |

### \$.properties.OverviewTile.Navigation

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-03-preview | Unknown             | No Swagger            |

### \$.properties.Version

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Default (0)         | No Swagger            |
| 2017-03-03-preview | Default (0)         | No Swagger            |

## workspaces

![3.33%25](https://img.shields.io/badge/3.33%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-20         | Unknown             | No Swagger            |
| 2015-11-01-preview | Unknown             | Unknown               |
| 2017-03-15-preview | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.features

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-20         | Unknown             | No Swagger            |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-03-preview | Unknown             | No Swagger            |
| 2017-03-15-preview | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.features.enableLogAccessUsingOnlyResourcePermissions

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-15-preview | Unknown             | No Swagger            |

### \$.properties.features.legacy

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Default (0)         | No Swagger            |
| 2017-03-15-preview | Default (0)         | No Swagger            |
| 2017-04-26-preview | Default (0)         | No Swagger            |

### \$.properties.features.searchVersion

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Default* (1)        | No Swagger            |

### \$.properties.mode

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-15-preview | Unknown             | No Swagger            |

### \$.properties.publicNetworkAccessForIngestion

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-03-preview | Unknown             | No Swagger            |
| 2017-03-15-preview | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.publicNetworkAccessForQuery

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-03-preview | Unknown             | No Swagger            |
| 2017-03-15-preview | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.retention

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-15-preview | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.retentionInDays

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-20         | Unknown             | No Swagger            |
| 2015-11-01-preview | Unknown             | Unknown               |
| 2017-03-15-preview | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | Unknown               |
| 2017-03-15-preview | Unknown             | No Swagger            |

### \$.properties.sku.Name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | Default ("pergb2018") |
| 2017-03-15-preview | Unknown             | No Swagger            |

### \$.properties.sku.capacityReservationLevel

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.properties.sku.features

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.properties.sku.lastSkuUpdate

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-20         | Unknown             | No Swagger            |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-03-preview | Unknown             | No Swagger            |
| 2017-03-15-preview | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.sku.name

| API version        | Detected noise type   | Determined noise type |
| ------------------ | --------------------- | --------------------- |
| 2015-11-01-preview | Default ("pergb2018") | Default ("pergb2018") |
| 2017-03-15-preview | Default ("pergb2018") | No Swagger            |
| 2017-04-26-preview | Default ("pergb2018") | No Swagger            |

### \$.properties.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-15-preview | Unknown             | No Swagger            |

### \$.properties.workspaceCapping

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-20         | Unknown             | No Swagger            |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-03-preview | Unknown             | No Swagger            |
| 2017-03-15-preview | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.workspaceCapping.dataIngestionStatus

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-15-preview | Unknown             | No Swagger            |

### \$.properties.workspaceCapping.quotaNextResetTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-15-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | Unknown               |
| 2017-03-15-preview | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.tags.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | Unknown               |
| 2017-03-15-preview | Unknown             | No Swagger            |

## workspaces/savedsearches/schedules/actions

!> No Swagger.

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.ScheduleTypeSpecified

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-15-preview | Default* (false)    | No Swagger            |

### \$.properties.Version

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-15-preview | Default* (1)        | No Swagger            |

### \$.properties.etag

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-15-preview | Unknown             | No Swagger            |

## workspaces/savedsearches/schedules

!> No Swagger.

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.Enabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-15-preview | Default* (true)     | No Swagger            |

### \$.properties.Interval

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-15-preview | Default* (5)        | No Swagger            |

### \$.properties.NearRealTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-15-preview | Default* (false)    | No Swagger            |

### \$.properties.QueryTimeSpan

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-15-preview | Unknown             | No Swagger            |

### \$.properties.enabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-15-preview | Unknown             | No Swagger            |

### \$.properties.etag

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-15-preview | Unknown             | No Swagger            |

### \$.properties.interval

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-15-preview | Unknown             | No Swagger            |

### \$.properties.queryTimeSpan

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-15-preview | Unknown             | No Swagger            |

## workspaces/savedsearches

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-20         | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.Category

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.DisplayName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.ETag

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-20         | Unknown             | No Swagger            |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-03-preview | Unknown             | No Swagger            |
| 2017-03-15-preview | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.FunctionAlias

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.Query

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.Tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.Version

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-20         | Default (2)         | Unknown               |
| 2015-11-01-preview | Default (2)         | No Swagger            |
| 2017-03-03-preview | Default (2)         | No Swagger            |
| 2017-03-15-preview | Default (2)         | No Swagger            |
| 2017-04-26-preview | Default (2)         | No Swagger            |

### \$.properties.category

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.displayname

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.etag

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-20         | Unknown             | No Swagger            |
| 2017-03-15-preview | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.functionAlias

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.query

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-03-20  | Unknown             | No Swagger            |
