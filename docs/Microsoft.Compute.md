# Microsoft.Compute

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## availabilitySets

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-brightgreen) ![progress](https://img.shields.io/badge/progress-100.00%25%20(69%20/%2069)-brightgreen)

### \$.properties

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2015-05-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-06-15) |
| 2015-06-15         | Unknown             | Put-as-patch                                          |
| 2016-03-30         | Unknown             | Put-as-patch                                          |
| 2017-03-30         | Unknown             | Put-as-patch                                          |
| 2017-12-01         | Unknown             | Put-as-patch                                          |
| 2019-07-01         | Unknown             | Put-as-patch                                          |

### \$.properties.PlatformFaultDomainCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-04-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.PlatformUpdateDomainCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-04-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.internalData

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Put-as-patch          |

### \$.properties.internalData.pinnedFabricCluster

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2017-12-01  | Unknown             | Put-as-patch          |

### \$.properties.platformFaultDomainCount

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2015-05-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-06-15) |
| 2015-06-15         | Unknown             | Put-as-patch                                          |
| 2016-03-30         | Unknown             | Put-as-patch                                          |
| 2017-03-30         | Unknown             | Put-as-patch                                          |
| 2017-12-01         | Unknown             | Put-as-patch                                          |
| 2018-04-01         | Unknown             | Put-as-patch                                          |

### \$.properties.platformUpdateDomainCount

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2015-05-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-06-15) |
| 2015-06-15         | Unknown             | Put-as-patch                                          |
| 2016-03-30         | Unknown             | Put-as-patch                                          |
| 2017-03-30         | Unknown             | Put-as-patch                                          |
| 2017-12-01         | Unknown             | Put-as-patch                                          |
| 2018-04-01         | Unknown             | Put-as-patch                                          |
| 2018-10-01         | Unknown             | Put-as-patch                                          |
| 2019-03-01         | Unknown             | Put-as-patch                                          |
| 2019-07-01         | Unknown             | Put-as-patch                                          |
| 2019-12-01         | Unknown             | Put-as-patch                                          |

### \$.properties.virtualMachines

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2015-05-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-06-15) |
| 2015-06-15         | Unknown             | Put-as-patch                                          |
| 2016-03-30         | Unknown             | Put-as-patch                                          |
| 2016-04-30-preview | Unknown             | Put-as-patch                                          |
| 2017-03-30         | Unknown             | Put-as-patch                                          |
| 2017-12-01         | Unknown             | Put-as-patch                                          |
| 2018-04-01         | Unknown             | Put-as-patch                                          |
| 2018-06-01         | Unknown             | Put-as-patch                                          |
| 2018-10-01         | Unknown             | Put-as-patch                                          |
| 2019-03-01         | Unknown             | Put-as-patch                                          |
| 2019-07-01         | Unknown             | Put-as-patch                                          |
| 2019-12-01         | Unknown             | Put-as-patch                                          |
| 2020-06-01         | Unknown             | Put-as-patch                                          |

### \$.properties.virtualMachines[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachines[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-04-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |

### \$.sku.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |

### \$.tags.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |

## diskencryptionsets

![cleanliness](https://img.shields.io/badge/cleanliness-85.71%25%20(12%20/%2014)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | No Swagger            |

## disks

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2074)-red)

### \$.managedByExtended

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.accountType

| API version        | Detected noise type       | Determined noise type |
| ------------------ | ------------------------- | --------------------- |
| 2016-04-30-preview | Default* ("Standard_LRS") | Unknown               |

### \$.properties.creationData.sourceResourceId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | No Swagger            |

### \$.properties.creationData.sourceURI

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | No Swagger            |

### \$.properties.creationData.sourceUri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | No Swagger            |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.diskIOPSReadOnly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.diskIOPSReadWrite

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-09-30  | Unknown             | No Swagger            |
| 2019-03-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |
| 2020-05-01  | Unknown             | No Swagger            |

### \$.properties.diskMBpsReadOnly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.diskMBpsReadWrite

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-09-30  | Unknown             | No Swagger            |
| 2019-03-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |
| 2020-05-01  | Unknown             | No Swagger            |

### \$.properties.diskSizeGB

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | No Swagger            |
| 2017-03-30         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |
| 2018-09-30         | Unknown             | No Swagger            |
| 2019-03-01         | Unknown             | No Swagger            |
| 2019-07-01         | Unknown             | No Swagger            |
| 2019-11-01         | Unknown             | No Swagger            |
| 2020-05-01         | Unknown             | No Swagger            |

### \$.properties.diskState

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | No Swagger            |
| 2017-03-30         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |

### \$.properties.encryption

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |
| 2020-05-01  | Unknown             | No Swagger            |

### \$.properties.encryptionSettingsCollection

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-09-30  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.hyperVGeneration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-09-30  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |
| 2020-05-01  | Unknown             | No Swagger            |

### \$.properties.maxShares

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Default* (1)        | No Swagger            |
| 2019-07-01  | Default* (1)        | No Swagger            |

### \$.properties.networkAccessPolicy

| API version | Detected noise type   | Determined noise type |
| ----------- | --------------------- | --------------------- |
| 2020-05-01  | Default* ("AllowAll") | No Swagger            |

### \$.properties.osType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | No Swagger            |
| 2017-03-30         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |
| 2018-09-30         | Unknown             | No Swagger            |
| 2019-03-01         | Unknown             | No Swagger            |
| 2019-07-01         | Unknown             | No Swagger            |
| 2019-11-01         | Unknown             | No Swagger            |
| 2020-05-01         | Unknown             | No Swagger            |

