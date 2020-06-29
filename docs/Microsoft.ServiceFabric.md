# Microsoft.ServiceFabric

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## clusters/applications/services

![cleanliness](https://img.shields.io/badge/cleanliness-55.56%25%20(25%20/%2045)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2020)-red)

### \$.properties.correlationScheme

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | Unknown               |
| 2019-03-01         | Unknown             | No Swagger            |

### \$.properties.hasPersistedState

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |
| 2019-03-01         | Unknown             | No Swagger            |

### \$.properties.partitionDescription.highKey

| API version        | Detected noise type           | Determined noise type |
| ------------------ | ----------------------------- | --------------------- |
| 2017-07-01-preview | Default (9223372036854776000) | No Swagger            |
| 2019-03-01         | Default (9223372036854776000) | No Swagger            |
| 2019-06-01-preview | Default (9223372036854776000) | No Swagger            |

### \$.properties.partitionDescription.lowKey

| API version        | Detected noise type            | Determined noise type |
| ------------------ | ------------------------------ | --------------------- |
| 2017-07-01-preview | Default (-9223372036854776000) | No Swagger            |
| 2019-03-01         | Default (-9223372036854776000) | No Swagger            |
| 2019-06-01-preview | Default (-9223372036854776000) | No Swagger            |

### \$.properties.quorumLossWaitDuration

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |
| 2019-03-01         | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.replicaRestartWaitDuration

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |
| 2019-03-01         | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.standByReplicaKeepDuration

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |
| 2019-03-01         | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.targetReplicaSetSize

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Default* (5)        | No Swagger            |

## clusters/applications

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%20203)-red)

### \$.properties.managedIdentities[*].principalId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AZSECPACK_CUSTOMPOLICY_LOCATION

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AZSECPACK_DISABLED_FEATURES

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AZSECPACK_DISABLED_SCENARIOS

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AZSECPACK_PILOT_FEATURES

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AdHocEnvironmentVariables

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__0__ObjectId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__0__TenantId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__10__ObjectId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__10__TenantId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__11__ObjectId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__11__TenantId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__12__ObjectId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__12__TenantId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__13__ObjectId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__13__TenantId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__1__ObjectId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__1__TenantId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__2__ObjectId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__2__TenantId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__3__ObjectId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__3__TenantId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__4__ObjectId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__4__TenantId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__5__ObjectId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__5__TenantId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__6__ObjectId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__6__TenantId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__7__ObjectId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__7__TenantId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__8__ObjectId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__8__TenantId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__9__ObjectId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AllowListPrincipals__9__TenantId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AppInsightsInstrumentationKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.ApplicationId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.ApplicationsThatReportDeployedApplicationHealth

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.ApplicationsThatReportHealthEvents

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.ApplicationsThatReportPartitionHealth

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.ApplicationsThatReportReplicaHealth

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.ApplicationsThatReportServiceHealth

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.ApplicationsThatReportServicePackageHealth

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AzureAdApplicationId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AzureClp_AppInsights_InstrumentationKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AzureStackKeyVaultClientCertLocation

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AzureStackKeyVaultClientCertStore

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AzureStackKeyVaultClientCertSubject

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AzureStackKeyVaultClientId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.AzureStackKeyVaultUri

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.ClusterName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.DataCenterName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.DocDbKeySecret

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.DocDbUri

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.DynamicAnalysisProxyService-InstanceCount

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.DynamicAnalysisProxyService-PlacementConstraints

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.EOPSonar-ApiKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.EOPSonar-EndpointUri

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.EOPSonar-IsEnabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.EOPSonar-WorkflowNames

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.EgressAppId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.EgressIdentityPrincipalId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.EventHub-ActivePriorities

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.EventHub-CheckPointStorageConnectionString

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.EventHub-CommitMaxDegreeOfParallelism

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.EventHub-ConsumerGroupName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.EventHub-MaxBatchSize

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.EventHub-Name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.EventHub-ReceiverConnectionString

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.EventHub-Relationship-Name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.EventHub-Relationship-SenderConnectionString

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.EventRouter-DestinationName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.EventRouter-DestinationSenderConnectionString

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.EventRouter-Enabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.EventRouter-SourceName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.EventRouter-SourceReceiverConnectionString

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.GCSAccount

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.GCSAgentVersion

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.GCSAuthId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.GCSAuthIdType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.GCSCertStore

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.GCSConfigVersion

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.GCSDsmsUrl

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.GCSEndpoint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.GCSEnvironment

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.GCSExactVersion

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.GCSNamespace

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.GCSRegion

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.GCSStorageResourceTagType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.GCSStorageResourceTagValue

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.GCSThumbprint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.HealthDataReadIntervalInMinutes

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.HealthDataReadTimeoutInSeconds

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.HealthQueryTimeoutInSeconds

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.ImporterService_EventHub_Configuration_1

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.ImporterService_EventHub_Configuration_2

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.ImporterService_InstanceCount

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.ImporterService_PlacementConstraints

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.InstallWindowsOSOnlyUpdates

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | No Swagger            |

