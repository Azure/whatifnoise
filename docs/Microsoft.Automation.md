# Microsoft.Automation

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## automationAccounts/certificates

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.base64Value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | Unknown               |

### \$.properties.isExportable

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Default* (false)    | Unknown               |

### \$.properties.thumbprint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | Unknown               |

## automationAccounts/compilationjobs

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-15  | Unknown             | Unknown               |

### \$.properties.incrementNodeConfigurationBuild

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-15  | Default* (false)    | Unknown               |

## automationAccounts/configurations

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.Source

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |

### \$.properties.description

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | Unknown               |

### \$.properties.logVerbose

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |
| 2015-10-31         | Unknown             | Unknown               |
| 2018-01-15         | Unknown             | No Swagger            |

### \$.properties.overwrite

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |
| 2018-01-15         | Unknown             | No Swagger            |

### \$.properties.parameters

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |
| 2015-10-31         | Unknown             | Unknown               |
| 2018-01-15         | Unknown             | No Swagger            |

### \$.properties.source

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |
| 2015-10-31         | Unknown             | Unknown               |
| 2018-01-15         | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |

## automationAccounts/connections

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.fieldDefinitionValues.CertificateThumbprint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | No Swagger            |

## automationAccounts/credentials

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |
| 2018-01-15         | Unknown             | No Swagger            |

### \$.properties.password

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |
| 2015-10-31         | Unknown             | Unknown               |
| 2018-01-15         | Unknown             | No Swagger            |

## automationAccounts/jobs

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |
| 2015-10-31         | Unknown             | No Swagger            |
| 2017-05-15-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |

## automationAccounts/jobSchedules

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-10-31         | Unknown             | No Swagger            |
| 2017-05-15-preview | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | No Swagger            |

## automationAccounts/modules

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |
| 2015-10-31         | Unknown             | Unknown               |
| 2017-05-15-preview | Unknown             | No Swagger            |
| 2018-06-30         | Unknown             | No Swagger            |

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |
| 2015-10-31         | Unknown             | Unknown               |
| 2017-05-15-preview | Unknown             | No Swagger            |
| 2018-06-30         | Unknown             | No Swagger            |

## automationAccounts/nodeConfigurations

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-15  | Unknown             | No Swagger            |

### \$.properties.Configuration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-15  | Unknown             | Unknown               |

### \$.properties.Source

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-15  | Unknown             | Unknown               |

### \$.properties.configuration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-15  | Unknown             | Unknown               |

### \$.properties.incrementNodeConfigurationBuild

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-15  | Default* (false)    | Unknown               |

## automationAccounts/runbooks