### \$.properties.readOnly

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Default* (false)    | No Swagger            |
| 2019-07-01  | Default* (false)    | No Swagger            |

### \$.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-09-30  | Unknown             | No Swagger            |
| 2019-03-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.sku.name

| API version | Detected noise type      | Determined noise type |
| ----------- | ------------------------ | --------------------- |
| 2019-07-01  | Default* ("Premium_LRS") | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-06-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.tags.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | No Swagger            |
| 2017-03-30         | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |
| 2018-09-30         | Unknown             | No Swagger            |
| 2019-07-01         | Unknown             | No Swagger            |

## galleries/images/versions

![cleanliness](https://img.shields.io/badge/cleanliness-74.60%25%20(47%20/%2063)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2016)-red)

### \$.properties.publishingProfile.endOfLifeDate

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Unknown               |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-12-01  | Unknown             | No Swagger            |

### \$.properties.publishingProfile.storageAccountType

| API version | Detected noise type       | Determined noise type |
| ----------- | ------------------------- | --------------------- |
| 2019-07-01  | Default* ("Standard_LRS") | No Swagger            |
| 2019-12-01  | Default* ("Standard_LRS") | No Swagger            |

### \$.properties.publishingProfile.targetRegions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.publishingProfile.targetRegions[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-12-01  | Unknown             | No Swagger            |

### \$.properties.publishingProfile.targetRegions[*].regionalReplicaCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Default (1)         | No Swagger            |
| 2019-07-01  | Default (1)         | No Swagger            |

### \$.properties.storageProfile.dataDiskImages

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-12-01  | Unknown             | No Swagger            |

### \$.properties.storageProfile.osDiskImage

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-12-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | No Swagger            |

## galleries/images

![cleanliness](https://img.shields.io/badge/cleanliness-87.23%25%20(41%20/%2047)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%206)-red)

### \$.properties.endOfLifeDate

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Unknown               |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-12-01  | Unknown             | No Swagger            |

### \$.properties.hyperVGeneration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Default* ("V1")     | No Swagger            |
| 2019-12-01  | Default* ("V1")     | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | No Swagger            |

## galleries

![cleanliness](https://img.shields.io/badge/cleanliness-66.67%25%20(4%20/%206)-yellowgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | No Swagger            |

## hostgroups/hosts

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.autoReplaceOnFailure

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Default* (true)     | No Swagger            |

## images

![cleanliness](https://img.shields.io/badge/cleanliness-9.09%25%20(3%20/%2033)-red) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2030)-red)

### \$.properties.hyperVGeneration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Default* ("V1")     | No Swagger            |

### \$.properties.storageProfile.dataDisks

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | No Swagger            |

### \$.properties.storageProfile.dataDisks[*].caching

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Default* ("None")   | No Swagger            |

### \$.properties.storageProfile.dataDisks[*].diskSizeGB

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | No Swagger            |
| 2017-03-30         | Unknown             | No Swagger            |

### \$.properties.storageProfile.dataDisks[*].lun

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Default (0)         | No Swagger            |

### \$.properties.storageProfile.dataDisks[*].storageAccountType

| API version | Detected noise type       | Determined noise type |
| ----------- | ------------------------- | --------------------- |
| 2017-03-30  | Default* ("Standard_LRS") | No Swagger            |

### \$.properties.storageProfile.osDisk.caching

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | No Swagger            |
| 2017-03-30         | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |
| 2018-10-01         | Unknown             | No Swagger            |
| 2019-03-01         | Unknown             | No Swagger            |

### \$.properties.storageProfile.osDisk.diskSizeGB

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | No Swagger            |
| 2017-03-30         | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |
| 2018-10-01         | Unknown             | No Swagger            |
| 2019-03-01         | Unknown             | No Swagger            |
| 2019-07-01         | Unknown             | No Swagger            |
| 2019-12-01         | Unknown             | No Swagger            |

### \$.properties.storageProfile.osDisk.managedDisk

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | No Swagger            |

### \$.properties.storageProfile.osDisk.managedDisk.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | No Swagger            |

### \$.properties.storageProfile.osDisk.osState

| API version        | Detected noise type     | Determined noise type |
| ------------------ | ----------------------- | --------------------- |
| 2016-04-30-preview | Default ("Generalized") | No Swagger            |
| 2017-03-30         | Default ("Generalized") | No Swagger            |
| 2019-03-01         | Default ("Generalized") | No Swagger            |

### \$.properties.storageProfile.osDisk.osType

| API version | Detected noise type  | Determined noise type |
| ----------- | -------------------- | --------------------- |
| 2019-03-01  | Default* ("Windows") | No Swagger            |

### \$.properties.storageProfile.osDisk.storageAccountType

| API version | Detected noise type      | Determined noise type |
| ----------- | ------------------------ | --------------------- |
| 2017-03-30  | Default ("Standard_LRS") | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.tags.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | No Swagger            |

## proximityPlacementGroups

![cleanliness](https://img.shields.io/badge/cleanliness-87.88%25%20(29%20/%2033)-green) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%204)-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |
| 2019-03-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |

## snapshots

![cleanliness](https://img.shields.io/badge/cleanliness-40.74%25%20(22%20/%2054)-yellow) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2032)-red)

### \$.properties.accountType

| API version        | Detected noise type      | Determined noise type |
| ------------------ | ------------------------ | --------------------- |
| 2016-04-30-preview | Default ("Standard_LRS") | No Swagger            |

### \$.properties.creationData.sourceResourceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | No Swagger            |
| 2019-03-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.creationData.sourceUri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.diskSizeGB

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | No Swagger            |
| 2017-03-30         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |
| 2019-03-01         | Unknown             | No Swagger            |
| 2019-07-01         | Unknown             | No Swagger            |
| 2020-05-01         | Unknown             | No Swagger            |

### \$.properties.diskState

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | No Swagger            |
| 2017-03-30         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |
| 2019-03-01         | Unknown             | No Swagger            |
| 2019-07-01         | Unknown             | No Swagger            |
| 2020-05-01         | Unknown             | No Swagger            |

### \$.properties.encryption

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | No Swagger            |
| 2020-05-01  | Unknown             | No Swagger            |

### \$.properties.encryptionSettingsCollection

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.hyperVGeneration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.osType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2020-05-01  | Unknown             | No Swagger            |

### \$.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

## virtualMachines/extensions

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%20155)-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-03-30  | Unknown             | No Swagger            |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.AutoUpgradeMinorVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.ProtectedSettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.Publisher

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.Settings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.Type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.TypeHandlerVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.autoUpgradeMinorVersion

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-04-30-preview | Unknown             | No Swagger            |
| 2017-03-30         | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |
| 2018-10-01         | Unknown             | No Swagger            |
| 2019-03-01         | Unknown             | No Swagger            |
| 2019-07-01         | Unknown             | No Swagger            |

### \$.properties.autoupgrademinorversion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.enableAutomaticUpgrade

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Default* (true)     | No Swagger            |

### \$.properties.forceUpdateTag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-03-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.instanceView

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-04-30-preview | Unknown             | No Swagger            |
| 2017-03-30         | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |
| 2018-10-01         | Unknown             | No Swagger            |
| 2019-03-01         | Unknown             | No Swagger            |
| 2019-07-01         | Unknown             | No Swagger            |
| 2019-12-01         | Unknown             | No Swagger            |

### \$.properties.migrationInfo

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.protectedsettings

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-04-30-preview | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2018-10-01         | Unknown             | No Swagger            |
| 2019-03-01         | Unknown             | No Swagger            |

### \$.properties.settings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.settings.AADClientID

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | No Swagger            |

### \$.properties.settings.EncryptionOperation

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | No Swagger            |

### \$.properties.settings.Exclusions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | No Swagger            |

### \$.properties.settings.KeyEncryptionAlgorithm

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | No Swagger            |

### \$.properties.settings.KeyEncryptionKeyURL

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.settings.KeyVaultURL

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | No Swagger            |
| 2017-03-30         | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |
| 2018-10-01         | Unknown             | No Swagger            |
| 2019-03-01         | Unknown             | No Swagger            |
| 2019-07-01         | Unknown             | No Swagger            |

### \$.properties.settings.Properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.settings.Properties.externalfqdn

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.settings.Properties[*].Value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | No Swagger            |
| 2017-12-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-03-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-12-01  | Unknown             | No Swagger            |

### \$.properties.settings.Restart

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.settings.ScheduledScanSettings.scanType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | No Swagger            |

### \$.properties.settings.WadCfg.DiagnosticMonitorConfiguration.DiagnosticInfrastructureLogs.scheduledTransferLogLevelFilter

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.settings.WadCfg.DiagnosticMonitorConfiguration.DiagnosticInfrastructureLogs.scheduledTransferPeriod

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.settings.WadCfg.DiagnosticMonitorConfiguration.Directories

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.settings.WadCfg.DiagnosticMonitorConfiguration.PerformanceCounters.PerformanceCounterConfiguration[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.settings.WadCfg.DiagnosticMonitorConfiguration.WindowsEventLog.DataSource[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.settings.WadCfg.SinksConfig.Sink[*].ApplicationInsights

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.settings.WadCfg.SinksConfig.Sink[*].EventHub.SharedAccessKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | No Swagger            |

### \$.properties.settings.commandToExecute

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2017-03-30         | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |
| 2019-03-01         | Unknown             | No Swagger            |
| 2019-12-01         | Unknown             | No Swagger            |

### \$.properties.settings.configuration.function

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |

### \$.properties.settings.configuration.script

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.settings.configuration.url

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.settings.configurationArguments.CNNamePrefix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.settings.configurationArguments.CNSize

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.settings.configurationArguments.CertificateUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.settings.configurationArguments.DomainName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.settings.configurationArguments.LinuxCommOverHttp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Default* (true)     | No Swagger            |

### \$.properties.settings.configurationArguments.Location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.settings.configurationArguments.RegistrationUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.settings.configurationArguments.ResourceGroup

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.settings.configurationArguments.SSLThumbprint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.settings.configurationArguments.Subnet

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.settings.configurationArguments.SubscriptionId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.settings.configurationArguments.Timestamp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.settings.configurationArguments.VNet

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.settings.configurationArguments.VaultResourceGroup

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | No Swagger            |

### \$.properties.settings.configurationArguments.sharedAccessKeyValue

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.settings.fileUris

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2019-03-01  | Unknown             | No Swagger            |

### \$.properties.settings.fileUris[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2017-03-30  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.settings.hints.platform

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.settings.hints.vm_name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.settings.networkInterface

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.settings.properties.CatalogMachine

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.settings.properties.registrationInfoToken

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.settings.secretsManagementSettings.observedCertificates[*]

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | No Swagger            |

### \$.properties.settings.timestamp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-03-01  | Unknown             | No Swagger            |

### \$.properties.settings.workspaceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2017-03-30  | Unknown             | No Swagger            |
| 2017-12-01  | Unknown             | No Swagger            |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-03-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-12-01  | Unknown             | No Swagger            |

### \$.properties.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.typeHandlerVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-04-30-preview | Unknown             | No Swagger            |
| 2017-03-30         | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |
| 2018-10-01         | Unknown             | No Swagger            |
| 2019-03-01         | Unknown             | No Swagger            |
| 2019-07-01         | Unknown             | No Swagger            |
| 2019-12-01         | Unknown             | No Swagger            |

### \$.tags.*

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-04-30-preview | Unknown             | No Swagger            |
| 2017-03-30         | Unknown             | No Swagger            |
| 2017-12-01         | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |
| 2018-10-01         | Unknown             | No Swagger            |
| 2019-03-01         | Unknown             | No Swagger            |
| 2019-07-01         | Unknown             | No Swagger            |

## virtualMachines

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-brightgreen) ![progress](https://img.shields.io/badge/progress-100.00%25%20(412%20/%20412)-brightgreen)

### \$.identity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |

### \$.identity.*

| API version | Detected noise type         | Determined noise type |
| ----------- | --------------------------- | --------------------- |
| 2018-06-01  | Default* ("SystemAssigned") | Put-as-patch          |

### \$.plan

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Put-as-patch          |
| 2017-03-30  | Unknown             | Put-as-patch          |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Put-as-patch          |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |

### \$.properties.OSProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |

### \$.properties.additionalCapabilities.ultraSSDEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.availabilitySet

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-15         | Unknown             | Put-as-patch          |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |

### \$.properties.availabilitySet.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Put-as-patch          |

### \$.properties.billingProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.diagnosticsProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Put-as-patch          |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |

### \$.properties.diagnosticsProfile.bootDiagnostics.Enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |

### \$.properties.diagnosticsProfile.bootDiagnostics.enabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-15         | Unknown             | Put-as-patch          |
| 2016-03-30         | Unknown             | Put-as-patch          |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-04-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |
| 2019-12-01         | Unknown             | Put-as-patch          |

### \$.properties.diagnosticsProfile.bootDiagnostics.storageUri

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-15         | Unknown             | Put-as-patch          |
| 2016-03-30         | Unknown             | Put-as-patch          |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-04-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |
| 2019-12-01         | Unknown             | Put-as-patch          |
| 2020-06-01         | Unknown             | Put-as-patch          |

### \$.properties.evictionPolicy

| API version | Detected noise type     | Determined noise type |
| ----------- | ----------------------- | --------------------- |
| 2019-07-01  | Default* ("Deallocate") | Put-as-patch          |

### \$.properties.hardwareProfile

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-15         | Unknown             | Put-as-patch          |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |
| 2019-12-01         | Unknown             | Put-as-patch          |

### \$.properties.hardwareProfile.vmSize

| API version | Detected noise type       | Determined noise type |
| ----------- | ------------------------- | --------------------- |
| 2019-07-01  | Default* ("Standard_F8s") | Put-as-patch          |

### \$.properties.licenseType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Put-as-patch          |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |

### \$.properties.migrationInfo

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Put-as-patch          |

### \$.properties.networkProfile

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-15         | Unknown             | Put-as-patch          |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-12-01         | Unknown             | Put-as-patch          |

### \$.properties.networkProfile.dependsOn

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |

### \$.properties.networkProfile.networkInterfaces

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |

### \$.properties.networkProfile.networkInterfaces[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2018-04-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.networkProfile.networkInterfaces[*].properties.enableAcceleratedNetworking

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | Put-as-patch          |

### \$.properties.networkProfile.networkInterfaces[*].properties.primary

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.osProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2017-12-01  | Unknown             | Put-as-patch          |

### \$.properties.osProfile.AdminPassword

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |

### \$.properties.osProfile.WindowsConfiguration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |

### \$.properties.osProfile.adminUserName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |

### \$.properties.osProfile.adminUsername

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-15         | Unknown             | Put-as-patch          |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-12-01         | Unknown             | Put-as-patch          |

### \$.properties.osProfile.computerName

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-15         | Unknown             | Put-as-patch          |
| 2016-03-30         | Unknown             | Put-as-patch          |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2018-04-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-12-01         | Unknown             | Put-as-patch          |

### \$.properties.osProfile.computername

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-15         | Unknown             | Put-as-patch          |
| 2016-03-30         | Unknown             | Put-as-patch          |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2018-04-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |

### \$.properties.osProfile.linuxConfiguration

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2015-05-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-06-15) |
| 2015-06-15         | Unknown             | Put-as-patch                                          |
| 2016-03-30         | Unknown             | Put-as-patch                                          |
| 2016-04-30-preview | Unknown             | Put-as-patch                                          |
| 2017-03-30         | Unknown             | Put-as-patch                                          |
| 2017-12-01         | Unknown             | Put-as-patch                                          |
| 2018-04-01         | Unknown             | Put-as-patch                                          |
| 2018-06-01         | Unknown             | Put-as-patch                                          |
| 2018-10-01         | Unknown             | Put-as-patch                                          |
| 2019-03-01         | Unknown             | Put-as-patch                                          |
| 2019-07-01         | Unknown             | Put-as-patch                                          |

### \$.properties.osProfile.linuxConfiguration.disablePasswordAuthentication

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2015-05-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-06-15) |
| 2015-06-15         | Unknown             | Put-as-patch                                          |
| 2016-03-30         | Unknown             | Put-as-patch                                          |
| 2016-04-30-preview | Unknown             | Put-as-patch                                          |
| 2017-03-30         | Unknown             | Put-as-patch                                          |
| 2017-12-01         | Unknown             | Put-as-patch                                          |
| 2018-04-01         | Unknown             | Put-as-patch                                          |
| 2018-06-01         | Unknown             | Put-as-patch                                          |
| 2018-10-01         | Unknown             | Put-as-patch                                          |
| 2019-03-01         | Unknown             | Put-as-patch                                          |
| 2019-07-01         | Unknown             | Put-as-patch                                          |
| 2019-12-01         | Unknown             | Put-as-patch                                          |

### \$.properties.osProfile.linuxConfiguration.ssh

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Put-as-patch          |

### \$.properties.osProfile.requireGuestProvisionSignal

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Default (true)      | Put-as-patch          |
| 2019-03-01  | Default (true)      | Put-as-patch          |
| 2019-07-01  | Default (true)      | Put-as-patch          |
| 2019-12-01  | Default (true)      | Put-as-patch          |

### \$.properties.osProfile.secrets

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-15         | Unknown             | Put-as-patch          |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |

### \$.properties.osProfile.secrets[*].vaultCertificates[*].certificateUrl

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-15         | Unknown             | Put-as-patch          |
| 2016-04-30-preview | Unknown             | Put-as-patch          |

### \$.properties.osProfile.windowsConfiguration

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-15         | Unknown             | Put-as-patch          |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2018-04-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |
| 2019-12-01         | Unknown             | Put-as-patch          |

### \$.properties.osProfile.windowsConfiguration.additionalUnattendContent

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |

### \$.properties.osProfile.windowsConfiguration.additionalUnattendContent[*].content

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-04-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |

### \$.properties.osProfile.windowsConfiguration.enableAutomaticUpdates

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2015-05-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-06-15) |
| 2015-06-15         | Unknown             | Put-as-patch                                          |
| 2016-04-30-preview | Unknown             | Put-as-patch                                          |
| 2017-03-30         | Unknown             | Put-as-patch                                          |
| 2017-12-01         | Unknown             | Put-as-patch                                          |
| 2018-04-01         | Unknown             | Put-as-patch                                          |
| 2018-06-01         | Unknown             | Put-as-patch                                          |
| 2018-10-01         | Unknown             | Put-as-patch                                          |
| 2019-03-01         | Unknown             | Put-as-patch                                          |
| 2019-07-01         | Unknown             | Put-as-patch                                          |
| 2019-12-01         | Unknown             | Put-as-patch                                          |

### \$.properties.osProfile.windowsConfiguration.provisionVmAgent

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-15         | Unknown             | Put-as-patch          |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-04-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |

### \$.properties.osProfile.windowsConfiguration.timeZone

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Put-as-patch          |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.osProfile.windowsConfiguration.winRM

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |

### \$.properties.osProfile.windowsConfiguration.winRM.listeners[*].certificateUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Put-as-patch          |

### \$.properties.proximityPlacementGroup

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.storageProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Put-as-patch          |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.dataDisks

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-15         | Unknown             | Put-as-patch          |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-04-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |
| 2019-12-01         | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.dataDisks[*].DiskSizeGB

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.dataDisks[*].caching

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-15         | Unknown             | Put-as-patch          |
| 2016-03-30         | Unknown             | Put-as-patch          |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-04-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |
| 2019-12-01         | Unknown             | Put-as-patch          |
| 2020-06-01         | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.dataDisks[*].createOption

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.dataDisks[*].diskSizeGB

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-15         | Unknown             | Put-as-patch          |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-04-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.dataDisks[*].lun

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Default* (1)        | Put-as-patch          |

### \$.properties.storageProfile.dataDisks[*].managedDisk

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-04-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |
| 2019-12-01         | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.dataDisks[*].managedDisk.id

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-04-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |
| 2019-12-01         | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.dataDisks[*].managedDisk.storageAccountType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-04-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.dataDisks[*].name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-04-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |
| 2019-12-01         | Unknown             | Put-as-patch          |
| 2020-06-01         | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.dataDisks[*].toBeDetached

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Default (false)     | Put-as-patch          |
| 2019-07-01  | Default (false)     | Put-as-patch          |
| 2019-12-01  | Default (false)     | Put-as-patch          |

### \$.properties.storageProfile.dataDisks[*].vhd.uri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Put-as-patch          |
| 2016-03-30  | Unknown             | Put-as-patch          |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.dataDisks[*].writeAcceleratorEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Default* (false)    | Put-as-patch          |
| 2018-06-01  | Default* (false)    | Put-as-patch          |
| 2019-03-01  | Default* (false)    | Put-as-patch          |

### \$.properties.storageProfile.imageReference

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.imageReference.Offer

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.imageReference.Publisher

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.imageReference.Sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.imageReference.Version

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.imageReference.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.imageReference.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.osDisk

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-04-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |
| 2019-12-01         | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.osDisk.caching

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-04-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |
| 2019-12-01         | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.osDisk.createOption

| API version        | Detected noise type   | Determined noise type |
| ------------------ | --------------------- | --------------------- |
| 2016-04-30-preview | Default ("FromImage") | Put-as-patch          |

### \$.properties.storageProfile.osDisk.diskSizeGB

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2015-06-15         | Unknown             | Put-as-patch                                          |
| 2016-03-30         | Unknown             | Put-as-patch                                          |
| 2016-04-30-preview | Unknown             | Put-as-patch                                          |
| 2016-08-30         | Unknown             | No Swagger, Put-as-patch (inheritted from 2017-03-30) |
| 2017-03-30         | Unknown             | Put-as-patch                                          |
| 2017-12-01         | Unknown             | Put-as-patch                                          |
| 2018-04-01         | Unknown             | Put-as-patch                                          |
| 2018-06-01         | Unknown             | Put-as-patch                                          |
| 2018-10-01         | Unknown             | Put-as-patch                                          |
| 2019-03-01         | Unknown             | Put-as-patch                                          |
| 2019-07-01         | Unknown             | Put-as-patch                                          |
| 2019-12-01         | Unknown             | Put-as-patch                                          |

### \$.properties.storageProfile.osDisk.diskSizeGb

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.osDisk.encryptionSettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.osDisk.encryptionSettings.diskEncryptionKey.secretUrl

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.osDisk.encryptionSettings.enabled

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Default* (true)     | Put-as-patch          |
| 2017-03-30         | Default* (true)     | Put-as-patch          |

### \$.properties.storageProfile.osDisk.image.uri

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-15         | Unknown             | Put-as-patch          |
| 2016-04-30-preview | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.osDisk.managedDisk

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-04-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |
| 2019-12-01         | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.osDisk.managedDisk.diskEncryptionSet

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.osDisk.managedDisk.id

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-04-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |
| 2019-12-01         | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.osDisk.managedDisk.storageAccountType

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |
| 2019-12-01         | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.osDisk.name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-04-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |
| 2019-12-01         | Unknown             | Put-as-patch          |

### \$.properties.storageProfile.osDisk.osType

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2015-05-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-06-15) |
| 2015-06-15         | Unknown             | Put-as-patch                                          |
| 2016-03-30         | Unknown             | Put-as-patch                                          |
| 2016-04-30-preview | Unknown             | Put-as-patch                                          |
| 2016-08-30         | Unknown             | No Swagger, Put-as-patch (inheritted from 2017-03-30) |
| 2017-03-30         | Unknown             | Put-as-patch                                          |
| 2017-12-01         | Unknown             | Put-as-patch                                          |
| 2018-04-01         | Unknown             | Put-as-patch                                          |
| 2018-06-01         | Unknown             | Put-as-patch                                          |
| 2018-10-01         | Unknown             | Put-as-patch                                          |
| 2019-03-01         | Unknown             | Put-as-patch                                          |
| 2019-07-01         | Unknown             | Put-as-patch                                          |
| 2019-12-01         | Unknown             | Put-as-patch                                          |

### \$.properties.storageProfile.osDisk.vhd.uri

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2015-05-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-06-15) |
| 2015-06-15         | Unknown             | Put-as-patch                                          |
| 2016-03-30         | Unknown             | Put-as-patch                                          |
| 2016-04-30-preview | Unknown             | Put-as-patch                                          |
| 2017-03-30         | Unknown             | Put-as-patch                                          |
| 2017-12-01         | Unknown             | Put-as-patch                                          |
| 2018-06-01         | Unknown             | Put-as-patch                                          |
| 2019-03-01         | Unknown             | Put-as-patch                                          |
| 2019-07-01         | Unknown             | Put-as-patch                                          |
| 2019-12-01         | Unknown             | Put-as-patch                                          |

### \$.properties.storageProfile.osDisk.writeAcceleratorEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Default* (false)    | Put-as-patch          |

### \$.properties.vmId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Put-as-patch          |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-15         | Unknown             | Put-as-patch          |
| 2016-03-30         | Unknown             | Put-as-patch          |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |

### \$.tags.*

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2015-05-01-preview | Unknown             | No Swagger, Put-as-patch (inheritted from 2015-06-15) |
| 2015-06-15         | Unknown             | Put-as-patch                                          |
| 2016-04-30-preview | Unknown             | Put-as-patch                                          |
| 2017-03-30         | Unknown             | Put-as-patch                                          |
| 2017-12-01         | Unknown             | Put-as-patch                                          |
| 2018-04-01         | Unknown             | Put-as-patch                                          |
| 2018-06-01         | Unknown             | Put-as-patch                                          |
| 2018-10-01         | Unknown             | Put-as-patch                                          |
| 2019-03-01         | Unknown             | Put-as-patch                                          |
| 2019-07-01         | Unknown             | Put-as-patch                                          |
| 2020-06-01         | Unknown             | Put-as-patch                                          |

### \$.zones

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |

## virtualMachineScaleSets/extensions

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-brightgreen) ![progress](https://img.shields.io/badge/progress-100.00%25%20(13%20/%2013)-brightgreen)

### \$.location

| API version | Detected noise type | Determined noise type                                 |
| ----------- | ------------------- | ----------------------------------------------------- |
| 2015-06-15  | Unknown             | No Swagger, Put-as-patch (inheritted from 2017-03-30) |
| 2017-03-30  | Unknown             | Put-as-patch                                          |
| 2017-12-01  | Unknown             | Put-as-patch                                          |
| 2018-06-01  | Unknown             | Put-as-patch                                          |
| 2018-10-01  | Unknown             | Put-as-patch                                          |
| 2019-03-01  | Unknown             | Put-as-patch                                          |

### \$.properties.autoUpgradeMinorVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2017-12-01  | Unknown             | Put-as-patch          |

### \$.properties.settings.KeyVaultURL

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |

### \$.properties.settings.timestamp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |

### \$.properties.settings.workspaceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |

## virtualMachineScaleSets

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-brightgreen) ![progress](https://img.shields.io/badge/progress-100.00%25%20(492%20/%20492)-brightgreen)

### \$.identity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | Put-as-patch          |

### \$.properties.automaticRepairsPolicy.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Default* (false)    | Put-as-patch          |

### \$.properties.automaticRepairsPolicy.gracePeriod

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.automaticRepairsPolicy.maxInstanceRepairsPercent

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Put-as-patch          |

### \$.properties.orchestrationMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.overProvision

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Put-as-patch          |

### \$.properties.overprovision

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-03-30         | Unknown             | Put-as-patch          |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-04-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |

### \$.properties.platformFaultDomainCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.singlePlacementGroup

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-04-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |
| 2019-12-01         | Unknown             | Put-as-patch          |

### \$.properties.uniqueId

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-03-30         | Unknown             | Put-as-patch          |
| 2016-04-30-preview | Unknown             | Put-as-patch          |

### \$.properties.upgradePolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.upgradePolicy.AutomaticOSUpgrade

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |

### \$.properties.upgradePolicy.automaticOSUpgrade

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-04-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |

### \$.properties.upgradePolicy.automaticOSUpgradePolicy.enableAutomaticOSUpgrade

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.upgradePolicy.automaticOSUpgradePolicy.schedulingPolicy.windows[*].startTime

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.upgradePolicy.mode

| API version | Detected noise type   | Determined noise type |
| ----------- | --------------------- | --------------------- |
| 2018-06-01  | Default ("Automatic") | Put-as-patch          |

### \$.properties.upgradePolicy.rollingUpgradePolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |

### \$.properties.upgradePolicy.rollingUpgradePolicy.maxBatchInstancePercent

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Default (20)        | Put-as-patch          |
| 2019-03-01  | Default (20)        | Put-as-patch          |

### \$.properties.upgradePolicy.rollingUpgradePolicy.maxUnhealthyInstancePercent

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Default* (20)       | Put-as-patch          |

### \$.properties.upgradePolicy.rollingUpgradePolicy.maxUnhealthyUpgradedInstancePercent

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Default (20)        | Put-as-patch          |

### \$.properties.upgradePolicy.rollingUpgradePolicy.pauseTimeBetweenBatches

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.billingProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.diagnosticsProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.diagnosticsProfile.bootDiagnostics.storageUri

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.evictionPolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-04-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.autoUpgradeMinorVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-04-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.enableAutomaticUpgrade

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.forceUpdateTag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.protectedSettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.protectedsettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.provisionAfterExtensions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.provisionAfterExtensions[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.publisher

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.AntimalwareEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.EncryptionOperation

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.Exclusions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.KekVaultResourceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.KeyEncryptionAlgorithm

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.KeyEncryptionKeyURL

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.KeyVaultResourceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.KeyVaultURL

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.Properties[*].Value

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.RealtimeProtectionEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.ResizeOSDisk

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.ScheduledScanSettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.StorageAccount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.UserName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.VolumeType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.WadCfg

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.WadCfg.SinksConfig.Sink[*].ApplicationInsights

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.authenticationSettings.msiClientId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.authenticationSettings.msiClientId 

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.certificate

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.certificate.thumbprint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.certificateSecondary

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.clusterEndpoint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.commandToExecute

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.configurationArguments.RegistrationUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.configurationArguments.clientId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.configurationArguments.uniqueString

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.cscfg

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.cspkgPath

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.dataPath

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.durabilityLevel

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.enableParallelJobs

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.fileUris

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.fileUris[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.forceUpdateTag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.modulesUrl

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.nicPrefixOverride

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.nodeTypeRef

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.port

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.protocol

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.requestPath

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.roles[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.secretsManagementSettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.secretsManagementSettings.observedCertificates[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.timestamp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.settings.workspaceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.extensionProfile.extensions[*].properties.typeHandlerVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.licenseType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.networkProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.networkProfile.loadBalancerConfigurations[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.networkProfile.networkInterfaceConfigurations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-04-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.networkProfile.networkInterfaceConfigurations[*].location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.networkProfile.networkInterfaceConfigurations[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.networkProfile.networkInterfaceConfigurations[*].properties.dnsSettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.networkProfile.networkInterfaceConfigurations[*].properties.enableAcceleratedNetworking

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-04-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.networkProfile.networkInterfaceConfigurations[*].properties.enableIPForwarding

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.networkProfile.networkInterfaceConfigurations[*].properties.ipConfigurations[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.networkProfile.networkInterfaceConfigurations[*].properties.ipConfigurations[*].properties.LoadBalancerBackendAddressPools

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.networkProfile.networkInterfaceConfigurations[*].properties.ipConfigurations[*].properties.LoadBalancerInboundNatPools

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.networkProfile.networkInterfaceConfigurations[*].properties.ipConfigurations[*].properties.loadBalancerBackendAddressPools

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.networkProfile.networkInterfaceConfigurations[*].properties.ipConfigurations[*].properties.loadBalancerBackendAddressPools[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.networkProfile.networkInterfaceConfigurations[*].properties.ipConfigurations[*].properties.loadBalancerBackendAddressPools[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.networkProfile.networkInterfaceConfigurations[*].properties.ipConfigurations[*].properties.loadBalancerInboundNatPools

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.networkProfile.networkInterfaceConfigurations[*].properties.ipConfigurations[*].properties.loadBalancerInboundNatPools[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.networkProfile.networkInterfaceConfigurations[*].properties.ipConfigurations[*].properties.primary

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.networkProfile.networkInterfaceConfigurations[*].properties.ipConfigurations[*].properties.privateIPAddressVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Default ("IPv4")    | Put-as-patch          |
| 2017-12-01  | Default ("IPv4")    | Put-as-patch          |
| 2018-04-01  | Default ("IPv4")    | Put-as-patch          |
| 2018-06-01  | Default ("IPv4")    | Put-as-patch          |
| 2018-10-01  | Default ("IPv4")    | Put-as-patch          |
| 2019-03-01  | Default ("IPv4")    | Put-as-patch          |
| 2019-07-01  | Default ("IPv4")    | Put-as-patch          |

### \$.properties.virtualMachineProfile.networkProfile.networkInterfaceConfigurations[*].properties.ipConfigurations[*].properties.privateIPAllocationMethod

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.networkProfile.networkInterfaceConfigurations[*].properties.ipConfigurations[*].properties.publicIPAddressConfiguration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.networkProfile.networkInterfaceConfigurations[*].properties.ipConfigurations[*].properties.publicIPAddressConfiguration.properties.idleTimeoutInMinutes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Default* (4)        | Put-as-patch          |
| 2019-07-01  | Default* (4)        | Put-as-patch          |

### \$.properties.virtualMachineProfile.networkProfile.networkInterfaceConfigurations[*].properties.ipConfigurations[*].properties.publicIPAddressConfiguration.properties.publicIPAddressVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Default ("IPv4")    | Put-as-patch          |
| 2019-12-01  | Default ("IPv4")    | Put-as-patch          |

### \$.properties.virtualMachineProfile.networkProfile.networkInterfaceConfigurations[*].properties.ipConfigurations[*].properties.publicIpAddressConfiguration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.networkProfile.networkInterfaceConfigurations[*].properties.ipConfigurations[*].properties.publicipaddressconfiguration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.networkProfile.networkInterfaceConfigurations[*].properties.ipConfigurations[*].properties.subnet.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.networkProfile.networkInterfaceConfigurations[*].properties.ipConfigurations[*].properties.subnet.privateIPAddressVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.networkProfile.networkInterfaceConfigurations[*].properties.primary

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-15         | Unknown             | Put-as-patch          |
| 2016-03-30         | Unknown             | Put-as-patch          |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-04-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.osProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.osProfile.AdminPassword

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-04-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.osProfile.AdminUsername

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.osProfile.adminUsername

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.osProfile.allowExtensionOperations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Default (true)      | Put-as-patch          |
| 2018-10-01  | Default (true)      | Put-as-patch          |
| 2019-03-01  | Default (true)      | Put-as-patch          |
| 2019-07-01  | Default (true)      | Put-as-patch          |
| 2019-12-01  | Default (true)      | Put-as-patch          |

### \$.properties.virtualMachineProfile.osProfile.computerNamePrefix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.osProfile.computernamePrefix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.osProfile.dsmsConfiguration.certificates[*].storeLocation

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.osProfile.dsmsConfiguration.certificates[*].storeName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.osProfile.linuxConfiguration

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-15         | Unknown             | Put-as-patch          |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-04-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.osProfile.linuxConfiguration.disablePasswordAuthentication

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.osProfile.linuxConfiguration.ssh

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.osProfile.requireGuestProvisionSignal

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Default (true)      | Put-as-patch          |
| 2019-03-01  | Default (true)      | Put-as-patch          |
| 2019-07-01  | Default (true)      | Put-as-patch          |
| 2019-12-01  | Default (true)      | Put-as-patch          |

### \$.properties.virtualMachineProfile.osProfile.secrets

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.osProfile.secrets[*].vaultCertificates[*].certificateUrl

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2018-04-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.osProfile.windowsConfiguration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.osProfile.windowsConfiguration.additionalUnattendContent[*].content

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.osProfile.windowsConfiguration.enableAutomaticUpdates

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-06-15         | Unknown             | Put-as-patch          |
| 2016-03-30         | Unknown             | Put-as-patch          |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-04-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |
| 2019-12-01         | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.osProfile.windowsConfiguration.provisionVMAgent

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Default (true)      | Put-as-patch          |
| 2018-06-01  | Default (true)      | Put-as-patch          |
| 2018-10-01  | Default (true)      | Put-as-patch          |
| 2019-03-01  | Default (true)      | Put-as-patch          |
| 2019-07-01  | Default (true)      | Put-as-patch          |

### \$.properties.virtualMachineProfile.osProfile.windowsConfiguration.provisionVmAgent

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.osProfile.windowsConfiguration.timeZone

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.osProfile.windowsConfiguration.timezone

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.scheduledEventsProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.storageProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.storageProfile.dataDisks

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.storageProfile.dataDisks[*].caching

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Default ("None")    | Put-as-patch          |
| 2018-06-01  | Default ("None")    | Put-as-patch          |
| 2018-10-01  | Default ("None")    | Put-as-patch          |
| 2019-03-01  | Default ("None")    | Put-as-patch          |
| 2019-07-01  | Default ("None")    | Put-as-patch          |

### \$.properties.virtualMachineProfile.storageProfile.dataDisks[*].diskSizeGB

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.storageProfile.dataDisks[*].managedDisk

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |
| 2019-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.storageProfile.dataDisks[*].managedDisk.storageAccountType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.storageProfile.osDisk

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-04-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.storageProfile.osDisk.caching

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.storageProfile.osDisk.diskSizeGB

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-04-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |
| 2019-12-01         | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.storageProfile.osDisk.managedDisk

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |
| 2019-12-01         | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.storageProfile.osDisk.managedDisk.storageAccountType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.storageProfile.osDisk.osType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.virtualMachineProfile.storageProfile.osDisk.vhdContainers[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.properties.zoneBalance

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-12-01  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.sku.capacity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-30  | Unknown             | Put-as-patch          |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-03-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.sku.tier

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2016-04-30-preview | Unknown             | Put-as-patch          |
| 2017-03-30         | Unknown             | Put-as-patch          |
| 2017-12-01         | Unknown             | Put-as-patch          |
| 2018-04-01         | Unknown             | Put-as-patch          |
| 2018-06-01         | Unknown             | Put-as-patch          |
| 2018-10-01         | Unknown             | Put-as-patch          |
| 2019-03-01         | Unknown             | Put-as-patch          |
| 2019-07-01         | Unknown             | Put-as-patch          |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | Put-as-patch          |
| 2018-10-01  | Unknown             | Put-as-patch          |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | Put-as-patch          |

### \$.zones

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | Put-as-patch          |
