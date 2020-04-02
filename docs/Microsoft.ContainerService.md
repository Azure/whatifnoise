# Microsoft.ContainerService

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## containerServices

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

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

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-30-preview | Unknown             | No Swagger            |

### \$.properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2018-09-30-preview | Unknown             | No Swagger            |

## managedClusters/agentPools

![13.33%25](https://img.shields.io/badge/13.33%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-orange)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |
| 2020-01-01  | Unknown             | No Swagger            |

### \$.properties.ScaleSetEvictionPolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | Default ("Delete")    |

### \$.properties.ScaleSetPriority

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | Default ("Regular")   |

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
| 2019-06-01  | Unknown             | Unknown               |

### \$.properties.enableAutoScaling

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Default* (true)     | Unknown               |

### \$.properties.maxPods

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Default* (35)       | Unknown               |

### \$.properties.minCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Default* (12)       | Unknown               |

### \$.properties.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.osDiskSizeGB

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Default* (100)      | Unknown               |

### \$.properties.storageProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |
| 2020-01-01  | Unknown             | No Swagger            |

### \$.properties.vnetSubnetID

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | Unknown               |

## managedClusters

![4.20%25](https://img.shields.io/badge/4.20%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.aadProfile.clientAppID

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.aadProfile.clientAppId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.aadProfile.serverAppID

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.aadProfile.serverAppId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.aadProfile.tenantID

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.aadProfile.tenantId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.addonProfiles

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | Unknown               |

### \$.properties.addonProfiles.httpApplicationRouting.config

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.addonProfiles.httpapplicationrouting.config

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.addonProfiles.omsagent

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.agentPoolProfiles[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].availabilityZones

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].count

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].dnsPrefix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].enableAutoScaling

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].enablePodSecurityPolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].maxCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].maxPods

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].minCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].nodeTaints

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].orchestratorVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2020-01-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].osDiskSizeGB

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-10-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].osType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].scaleSetEvictionPolicy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].scaleSetPriority

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].storageProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2020-01-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].type

| API version | Detected noise type          | Determined noise type |
| ----------- | ---------------------------- | --------------------- |
| 2019-04-01  | Default* ("AvailabilitySet") | No Swagger            |
| 2019-06-01  | Default* ("AvailabilitySet") | No Swagger            |
| 2019-08-01  | Default* ("AvailabilitySet") | No Swagger            |
| 2020-01-01  | Default* ("AvailabilitySet") | No Swagger            |
| 2020-02-01  | Default* ("AvailabilitySet") | No Swagger            |

### \$.properties.agentPoolProfiles[*].vmSize

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolProfiles[*].vnetSubnetID

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.agentPoolType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |

### \$.properties.apiServerAccessProfile.authorizedIPRanges[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.autoScalerProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | Unknown               |

### \$.properties.comment

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.enablePrivateCluster

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.enableRBAC

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Default* (false)    | Unknown               |
| 2019-04-01  | Default* (false)    | Unknown               |
| 2019-08-01  | Default* (false)    | Unknown               |

### \$.properties.kubernetesVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-06-01  | Unknown             | Unknown               |

### \$.properties.masterProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.networkProfile.dnsServiceIP

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | Default ("10.0.0.10") |

### \$.properties.networkProfile.dnsServiceIp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Default ("10.0.0.10") |

### \$.properties.networkProfile.dockerBridgeCidr

| API version | Detected noise type | Determined noise type     |
| ----------- | ------------------- | ------------------------- |
| 2018-03-31  | Unknown             | Default ("172.17.0.1/16") |

### \$.properties.networkProfile.loadBalancerProfile.effectiveOutboundIPs

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | Unknown               |
| 2020-02-01  | Unknown             | Unknown               |

### \$.properties.networkProfile.loadBalancerSku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-06-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |
| 2020-01-01  | Unknown             | Unknown               |
| 2020-02-01  | Unknown             | Unknown               |

### \$.properties.networkProfile.outboundType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-10-01  | Unknown             | No Swagger            |

### \$.properties.networkProfile.podCidr

| API version | Detected noise type | Determined noise type     |
| ----------- | ------------------- | ------------------------- |
| 2019-06-01  | Unknown             | Default ("10.244.0.0/16") |

### \$.properties.networkProfile.serviceCidr

| API version | Detected noise type | Determined noise type   |
| ----------- | ------------------- | ----------------------- |
| 2018-03-31  | Unknown             | Default ("10.0.0.0/16") |

### \$.properties.nodeResourceGroup

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-06-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |
| 2020-02-01  | Unknown             | Unknown               |

### \$.properties.orchestratorProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.servicePrincipal

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.servicePrincipalProfile.ClientId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.servicePrincipalProfile.Secret

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | Unknown               |
| 2019-02-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-06-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |
| 2020-02-01  | Unknown             | Unknown               |

### \$.properties.servicePrincipalProfile.aadSessionKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |
| 2020-02-01  | Unknown             | No Swagger            |

### \$.properties.servicePrincipalProfile.clientId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | Unknown               |
| 2019-06-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.properties.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.windowsProfile

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-02-01  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-31  | Unknown             | Unknown               |
| 2019-06-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | Unknown               |
| 2019-06-01  | Unknown             | Unknown               |
