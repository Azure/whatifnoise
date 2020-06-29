# Microsoft.Automation

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## automationAccounts/certificates

![cleanliness](https://img.shields.io/badge/cleanliness-66.67%25%20(6%20/%209)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%203)-red)

### \$.properties.base64Value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | Unknown               |

### \$.properties.isExportable

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Default* (false)    | No Swagger            |

### \$.properties.thumbprint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | No Swagger            |

## automationAccounts/compilationjobs

![cleanliness](https://img.shields.io/badge/cleanliness-78.95%25%20(15%20/%2019)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%204)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-15  | Unknown             | No Swagger            |
| 2018-06-30  | Unknown             | No Swagger            |

### \$.properties.incrementNodeConfigurationBuild

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-15  | Default* (false)    | No Swagger            |
| 2018-06-30  | Default* (false)    | No Swagger            |

## automationAccounts/configurations

![cleanliness](https://img.shields.io/badge/cleanliness-33.33%25%20(8%20/%2024)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2016)-red)

### \$.properties.Source

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |

### \$.properties.description

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | No Swagger            |

### \$.properties.logProgress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-15  | Unknown             | No Swagger            |
| 2018-06-30  | Unknown             | No Swagger            |

### \$.properties.logVerbose

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |
| 2015-10-31         | Unknown             | No Swagger            |
| 2018-01-15         | Unknown             | No Swagger            |

### \$.properties.overwrite

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |

### \$.properties.parameters

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |
| 2015-10-31         | Unknown             | No Swagger            |
| 2018-01-15         | Unknown             | No Swagger            |

### \$.properties.source

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |
| 2015-10-31         | Unknown             | No Swagger            |
| 2018-01-15         | Unknown             | No Swagger            |
| 2018-06-30         | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |

## automationAccounts/connections

![cleanliness](https://img.shields.io/badge/cleanliness-87.50%25%20(7%20/%208)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.properties.fieldDefinitionValues.CertificateThumbprint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | No Swagger            |

## automationAccounts/credentials

![cleanliness](https://img.shields.io/badge/cleanliness-16.67%25%20(1%20/%206)-orange) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%205)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | No Swagger            |

### \$.properties.password

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |
| 2015-10-31         | Unknown             | No Swagger            |
| 2018-01-15         | Unknown             | No Swagger            |
| 2018-06-30         | Unknown             | No Swagger            |

## automationAccounts/jobs

![cleanliness](https://img.shields.io/badge/cleanliness-90.00%25%20(18%20/%2020)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |

## automationAccounts/jobSchedules

![cleanliness](https://img.shields.io/badge/cleanliness-66.67%25%20(6%20/%209)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%203)-red)

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

![cleanliness](https://img.shields.io/badge/cleanliness-50.00%25%20(10%20/%2020)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2010)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |
| 2015-10-31         | Unknown             | No Swagger            |
| 2017-05-15-preview | Unknown             | No Swagger            |
| 2018-01-15         | Unknown             | No Swagger            |
| 2018-06-30         | Unknown             | No Swagger            |

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |
| 2015-10-31         | Unknown             | No Swagger            |
| 2017-05-15-preview | Unknown             | No Swagger            |
| 2018-01-15         | Unknown             | No Swagger            |
| 2018-06-30         | Unknown             | No Swagger            |

## automationAccounts/nodeConfigurations

![cleanliness](https://img.shields.io/badge/cleanliness-60.00%25%20(9%20/%2015)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%206)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-15  | Unknown             | No Swagger            |

### \$.properties.Configuration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-15  | Unknown             | No Swagger            |

### \$.properties.Source

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-15  | Unknown             | No Swagger            |

### \$.properties.configuration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-15  | Unknown             | No Swagger            |

### \$.properties.incrementNodeConfigurationBuild

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-15  | Default (false)     | No Swagger            |

### \$.properties.source

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-15  | Unknown             | No Swagger            |

## automationAccounts/runbooks

![cleanliness](https://img.shields.io/badge/cleanliness-74.24%25%20(49%20/%2066)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2017)-red)

### \$.properties.draft

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-30  | Unknown             | Unknown               |

### \$.properties.logActivityTrace

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Default (0)         | No Swagger            |
| 2015-10-31         | Default (0)         | No Swagger            |
| 2017-05-15-preview | Default (0)         | No Swagger            |
| 2018-06-30         | Default (0)         | No Swagger            |

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
| 2015-10-31         | Unknown             | No Swagger            |
| 2017-05-15-preview | Unknown             | No Swagger            |
| 2018-06-30         | Unknown             | No Swagger            |

### \$.properties.publishcontentLink

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |
| 2018-06-30         | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | No Swagger            |

## automationAccounts/schedules

![cleanliness](https://img.shields.io/badge/cleanliness-55.00%25%20(11%20/%2020)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%209)-red)

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
| 2015-10-31         | Unknown             | No Swagger            |
| 2017-05-15-preview | Unknown             | No Swagger            |

### \$.properties.frequency

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Default* ("Week")   | No Swagger            |

### \$.properties.startTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-10-31         | Unknown             | No Swagger            |
| 2017-05-15-preview | Unknown             | No Swagger            |

### \$.properties.timeZone

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-10-31         | Unknown             | No Swagger            |
| 2017-05-15-preview | Unknown             | No Swagger            |

## automationAccounts/softwareUpdateConfigurations

![cleanliness](https://img.shields.io/badge/cleanliness-70.31%25%20(45%20/%2064)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2019)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Unknown             | No Swagger            |

### \$.properties.scheduleInfo

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
| 2017-05-15-preview | Unknown             | No Swagger            |

### \$.properties.scheduleInfo.expiryTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Unknown             | No Swagger            |

### \$.properties.scheduleInfo.expiryTimeOffsetMinutes

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Unknown             | No Swagger            |

### \$.properties.scheduleInfo.isEnabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Default (true)      | No Swagger            |

### \$.properties.scheduleInfo.lastModifiedTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Unknown             | No Swagger            |

### \$.properties.scheduleInfo.nextRun

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Unknown             | No Swagger            |

### \$.properties.scheduleInfo.nextRunOffsetMinutes

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Unknown             | No Swagger            |

### \$.properties.scheduleInfo.startTime

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Unknown             | No Swagger            |

### \$.properties.updateConfiguration.duration

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Unknown             | No Swagger            |

### \$.properties.updateConfiguration.linux.IsInvalidPackageNameMasks

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Default (false)     | No Swagger            |

### \$.properties.updateConfiguration.linux.includedPackageClassifications

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Unknown             | No Swagger            |

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
| 2017-05-15-preview | Unknown             | No Swagger            |

### \$.properties.updateConfiguration.windows.rebootSetting

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-05-15-preview | Unknown             | No Swagger            |

## automationAccounts/variables

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2012)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | No Swagger            |

### \$.properties.isEncrypted

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-10-31         | Unknown             | No Swagger            |
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
| 2017-05-15-preview | Unknown             | No Swagger            |

### \$.properties.value

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-10-31         | Unknown             | No Swagger            |
| 2017-05-15-preview | Unknown             | No Swagger            |
| 2018-01-15         | Unknown             | No Swagger            |
| 2018-06-30         | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | No Swagger            |

## automationAccounts/webhooks

![cleanliness](https://img.shields.io/badge/cleanliness-85.71%25%20(12%20/%2014)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties.expiryTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | No Swagger            |

### \$.properties.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | No Swagger            |

## automationAccounts

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2018)-red)

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
| 2015-10-31  | Unknown             | No Swagger            |

### \$.properties.sku.name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Default ("Basic")   | No Swagger            |
| 2015-10-31         | Default ("Basic")   | No Swagger            |
| 2017-05-15-preview | Default ("Basic")   | No Swagger            |
| 2018-01-15         | Default ("Basic")   | No Swagger            |
| 2018-06-30         | Default ("Basic")   | No Swagger            |

### \$.properties.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-10-31  | Unknown             | No Swagger            |

### \$.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |
| 2015-10-31         | Unknown             | No Swagger            |

### \$.tags.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-01-01-preview | Unknown             | No Swagger            |
| 2015-10-31         | Unknown             | No Swagger            |