### \$.properties.parameters.JobInfraSAConnectionString

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.KustoDataManagementEndpoint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | No Swagger            |

### \$.properties.parameters.KustoEndpoint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | No Swagger            |

### \$.properties.parameters.MAConfigFileName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.MAMdmAccountName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.MAMdmNamespace

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.MARestartDelayInSeconds

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.MAXStoreAccounts

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.ManagedIdentityPrincipalId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.MdsAgentService_InstanceCount

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.Metadata-AppName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.Metadata-ChangeFlags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.Metadata-Key

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.Metadata-MaxRetries

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.Metadata-ResultsFileNamePerWorkflow

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.Metadata-ResultsFileNamesPerWorkflow

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.Metadata-RetryCadence

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.Metadata-ServicePrefix

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.MonitoringService_MinReplicaSetSize

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.MonitoringService_TargetReplicaSetSize

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.MsiKeyVaultUri

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.Relationship-AdHocRelationshipMapPerWorkflow

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.Relationship-RequiredRelationshipMapPerWorkflow

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.RelationshipService_EventHub_Configuration_1

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.RelationshipService_EventHub_Configuration_10

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.RelationshipService_EventHub_Configuration_11

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.RelationshipService_EventHub_Configuration_12

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.RelationshipService_EventHub_Configuration_13

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.RelationshipService_EventHub_Configuration_14

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.RelationshipService_EventHub_Configuration_15

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.RelationshipService_EventHub_Configuration_2

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.RelationshipService_EventHub_Configuration_3

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.RelationshipService_EventHub_Configuration_4

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.RelationshipService_EventHub_Configuration_5

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.RelationshipService_EventHub_Configuration_6

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.RelationshipService_EventHub_Configuration_7

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.RelationshipService_EventHub_Configuration_8

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.RelationshipService_EventHub_Configuration_9

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.RelationshipService_InstanceCount

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.RelationshipService_PlacementConstraints

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.ReportDeployedApplicationHealth

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.ReportHealthEvents

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.ReportPartitionHealth

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.ReportReplicaHealth

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.ReportServiceHealth

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.ReportServicePackageHealth

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.SampleStore-ApiKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.SampleStore-Timeout

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.SampleStore-Uri

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.SecretsCertificateThumbprint

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.Sonar-ApiKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.Sonar-BaseParameters

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.Sonar-DailyRequestLimit

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.Sonar-EhItemExponentialBackoffInSecondsBase

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.Sonar-EndpointUri

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.Sonar-HourlyRequestLimit

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.Sonar-IsEnabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.Sonar-MaxRetries

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.Sonar-WorkflowNames

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.UseConfigFile

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.UseGCS

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.WmsAppId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.XplatDetonation-IsEnabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.XplatDetonation-ServiceBusConnectionString

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters.XplatDetonation-WorkflowNames

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |

### \$.properties.removeApplicationCapacity

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Default (false)     | No Swagger            |
| 2019-03-01         | Default (false)     | No Swagger            |
| 2019-06-01-preview | Default (false)     | No Swagger            |

### \$.properties.upgradePolicy.applicationHealthPolicy.considerWarningAsError

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |
| 2019-03-01         | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.upgradePolicy.applicationHealthPolicy.defaultServiceTypeHealthPolicy.maxPercentUnhealthyPartitionsPerService

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Default* (0)        | No Swagger            |

### \$.properties.upgradePolicy.applicationHealthPolicy.defaultServiceTypeHealthPolicy.maxPercentUnhealthyReplicasPerPartition

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Default* (0)        | No Swagger            |

### \$.properties.upgradePolicy.applicationHealthPolicy.maxPercentUnhealthyDeployedApplications

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Default* (0)        | No Swagger            |

### \$.properties.upgradePolicy.forceRestart

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |
| 2019-03-01         | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.upgradePolicy.rollingUpgradeMonitoringPolicy.failureAction

| API version        | Detected noise type  | Determined noise type |
| ------------------ | -------------------- | --------------------- |
| 2017-07-01-preview | Default ("Rollback") | No Swagger            |
| 2019-03-01         | Default ("Rollback") | No Swagger            |

### \$.properties.upgradePolicy.rollingUpgradeMonitoringPolicy.healthCheckRetryTimeout

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |
| 2019-03-01-preview | Unknown             | No Swagger            |
| 2019-03-01         | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.upgradePolicy.rollingUpgradeMonitoringPolicy.healthCheckStableDuration

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |
| 2019-03-01-preview | Unknown             | No Swagger            |
| 2019-03-01         | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.upgradePolicy.rollingUpgradeMonitoringPolicy.healthCheckWaitDuration

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |
| 2019-03-01-preview | Unknown             | No Swagger            |
| 2019-03-01         | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.upgradePolicy.rollingUpgradeMonitoringPolicy.upgradeDomainTimeout

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |
| 2019-03-01-preview | Unknown             | No Swagger            |
| 2019-03-01         | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.upgradePolicy.rollingUpgradeMonitoringPolicy.upgradeTimeout

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |
| 2019-03-01-preview | Unknown             | No Swagger            |
| 2019-03-01         | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

### \$.properties.upgradePolicy.upgradeReplicaSetCheckTimeout

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |
| 2019-03-01-preview | Unknown             | No Swagger            |
| 2019-03-01         | Unknown             | No Swagger            |
| 2019-06-01-preview | Unknown             | No Swagger            |

## clusters/applicationTypes/versions