![23.53%25](https://img.shields.io/badge/23.53%25-%E2%98%85★%E2%98%86☆☆☆☆☆☆☆-orange)

### \$.properties.draft

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-30  | Unknown             | Unknown               |

### \$.properties.logActivityTrace

| API version        | Detected noise type | Determined noise type                                |
| ------------------ | ------------------- | ---------------------------------------------------- |
| 2015-01-01-preview | Default (0)         | No Swagger, Default (0) (inheritted from 2015-10-31) |
| 2015-10-31         | Default (0)         | Default (0)                                          |
| 2017-05-15-preview | Default (0)         | No Swagger, Default (0) (inheritted from 2018-06-30) |
| 2018-06-30         | Default (0)         | Default (0)                                          |

### \$.properties.logProgress

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Default (false)     | No Swagger            |
| 2017-05-15-preview | Default (false)     | No Swagger            |

### \$.properties.logVerbose

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Default (false)     | No Swagger            |
| 2017-05-15-preview | Default (false)     | No Swagger            |

### \$.properties.publishContentLink

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |
| 2015-10-31         | Unknown             | Unknown               |
| 2017-05-15-preview | Unknown             | No Swagger            |
| 2018-06-30         | Unknown             | Unknown               |

### \$.properties.publishcontentLink

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | Unknown               |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |
| 2018-06-30         | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | Unknown               |

## automationAccounts/schedules

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | No Swagger            |

### \$.properties.advancedSchedule

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Unknown             | No Swagger            |

### \$.properties.expiryTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-10-31         | Unknown             | Unknown               |
| 2017-05-15-preview | Unknown             | No Swagger            |

### \$.properties.frequency

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Default* ("Week")   | No Swagger            |

### \$.properties.startTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-10-31         | Unknown             | Unknown               |
| 2017-05-15-preview | Unknown             | No Swagger            |

### \$.properties.timeZone

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-10-31         | Unknown             | Unknown               |
| 2017-05-15-preview | Unknown             | No Swagger            |

## automationAccounts/softwareUpdateConfigurations

![6.67%25](https://img.shields.io/badge/6.67%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Unknown             | No Swagger            |

### \$.properties.scheduleInfo.advancedSchedule.weekDays[*]

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Unknown             | No Swagger            |

### \$.properties.scheduleInfo.creationTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Unknown             | Unknown               |

### \$.properties.scheduleInfo.expiryTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Unknown             | Unknown               |

### \$.properties.scheduleInfo.isEnabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Default (true)      | Default (true)        |

### \$.properties.scheduleInfo.lastModifiedTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Unknown             | Unknown               |

### \$.properties.scheduleInfo.nextRun

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Unknown             | Unknown               |

### \$.properties.scheduleInfo.startTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Unknown             | Unknown               |

### \$.properties.updateConfiguration.duration

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Unknown             | Unknown               |

### \$.properties.updateConfiguration.linux.IsInvalidPackageNameMasks

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Default* (false)    | No Swagger            |

### \$.properties.updateConfiguration.targets.azureQueries[*].scope[*]

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Unknown             | No Swagger            |

### \$.properties.updateConfiguration.windows.IsInvalidKbNumbers

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Default (false)     | No Swagger            |

### \$.properties.updateConfiguration.windows.includedUpdateClassifications

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Unknown             | Unknown               |

### \$.properties.updateConfiguration.windows.rebootSetting

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Unknown             | Unknown               |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Unknown             | No Swagger            |

## automationAccounts/variables

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | No Swagger            |
| 2018-01-15  | Unknown             | No Swagger            |

### \$.properties.isEncrypted

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-10-31         | Unknown             | Unknown               |
| 2017-05-15-preview | Unknown             | No Swagger            |
| 2018-01-15         | Unknown             | No Swagger            |
| 2018-06-30         | Unknown             | No Swagger            |

### \$.properties.mode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | No Swagger            |

### \$.properties.type

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-10-31         | Unknown             | No Swagger            |
| 2017-05-15-preview | Unknown             | No Swagger            |
| 2018-06-30         | Unknown             | No Swagger            |

### \$.properties.value

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-10-31         | Unknown             | Unknown               |
| 2017-05-15-preview | Unknown             | No Swagger            |
| 2018-01-15         | Unknown             | No Swagger            |
| 2018-06-30         | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | No Swagger            |

## automationAccounts/webhooks

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.expiryTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | Unknown               |

### \$.properties.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | Unknown               |

## automationAccounts

![11.76%25](https://img.shields.io/badge/11.76%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-orange)

### \$.properties.RegistrationUrl

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |
| 2015-10-31         | Unknown             | No Swagger            |
| 2017-05-15-preview | Unknown             | No Swagger            |
| 2018-01-15         | Unknown             | No Swagger            |
| 2018-06-30         | Unknown             | No Swagger            |

### \$.properties.mode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | No Swagger            |

### \$.properties.sku.family

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | Unknown               |

### \$.properties.sku.name

| API version        | Detected noise type | Determined noise type                                      |
| ------------------ | ------------------- | ---------------------------------------------------------- |
| 2015-01-01-preview | Default ("Basic")   | No Swagger, Default ("Basic") (inheritted from 2015-10-31) |
| 2015-10-31         | Default ("Basic")   | Default ("Basic")                                          |
| 2017-05-15-preview | Default ("Basic")   | No Swagger                                                 |
| 2018-01-15         | Default ("Basic")   | No Swagger                                                 |
| 2018-06-30         | Default ("Basic")   | No Swagger                                                 |

### \$.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |
| 2015-10-31         | Unknown             | Unknown               |

### \$.tags.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |
| 2015-10-31         | Unknown             | Unknown               |
