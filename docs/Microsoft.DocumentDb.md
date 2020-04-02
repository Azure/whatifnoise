# Microsoft.DocumentDb

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## databaseAccounts/apis/databases/collections

![22.22%25](https://img.shields.io/badge/22.22%25-%E2%98%85★%E2%98%86☆☆☆☆☆☆☆-orange)

### \$.properties._etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |
| 2016-03-31  | Unknown             | No Swagger            |

### \$.properties._rid

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |
| 2016-03-31  | Unknown             | No Swagger            |

### \$.properties._ts

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | Read-only             |
| 2016-03-31  | Unknown             | Read-only             |

### \$.properties.options

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-31  | Unknown             | Unknown               |

### \$.properties.resource

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | Unknown               |
| 2016-03-31  | Unknown             | Unknown               |

## databaseAccounts/apis/databases/containers/settings

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.minimumThroughput

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-31  | Unknown             | No Swagger            |

### \$.properties.resource

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-31  | Unknown             | Unknown               |

## databaseAccounts/apis/databases/containers

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties._conflicts

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |
| 2016-03-31  | Unknown             | No Swagger            |

### \$.properties._docs

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |
| 2016-03-31  | Unknown             | No Swagger            |

### \$.properties._self

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |
| 2016-03-31  | Unknown             | No Swagger            |

### \$.properties._sprocs

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |
| 2016-03-31  | Unknown             | No Swagger            |

### \$.properties._triggers

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |
| 2016-03-31  | Unknown             | No Swagger            |

### \$.properties._udfs

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |
| 2016-03-31  | Unknown             | No Swagger            |

### \$.properties.geospatialConfig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |
| 2016-03-31  | Unknown             | No Swagger            |

### \$.properties.options

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | Unknown               |
| 2016-03-31  | Unknown             | Unknown               |

### \$.properties.resource

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | Unknown               |
| 2016-03-31  | Unknown             | Unknown               |

### \$.properties.statistics

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |
| 2016-03-31  | Unknown             | No Swagger            |

## databaseAccounts/apis/databases/graphs

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties._conflicts

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-31  | Unknown             | No Swagger            |

### \$.properties._docs

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-31  | Unknown             | No Swagger            |

### \$.properties._self

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-31  | Unknown             | No Swagger            |

### \$.properties._sprocs

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-31  | Unknown             | No Swagger            |

### \$.properties._triggers

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-31  | Unknown             | No Swagger            |

### \$.properties._udfs

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-31  | Unknown             | No Swagger            |

### \$.properties.geospatialConfig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-31  | Unknown             | No Swagger            |

### \$.properties.resource

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-31  | Unknown             | Unknown               |

### \$.properties.statistics

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-31  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-31  | Unknown             | Unknown               |

## databaseAccounts/apis/databases/settings

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.minimumThroughput

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-31  | Unknown             | No Swagger            |

### \$.properties.resource

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-31  | Unknown             | Unknown               |

## databaseAccounts/apis/databases

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | Unknown               |
| 2016-03-31  | Unknown             | Unknown               |

### \$.properties._self

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |
| 2016-03-31  | Unknown             | No Swagger            |

### \$.properties.options

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | Unknown               |
| 2016-03-31  | Unknown             | Unknown               |

### \$.properties.resource

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | Unknown               |
| 2016-03-31  | Unknown             | Unknown               |

### \$.properties.throughput

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-31  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-31  | Unknown             | Unknown               |

## databaseAccounts/apis/tables

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties._etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |

### \$.properties._rid

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |

### \$.properties.options

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | Unknown               |

### \$.properties.resource

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | Unknown               |

## databaseAccounts/cassandraKeyspaces/tables

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.resource.defaultTtl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Default* (-1)       | Unknown               |

### \$.properties.resource.options

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.resource.schema.clusterKeys[*].orderBy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

## databaseAccounts/gremlinDatabases/graphs

![5.00%25](https://img.shields.io/badge/5.00%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-red)

### \$.properties.options

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-12-12  | Unknown             | Unknown               |

### \$.properties.resource._conflicts

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-12-12  | Unknown             | No Swagger            |

### \$.properties.resource._docs

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-12-12  | Unknown             | No Swagger            |

### \$.properties.resource._self

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Read-only             |

### \$.properties.resource._sprocs

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-12-12  | Unknown             | No Swagger            |

### \$.properties.resource._triggers

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-12-12  | Unknown             | No Swagger            |

### \$.properties.resource._udfs

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-12-12  | Unknown             | No Swagger            |

### \$.properties.resource.conflictResolutionPolicy.conflictResolutionPath

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.resource.geospatialConfig

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-12-12  | Unknown             | No Swagger            |

### \$.properties.resource.indexingPolicy.automatic

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Default* (true)     | Unknown               |

### \$.properties.resource.indexingPolicy.excludedPaths[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.resource.options

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.resource.statistics

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-12-12  | Unknown             | No Swagger            |

## databaseAccounts/gremlinDatabases

![20.00%25](https://img.shields.io/badge/20.00%25-%E2%98%85★%E2%98%86☆☆☆☆☆☆☆-orange)

### \$.properties.resource._colls

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-12-12  | Unknown             | No Swagger            |

### \$.properties.resource._self

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Read-only             |

### \$.properties.resource._users

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-12-12  | Unknown             | No Swagger            |

## databaseAccounts/mongodbDatabases/collections

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.options

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.resource.indexes[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.resource.indexes[*].key.keys[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.resource.indexes[*].options

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.resource.indexes[*].options.unique

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Default* (true)     | No Swagger            |

### \$.properties.resource.options

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

## databaseAccounts/mongodbDatabases

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.options

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Unknown               |

## databaseAccounts/notebookWorkspaces

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-12-12  | Unknown             | No Swagger            |

## databaseAccounts/sqlDatabases/containers/storedProcedures

![100.00%25](https://img.shields.io/badge/100.00%25-%E2%98%85★★★★★★★★★-brightgreen)

### \$.properties.resource._self

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Read-only             |

## databaseAccounts/sqlDatabases/containers/triggers

![100.00%25](https://img.shields.io/badge/100.00%25-%E2%98%85★★★★★★★★★-brightgreen)

### \$.properties.resource._self

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Read-only             |

## databaseAccounts/sqlDatabases/containers/userDefinedFunctions

![100.00%25](https://img.shields.io/badge/100.00%25-%E2%98%85★★★★★★★★★-brightgreen)

### \$.properties.resource._self

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Read-only             |

## databaseAccounts/sqlDatabases/containers

![41.67%25](https://img.shields.io/badge/41.67%25-%E2%98%85★★★%E2%98%86☆☆☆☆☆-yellow)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.options

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Unknown               |
| 2019-12-12  | Unknown             | Unknown               |

### \$.properties.resource._conflicts

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Read-only             |

### \$.properties.resource._docs

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Read-only             |

### \$.properties.resource._self

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Read-only             |

### \$.properties.resource._sprocs

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Read-only             |

### \$.properties.resource._triggers

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Read-only             |

### \$.properties.resource._udfs

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Read-only             |

### \$.properties.resource.conflictResolutionPolicy.conflictResolutionPath

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Unknown               |
| 2019-12-12  | Unknown             | Unknown               |

### \$.properties.resource.geospatialConfig

| API version | Detected noise type | Determined noise type          |
| ----------- | ------------------- | ------------------------------ |
| 2019-08-01  | Unknown             | Default ({"type":"Geography"}) |

### \$.properties.resource.indexingPolicy.automatic

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Default (true)      | Default (true)        |
| 2019-12-12  | Default (true)      | Default (true)        |

### \$.properties.resource.indexingPolicy.excludedPaths

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Unknown               |
| 2019-12-12  | Unknown             | Unknown               |

### \$.properties.resource.indexingPolicy.excludedPaths[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.resource.indexingPolicy.includedPaths

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Unknown               |
| 2019-12-12  | Unknown             | Unknown               |

### \$.properties.resource.indexingPolicy.includedPaths[*].indexes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.resource.indexingPolicy.indexinMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-12-12  | Unknown             | No Swagger            |

### \$.properties.resource.statistics

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Read-only             |

### \$.properties.resource.uniqueKeyPolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-12-12  | Unknown             | Unknown               |

## databaseAccounts/sqlDatabases

![8.33%25](https://img.shields.io/badge/8.33%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties._colls

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |

### \$.properties._etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |

### \$.properties._rid

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |

### \$.properties._self

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |

### \$.properties._users

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |

### \$.properties.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |

### \$.properties.options

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Unknown               |
| 2019-12-12  | Unknown             | Unknown               |

### \$.properties.resource

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |

### \$.properties.resource._self

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Read-only             |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Unknown               |

## databaseAccounts/tables

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.options

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Unknown               |
| 2019-12-12  | Unknown             | Unknown               |

## databaseAccounts

![35.09%25](https://img.shields.io/badge/35.09%25-%E2%98%85★★★%E2%98%86☆☆☆☆☆-yellow)

### \$.properties.EnabledApiTypes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | Default ("Sql")       |
| 2016-03-19  | Unknown             | Default ("Sql")       |
| 2016-03-31  | Unknown             | Default ("Sql")       |
| 2019-08-01  | Unknown             | Default ("Sql")       |
| 2019-12-12  | Unknown             | Default ("Sql")       |

### \$.properties.apiProperties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-12-12  | Unknown             | No Swagger            |

### \$.properties.capabilities

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.capabilities[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |

### \$.properties.cassandraEndpoint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | Read-only             |
| 2019-08-01  | Unknown             | Read-only             |

### \$.properties.configurationOverrides

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |
| 2016-03-31  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-12-12  | Unknown             | No Swagger            |

### \$.properties.consistencyPolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | Unknown               |
| 2016-03-31  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |
| 2019-12-12  | Unknown             | Unknown               |

### \$.properties.consistencyPolicy.defaultConsistencyLevel

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | Unknown               |
| 2016-03-31  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |
| 2019-12-12  | Unknown             | Unknown               |
| 2020-03-01  | Unknown             | Unknown               |

### \$.properties.consistencyPolicy.maxIntervalInSeconds

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | Unknown               |
| 2016-03-31  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |
| 2019-12-12  | Unknown             | Unknown               |

### \$.properties.consistencyPolicy.maxIntervallInSeconds

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |

### \$.properties.consistencyPolicy.maxStalenessPrefix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | Unknown               |
| 2016-03-19  | Unknown             | Unknown               |
| 2016-03-31  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |
| 2019-12-12  | Unknown             | Unknown               |

### \$.properties.databaseAccountName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |

### \$.properties.dependsOn

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |
| 2019-12-12  | Unknown             | No Swagger            |

### \$.properties.disableKeyBasedMetadataWriteAccess

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Default (false)     | Default (false)       |
| 2016-03-19  | Default (false)     | Default (false)       |
| 2016-03-31  | Default (false)     | Default (false)       |
| 2019-08-01  | Default (false)     | Default (false)       |
| 2019-12-12  | Default (false)     | Default (false)       |

### \$.properties.enableAutomaticFailover

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | Default (false)       |
| 2016-03-19  | Unknown             | Default (false)       |
| 2016-03-31  | Unknown             | Default (false)       |
| 2019-08-01  | Unknown             | Default (false)       |
| 2019-12-12  | Unknown             | Default (false)       |

### \$.properties.enableFreeTier

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Default (false)     | No Swagger            |
| 2016-03-31  | Default (false)     | No Swagger            |
| 2019-08-01  | Default (false)     | No Swagger            |
| 2019-12-12  | Default (false)     | No Swagger            |
| 2020-03-01  | Default (false)     | No Swagger            |

### \$.properties.enableMultipleWriteLocations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Default (false)     | Default (false)       |
| 2016-03-19  | Default (false)     | Default (false)       |
| 2016-03-31  | Default (false)     | Default (false)       |
| 2019-08-01  | Default (false)     | Default (false)       |
| 2019-12-12  | Default (false)     | Default (false)       |

### \$.properties.enablePartitionKeyMonitor

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Default (false)     | Default (false)       |
| 2016-03-19  | Default (false)     | Default (false)       |
| 2016-03-31  | Default (false)     | Default (false)       |
| 2019-08-01  | Default (false)     | Default (false)       |
| 2019-12-12  | Default (false)     | Default (false)       |

### \$.properties.gremlinEndpoint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | Read-only             |
| 2019-08-01  | Unknown             | Read-only             |
| 2019-12-12  | Unknown             | Read-only             |

### \$.properties.ipRangeFilter

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.isVirtualNetworkFilterEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | Default (false)       |
| 2016-03-19  | Unknown             | Default (false)       |
| 2016-03-31  | Unknown             | Default (false)       |
| 2019-08-01  | Unknown             | Default (false)       |
| 2019-12-12  | Unknown             | Default (false)       |

### \$.properties.locationName1

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |

### \$.properties.locations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | Unknown               |
| 2016-03-19  | Unknown             | Unknown               |
| 2016-03-31  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |
| 2019-12-12  | Unknown             | Unknown               |

### \$.properties.locations[*].failoverPriority

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |
| 2016-03-31  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.locations[*].isZoneRedundant

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Default (false)     | No Swagger            |
| 2016-03-31  | Default (false)     | No Swagger            |
| 2019-08-01  | Default (false)     | No Swagger            |
| 2019-12-12  | Default (false)     | No Swagger            |

### \$.properties.locations[*].locationName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |
| 2016-03-31  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.mongoEndpoint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Read-only             |
| 2019-12-12  | Unknown             | Read-only             |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |
| 2016-03-19  | Unknown             | No Swagger            |
| 2016-03-31  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.publicNetworkAccess

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |
| 2016-03-31  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-12-12  | Unknown             | No Swagger            |

### \$.properties.tableEndpoint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | Read-only             |
| 2019-08-01  | Unknown             | Read-only             |
| 2019-12-12  | Unknown             | Read-only             |

### \$.properties.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | No Swagger            |

### \$.properties.virtualNetworkRules[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-31  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.virtualNetworkRules[*].ignoreMissingVNetServiceEndpoint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Default (false)     | No Swagger            |
| 2019-12-12  | Default (false)     | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-12-12  | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-04-08  | Unknown             | Unknown               |
| 2016-03-31  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |
| 2019-12-12  | Unknown             | Unknown               |

## databaseaccounts/cassandrakeyspaces

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.options

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-12-12  | Unknown             | Unknown               |
