# Microsoft.OperationalInsights

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## workspaces/configurationScopes

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

## workspaces/dataSources

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2016)-red)

### \$.kind

| API version        | Detected noise type                  | Determined noise type |
| ------------------ | ------------------------------------ | --------------------- |
| 2015-11-01-preview | Default ("ChangeTrackingCustomPath") | No Swagger            |

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

### \$.properties.counterName

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
| 2015-11-01-preview | Default (0)         | No Swagger            |

### \$.properties.maxOutputSize

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Default (0)         | No Swagger            |

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
| 2015-11-01-preview | Unknown             | No Swagger            |

## workspaces/linkedServices

![cleanliness](https://img.shields.io/badge/cleanliness-40.00%25%20(2%20/%205)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%203)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2020-03-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

## workspaces/storageInsightConfigs

![cleanliness](https://img.shields.io/badge/cleanliness-70.00%25%20(7%20/%2010)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%203)-red)

### \$.properties.containers

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-03-20  | Unknown             | No Swagger            |

### \$.properties.workspaceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-03-20  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-03-20  | Unknown             | No Swagger            |

## workspaces/views

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2011)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-03-preview | Unknown             | No Swagger            |

### \$.properties.Description

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
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

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%20103)-red)

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-20         | Unknown             | No Swagger            |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-15-preview | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.Actions

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.properties.createdDate

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-20         | Unknown             | No Swagger            |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-15-preview | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2020-03-01-preview | Unknown             | No Swagger            |

### \$.properties.enableFailover

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-20         | Default (false)     | No Swagger            |
| 2015-11-01-preview | Default (false)     | No Swagger            |
| 2017-03-15-preview | Default (false)     | No Swagger            |
| 2017-04-26-preview | Default (false)     | No Swagger            |
| 2020-03-01-preview | Default (false)     | No Swagger            |

### \$.properties.features

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-20         | Unknown             | No Swagger            |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-03-preview | Unknown             | No Swagger            |
| 2017-03-15-preview | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2020-03-01-preview | Unknown             | No Swagger            |

### \$.properties.features.enableLogAccessUsingOnlyResourcePermissions

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-15-preview | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2020-03-01-preview | Unknown             | No Swagger            |

### \$.properties.features.immediatePurgeDataOn30Days

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-15-preview | Unknown             | No Swagger            |

### \$.properties.features.legacy

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-15-preview | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2020-03-01-preview | Unknown             | No Swagger            |

### \$.properties.features.searchVersion

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Default* (1)        | No Swagger            |
| 2017-03-15-preview | Default* (1)        | No Swagger            |
| 2017-04-26-preview | Default* (1)        | No Swagger            |

### \$.properties.mode

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-15-preview | Unknown             | No Swagger            |

### \$.properties.modifiedDate

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-20         | Unknown             | No Swagger            |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-15-preview | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2020-03-01-preview | Unknown             | No Swagger            |

### \$.properties.publicNetworkAccessForIngestion

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-20         | Unknown             | No Swagger            |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-03-preview | Unknown             | No Swagger            |
| 2017-03-15-preview | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.publicNetworkAccessForQuery

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-20         | Unknown             | No Swagger            |
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

### \$.properties.retentionDays

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2020-03-01-preview | Unknown             | No Swagger            |

### \$.properties.retentionInDays

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-20         | Unknown             | No Swagger            |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-15-preview | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2020-03-01-preview | Unknown             | No Swagger            |

### \$.properties.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-15-preview | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2020-03-01-preview | Unknown             | No Swagger            |

### \$.properties.sku.Name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |
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
| 2020-03-01-preview | Unknown             | No Swagger            |

### \$.properties.sku.maxCapacityReservationLevel

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-20         | Unknown             | No Swagger            |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-03-preview | Unknown             | No Swagger            |
| 2017-03-15-preview | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2020-03-01-preview | Unknown             | No Swagger            |

### \$.properties.sku.name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-03-preview | Unknown             | No Swagger            |
| 2017-03-15-preview | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.sku.retentionInDays

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |

### \$.properties.source

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-03-preview | Unknown             | No Swagger            |
| 2017-03-15-preview | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2020-03-01-preview | Unknown             | No Swagger            |

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
| 2020-03-01-preview | Unknown             | No Swagger            |

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
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-15-preview | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.tags.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-11-01-preview | Unknown             | No Swagger            |
| 2017-03-15-preview | Unknown             | No Swagger            |

## workspaces/savedsearches/schedules/actions

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%206)-red)

### \$.properties.ScheduleTypeSpecified

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-15-preview | Default (false)     | No Swagger            |
| 2017-04-26-preview | Default (false)     | No Swagger            |

### \$.properties.Version

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-15-preview | Default (1)         | No Swagger            |
| 2017-04-26-preview | Default (1)         | No Swagger            |

### \$.properties.etag

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-15-preview | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |

## workspaces/savedsearches/schedules

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2010)-red)

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
| 2017-03-15-preview | Default (false)     | No Swagger            |
| 2017-04-26-preview | Default (false)     | No Swagger            |

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
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.interval

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-15-preview | Unknown             | No Swagger            |

### \$.properties.queryTimeSpan

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-15-preview | Unknown             | No Swagger            |

## workspaces/savedsearches

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2027)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-15-preview | Unknown             | No Swagger            |
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
| 2015-03-20         | Default (2)         | No Swagger            |
| 2015-11-01-preview | Default (2)         | No Swagger            |
| 2017-03-03-preview | Default (2)         | No Swagger            |
| 2017-03-15-preview | Default (2)         | No Swagger            |
| 2017-04-26-preview | Default (2)         | No Swagger            |

### \$.properties.category

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.description

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-03-15-preview | Unknown             | No Swagger            |

### \$.properties.displayname

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.etag

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-03-20         | Unknown             | No Swagger            |
| 2015-11-01-preview | Unknown             | No Swagger            |
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
| 2015-03-20  | Unknown             | Unknown               |