![cleanliness](https://img.shields.io/badge/cleanliness-80.00%25%20(4%20/%205)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties.appPackageUrl

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | Unknown               |

## clusters/applicationTypes

![cleanliness](https://img.shields.io/badge/cleanliness-66.67%25%20(2%20/%203)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | No Swagger            |

## clusters

![cleanliness](https://img.shields.io/badge/cleanliness-32.20%25%20(57%20/%20177)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%20120)-red)

### \$.properties.ClientCertificateCommonNames

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Unknown               |

### \$.properties.ReverseProxyCertificateCommonNames

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.addOnFeatures

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.addonFeatures

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.certificate.thumbprint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.certificate.x509StoreName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | No Swagger            |

### \$.properties.certificateCommonNames.x509StoreName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | No Swagger            |

### \$.properties.clientCertificateCommonNames

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.clientCertificateThumbprints

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2017-07-01-privatepreview | Unknown             | No Swagger            |

### \$.properties.clientCertificateThumbprints[*].IsAdmin

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2017-07-01-privatepreview | Unknown             | No Swagger            |
| 2019-03-01-privatepreview | Unknown             | No Swagger            |

### \$.properties.clientCertificateThumbprints[*].isAdmin

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2017-07-01-privatepreview | Default (true)      | No Swagger            |

### \$.properties.clusterCodeVersion

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2016-03-01                | Unknown             | No Swagger            |
| 2016-09-01                | Unknown             | No Swagger            |
| 2017-07-01-privatepreview | Unknown             | No Swagger            |
| 2017-07-01-preview        | Unknown             | No Swagger            |
| 2018-02-01                | Unknown             | No Swagger            |
| 2019-03-01-privatepreview | Unknown             | No Swagger            |
| 2019-03-01-preview        | Unknown             | No Swagger            |
| 2019-03-01                | Unknown             | No Swagger            |
| 2019-06-01-preview        | Unknown             | No Swagger            |

### \$.properties.diagnosticsStorageAccountConfig.blobEndpoint

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2016-03-01                | Unknown             | No Swagger            |
| 2016-09-01                | Unknown             | No Swagger            |
| 2017-07-01-privatepreview | Unknown             | No Swagger            |
| 2017-07-01-preview        | Unknown             | No Swagger            |
| 2018-02-01                | Unknown             | No Swagger            |
| 2019-03-01-privatepreview | Unknown             | No Swagger            |
| 2019-03-01-preview        | Unknown             | No Swagger            |
| 2019-03-01                | Unknown             | No Swagger            |
| 2019-06-01-privatepreview | Unknown             | No Swagger            |
| 2019-06-01-preview        | Unknown             | No Swagger            |

### \$.properties.diagnosticsStorageAccountConfig.queueEndpoint

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2016-03-01                | Unknown             | No Swagger            |
| 2016-09-01                | Unknown             | No Swagger            |
| 2017-07-01-privatepreview | Unknown             | No Swagger            |
| 2017-07-01-preview        | Unknown             | No Swagger            |
| 2018-02-01                | Unknown             | No Swagger            |
| 2019-03-01-privatepreview | Unknown             | No Swagger            |
| 2019-03-01-preview        | Unknown             | No Swagger            |
| 2019-03-01                | Unknown             | No Swagger            |
| 2019-06-01-privatepreview | Unknown             | No Swagger            |
| 2019-06-01-preview        | Unknown             | No Swagger            |

### \$.properties.diagnosticsStorageAccountConfig.tableEndpoint

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2016-03-01                | Unknown             | No Swagger            |
| 2016-09-01                | Unknown             | No Swagger            |
| 2017-07-01-privatepreview | Unknown             | No Swagger            |
| 2017-07-01-preview        | Unknown             | No Swagger            |
| 2018-02-01                | Unknown             | No Swagger            |
| 2019-03-01-privatepreview | Unknown             | No Swagger            |
| 2019-03-01-preview        | Unknown             | No Swagger            |
| 2019-03-01                | Unknown             | No Swagger            |
| 2019-06-01-privatepreview | Unknown             | No Swagger            |
| 2019-06-01-preview        | Unknown             | No Swagger            |

### \$.properties.fabricSettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.fabricSettings[*].parameters[*].value

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2018-02-01                | Unknown             | No Swagger            |
| 2019-03-01-privatepreview | Unknown             | No Swagger            |
| 2019-03-01-preview        | Unknown             | No Swagger            |
| 2019-03-01                | Unknown             | No Swagger            |

### \$.properties.managementEndpoint

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2016-09-01                | Unknown             | No Swagger            |
| 2017-07-01-privatepreview | Unknown             | No Swagger            |
| 2017-07-01-preview        | Unknown             | No Swagger            |
| 2018-02-01                | Unknown             | No Swagger            |
| 2019-03-01-privatepreview | Unknown             | No Swagger            |
| 2019-03-01-preview        | Unknown             | No Swagger            |
| 2019-03-01                | Unknown             | No Swagger            |
| 2019-06-01-privatepreview | Unknown             | No Swagger            |
| 2019-06-01-preview        | Unknown             | No Swagger            |

### \$.properties.nodeTypes[*].applicationPorts

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.nodeTypes[*].durabilityLevel

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2019-03-01  | Unknown             | No Swagger            |

### \$.properties.nodeTypes[*].ephemeralPorts

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.nodeTypes[*].isPrimary

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.nodeTypes[*].placementProperties.IsBackend

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.nodeTypes[*].placementProperties.IsFrontend

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.nodeTypes[*].placementProperties.backend

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.nodeTypes[*].placementProperties.frontend

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.nodeTypes[*].placementProperties.internalApi

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.nodeTypes[*].placementProperties.manager

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.nodeTypes[*].placementProperties.publicApi

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.nodeTypes[*].placementProperties.system

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.nodeTypes[*].placementProperties.worker

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.privateBuilds

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2017-07-01-privatepreview | Unknown             | No Swagger            |

### \$.properties.privateBuilds[*].BuildUrl

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2017-07-01-privatepreview | Unknown             | No Swagger            |
| 2019-03-01-privatepreview | Unknown             | No Swagger            |

### \$.properties.privateBuilds[*].FabricSettingsUrl

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2017-07-01-privatepreview | Unknown             | No Swagger            |
| 2019-03-01-privatepreview | Unknown             | No Swagger            |

### \$.properties.privateBuilds[*].Version

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2017-07-01-privatepreview | Unknown             | No Swagger            |
| 2019-03-01-privatepreview | Unknown             | No Swagger            |

### \$.properties.privateBuilds[*].buildUrl

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2017-07-01-privatepreview | Unknown             | No Swagger            |
| 2019-03-01-privatepreview | Unknown             | No Swagger            |

### \$.properties.privateBuilds[*].fabricSettingsUrl

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2017-07-01-privatepreview | Unknown             | No Swagger            |
| 2019-03-01-privatepreview | Unknown             | No Swagger            |

### \$.properties.privateBuilds[*].version

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2017-07-01-privatepreview | Unknown             | No Swagger            |
| 2019-03-01-privatepreview | Unknown             | No Swagger            |

### \$.properties.reliabilityLevel

| API version               | Detected noise type | Determined noise type |
| ------------------------- | ------------------- | --------------------- |
| 2017-07-01-privatepreview | Unknown             | No Swagger            |
| 2018-02-01                | Unknown             | No Swagger            |
| 2019-03-01-privatepreview | Unknown             | No Swagger            |
| 2019-03-01                | Unknown             | No Swagger            |
| 2019-06-01-preview        | Unknown             | No Swagger            |

### \$.properties.reverseProxyCertificateCommonNames

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.upgradeDescription.deltaHealthPolicy.maxPercentDeltaUnhealthyApplications

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Default* (0)        | No Swagger            |

### \$.properties.upgradeDescription.forceRestart

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Default* (false)    | No Swagger            |
| 2018-02-01         | Default* (false)    | No Swagger            |

### \$.properties.upgradeDescription.healthCheckRetryTimeout

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |
| 2018-02-01         | Unknown             | No Swagger            |
| 2019-03-01         | Unknown             | No Swagger            |

### \$.properties.upgradeDescription.healthCheckStableDuration

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |
| 2018-02-01         | Unknown             | No Swagger            |

### \$.properties.upgradeDescription.healthCheckWaitDuration

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |
| 2018-02-01         | Unknown             | No Swagger            |

### \$.properties.upgradeDescription.overrideUserUpgradePolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | No Swagger            |

### \$.properties.upgradeDescription.upgradeDomainTimeout

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |
| 2018-02-01         | Unknown             | No Swagger            |

### \$.properties.upgradeDescription.upgradeReplicaSetCheckTimeout

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |
| 2018-02-01         | Unknown             | No Swagger            |

### \$.properties.upgradeDescription.upgradeTimeout

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-07-01-preview | Unknown             | No Swagger            |
| 2018-02-01         | Unknown             | No Swagger            |
| 2019-03-01         | Unknown             | No Swagger            |

### \$.properties.upgradeMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |
| 2019-03-01  | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |
