# Microsoft.DevTestLab

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## labs/artifactSources

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%207)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.armTemplateFolderPath

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.branchRef

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.displayName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.folderPath

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.sourceType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-10-15-preview | Default* ("GitHub") | No Swagger            |

### \$.properties.uri

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-10-15-preview | Unknown             | No Swagger            |

## labs/customimages

![cleanliness](https://img.shields.io/badge/cleanliness-79.31%25%20(23%20/%2029)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%206)-red)

### \$.properties.author

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.managedImageId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-05-15         | Unknown             | Unknown               |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.managedSnapshotId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.osType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.uniqueIdentifier

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-05-15  | Unknown             | No Swagger            |

## labs/schedules

![cleanliness](https://img.shields.io/badge/cleanliness-77.27%25%20(17%20/%2022)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%205)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-15         | Unknown             | No Swagger            |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.dailyRecurrence.time

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-09-15  | Unknown             | No Swagger            |

### \$.properties.notificationSettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-09-15  | Unknown             | No Swagger            |

### \$.properties.weeklyRecurrence.time

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-10-15-preview | Unknown             | No Swagger            |

## labs/virtualmachines

![cleanliness](https://img.shields.io/badge/cleanliness-73.94%25%20(244%20/%20330)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2086)-red)

### \$.properties.AllowClaim

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.Artifacts

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.CustomImageId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.DisallowPublicIpAddress

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.ExpirationDate

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.IsAuthenticationWithSshKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.LabSubnetName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.LabVirtualNetworkId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.Notes

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.Password

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.Size

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.StorageType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.UserName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.allowClaim

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2018-09-15         | Unknown             | Unknown               |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.artifactDeploymentStatus

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-05-15         | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2018-09-15         | Unknown             | No Swagger            |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.artifacts

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2018-09-15         | Unknown             | No Swagger            |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.computeId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2018-09-15         | Unknown             | No Swagger            |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.createdByUser

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2018-09-15         | Unknown             | No Swagger            |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.createdByUserId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2018-09-15         | Unknown             | No Swagger            |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.createdDate

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2018-09-15         | Unknown             | No Swagger            |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.customImageId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.disallowPublicIpAddress

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Default* (true)     | No Swagger            |

### \$.properties.expirationDate

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-05-15         | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.fqdn

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-05-15         | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2018-09-15         | Unknown             | No Swagger            |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.isAuthenticationWithSshKey

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-05-15         | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2018-09-15         | Unknown             | No Swagger            |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.labStorageType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.labSubnetName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-05-15  | Unknown             | No Swagger            |

### \$.properties.labVirtualNetworkId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-05-15  | Unknown             | No Swagger            |

### \$.properties.lastKnownPowerState

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2018-09-15         | Unknown             | No Swagger            |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.networkInterface

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-15         | Unknown             | No Swagger            |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.notes

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.osType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-05-15         | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2018-09-15         | Unknown             | No Swagger            |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.ownerObjectId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-05-15         | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2018-09-15         | Unknown             | No Swagger            |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.ownerUserPrincipalName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2018-09-15         | Unknown             | No Swagger            |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.password

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2018-09-15         | Unknown             | No Swagger            |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.size

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.storageProfile

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.storageType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-05-15         | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2018-09-15         | Unknown             | No Swagger            |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.uniqueIdentifier

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-05-15  | Unknown             | No Swagger            |

### \$.properties.userName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.virtualMachineCreationSource

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2018-09-15         | Unknown             | No Swagger            |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.tags.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-05-15         | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2018-10-15-preview | Unknown             | No Swagger            |

## labs/virtualNetworks

![cleanliness](https://img.shields.io/badge/cleanliness-58.33%25%20(14%20/%2024)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2010)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-05-15         | Unknown             | No Swagger            |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.allowedSubnets

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-15         | Unknown             | No Swagger            |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.mode

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.subnetOverrides[*].labSubnetName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-15         | Unknown             | No Swagger            |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.subnetOverrides[*].name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-15         | Unknown             | No Swagger            |
| 2018-10-15-preview | Unknown             | No Swagger            |

## labs

![cleanliness](https://img.shields.io/badge/cleanliness-61.70%25%20(29%20/%2047)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2018)-red)

### \$.identity

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-21-preview | Unknown             | No Swagger            |
| 2016-05-15         | Unknown             | No Swagger            |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.announcement

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2018-09-15         | Unknown             | Unknown               |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.browserConnect

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.disableAutoUpgradeCseMinorVersion

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-10-15-preview | Default (false)     | No Swagger            |

### \$.properties.environmentPermission

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Default* ("Reader") | No Swagger            |
| 2018-10-15-preview | Default* ("Reader") | No Swagger            |

### \$.properties.extendedProperties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.labStorageType

| API version        | Detected noise type  | Determined noise type |
| ------------------ | -------------------- | --------------------- |
| 2018-10-15-preview | Default* ("Premium") | No Swagger            |

### \$.properties.premiumDataDisks

| API version        | Detected noise type   | Determined noise type |
| ------------------ | --------------------- | --------------------- |
| 2017-04-26-preview | Default* ("Disabled") | No Swagger            |
| 2018-10-15-preview | Default* ("Disabled") | No Swagger            |

### \$.properties.support

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-15         | Unknown             | No Swagger            |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.support.markdown

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

## labs/notificationchannels

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%203)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.description

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.notificationLocale

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-10-15-preview | Unknown             | No Swagger            |

## labs/policysets/policies

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%201)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-10-15-preview | Unknown             | No Swagger            |

## schedules

![cleanliness](https://img.shields.io/badge/cleanliness-18.18%25%20(4%20/%2022)-orange) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2018)-red)

### \$.properties.dailyRecurrence.time

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-05-15         | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2018-09-15         | Unknown             | No Swagger            |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.properties.dependsOn

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2017-04-26-preview | Unknown             | No Swagger            |

### \$.properties.notificationSettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-05-15  | Unknown             | No Swagger            |
| 2018-09-15  | Unknown             | No Swagger            |

### \$.properties.notificationSettings.status

| API version        | Detected noise type  | Determined noise type |
| ------------------ | -------------------- | --------------------- |
| 2016-05-15         | Default ("Disabled") | No Swagger            |
| 2017-04-26-preview | Default ("Disabled") | No Swagger            |
| 2018-09-15         | Default ("Disabled") | No Swagger            |
| 2018-10-15-preview | Default ("Disabled") | No Swagger            |

### \$.properties.targetResourceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-05-15  | Unknown             | No Swagger            |

### \$.properties.uniqueIdentifier

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-05-15  | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-05-15         | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |
| 2018-10-15-preview | Unknown             | No Swagger            |

### \$.tags.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-05-15         | Unknown             | No Swagger            |
| 2017-04-26-preview | Unknown             | No Swagger            |
