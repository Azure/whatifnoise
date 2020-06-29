# Microsoft.DataFactory

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## dataFactories/datapipelines

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2010)-red)

### \$.properties.activities[*].scheduler

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.sink.writeBatchSize

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-01  | Default* (0)        | No Swagger            |

### \$.properties.activities[*].typeProperties.sink.writeBatchTimeout

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-01  | Unknown             | No Swagger            |

### \$.properties.end

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-01  | Unknown             | No Swagger            |

### \$.properties.hubName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-01  | Unknown             | No Swagger            |

### \$.properties.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-01  | Unknown             | No Swagger            |

### \$.properties.isPaused

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-01  | Default* (false)    | No Swagger            |

### \$.properties.pipelineMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-01  | Unknown             | No Swagger            |

### \$.properties.runtimeInfo

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-01  | Unknown             | No Swagger            |

### \$.properties.start

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-01  | Unknown             | No Swagger            |

## dataFactories/datasets

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%204)-red)

### \$.properties.createTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-01  | Unknown             | No Swagger            |

### \$.properties.external

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-01  | Unknown             | No Swagger            |

### \$.properties.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-01  | Unknown             | No Swagger            |

### \$.properties.published

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-01  | Default* (false)    | No Swagger            |

## dataFactories/gateways

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%206)-red)

### \$.properties.createTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-01  | Unknown             | No Swagger            |

### \$.properties.dataFactoryName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-01  | Unknown             | No Swagger            |

### \$.properties.isCredentialSyncFailed

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-01  | Default* (false)    | No Swagger            |

### \$.properties.serviceUrls

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-01  | Unknown             | No Swagger            |

### \$.properties.status

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-01  | Unknown             | No Swagger            |

### \$.properties.versionStatus

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-01  | Unknown             | No Swagger            |

## datafactories/linkedservices

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%205)-red)

### \$.properties.hubName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-01  | Unknown             | No Swagger            |

### \$.properties.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.connectionString

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.password

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.securityToken

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-01  | Unknown             | No Swagger            |

## dataFactories

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-09-01  | Unknown             | No Swagger            |
| 2015-10-01  | Unknown             | No Swagger            |

## factories/integrationRuntimes

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2010)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.managedVirtualNetwork.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.state

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-09-01-preview | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |

### \$.properties.typeProperties.ssisProperties.catalogInfo.catalogAdminPassword.value

| API version        | Detected noise type     | Determined noise type |
| ------------------ | ----------------------- | --------------------- |
| 2017-09-01-preview | Default* ("**********") | No Swagger            |
| 2018-06-01         | Default* ("**********") | No Swagger            |

### \$.properties.typeProperties.ssisProperties.catalogInfo.catalogServerEndpoint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.ssisProperties.customSetupScriptProperties.sasToken.value

| API version        | Detected noise type     | Determined noise type |
| ------------------ | ----------------------- | --------------------- |
| 2017-09-01-preview | Default* ("**********") | No Swagger            |
| 2018-06-01         | Default* ("**********") | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

## factories/linkedServices

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2035)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.accessKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.accessToken

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.accountKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.accountKey.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.apiKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.batchUri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.clientSecret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.clusterPassword

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.clusterSshPassword

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.connectionString

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-09-01-preview | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |

### \$.properties.typeProperties.connectionString.value

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-09-01-preview | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |

### \$.properties.typeProperties.credential.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.embeddedCertData.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.endpoint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.functionAppUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.functionKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.key

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.passPhrase

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.passPhrase.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.password

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-09-01-preview | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |

### \$.properties.typeProperties.privateKeyContent

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.refreshToken

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.sasUri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.secretAccessKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.securityToken

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-09-01-preview | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |

### \$.properties.typeProperties.serviceEndpoint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.servicePrincipalCredential

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.url

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-09-01-preview | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |

## factories/pipelines

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2053)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.activities[*].typeProperties.ifTrueActivities[*].typeProperties.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.activities[*].typeProperties.source.storeSettings.modifiedDatetimeStart

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.authentication.password.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.executionCredential.password.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.extendedProperties.activityTrackers[*].TriggerStartTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.extendedProperties.application-client-id.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.extendedProperties.application-client-id.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.extendedProperties.application-client-key.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.extendedProperties.application-client-key.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.extendedProperties.batchAccountKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.extendedProperties.monitoring-db-connection-string.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.extendedProperties.monitoring-db-connection-string.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.extendedProperties.storageAccountKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.extendedProperties.triggerStartTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.ifFalseActivities[*].typeProperties.extendedProperties.activityTrackers[*].TriggerStartTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.ifFalseActivities[*].typeProperties.extendedProperties.dataInterfaceTrackers[*].TriggerStartTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.ifFalseActivities[*].typeProperties.extendedProperties.triggerStartTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.ifTrueActivities[*].typeProperties.parameters.delta_default_date

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.mlPipelineId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.packageConnectionManagers.NEWDRSD.crmextr.Password.value.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.packageConnectionManagers.asazure://southcentralus.asazure.windows.net/nscl1epdb019.HospitalAccountDetails.Password.value.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.packageConnectionManagers.asazure://southcentralus.asazure.windows.net/nscl1epdb019.Password.value.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.packageConnectionManagers.asazure://southcentralus.asazure.windows.net/nscl1epdb019.ambulatory_flow.Password.value.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.packageConnectionManagers.asazure://southcentralus.asazure.windows.net/nscl1epdb019.datamodel_Inpatient_Flow.Password.value.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.packageConnectionManagers.ihazuresql004.database.windows.net.Pensieve.integrisadmin.Password.value.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.packageLocation.typeProperties.accessCredential.password.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.packageLocation.typeProperties.packagePassword.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.projectParameters.SOLTANTHONYNOLANORGUK_Password.value.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.source.storeSettings.modifiedDatetimeEnd

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.source.storeSettings.modifiedDatetimeStart

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.storeSettings.modifiedDatetimeEnd

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.storeSettings.modifiedDatetimeStart

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.activities[*].typeProperties.url

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.DateTimeTo.defaultValue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.LastLoadTimestamp.defaultValue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.LastModified_From.defaultValue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.LastModified_To.defaultValue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.LastSuccessfulRunDate.defaultValue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.LastSuccessfulRunDate_Utc.defaultValue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.ProcessStartTime.defaultValue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.WindowEnd.defaultValue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.WindowStart.defaultValue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.a11b49f1205e94ab28a4a0b244b861174-data-factory_connectionString.defaultValue.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.a18fb639a-f732-4768-9924-5532a9b25e4f-data-factory_connectionString.defaultValue.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.a37f605e3-8345-43a6-9278-c5cc143ec5a1-data-factory_connectionString.defaultValue.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.a7213653f5dd14a91bd35abeeb865d81e-data-factory_connectionString.defaultValue.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.afb2997ff0ce7455490a135c6ca5cd028-data-factory_connectionString.defaultValue.value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.parameters.delta_default_date.defaultValue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.variables.v_target_end_time.defaultValue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.variables.v_target_start_time.defaultValue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-09-01-preview | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |

## factories/triggers

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2011)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.pipeline.parameters.triggerStartTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.pipelines[*].parameters.windowEnd

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.pipelines[*].parameters.windowStart

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.endTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.recurrence.endTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.typeProperties.recurrence.startTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-09-01-preview | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |

### \$.properties.typeProperties.startTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-09-01-preview | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

## factories

![cleanliness](https://img.shields.io/badge/cleanliness-75.00%25%20(15%20/%2020)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%205)-red)

### \$.identity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.kind

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

## factories/managedvirtualnetworks

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |
