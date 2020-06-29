# Microsoft.ContainerService

Legend of noise types:

| Noise type   | Description                                                                                   |
| ------------ | --------------------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                             |
| Default*     | The property may have a default value, but further investigation is required to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.                         |
| Put-as-patch | The property value does not change when missing from PUT body.                                |
| Unknown      | The property is in Swagger, but noise type is unclear.                                        |
| No Swagger   | The property does not exist in Swagger.                                                       |

## containerServices

![cleanliness](https://img.shields.io/badge/cleanliness-93.75%25%20(30%20/%2032)-brightgreen) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.properties.agentPoolProfiles[*].osType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-30  | Unknown             | No Swagger            |

### \$.properties.masterProfile.vmSize

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-30  | Unknown             | No Swagger            |

## locations/openShiftClusters

!> No Swagger.

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%202)-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-30-preview | Unknown             | No Swagger            |

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-30-preview | Unknown             | No Swagger            |

## managedClusters/agentPools

![cleanliness](https://img.shields.io/badge/cleanliness-12.50%25%20(3%20/%2024)-orange) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%2021)-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.ScaleSetEvictionPolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.ScaleSetPriority

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.clusterName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.count

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.enableAutoScaling

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Default* (true)     | No Swagger            |

### \$.properties.enableNodePublicIP

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Default* (false)    | No Swagger            |

### \$.properties.maxPods

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Default* (35)       | No Swagger            |

### \$.properties.minCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Default* (12)       | No Swagger            |

### \$.properties.mode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.orchestratorVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.osDiskSizeGB

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Default* (100)      | No Swagger            |
| 2020-02-01  | Default* (100)      | No Swagger            |

### \$.properties.storageProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.vnetSubnetID

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-10-01  | Unknown             | No Swagger            |

## managedClusters

![cleanliness](https://img.shields.io/badge/cleanliness-unknown-blue) ![progress](https://img.shields.io/badge/progress-0.00%25%20(0%20/%20228)-red)

### \$.properties.aadProfile.clientAppID

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.aadProfile.clientAppId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.aadProfile.serverAppID

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.aadProfile.serverAppId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.aadProfile.tenantID

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.aadProfile.tenantId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.addonProfiles

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.addonProfiles.KubeDashboard

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2020-01-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.addonProfiles.aciConnectorLinux.identity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.addonProfiles.azurePolicy.identity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.addonProfiles.httpApplicationRouting

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.addonProfiles.httpApplicationRouting.config

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.addonProfiles.httpApplicationRouting.identity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.addonProfiles.httpapplicationrouting.config

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.addonProfiles.omsagent

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | No Swagger            |

### \$.properties.addonProfiles.omsagent.identity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].apiVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].availabilityZones

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].availablityZone

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].count

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2020-01-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].customNodeLabels

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].dnsPrefix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].enableAutoScaling

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].enableNodePublicIP

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Default* (false)    | No Swagger            |

### \$.properties.agentPoolProfiles[*].enablePodSecurityPolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].enable_auto_scaling

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].maxCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].maxPods

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-10-01  | Unknown             | No Swagger            |
| 2020-01-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].max_count

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].minCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].min_count

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].mode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].nodeLabels

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].nodeLabels.nodepool

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].nodeTaints

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].orchestratorVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-10-01  | Unknown             | No Swagger            |
| 2020-01-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].osDiskSizeGB

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-31  | Unknown             | No Swagger            |
| 2018-03-31  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-10-01  | Unknown             | No Swagger            |
| 2020-01-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].osType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].scaleSetEvictionPolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].scaleSetPriority

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].spotMaxPrice

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].storageProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-10-01  | Unknown             | No Swagger            |
| 2020-01-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].tags.role

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].type

| API version | Detected noise type         | Determined noise type |
| ----------- | --------------------------- | --------------------- |
| 2018-03-31  | Default ("AvailabilitySet") | No Swagger            |
| 2019-02-01  | Default ("AvailabilitySet") | No Swagger            |
| 2019-04-01  | Default ("AvailabilitySet") | No Swagger            |
| 2019-06-01  | Default ("AvailabilitySet") | No Swagger            |
| 2019-08-01  | Default ("AvailabilitySet") | No Swagger            |
| 2020-01-01  | Default ("AvailabilitySet") | No Swagger            |
| 2020-02-01  | Default ("AvailabilitySet") | No Swagger            |
| 2020-03-01  | Default ("AvailabilitySet") | No Swagger            |

### \$.properties.agentPoolProfiles[*].vmSize

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].vnetSubnetID

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |

### \$.properties.apiServerAccessProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.apiServerAccessProfile.authorizedIPRanges[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.apiServerAuthorizedIPRanges

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.autoScalerProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.autoScalerProfile.balance-similar-node-groups

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.autoScalerProfile.max-graceful-termination-sec

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.autoScalerProfile.scale-down-delay-after-delete

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.autoScalerProfile.scale-down-delay-after-failure

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.autoScalerProfile.scale-down-unneeded-time

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.autoScalerProfile.scale-down-unready-time

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.autoScalerProfile.scale-down-utilization-threshold

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.comment

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.dnsPrefix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-01-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.enablePrivateCluster

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.enableRBAC

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-10-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.enabledRBAC

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.identityProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.kubernetesVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.linuxProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-01-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.linuxProfile.disablePasswordAuthentication

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.linuxProfile.ssh.publicKeys[*].path

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.masterProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.networkProfile.dnsServiceIP

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.networkProfile.dnsServiceIp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.networkProfile.dockerBridgeCidr

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.networkProfile.loadBalancerProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.networkProfile.loadBalancerProfile.effectiveOutboundIPs

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-10-01  | Unknown             | No Swagger            |
| 2020-01-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.networkProfile.loadBalancerProfile.effectiveOutboundIPs[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.networkProfile.loadBalancerSku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-10-01  | Unknown             | No Swagger            |
| 2020-01-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.networkProfile.networkPlugin

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.networkProfile.networkPolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.networkProfile.outboundType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-10-01  | Unknown             | No Swagger            |

### \$.properties.networkProfile.podCidr

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.networkProfile.serviceCidr

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.nodeResourceGroup

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-10-01  | Unknown             | No Swagger            |
| 2020-01-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.orchestratorProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.privateLinkResources

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.servicePrincipal

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.servicePrincipalProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.servicePrincipalProfile.ClientId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.servicePrincipalProfile.Secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-31  | Unknown             | No Swagger            |
| 2018-03-31  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-10-01  | Unknown             | No Swagger            |
| 2020-01-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.servicePrincipalProfile.aadSessionKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.servicePrincipalProfile.clientId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.useManagedIdentity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.windowsProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-10-01  | Unknown             | No Swagger            |
| 2020-01-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
