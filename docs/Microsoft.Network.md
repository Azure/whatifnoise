# Microsoft.Network

Legend of noise types:

| Noise type   | Description                                                                       |
| ------------ | --------------------------------------------------------------------------------- |
| Default      | The property has a default value.                                                 |
| Default*     | The property may have a default value, but further investigation to confirm that. |
| Read-only    | The property is read-only and should be excluded from What-If output.             |
| Put-as-patch | The property value does not change when missing from PUT body.                    |
| Unknown      | The property is in Swagger, but noise type is unclear.                            |
| No Swagger   | The property does not exist in Swagger.                                           |

## applicationGateways

![1.38%25](https://img.shields.io/badge/1.38%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.authenticationCertificates[*].etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.authenticationCertificates[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.authenticationCertificates[*].properties.backendHttpSettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.authenticationCertificates[*].properties.data

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.authenticationCertificates[*].properties.provisioningState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.authenticationCertificates[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.autoscaleConfiguration.minCapacity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-11-01  | Default* (0)        | Unknown               |

### \$.properties.backendAddressPools

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | Unknown               |
| 2018-07-01  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Unknown               |

### \$.properties.backendAddressPools[*].etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.backendAddressPools[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.backendAddressPools[*].properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.backendAddressPools[*].properties.BackendAddresses

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.backendAddressPools[*].properties.backendAddresses

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.backendAddressPools[*].properties.backendAddresses[*].fqdn

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |

### \$.properties.backendAddressPools[*].properties.backendAddresses[*].ipAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.backendAddressPools[*].properties.pathRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.backendAddressPools[*].properties.provisioningState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.backendAddressPools[*].properties.requestRoutingRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.backendAddressPools[*].properties.urlPathMaps

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.backendAddressPools[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.backendHttpSettingsCollection

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | Unknown               |
| 2018-07-01  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Unknown               |

### \$.properties.backendHttpSettingsCollection[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.backendHttpSettingsCollection[*].etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.backendHttpSettingsCollection[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.backendHttpSettingsCollection[*].properties.CookieBasedAffinity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.backendHttpSettingsCollection[*].properties.PickHostNameFromBackendAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.properties.backendHttpSettingsCollection[*].properties.Port

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.backendHttpSettingsCollection[*].properties.Probe

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |

### \$.properties.backendHttpSettingsCollection[*].properties.ProbeEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.backendHttpSettingsCollection[*].properties.Protocol

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.backendHttpSettingsCollection[*].properties.RequestTimeout

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.backendHttpSettingsCollection[*].properties.affinityCookieName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.backendHttpSettingsCollection[*].properties.cookieBasedAffinity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.backendHttpSettingsCollection[*].properties.hostName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.backendHttpSettingsCollection[*].properties.pathRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.backendHttpSettingsCollection[*].properties.pickHostNameFromBackendAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.backendHttpSettingsCollection[*].properties.port

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.backendHttpSettingsCollection[*].properties.probe

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |

### \$.properties.backendHttpSettingsCollection[*].properties.probeEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.backendHttpSettingsCollection[*].properties.protocol

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Default* ("Http")   | No Swagger            |
| 2018-10-01  | Default* ("Http")   | No Swagger            |
| 2019-04-01  | Default* ("Http")   | No Swagger            |

### \$.properties.backendHttpSettingsCollection[*].properties.provisioningState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.backendHttpSettingsCollection[*].properties.requestRoutingRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.backendHttpSettingsCollection[*].properties.requestTimeout

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.backendHttpSettingsCollection[*].properties.urlPathMaps

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.backendHttpSettingsCollection[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | Unknown               |
| 2018-07-01  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Unknown               |

### \$.properties.frontendIPConfigurations[*].etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.PublicIPAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.httpListeners

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.privateIPAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.privateIPAllocationMethod

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Default ("Dynamic") | No Swagger            |
| 2017-06-01  | Default ("Dynamic") | No Swagger            |
| 2018-04-01  | Default ("Dynamic") | No Swagger            |
| 2018-07-01  | Default ("Dynamic") | No Swagger            |
| 2018-08-01  | Default ("Dynamic") | No Swagger            |
| 2018-10-01  | Default ("Dynamic") | No Swagger            |
| 2019-02-01  | Default ("Dynamic") | No Swagger            |
| 2019-04-01  | Default ("Dynamic") | No Swagger            |
| 2019-09-01  | Default ("Dynamic") | No Swagger            |
| 2019-11-01  | Default ("Dynamic") | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.provisioningState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.publicIPAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.publicIPAddress.etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.publicIPAddress.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.publicIPAddress.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.publicIPAddress.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.publicIPAddress.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.publicIPAddress.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.publicIPAddress.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.publicIPAddress.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.publicIPAddress.zones

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.frontendPorts

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | Unknown               |
| 2018-07-01  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Unknown               |

### \$.properties.frontendPorts[*].etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.frontendPorts[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.frontendPorts[*].properties.Port

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.frontendPorts[*].properties.httpListeners

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.frontendPorts[*].properties.port

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.frontendPorts[*].properties.provisioningState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.frontendPorts[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.gatewayIPConfigurations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | Unknown               |
| 2018-07-01  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Unknown               |

### \$.properties.gatewayIPConfigurations[*].etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.gatewayIPConfigurations[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.gatewayIPConfigurations[*].properties.provisioningState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.gatewayIPConfigurations[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.httpListeners

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | Unknown               |
| 2018-07-01  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Unknown               |

### \$.properties.httpListeners[*].etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.httpListeners[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.httpListeners[*].properties.FrontendIPConfiguration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.httpListeners[*].properties.FrontendIpConfiguration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.httpListeners[*].properties.FrontendPort

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.httpListeners[*].properties.Protocol

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.httpListeners[*].properties.SslCertificate

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.httpListeners[*].properties.frontendIPConfiguration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.httpListeners[*].properties.frontendIpConfiguration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.httpListeners[*].properties.frontendPort

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.httpListeners[*].properties.protocol

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.httpListeners[*].properties.provisioningState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.httpListeners[*].properties.redirectConfiguration

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.httpListeners[*].properties.requestRoutingRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.httpListeners[*].properties.requireServerNameIndication

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Default (false)     | No Swagger            |
| 2017-10-01  | Default (false)     | No Swagger            |
| 2018-07-01  | Default (false)     | No Swagger            |
| 2018-08-01  | Default (false)     | No Swagger            |
| 2018-11-01  | Default (false)     | No Swagger            |
| 2018-12-01  | Default (false)     | No Swagger            |
| 2019-02-01  | Default (false)     | No Swagger            |
| 2019-04-01  | Default (false)     | No Swagger            |
| 2019-09-01  | Default (false)     | No Swagger            |
| 2019-11-01  | Default (false)     | No Swagger            |

### \$.properties.httpListeners[*].properties.sslCertificate

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.httpListeners[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.probes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | Unknown               |
| 2018-07-01  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Unknown               |

### \$.properties.probes[*].Name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.probes[*].etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.probes[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.probes[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.probes[*].properties.Host

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.probes[*].properties.Interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.probes[*].properties.Match

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |

### \$.properties.probes[*].properties.MinServers

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |

### \$.properties.probes[*].properties.Path

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.probes[*].properties.PickHostNameFromBackendHttpSettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |

### \$.properties.probes[*].properties.Protocol

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.probes[*].properties.Timeout

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.probes[*].properties.UnhealthyThreshold

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |

### \$.properties.probes[*].properties.backendHttpSettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.probes[*].properties.host

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.probes[*].properties.interval

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Default* (30)       | No Swagger            |
| 2018-07-01  | Default* (30)       | No Swagger            |

### \$.properties.probes[*].properties.match

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |

### \$.properties.probes[*].properties.minServers

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Default (0)         | No Swagger            |
| 2018-07-01  | Default (0)         | No Swagger            |
| 2018-12-01  | Default (0)         | No Swagger            |

### \$.properties.probes[*].properties.path

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.probes[*].properties.pickHostNameFromBackendHttpSettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |

### \$.properties.probes[*].properties.protocol

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Default* ("Http")   | No Swagger            |

### \$.properties.probes[*].properties.provisioningState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.probes[*].properties.timeout

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.probes[*].properties.unhealthyThreshold

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.probes[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.redirectConfigurations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | Unknown               |

### \$.properties.redirectConfigurations[*].etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.redirectConfigurations[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.redirectConfigurations[*].properties.provisioningState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.redirectConfigurations[*].properties.requestRoutingRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.redirectConfigurations[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |

### \$.properties.requestRoutingRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | Unknown               |
| 2018-07-01  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Unknown               |

### \$.properties.requestRoutingRules[*].Name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.requestRoutingRules[*].etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.requestRoutingRules[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.requestRoutingRules[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.requestRoutingRules[*].properties.RuleType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.requestRoutingRules[*].properties.provisioningState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.requestRoutingRules[*].properties.ruleType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Default* ("Basic")  | No Swagger            |
| 2018-08-01  | Default* ("Basic")  | No Swagger            |
| 2018-10-01  | Default* ("Basic")  | No Swagger            |
| 2019-04-01  | Default* ("Basic")  | No Swagger            |

### \$.properties.requestRoutingRules[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.rewriteRuleSets[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.rewriteRuleSets[*].properties.requestRoutingRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.rewriteRuleSets[*].properties.rewriteRules[*].ruleSequence

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Default* (100)      | No Swagger            |

### \$.properties.rewriteRuleSets[*].properties.urlPathMaps

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.rewriteRuleSets[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.sslCertificates

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | Unknown               |

### \$.properties.sslCertificates[*].etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.sslCertificates[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.sslCertificates[*].properties.Data

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.sslCertificates[*].properties.Password

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.sslCertificates[*].properties.data

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.sslCertificates[*].properties.httpListeners

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.sslCertificates[*].properties.keyVaultSecretId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.sslCertificates[*].properties.provisioningState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.sslCertificates[*].properties.publicCertData

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.sslCertificates[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.trustedRootCertificates[*].etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.trustedRootCertificates[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.trustedRootCertificates[*].properties.backendHttpSettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.trustedRootCertificates[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.urlPathMaps[*].etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.urlPathMaps[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.urlPathMaps[*].properties.pathRules[*].etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.urlPathMaps[*].properties.pathRules[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.urlPathMaps[*].properties.pathRules[*].properties.provisioningState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.urlPathMaps[*].properties.pathRules[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.urlPathMaps[*].properties.provisioningState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.urlPathMaps[*].properties.requestRoutingRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.urlPathMaps[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |

### \$.properties.webApplicationFirewallConfiguration.enabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Default* (true)     | Unknown               |
| 2018-11-01  | Default* (true)     | Unknown               |
| 2019-09-01  | Default* (true)     | Unknown               |

### \$.properties.webApplicationFirewallConfiguration.fileUploadLimitInMb

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Default (100)       | Default (100)         |
| 2018-11-01  | Default (100)       | Default (100)         |
| 2018-12-01  | Default (100)       | Default (100)         |
| 2019-02-01  | Default (100)       | Default (100)         |
| 2019-04-01  | Default (100)       | Default (100)         |
| 2019-09-01  | Default (100)       | Default (100)         |

### \$.properties.webApplicationFirewallConfiguration.firewallMode

| API version | Detected noise type    | Determined noise type |
| ----------- | ---------------------- | --------------------- |
| 2017-06-01  | Default* ("Detection") | Unknown               |

### \$.properties.webApplicationFirewallConfiguration.maxRequestBodySizeInKb

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Default (128)       | Default (128)         |
| 2018-11-01  | Default (128)       | Default (128)         |
| 2019-02-01  | Default (128)       | Default (128)         |
| 2019-04-01  | Default (128)       | Default (128)         |
| 2019-09-01  | Default (128)       | Default (128)         |

### \$.properties.webApplicationFirewallConfiguration.requestBodyCheck

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Default (true)      | Default (true)        |
| 2018-07-01  | Default (true)      | Default (true)        |
| 2018-11-01  | Default (true)      | Default (true)        |
| 2019-02-01  | Default (true)      | Default (true)        |
| 2019-09-01  | Default (true)      | Default (true)        |

### \$.properties.webApplicationFirewallConfiguration.ruleSetType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | Unknown               |
| 2018-08-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |

### \$.properties.webApplicationFirewallConfiguration.ruleSetVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | Unknown               |
| 2018-08-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-12-01  | Unknown             | Unknown               |
| 2019-02-01  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Unknown               |

## applicationGatewayWebApplicationFirewallPolicies

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.policySettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-11-01  | Unknown             | Unknown               |

## applicationSecurityGroups

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | Unknown               |
| 2019-02-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |

## azureFirewalls

![8.57%25](https://img.shields.io/badge/8.57%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-red)

### \$.properties.applicationRuleCollections[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.applicationRuleCollections[*].properties.rules[*].direction

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.applicationRuleCollections[*].properties.rules[*].priority

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Default (0)         | No Swagger            |
| 2019-04-01  | Default (0)         | No Swagger            |
| 2019-07-01  | Default (0)         | No Swagger            |
| 2019-09-01  | Default (0)         | No Swagger            |
| 2019-11-01  | Default (0)         | No Swagger            |

### \$.properties.applicationRuleCollections[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.privateIPAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.privateIPAllocationMethod

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.natRuleCollections[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.natRuleCollections[*].properties.rules[*].destinationAddresses[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.natRuleCollections[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.networkRuleCollections[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.networkRuleCollections[*].properties.rules[*].protocols[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.networkRuleCollections[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | Unknown               |
| 2019-11-01  | Unknown             | Unknown               |

### \$.properties.threatIntelMode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Default ("Alert")   | Default ("Alert")     |
| 2019-04-01  | Default ("Alert")   | Default ("Alert")     |
| 2019-06-01  | Default ("Alert")   | Default ("Alert")     |
| 2019-07-01  | Default ("Alert")   | Default ("Alert")     |
| 2019-09-01  | Default ("Alert")   | Default ("Alert")     |
| 2019-11-01  | Default ("Alert")   | Default ("Alert")     |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | Unknown               |

## bastionHosts

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.dnsName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Unknown               |

### \$.properties.ipConfigurations[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.privateIPAllocationMethod

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Default ("Dynamic") | No Swagger            |

### \$.properties.scaleUnits

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Default (2)         | No Swagger            |
| 2019-04-01  | Default (2)         | No Swagger            |
| 2019-09-01  | Default (2)         | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | No Swagger            |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | No Swagger            |

## connections

![27.45%25](https://img.shields.io/badge/27.45%25-%E2%98%85★★%E2%98%86☆☆☆☆☆☆-orange)

### \$.properties.connectionProtocol

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Default* ("IKEv2")  | Unknown               |
| 2019-07-01  | Default* ("IKEv2")  | Unknown               |
| 2019-11-01  | Default* ("IKEv2")  | Unknown               |

### \$.properties.connectionStatus

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Read-only             |
| 2015-06-15         | Unknown             | Read-only             |
| 2016-03-30         | Unknown             | Read-only             |

### \$.properties.egressBytesTransferred

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |
| 2015-06-15         | Unknown             | Unknown               |
| 2016-03-30         | Unknown             | Unknown               |

### \$.properties.enableBGP

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | Unknown               |

### \$.properties.enableBgp

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | Unknown               |
| 2016-03-30         | Unknown             | Unknown               |
| 2017-10-01         | Unknown             | Unknown               |
| 2019-02-01         | Unknown             | Unknown               |

### \$.properties.expressRouteGatewayBypass

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Default (false)     | Default (false)       |
| 2018-08-01  | Default (false)     | Default (false)       |
| 2019-02-01  | Default (false)     | Default (false)       |
| 2019-07-01  | Default (false)     | Default (false)       |
| 2019-11-01  | Default (false)     | Default (false)       |

### \$.properties.ingressBytesTransferred

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |
| 2015-06-15         | Unknown             | Unknown               |
| 2016-03-30         | Unknown             | Unknown               |

### \$.properties.ipsecPolicies[*].saDataSizeKilobytes

| API version | Detected noise type  | Determined noise type |
| ----------- | -------------------- | --------------------- |
| 2019-11-01  | Default* (102400000) | No Swagger            |

### \$.properties.ipsecPolicies[*].saLifeTimeSeconds

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-11-01  | Default* (27000)    | No Swagger            |

### \$.properties.localNetworkGateway2.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Unknown               |

### \$.properties.packetCaptureDiagnosticState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.routingWeight

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Unknown               |
| 2018-08-01  | Unknown             | Unknown               |
| 2019-02-01  | Unknown             | Unknown               |

### \$.properties.tunnelConnectionStatus

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Read-only             |

### \$.properties.useLocalAzureIpAddress

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Default (false)     | No Swagger            |
| 2015-06-15         | Default (false)     | No Swagger            |
| 2016-03-30         | Default (false)     | No Swagger            |
| 2017-10-01         | Default (false)     | No Swagger            |
| 2018-07-01         | Default (false)     | No Swagger            |
| 2018-08-01         | Default (false)     | No Swagger            |
| 2018-10-01         | Default (false)     | No Swagger            |
| 2019-02-01         | Default (false)     | No Swagger            |
| 2019-04-01         | Default (false)     | No Swagger            |
| 2019-07-01         | Default (false)     | No Swagger            |
| 2019-08-01         | Default (false)     | No Swagger            |
| 2019-09-01         | Default (false)     | No Swagger            |
| 2019-11-01         | Default (false)     | No Swagger            |

### \$.properties.usePolicyBasedTrafficSelectors

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Default (false)     | Default (false)       |
| 2018-07-01  | Default (false)     | Default (false)       |
| 2018-08-01  | Default (false)     | Default (false)       |
| 2019-02-01  | Default (false)     | Default (false)       |
| 2019-08-01  | Default (false)     | Default (false)       |

### \$.properties.virtualNetworkGateway1.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | Unknown               |

### \$.properties.vpnType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

## dnszones/a

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-01  | Unknown             | No Swagger            |
| 2017-09-01  | Unknown             | No Swagger            |
| 2018-05-01  | Unknown             | No Swagger            |

### \$.properties.ARecords[*].ipv4Address

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-05-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-01  | Unknown             | No Swagger            |

## dnszones/cname

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-01  | Unknown             | No Swagger            |
| 2017-09-01  | Unknown             | No Swagger            |
| 2018-05-01  | Unknown             | No Swagger            |

### \$.properties.CNAMERecord.cname

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-01  | Unknown             | Unknown               |
| 2018-05-01  | Unknown             | Unknown               |

### \$.properties.metadata.InclureAuGateway

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-01  | Unknown             | No Swagger            |
| 2018-05-01  | Unknown             | No Swagger            |

## dnszones/mx

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-01  | Unknown             | No Swagger            |

## dnszones/ns

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.NSRecords[*].nsdname

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-01  | Unknown             | No Swagger            |

## dnsZones/txt

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-01  | Unknown             | No Swagger            |
| 2018-05-01  | Unknown             | No Swagger            |

## dnszones

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-01  | Unknown             | Unknown               |
| 2017-09-01  | Unknown             | Unknown               |

### \$.properties.numberOfRecordSets

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-01  | Default* (46)       | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-04-01  | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-05-01  | Unknown             | Unknown               |

## expressRouteCircuits

![27.27%25](https://img.shields.io/badge/27.27%25-%E2%98%85★★%E2%98%86☆☆☆☆☆☆-orange)

### \$.properties.allowClassicOperations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Default (false)     | No Swagger            |

### \$.properties.allowGlobalReach

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Default* (false)    | No Swagger            |
| 2019-04-01  | Default* (false)    | No Swagger            |

### \$.properties.circuitProvisioningState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Read-only             |
| 2019-02-01  | Unknown             | Read-only             |
| 2019-04-01  | Unknown             | Read-only             |

### \$.properties.globalReachEnabled

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Default* (false)    | Unknown               |
| 2019-04-01  | Default* (false)    | Unknown               |

### \$.properties.peerings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | Unknown               |

### \$.properties.peerings[*].properties.PrimaryPeerAddressPrefix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.peerings[*].properties.SecondaryPeerAddressPrefix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.peerings[*].properties.azureASN

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Default (12076)     | No Swagger            |

### \$.properties.peerings[*].properties.lastModifiedBy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |

### \$.properties.peerings[*].properties.microsoftPeeringConfig.advertisedPublicPrefixes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.peerings[*].properties.microsoftPeeringConfig.advertisedPublicPrefixesState

| API version | Detected noise type          | Determined noise type |
| ----------- | ---------------------------- | --------------------- |
| 2015-06-15  | Default ("ValidationNeeded") | No Swagger            |

### \$.properties.peerings[*].properties.microsoftPeeringConfig.advertisedpublicprefixes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.peerings[*].properties.microsoftPeeringConfig.customerASN

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Default* (124)      | No Swagger            |

### \$.properties.peerings[*].properties.microsoftPeeringConfig.customerAsn

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.peerings[*].properties.primaryPeerAddressPrefix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.peerings[*].properties.secondaryPeerAddressPrefix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.peerings[*].properties.sharedKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.peerings[*].properties.state

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Default ("Enabled") | No Swagger            |
| 2019-02-01  | Default ("Enabled") | No Swagger            |

### \$.properties.resourceGuid

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Read-only             |
| 2019-02-01  | Unknown             | Read-only             |
| 2019-04-01  | Unknown             | Read-only             |

### \$.properties.serviceKey

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Unknown               |
| 2019-02-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |

### \$.properties.serviceProviderProvisioningState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Read-only             |
| 2019-02-01  | Unknown             | Read-only             |
| 2019-04-01  | Unknown             | Read-only             |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Unknown               |

## expressRouteGateways

![66.67%25](https://img.shields.io/badge/66.67%25-%E2%98%85★★★★★★%E2%98%86☆☆-yellowgreen)

### \$.properties.resourceGuid

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | Read-only             |
| 2019-11-01  | Unknown             | Read-only             |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | Unknown               |

## frontdoors

![12.90%25](https://img.shields.io/badge/12.90%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-orange)

### \$.properties.backendPoolsSettings.enforceCertificateNameCheck

| API version | Detected noise type   | Determined noise type |
| ----------- | --------------------- | --------------------- |
| 2019-05-01  | Default* ("Disabled") | Default ("Enabled")   |

### \$.properties.backendPoolsSettings.sendRecvTimeoutSeconds

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Default* (30)       | Unknown               |

### \$.properties.backendPools[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.backendPools[*].properties.backends[*].enabledState

| API version | Detected noise type  | Determined noise type |
| ----------- | -------------------- | --------------------- |
| 2019-05-01  | Default* ("Enabled") | No Swagger            |

### \$.properties.cName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Unknown             | Read-only             |
| 2019-04-01  | Unknown             | Read-only             |
| 2019-05-01  | Unknown             | Read-only             |

### \$.properties.enabledState

| API version | Detected noise type  | Determined noise type |
| ----------- | -------------------- | --------------------- |
| 2019-05-01  | Default* ("Enabled") | Unknown               |

### \$.properties.frontendEndpoints[*].properties.sessionAffinityEnabledState

| API version | Detected noise type   | Determined noise type |
| ----------- | --------------------- | --------------------- |
| 2019-05-01  | Default* ("Disabled") | No Swagger            |

### \$.properties.frontendEndpoints[*].properties.sessionAffinityTtlSeconds

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Default (0)         | No Swagger            |
| 2019-05-01  | Default (0)         | No Swagger            |

### \$.properties.healthProbeSettings[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.healthProbeSettings[*].properties.enabledState

| API version | Detected noise type  | Determined noise type |
| ----------- | -------------------- | --------------------- |
| 2019-05-01  | Default* ("Enabled") | No Swagger            |

### \$.properties.healthProbeSettings[*].properties.healthProbeMethod

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Default* ("Get")    | No Swagger            |

### \$.properties.loadBalancingSettings[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.loadBalancingSettings[*].properties.additionalLatencyMilliseconds

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Default (0)         | No Swagger            |
| 2019-04-01  | Default (0)         | No Swagger            |
| 2019-05-01  | Default (0)         | No Swagger            |

### \$.properties.routingRules[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-05-01  | Unknown             | No Swagger            |

### \$.properties.routingRules[*].properties.enabledState

| API version | Detected noise type  | Determined noise type |
| ----------- | -------------------- | --------------------- |
| 2018-08-01  | Default* ("Enabled") | No Swagger            |
| 2019-05-01  | Default* ("Enabled") | No Swagger            |

### \$.properties.routingRules[*].properties.forwardingProtocol

| API version | Detected noise type       | Determined noise type |
| ----------- | ------------------------- | --------------------- |
| 2018-08-01  | Default* ("MatchRequest") | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-05-01  | Unknown             | Unknown               |

## frontDoorWebApplicationFirewallPolicies

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.customRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Unknown             | Unknown               |

### \$.properties.customRules.rules[*].matchConditions[*].negateCondition

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-03-01  | Default* (false)    | No Swagger            |

## loadBalancers/inboundNatRules

![11.76%25](https://img.shields.io/badge/11.76%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-orange)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.allowBackendPortConflict

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Default* (false)    | No Swagger            |

### \$.properties.enableDestinationServiceEndpoint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Default (false)     | No Swagger            |
| 2018-08-01  | Default (false)     | No Swagger            |
| 2019-06-01  | Default (false)     | No Swagger            |

### \$.properties.enableFloatingIP

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Default* (false)    | No Swagger            |

### \$.properties.enableTcpReset

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Default* (false)    | Unknown               |
| 2019-06-01  | Default* (false)    | Unknown               |

### \$.properties.enabledFloatingIP

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.idleTimeoutInMinutes

| API version | Detected noise type | Determined noise type                                |
| ----------- | ------------------- | ---------------------------------------------------- |
| 2015-06-15  | Default (4)         | No Swagger, Default (4) (inheritted from 2019-06-01) |
| 2019-06-01  | Default (4)         | Default (4)                                          |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

## loadBalancers

![6.88%25](https://img.shields.io/badge/6.88%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-red)

### \$.properties.LoadBalancingRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Read-only             |

### \$.properties.backendAddressPools

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |
| 2016-09-01         | Unknown             | Unknown               |
| 2018-06-01         | Unknown             | Unknown               |
| 2018-10-01         | Unknown             | Unknown               |

### \$.properties.backendAddressPools[*].etag

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | No Swagger            |

### \$.properties.backendAddressPools[*].id

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | No Swagger            |

### \$.properties.backendAddressPools[*].properties

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |

### \$.properties.backendAddressPools[*].properties.backendIPConfigurations

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.backendAddressPools[*].properties.provisioningState

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |

### \$.properties.backendAddressPools[*].type

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |
| 2016-09-01         | Unknown             | Unknown               |
| 2017-06-01         | Unknown             | Unknown               |
| 2017-08-01         | Unknown             | Unknown               |
| 2017-10-01         | Unknown             | Unknown               |
| 2018-01-01         | Unknown             | Unknown               |
| 2018-02-01         | Unknown             | Unknown               |
| 2018-04-01         | Unknown             | Unknown               |
| 2018-06-01         | Unknown             | Unknown               |
| 2018-07-01         | Unknown             | Unknown               |
| 2018-08-01         | Unknown             | Unknown               |
| 2018-10-01         | Unknown             | Unknown               |
| 2018-11-01         | Unknown             | Unknown               |
| 2018-12-01         | Unknown             | Unknown               |
| 2019-02-01         | Unknown             | Unknown               |
| 2019-06-01         | Unknown             | Unknown               |
| 2019-07-01         | Unknown             | Unknown               |
| 2019-08-01         | Unknown             | Unknown               |
| 2020-03-01         | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].etag

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].id

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.inboundNatPools

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.inboundNatRules

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.loadBalancingRules

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.outboundRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.privateIPAddress

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2017-04-01         | Unknown             | No Swagger            |
| 2017-08-01         | Unknown             | No Swagger            |
| 2017-10-01         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |
| 2018-07-01         | Unknown             | No Swagger            |
| 2018-08-01         | Unknown             | No Swagger            |
| 2018-10-01         | Unknown             | No Swagger            |
| 2018-12-01         | Unknown             | No Swagger            |
| 2019-02-01         | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |
| 2019-07-01         | Unknown             | No Swagger            |
| 2019-09-01         | Unknown             | No Swagger            |
| 2019-11-01         | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.privateIPAddressVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Default ("IPv4")    | No Swagger            |
| 2019-06-01  | Default ("IPv4")    | No Swagger            |
| 2019-07-01  | Default ("IPv4")    | No Swagger            |
| 2019-08-01  | Default ("IPv4")    | No Swagger            |
| 2019-09-01  | Default ("IPv4")    | No Swagger            |
| 2019-11-01  | Default ("IPv4")    | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.privateIPAllocationMethod

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Default ("Dynamic") | No Swagger            |
| 2015-06-15         | Default ("Dynamic") | No Swagger            |
| 2016-03-30         | Default ("Dynamic") | No Swagger            |
| 2016-09-01         | Default ("Dynamic") | No Swagger            |
| 2017-04-01         | Default ("Dynamic") | No Swagger            |
| 2017-06-01         | Default ("Dynamic") | No Swagger            |
| 2017-08-01         | Default ("Dynamic") | No Swagger            |
| 2017-09-01         | Default ("Dynamic") | No Swagger            |
| 2017-10-01         | Default ("Dynamic") | No Swagger            |
| 2017-11-01         | Default ("Dynamic") | No Swagger            |
| 2018-01-01         | Default ("Dynamic") | No Swagger            |
| 2018-02-01         | Default ("Dynamic") | No Swagger            |
| 2018-04-01         | Default ("Dynamic") | No Swagger            |
| 2018-06-01         | Default ("Dynamic") | No Swagger            |
| 2018-07-01         | Default ("Dynamic") | No Swagger            |
| 2018-08-01         | Default ("Dynamic") | No Swagger            |
| 2018-10-01         | Default ("Dynamic") | No Swagger            |
| 2018-11-01         | Default ("Dynamic") | No Swagger            |
| 2018-12-01         | Default ("Dynamic") | No Swagger            |
| 2019-02-01         | Default ("Dynamic") | No Swagger            |
| 2019-04-01         | Default ("Dynamic") | No Swagger            |
| 2019-06-01         | Default ("Dynamic") | No Swagger            |
| 2019-07-01         | Default ("Dynamic") | No Swagger            |
| 2019-08-01         | Default ("Dynamic") | No Swagger            |
| 2019-09-01         | Default ("Dynamic") | No Swagger            |
| 2019-11-01         | Default ("Dynamic") | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.provisioningState

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.publicIPAddress.etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.publicIPAddress.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.publicIPAddress.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.publicIPAddress.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].properties.publicIPAddress.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.frontendIPConfigurations[*].type

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | No Swagger            |

### \$.properties.frontendIpConfigurations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-10-01  | Unknown             | Unknown               |
| 2019-02-01  | Unknown             | Unknown               |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.inboundNatPools

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | Read-only             |
| 2017-08-01  | Unknown             | Read-only             |
| 2017-10-01  | Unknown             | Read-only             |
| 2018-01-01  | Unknown             | Read-only             |
| 2018-06-01  | Unknown             | Read-only             |
| 2018-07-01  | Unknown             | Read-only             |
| 2018-08-01  | Unknown             | Read-only             |
| 2018-10-01  | Unknown             | Read-only             |
| 2018-11-01  | Unknown             | Read-only             |
| 2018-12-01  | Unknown             | Read-only             |
| 2019-07-01  | Unknown             | Read-only             |
| 2019-08-01  | Unknown             | Read-only             |
| 2019-09-01  | Unknown             | Read-only             |

### \$.properties.inboundNatPools[*].comments

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.inboundNatPools[*].properties.allowBackendPortConflict

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Default (false)     | No Swagger            |
| 2018-12-01  | Default (false)     | No Swagger            |
| 2019-02-01  | Default (false)     | No Swagger            |
| 2019-04-01  | Default (false)     | No Swagger            |
| 2019-06-01  | Default (false)     | No Swagger            |
| 2019-07-01  | Default (false)     | No Swagger            |
| 2019-08-01  | Default (false)     | No Swagger            |
| 2019-09-01  | Default (false)     | No Swagger            |
| 2019-11-01  | Default (false)     | No Swagger            |

### \$.properties.inboundNatPools[*].properties.enableDestinationServiceEndpoint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-11-01  | Default (false)     | No Swagger            |
| 2018-01-01  | Default (false)     | No Swagger            |
| 2018-02-01  | Default (false)     | No Swagger            |
| 2018-03-01  | Default (false)     | No Swagger            |
| 2018-04-01  | Default (false)     | No Swagger            |
| 2018-06-01  | Default (false)     | No Swagger            |
| 2018-07-01  | Default (false)     | No Swagger            |
| 2018-08-01  | Default (false)     | No Swagger            |
| 2018-10-01  | Default (false)     | No Swagger            |
| 2018-11-01  | Default (false)     | No Swagger            |
| 2018-12-01  | Default (false)     | No Swagger            |
| 2019-02-01  | Default (false)     | No Swagger            |
| 2019-04-01  | Default (false)     | No Swagger            |
| 2019-06-01  | Default (false)     | No Swagger            |
| 2019-07-01  | Default (false)     | No Swagger            |
| 2019-08-01  | Default (false)     | No Swagger            |
| 2019-09-01  | Default (false)     | No Swagger            |
| 2019-11-01  | Default (false)     | No Swagger            |

### \$.properties.inboundNatPools[*].properties.enableFloatingIP

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Default (false)     | No Swagger            |
| 2018-06-01  | Default (false)     | No Swagger            |
| 2018-07-01  | Default (false)     | No Swagger            |
| 2018-08-01  | Default (false)     | No Swagger            |
| 2018-11-01  | Default (false)     | No Swagger            |
| 2018-12-01  | Default (false)     | No Swagger            |
| 2019-04-01  | Default (false)     | No Swagger            |
| 2019-07-01  | Default (false)     | No Swagger            |
| 2019-09-01  | Default (false)     | No Swagger            |

### \$.properties.inboundNatPools[*].properties.enableTcpReset

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Default (false)     | No Swagger            |
| 2018-08-01  | Default (false)     | No Swagger            |
| 2018-10-01  | Default (false)     | No Swagger            |
| 2018-11-01  | Default (false)     | No Swagger            |
| 2018-12-01  | Default (false)     | No Swagger            |
| 2019-04-01  | Default (false)     | No Swagger            |
| 2019-07-01  | Default (false)     | No Swagger            |
| 2019-09-01  | Default (false)     | No Swagger            |

### \$.properties.inboundNatPools[*].properties.frontendIPConfiguration.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-12-01  | Unknown             | No Swagger            |

### \$.properties.inboundNatPools[*].properties.frontendIPConfiguration.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-12-01  | Unknown             | No Swagger            |

### \$.properties.inboundNatPools[*].properties.idleTimeoutInMinutes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Default (4)         | No Swagger            |
| 2018-06-01  | Default (4)         | No Swagger            |
| 2018-07-01  | Default (4)         | No Swagger            |
| 2018-08-01  | Default (4)         | No Swagger            |
| 2018-10-01  | Default (4)         | No Swagger            |
| 2018-11-01  | Default (4)         | No Swagger            |
| 2018-12-01  | Default (4)         | No Swagger            |
| 2019-04-01  | Default (4)         | No Swagger            |
| 2019-07-01  | Default (4)         | No Swagger            |
| 2019-09-01  | Default (4)         | No Swagger            |

### \$.properties.inboundNatPools[*].type

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | No Swagger            |
| 2017-04-01         | Unknown             | No Swagger            |
| 2017-06-01         | Unknown             | No Swagger            |
| 2017-08-01         | Unknown             | No Swagger            |
| 2017-09-01         | Unknown             | No Swagger            |
| 2017-10-01         | Unknown             | No Swagger            |
| 2017-11-01         | Unknown             | No Swagger            |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-02-01         | Unknown             | No Swagger            |
| 2018-03-01         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |
| 2018-07-01         | Unknown             | No Swagger            |
| 2018-08-01         | Unknown             | No Swagger            |
| 2018-10-01         | Unknown             | No Swagger            |
| 2018-11-01         | Unknown             | No Swagger            |
| 2018-12-01         | Unknown             | No Swagger            |
| 2019-02-01         | Unknown             | No Swagger            |
| 2019-04-01         | Unknown             | No Swagger            |

### \$.properties.loadBalancingRules

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |
| 2016-09-01         | Unknown             | Read-only             |
| 2017-08-01         | Unknown             | Read-only             |
| 2017-10-01         | Unknown             | Read-only             |
| 2018-01-01         | Unknown             | Read-only             |
| 2018-04-01         | Unknown             | Read-only             |
| 2018-06-01         | Unknown             | Read-only             |
| 2018-07-01         | Unknown             | Read-only             |
| 2018-08-01         | Unknown             | Read-only             |
| 2018-10-01         | Unknown             | Read-only             |
| 2018-11-01         | Unknown             | Read-only             |
| 2018-12-01         | Unknown             | Read-only             |
| 2019-04-01         | Unknown             | Read-only             |
| 2019-06-01         | Unknown             | Read-only             |
| 2019-09-01         | Unknown             | Read-only             |

### \$.properties.loadBalancingRules[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.loadBalancingRules[*].Name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.loadBalancingRules[*].dependsOn

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.loadBalancingRules[*].etag

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | No Swagger            |

### \$.properties.loadBalancingRules[*].id

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | No Swagger            |

### \$.properties.loadBalancingRules[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.loadBalancingRules[*].properties.allowBackendPortConflict

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Default (false)     | No Swagger            |
| 2018-12-01  | Default (false)     | No Swagger            |
| 2019-02-01  | Default (false)     | No Swagger            |
| 2019-04-01  | Default (false)     | No Swagger            |
| 2019-06-01  | Default (false)     | No Swagger            |
| 2019-07-01  | Default (false)     | No Swagger            |
| 2019-08-01  | Default (false)     | No Swagger            |
| 2019-09-01  | Default (false)     | No Swagger            |
| 2019-11-01  | Default (false)     | No Swagger            |
| 2020-03-01  | Default (false)     | No Swagger            |

### \$.properties.loadBalancingRules[*].properties.backendPort

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | No Swagger            |

### \$.properties.loadBalancingRules[*].properties.disableOutboundSNAT

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | No Swagger            |

### \$.properties.loadBalancingRules[*].properties.disableOutboundSnat

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.loadBalancingRules[*].properties.enableDestinationServiceEndpoint

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-11-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.loadBalancingRules[*].properties.enableFloatingIP

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Default (false)     | No Swagger            |
| 2015-06-15         | Default (false)     | No Swagger            |
| 2017-08-01         | Default (false)     | No Swagger            |
| 2017-09-01         | Default (false)     | No Swagger            |
| 2018-02-01         | Default (false)     | No Swagger            |
| 2018-04-01         | Default (false)     | No Swagger            |
| 2018-07-01         | Default (false)     | No Swagger            |
| 2018-08-01         | Default (false)     | No Swagger            |
| 2018-11-01         | Default (false)     | No Swagger            |
| 2019-04-01         | Default (false)     | No Swagger            |
| 2019-06-01         | Default (false)     | No Swagger            |
| 2019-09-01         | Default (false)     | No Swagger            |
| 2019-11-01         | Default (false)     | No Swagger            |

### \$.properties.loadBalancingRules[*].properties.enableTcpReset

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Default (false)     | No Swagger            |
| 2018-08-01  | Default (false)     | No Swagger            |
| 2018-10-01  | Default (false)     | No Swagger            |
| 2018-11-01  | Default (false)     | No Swagger            |
| 2018-12-01  | Default (false)     | No Swagger            |
| 2019-04-01  | Default (false)     | No Swagger            |
| 2019-06-01  | Default (false)     | No Swagger            |
| 2019-09-01  | Default (false)     | No Swagger            |
| 2019-11-01  | Default (false)     | No Swagger            |

### \$.properties.loadBalancingRules[*].properties.frontendIPConfiguration.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-12-01  | Unknown             | No Swagger            |

### \$.properties.loadBalancingRules[*].properties.frontendIPConfiguration.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-12-01  | Unknown             | No Swagger            |

### \$.properties.loadBalancingRules[*].properties.frontendPort

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | No Swagger            |

### \$.properties.loadBalancingRules[*].properties.idleTimeoutInMinutes

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Default (4)         | No Swagger            |
| 2015-06-15         | Default (4)         | No Swagger            |
| 2016-09-01         | Default (4)         | No Swagger            |
| 2017-08-01         | Default (4)         | No Swagger            |
| 2018-07-01         | Default (4)         | No Swagger            |
| 2018-10-01         | Default (4)         | No Swagger            |
| 2018-12-01         | Default (4)         | No Swagger            |
| 2019-06-01         | Default (4)         | No Swagger            |

### \$.properties.loadBalancingRules[*].properties.loadDistribution

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Default ("Default") | No Swagger            |
| 2015-06-15         | Default ("Default") | No Swagger            |
| 2016-03-30         | Default ("Default") | No Swagger            |
| 2016-09-01         | Default ("Default") | No Swagger            |
| 2017-04-01         | Default ("Default") | No Swagger            |
| 2017-06-01         | Default ("Default") | No Swagger            |
| 2017-08-01         | Default ("Default") | No Swagger            |
| 2017-09-01         | Default ("Default") | No Swagger            |
| 2017-10-01         | Default ("Default") | No Swagger            |
| 2018-01-01         | Default ("Default") | No Swagger            |
| 2018-04-01         | Default ("Default") | No Swagger            |
| 2018-06-01         | Default ("Default") | No Swagger            |
| 2018-07-01         | Default ("Default") | No Swagger            |
| 2018-08-01         | Default ("Default") | No Swagger            |
| 2018-10-01         | Default ("Default") | No Swagger            |
| 2018-11-01         | Default ("Default") | No Swagger            |
| 2018-12-01         | Default ("Default") | No Swagger            |
| 2019-02-01         | Default ("Default") | No Swagger            |
| 2019-04-01         | Default ("Default") | No Swagger            |
| 2019-09-01         | Default ("Default") | No Swagger            |
| 2019-11-01         | Default ("Default") | No Swagger            |

### \$.properties.loadBalancingRules[*].properties.provisioningState

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |

### \$.properties.loadBalancingRules[*].type

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | No Swagger            |

### \$.properties.loadbalancingRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | Read-only             |

### \$.properties.migrationPhase

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.mode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.outboundRules

| API version | Detected noise type | Determined noise type                              |
| ----------- | ------------------- | -------------------------------------------------- |
| 2018-06-01  | Unknown             | No Swagger, Read-only (inheritted from 2018-08-01) |
| 2018-08-01  | Unknown             | Read-only                                          |
| 2018-12-01  | Unknown             | Read-only                                          |
| 2019-07-01  | Unknown             | Read-only                                          |

### \$.properties.outboundRules[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-12-01  | Unknown             | No Swagger            |

### \$.properties.outboundRules[*].etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.outboundRules[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.outboundRules[*].properties.allocatedOutboundPorts

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Default (1024)      | No Swagger            |
| 2018-08-01  | Default (1024)      | No Swagger            |
| 2018-10-01  | Default (1024)      | No Swagger            |
| 2018-11-01  | Default (1024)      | No Swagger            |
| 2019-06-01  | Default (1024)      | No Swagger            |

### \$.properties.outboundRules[*].properties.enableTcpReset

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Default (false)     | No Swagger            |
| 2018-08-01  | Default (false)     | No Swagger            |
| 2018-10-01  | Default (false)     | No Swagger            |
| 2019-07-01  | Default (false)     | No Swagger            |

### \$.properties.outboundRules[*].properties.frontendIPConfigurations[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-12-01  | Unknown             | No Swagger            |

### \$.properties.outboundRules[*].properties.frontendIPConfigurations[*].properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-12-01  | Unknown             | No Swagger            |

### \$.properties.outboundRules[*].properties.idleTimeoutInMinutes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Default (4)         | No Swagger            |
| 2018-08-01  | Default (4)         | No Swagger            |
| 2018-10-01  | Default (4)         | No Swagger            |
| 2018-11-01  | Default (4)         | No Swagger            |

### \$.properties.outboundRules[*].properties.protocol

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.outboundRules[*].properties.provisioningState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.outboundRules[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.probes

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |
| 2016-09-01         | Unknown             | Unknown               |
| 2018-07-01         | Unknown             | Unknown               |
| 2018-10-01         | Unknown             | Unknown               |
| 2019-06-01         | Unknown             | Unknown               |
| 2019-09-01         | Unknown             | Unknown               |

### \$.properties.probes[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.probes[*].etag

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | No Swagger            |

### \$.properties.probes[*].id

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | No Swagger            |

### \$.properties.probes[*].properties.destinationServiceEndpointEnabledRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.probes[*].properties.intervalInSeconds

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Default* (15)       | No Swagger            |
| 2017-11-01  | Default* (15)       | No Swagger            |
| 2018-07-01  | Default* (15)       | No Swagger            |

### \$.properties.probes[*].properties.loadBalancingRules

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |

### \$.properties.probes[*].properties.loadDistribution

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.probes[*].properties.numberOfProbes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-03-01  | Default* (2)        | No Swagger            |
| 2018-07-01  | Default* (2)        | No Swagger            |

### \$.properties.probes[*].properties.provisioningState

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |

### \$.properties.probes[*].type

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | No Swagger            |

### \$.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | Unknown               |
| 2017-09-01  | Unknown             | Unknown               |
| 2017-10-01  | Unknown             | Unknown               |
| 2017-11-01  | Unknown             | Unknown               |
| 2018-01-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-04-01  | Unknown             | Unknown               |
| 2018-06-01  | Unknown             | Unknown               |
| 2018-08-01  | Unknown             | Unknown               |
| 2018-10-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2018-12-01  | Unknown             | Unknown               |
| 2019-02-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-07-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Unknown               |
| 2019-11-01  | Unknown             | Unknown               |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.sku.tier

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |
| 2016-03-30         | Unknown             | Unknown               |
| 2017-08-01         | Unknown             | Unknown               |
| 2018-01-01         | Unknown             | Unknown               |
| 2018-08-01         | Unknown             | Unknown               |
| 2019-07-01         | Unknown             | Unknown               |
| 2019-09-01         | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | Unknown               |
| 2017-10-01  | Unknown             | Unknown               |
| 2018-06-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-06-01  | Unknown             | Unknown               |

## localNetworkGateways

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.bgpSettings.peerWeight

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Default* (0)        | Unknown               |

## natGateways

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.idleTimeoutInMinutes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Default* (4)        | No Swagger            |

## networkInterfaces

![42.54%25](https://img.shields.io/badge/42.54%25-%E2%98%85★★★%E2%98%86☆☆☆☆☆-yellow)

### \$.properties.NetworkSecurityGroup

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Unknown               |

### \$.properties.dnsSettings

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-12-01-preview | Unknown             | No Swagger            |
| 2015-05-01-preview | Unknown             | Unknown               |
| 2015-06-15         | Unknown             | Unknown               |
| 2016-03-30         | Unknown             | Unknown               |
| 2016-06-01         | Unknown             | Unknown               |
| 2016-09-01         | Unknown             | Unknown               |
| 2016-10-01         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | Unknown               |
| 2017-04-01         | Unknown             | No Swagger            |
| 2017-06-01         | Unknown             | Unknown               |
| 2017-08-01         | Unknown             | Unknown               |
| 2017-09-01         | Unknown             | Unknown               |
| 2017-10-01         | Unknown             | Unknown               |
| 2017-11-01         | Unknown             | Unknown               |
| 2018-01-01         | Unknown             | Unknown               |
| 2018-02-01         | Unknown             | Unknown               |
| 2018-03-01         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | Unknown               |
| 2018-05-01         | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | Unknown               |
| 2018-07-01         | Unknown             | Unknown               |
| 2018-08-01         | Unknown             | Unknown               |
| 2018-10-01         | Unknown             | Unknown               |
| 2018-11-01         | Unknown             | Unknown               |
| 2018-12-01         | Unknown             | Unknown               |
| 2019-02-01         | Unknown             | Unknown               |
| 2019-04-01         | Unknown             | Unknown               |
| 2019-06-01         | Unknown             | Unknown               |
| 2019-07-01         | Unknown             | Unknown               |
| 2019-08-01         | Unknown             | Unknown               |
| 2019-09-01         | Unknown             | Unknown               |
| 2019-11-01         | Unknown             | Unknown               |

### \$.properties.dnsSettings.appliedDnsServers

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Read-only             |
| 2016-03-30  | Unknown             | Read-only             |
| 2016-09-01  | Unknown             | Read-only             |
| 2017-03-01  | Unknown             | Read-only             |
| 2017-09-01  | Unknown             | Read-only             |
| 2017-10-01  | Unknown             | Read-only             |
| 2017-11-01  | Unknown             | Read-only             |
| 2018-01-01  | Unknown             | Read-only             |
| 2018-11-01  | Unknown             | Read-only             |
| 2019-02-01  | Unknown             | Read-only             |
| 2019-07-01  | Unknown             | Read-only             |
| 2019-08-01  | Unknown             | Read-only             |

### \$.properties.dnsSettings.appliedDnsServers[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.dnsSettings.dnsServers[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | No Swagger            |

### \$.properties.dnsSettings.internalDomainNameSuffix

| API version | Detected noise type | Determined noise type                              |
| ----------- | ------------------- | -------------------------------------------------- |
| 2015-06-15  | Unknown             | No Swagger, Read-only (inheritted from 2016-03-30) |
| 2016-03-30  | Unknown             | Read-only                                          |
| 2016-09-01  | Unknown             | Read-only                                          |
| 2017-03-01  | Unknown             | Read-only                                          |
| 2017-09-01  | Unknown             | Read-only                                          |
| 2017-10-01  | Unknown             | Read-only                                          |
| 2017-11-01  | Unknown             | Read-only                                          |
| 2018-01-01  | Unknown             | Read-only                                          |
| 2018-02-01  | Unknown             | Read-only                                          |
| 2018-04-01  | Unknown             | Read-only                                          |
| 2018-06-01  | Unknown             | Read-only                                          |
| 2018-10-01  | Unknown             | Read-only                                          |
| 2018-11-01  | Unknown             | Read-only                                          |
| 2018-12-01  | Unknown             | Read-only                                          |
| 2019-02-01  | Unknown             | Read-only                                          |
| 2019-07-01  | Unknown             | Read-only                                          |
| 2019-08-01  | Unknown             | Read-only                                          |

### \$.properties.dnsSettings.internalFqdn

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Read-only             |

### \$.properties.dnsSettings.migratedTenantIdnsFqdnSuffix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.enableAcceleratedNetworking

| API version | Detected noise type | Determined noise type                                    |
| ----------- | ------------------- | -------------------------------------------------------- |
| 2016-09-01  | Unknown             | Default (false)                                          |
| 2017-03-01  | Unknown             | Default (false)                                          |
| 2017-04-01  | Unknown             | No Swagger, Default (false) (inheritted from 2017-06-01) |
| 2017-06-01  | Unknown             | Default (false)                                          |
| 2017-08-01  | Unknown             | Default (false)                                          |
| 2017-09-01  | Unknown             | Default (false)                                          |
| 2017-10-01  | Unknown             | Default (false)                                          |
| 2017-11-01  | Unknown             | Default (false)                                          |
| 2018-01-01  | Unknown             | Default (false)                                          |
| 2018-02-01  | Unknown             | Default (false)                                          |
| 2018-03-01  | Unknown             | No Swagger, Default (false) (inheritted from 2018-04-01) |
| 2018-04-01  | Unknown             | Default (false)                                          |
| 2018-06-01  | Unknown             | Default (false)                                          |
| 2018-08-01  | Unknown             | Default (false)                                          |
| 2018-10-01  | Unknown             | Default (false)                                          |
| 2018-11-01  | Unknown             | Default (false)                                          |
| 2018-12-01  | Unknown             | Default (false)                                          |
| 2019-02-01  | Unknown             | Default (false)                                          |
| 2019-04-01  | Unknown             | Default (false)                                          |
| 2019-06-01  | Unknown             | Default (false)                                          |
| 2019-07-01  | Unknown             | Default (false)                                          |
| 2019-08-01  | Unknown             | Default (false)                                          |
| 2019-09-01  | Unknown             | Default (false)                                          |
| 2019-11-01  | Unknown             | Default (false)                                          |

### \$.properties.enableIPForwarding

| API version        | Detected noise type | Determined noise type                                            |
| ------------------ | ------------------- | ---------------------------------------------------------------- |
| 2014-12-01-preview | Unknown             | No Swagger, Default (false) (inheritted from 2015-05-01-preview) |
| 2015-05-01-preview | Unknown             | Default (false)                                                  |
| 2015-06-15         | Unknown             | Default (false)                                                  |
| 2016-03-30         | Unknown             | Default (false)                                                  |
| 2016-06-01         | Unknown             | Default (false)                                                  |
| 2016-09-01         | Unknown             | Default (false)                                                  |
| 2017-03-01         | Unknown             | Default (false)                                                  |
| 2017-04-01         | Unknown             | No Swagger, Default (false) (inheritted from 2017-06-01)         |
| 2017-06-01         | Unknown             | Default (false)                                                  |
| 2017-08-01         | Unknown             | Default (false)                                                  |
| 2017-09-01         | Unknown             | Default (false)                                                  |
| 2017-10-01         | Unknown             | Default (false)                                                  |
| 2017-11-01         | Unknown             | Default (false)                                                  |
| 2018-01-01         | Unknown             | Default (false)                                                  |
| 2018-02-01         | Unknown             | Default (false)                                                  |
| 2018-03-01         | Unknown             | No Swagger, Default (false) (inheritted from 2018-04-01)         |
| 2018-04-01         | Unknown             | Default (false)                                                  |
| 2018-06-01         | Unknown             | Default (false)                                                  |
| 2018-07-01         | Unknown             | Default (false)                                                  |
| 2018-08-01         | Unknown             | Default (false)                                                  |
| 2018-10-01         | Unknown             | Default (false)                                                  |
| 2018-11-01         | Unknown             | Default (false)                                                  |
| 2018-12-01         | Unknown             | Default (false)                                                  |
| 2019-02-01         | Unknown             | Default (false)                                                  |
| 2019-04-01         | Unknown             | Default (false)                                                  |
| 2019-06-01         | Unknown             | Default (false)                                                  |
| 2019-07-01         | Unknown             | Default (false)                                                  |
| 2019-08-01         | Unknown             | Default (false)                                                  |
| 2019-09-01         | Unknown             | Default (false)                                                  |
| 2019-11-01         | Unknown             | Default (false)                                                  |

### \$.properties.ipConfigurations

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-12-01-preview | Unknown             | No Swagger            |
| 2015-05-01-preview | Unknown             | Unknown               |
| 2015-06-15         | Unknown             | Unknown               |
| 2016-03-30         | Unknown             | Unknown               |
| 2016-09-01         | Unknown             | Unknown               |
| 2017-03-01         | Unknown             | Unknown               |
| 2017-04-01         | Unknown             | No Swagger            |
| 2017-06-01         | Unknown             | Unknown               |
| 2017-10-01         | Unknown             | Unknown               |
| 2017-11-01         | Unknown             | Unknown               |
| 2018-01-01         | Unknown             | Unknown               |
| 2018-02-01         | Unknown             | Unknown               |
| 2018-03-01         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | Unknown               |
| 2018-08-01         | Unknown             | Unknown               |
| 2018-10-01         | Unknown             | Unknown               |
| 2018-11-01         | Unknown             | Unknown               |
| 2018-12-01         | Unknown             | Unknown               |
| 2019-02-01         | Unknown             | Unknown               |
| 2019-04-01         | Unknown             | Unknown               |
| 2019-07-01         | Unknown             | Unknown               |
| 2019-09-01         | Unknown             | Unknown               |
| 2019-11-01         | Unknown             | Unknown               |

### \$.properties.ipConfigurations[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].Name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].etag

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-12-01-preview | Unknown             | No Swagger            |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-06-01         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2016-10-01         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].id

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-12-01-preview | Unknown             | No Swagger            |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-06-01         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2016-10-01         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].loadBalancerBackendAddressPools

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.Primary

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.PrivateIpAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.PrivateIpAddressVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.PrivateIpAllocationMethod

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.Subnet

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.loadBalancerBackendAddressPools

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2018-08-01         | Unknown             | No Swagger            |
| 2019-07-01         | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.loadBalancerInboundNatRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.loadBalancerInboundNatRules[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.primary

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-12-01-preview | Unknown             | No Swagger            |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-06-01         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2016-10-01         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | No Swagger            |
| 2017-04-01         | Unknown             | No Swagger            |
| 2017-06-01         | Unknown             | No Swagger            |
| 2017-08-01         | Unknown             | No Swagger            |
| 2017-09-01         | Unknown             | No Swagger            |
| 2017-10-01         | Unknown             | No Swagger            |
| 2017-11-01         | Unknown             | No Swagger            |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-02-01         | Unknown             | No Swagger            |
| 2018-03-01         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2018-05-01         | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |
| 2018-07-01         | Unknown             | No Swagger            |
| 2018-08-01         | Unknown             | No Swagger            |
| 2018-10-01         | Unknown             | No Swagger            |
| 2018-11-01         | Unknown             | No Swagger            |
| 2018-12-01         | Unknown             | No Swagger            |
| 2019-02-01         | Unknown             | No Swagger            |
| 2019-04-01         | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |
| 2019-07-01         | Unknown             | No Swagger            |
| 2019-08-01         | Unknown             | No Swagger            |
| 2019-09-01         | Unknown             | No Swagger            |
| 2019-11-01         | Unknown             | No Swagger            |
| 2020-03-01         | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.privateIPAddress

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-12-01-preview | Unknown             | No Swagger            |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-06-01         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2016-10-01         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | No Swagger            |
| 2017-04-01         | Unknown             | No Swagger            |
| 2017-06-01         | Unknown             | No Swagger            |
| 2017-08-01         | Unknown             | No Swagger            |
| 2017-09-01         | Unknown             | No Swagger            |
| 2017-10-01         | Unknown             | No Swagger            |
| 2017-11-01         | Unknown             | No Swagger            |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-02-01         | Unknown             | No Swagger            |
| 2018-03-01         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |
| 2018-07-01         | Unknown             | No Swagger            |
| 2018-08-01         | Unknown             | No Swagger            |
| 2018-10-01         | Unknown             | No Swagger            |
| 2018-11-01         | Unknown             | No Swagger            |
| 2018-12-01         | Unknown             | No Swagger            |
| 2019-02-01         | Unknown             | No Swagger            |
| 2019-04-01         | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |
| 2019-07-01         | Unknown             | No Swagger            |
| 2019-08-01         | Unknown             | No Swagger            |
| 2019-09-01         | Unknown             | No Swagger            |
| 2019-11-01         | Unknown             | No Swagger            |
| 2020-03-01         | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.privateIPAddressVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2016-06-01  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | No Swagger            |
| 2016-10-01  | Unknown             | No Swagger            |
| 2017-03-01  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-08-01  | Unknown             | No Swagger            |
| 2017-09-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2017-11-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-05-01  | Unknown             | No Swagger            |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.privateIPAllocationMethod

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | No Swagger            |
| 2017-06-01         | Unknown             | No Swagger            |
| 2017-08-01         | Unknown             | No Swagger            |
| 2017-09-01         | Unknown             | No Swagger            |
| 2017-10-01         | Unknown             | No Swagger            |
| 2018-02-01         | Unknown             | No Swagger            |
| 2018-03-01         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2018-07-01         | Unknown             | No Swagger            |
| 2018-08-01         | Unknown             | No Swagger            |
| 2018-11-01         | Unknown             | No Swagger            |
| 2018-12-01         | Unknown             | No Swagger            |
| 2019-04-01         | Unknown             | No Swagger            |
| 2019-07-01         | Unknown             | No Swagger            |
| 2019-09-01         | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.privateIpAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.privateIpAddressVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.privateipaddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.provisioningState

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-12-01-preview | Unknown             | No Swagger            |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-06-01         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2016-10-01         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.publicIPAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | No Swagger            |
| 2017-03-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.publicIPAddress.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.publicIpAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-09-01  | Unknown             | No Swagger            |
| 2017-03-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.subnet

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.subnet.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | No Swagger            |
| 2017-03-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].type

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-12-01-preview | Unknown             | No Swagger            |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-06-01         | Unknown             | No Swagger            |
| 2016-09-01         | Unknown             | No Swagger            |
| 2016-10-01         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | No Swagger            |

### \$.properties.macAddress

| API version        | Detected noise type | Determined noise type                                      |
| ------------------ | ------------------- | ---------------------------------------------------------- |
| 2014-12-01-preview | Unknown             | No Swagger, Read-only (inheritted from 2015-05-01-preview) |
| 2015-05-01-preview | Unknown             | Read-only                                                  |
| 2015-06-15         | Unknown             | Read-only                                                  |
| 2016-03-30         | Unknown             | Read-only                                                  |
| 2016-06-01         | Unknown             | Read-only                                                  |
| 2016-09-01         | Unknown             | Read-only                                                  |
| 2016-10-01         | Unknown             | No Swagger, Read-only (inheritted from 2017-03-01)         |
| 2017-03-01         | Unknown             | Read-only                                                  |
| 2017-04-01         | Unknown             | No Swagger, Read-only (inheritted from 2017-06-01)         |
| 2017-06-01         | Unknown             | Read-only                                                  |
| 2017-08-01         | Unknown             | Read-only                                                  |
| 2017-09-01         | Unknown             | Read-only                                                  |
| 2017-10-01         | Unknown             | Read-only                                                  |
| 2017-11-01         | Unknown             | Read-only                                                  |
| 2018-01-01         | Unknown             | Read-only                                                  |
| 2018-02-01         | Unknown             | Read-only                                                  |
| 2018-03-01         | Unknown             | No Swagger, Read-only (inheritted from 2018-04-01)         |
| 2018-04-01         | Unknown             | Read-only                                                  |
| 2018-05-01         | Unknown             | No Swagger, Read-only (inheritted from 2018-06-01)         |
| 2018-06-01         | Unknown             | Read-only                                                  |
| 2018-07-01         | Unknown             | Read-only                                                  |
| 2018-08-01         | Unknown             | Read-only                                                  |
| 2018-10-01         | Unknown             | Read-only                                                  |
| 2018-11-01         | Unknown             | Read-only                                                  |
| 2018-12-01         | Unknown             | Read-only                                                  |
| 2019-02-01         | Unknown             | Read-only                                                  |
| 2019-04-01         | Unknown             | Read-only                                                  |
| 2019-06-01         | Unknown             | Read-only                                                  |
| 2019-07-01         | Unknown             | Read-only                                                  |
| 2019-08-01         | Unknown             | Read-only                                                  |

### \$.properties.migrationPhase

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.networkSecurityGroup

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |
| 2015-06-15         | Unknown             | Unknown               |

### \$.properties.networkSecurityGroup.id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | Unknown               |

### \$.properties.nicType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.primary

| API version        | Detected noise type | Determined noise type                                      |
| ------------------ | ------------------- | ---------------------------------------------------------- |
| 2014-12-01-preview | Unknown             | No Swagger, Read-only (inheritted from 2015-05-01-preview) |
| 2015-05-01-preview | Unknown             | Read-only                                                  |
| 2015-06-15         | Unknown             | Read-only                                                  |
| 2016-03-30         | Unknown             | Read-only                                                  |
| 2016-06-01         | Unknown             | Read-only                                                  |
| 2016-09-01         | Unknown             | Read-only                                                  |
| 2017-03-01         | Unknown             | Read-only                                                  |
| 2017-04-01         | Unknown             | No Swagger, Read-only (inheritted from 2017-06-01)         |
| 2017-06-01         | Unknown             | Read-only                                                  |
| 2017-08-01         | Unknown             | Read-only                                                  |
| 2017-09-01         | Unknown             | Read-only                                                  |
| 2017-10-01         | Unknown             | Read-only                                                  |
| 2017-11-01         | Unknown             | Read-only                                                  |
| 2018-01-01         | Unknown             | Read-only                                                  |
| 2018-02-01         | Unknown             | Read-only                                                  |
| 2018-03-01         | Unknown             | No Swagger, Read-only (inheritted from 2018-04-01)         |
| 2018-04-01         | Unknown             | Read-only                                                  |
| 2018-06-01         | Unknown             | Read-only                                                  |
| 2018-07-01         | Unknown             | Read-only                                                  |
| 2018-08-01         | Unknown             | Read-only                                                  |
| 2018-10-01         | Unknown             | Read-only                                                  |
| 2018-11-01         | Unknown             | Read-only                                                  |
| 2018-12-01         | Unknown             | Read-only                                                  |
| 2019-02-01         | Unknown             | Read-only                                                  |
| 2019-04-01         | Unknown             | Read-only                                                  |
| 2019-06-01         | Unknown             | Read-only                                                  |
| 2019-07-01         | Unknown             | Read-only                                                  |
| 2019-08-01         | Unknown             | Read-only                                                  |

### \$.properties.virtualMachine

| API version        | Detected noise type | Determined noise type                                      |
| ------------------ | ------------------- | ---------------------------------------------------------- |
| 2014-12-01-preview | Unknown             | No Swagger, Read-only (inheritted from 2015-05-01-preview) |
| 2015-05-01-preview | Unknown             | Read-only                                                  |
| 2015-06-15         | Unknown             | Read-only                                                  |
| 2016-03-30         | Unknown             | Read-only                                                  |
| 2016-06-01         | Unknown             | Read-only                                                  |
| 2016-09-01         | Unknown             | Read-only                                                  |
| 2016-10-01         | Unknown             | No Swagger, Read-only (inheritted from 2017-03-01)         |
| 2017-03-01         | Unknown             | Read-only                                                  |
| 2017-04-01         | Unknown             | No Swagger, Read-only (inheritted from 2017-06-01)         |
| 2017-06-01         | Unknown             | Read-only                                                  |
| 2017-08-01         | Unknown             | Read-only                                                  |
| 2017-09-01         | Unknown             | Read-only                                                  |
| 2017-10-01         | Unknown             | Read-only                                                  |
| 2017-11-01         | Unknown             | Read-only                                                  |
| 2018-01-01         | Unknown             | Read-only                                                  |
| 2018-02-01         | Unknown             | Read-only                                                  |
| 2018-03-01         | Unknown             | No Swagger, Read-only (inheritted from 2018-04-01)         |
| 2018-04-01         | Unknown             | Read-only                                                  |
| 2018-05-01         | Unknown             | No Swagger, Read-only (inheritted from 2018-06-01)         |
| 2018-06-01         | Unknown             | Read-only                                                  |
| 2018-07-01         | Unknown             | Read-only                                                  |

### \$.tags

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2015-05-01-preview | Unknown             | Put-as-patch                                          |
| 2015-06-15         | Unknown             | Put-as-patch                                          |
| 2016-03-30         | Unknown             | Put-as-patch                                          |
| 2016-06-01         | Unknown             | Put-as-patch                                          |
| 2016-09-01         | Unknown             | Put-as-patch                                          |
| 2017-04-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2017-10-01) |
| 2017-10-01         | Unknown             | Put-as-patch                                          |
| 2018-04-01         | Unknown             | Put-as-patch                                          |
| 2018-08-01         | Unknown             | Put-as-patch                                          |
| 2018-11-01         | Unknown             | Put-as-patch                                          |
| 2019-06-01         | Unknown             | Put-as-patch                                          |
| 2019-07-01         | Unknown             | Put-as-patch                                          |
| 2019-09-01         | Unknown             | Put-as-patch                                          |

### \$.tags.*

| API version        | Detected noise type | Determined noise type                                 |
| ------------------ | ------------------- | ----------------------------------------------------- |
| 2015-05-01-preview | Unknown             | Put-as-patch                                          |
| 2015-06-15         | Unknown             | Put-as-patch                                          |
| 2016-09-01         | Unknown             | Put-as-patch                                          |
| 2017-04-01         | Unknown             | No Swagger, Put-as-patch (inheritted from 2017-10-01) |
| 2017-10-01         | Unknown             | Put-as-patch                                          |
| 2018-04-01         | Unknown             | Put-as-patch                                          |
| 2018-06-01         | Unknown             | Put-as-patch                                          |
| 2018-08-01         | Unknown             | Put-as-patch                                          |
| 2018-11-01         | Unknown             | Put-as-patch                                          |
| 2018-12-01         | Unknown             | Put-as-patch                                          |
| 2019-04-01         | Unknown             | Put-as-patch                                          |
| 2019-06-01         | Unknown             | Put-as-patch                                          |
| 2019-07-01         | Unknown             | Put-as-patch                                          |
| 2019-09-01         | Unknown             | Put-as-patch                                          |
| 2019-11-01         | Unknown             | Put-as-patch                                          |

## networkProfiles

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.containerNetworkInterfaceConfigurations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.containerNetworkInterfaceConfigurations[*].etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.containerNetworkInterfaceConfigurations[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.containerNetworkInterfaceConfigurations[*].properties.containerNetworkInterfaces

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.containerNetworkInterfaceConfigurations[*].properties.ipConfigurations[*].etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.containerNetworkInterfaceConfigurations[*].properties.ipConfigurations[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.containerNetworkInterfaces

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |

## networkSecurityGroups/securityRules

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | Unknown               |
| 2018-06-01  | Unknown             | Unknown               |
| 2018-07-01  | Unknown             | Unknown               |
| 2018-08-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |

### \$.properties.destinationAddressPrefix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | Unknown               |

### \$.properties.priority

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | Unknown               |

### \$.properties.sourceAddressPrefix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-11-01  | Unknown             | Unknown               |

### \$.properties.sourceAddressPrefixes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Unknown               |

### \$.properties.sourceAddressPrefixes[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |

## networkSecurityGroups

![4.51%25](https://img.shields.io/badge/4.51%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Unknown               |
| 2016-03-30  | Unknown             | Unknown               |
| 2018-01-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | Unknown               |
| 2018-08-01  | Unknown             | Unknown               |
| 2019-02-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-06-01  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Unknown               |
| 2019-11-01  | Unknown             | Unknown               |

### \$.properties.flowLogs

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.networkInterfaces

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Read-only             |
| 2015-06-15         | Unknown             | Read-only             |
| 2016-03-30         | Unknown             | Read-only             |

### \$.properties.secrityRules[*].properties.destinationAddressPrefix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.securityRules

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | Unknown               |
| 2017-08-01  | Unknown             | Unknown               |
| 2018-06-01  | Unknown             | Unknown               |
| 2018-08-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-02-01  | Unknown             | Unknown               |
| 2019-07-01  | Unknown             | Unknown               |

### \$.properties.securityRules[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-09-01  | Unknown             | No Swagger            |
| 2017-03-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-08-01  | Unknown             | No Swagger            |
| 2017-09-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.securityRules[*].Name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | No Swagger            |

### \$.properties.securityRules[*].Properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | No Swagger            |

### \$.properties.securityRules[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2017-08-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.properties.securityRules[*].properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | No Swagger            |

### \$.properties.securityRules[*].properties.access

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.securityRules[*].properties.description

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.securityRules[*].properties.destinationAddressPrefix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.securityRules[*].properties.destinationAddressPrefixes[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |

### \$.properties.securityRules[*].properties.destinationApplicationSecurityGroups[*].location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.securityRules[*].properties.destinationPortRange

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.properties.securityRules[*].properties.destinationPortRanges

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.properties.securityRules[*].properties.destinationPortRanges[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |

### \$.properties.securityRules[*].properties.priority

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.securityRules[*].properties.protocol

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.securityRules[*].properties.sourceAddressPrefix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.securityRules[*].properties.sourceAddressPrefixes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.properties.securityRules[*].properties.sourceAddressPrefixes[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |

### \$.properties.securityRules[*].properties.sourceApplicationSecurityGroups[*].location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.subnets

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Read-only             |
| 2015-06-15         | Unknown             | Read-only             |
| 2016-03-30         | Unknown             | Read-only             |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |
| 2015-06-15         | Unknown             | Unknown               |
| 2016-09-01         | Unknown             | Unknown               |
| 2017-06-01         | Unknown             | Unknown               |
| 2017-10-01         | Unknown             | Unknown               |
| 2018-02-01         | Unknown             | Unknown               |
| 2018-03-01         | Unknown             | No Swagger            |
| 2018-08-01         | Unknown             | Unknown               |
| 2018-12-01         | Unknown             | Unknown               |
| 2019-02-01         | Unknown             | Unknown               |
| 2019-04-01         | Unknown             | Unknown               |
| 2019-07-01         | Unknown             | Unknown               |
| 2019-08-01         | Unknown             | Unknown               |
| 2019-09-01         | Unknown             | Unknown               |
| 2019-11-01         | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | Unknown               |
| 2017-09-01  | Unknown             | Unknown               |
| 2017-10-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | Unknown               |
| 2018-08-01  | Unknown             | Unknown               |
| 2019-02-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-06-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Unknown               |
| 2019-11-01  | Unknown             | Unknown               |

## networkWatchers/connectionMonitors

![50.00%25](https://img.shields.io/badge/50.00%25-%E2%98%85★★★★%E2%98%86☆☆☆☆-yellow)

### \$.properties.resourceGuid

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | Read-only             |

### \$.properties.source.port

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Default* (0)        | Unknown               |

## networkWatchers/flowLogs

![22.22%25](https://img.shields.io/badge/22.22%25-%E2%98%85★%E2%98%86☆☆☆☆☆☆☆-orange)

### \$.properties.flowAnalyticsConfiguration.networkWatcherFlowAnalyticsConfiguration.workspaceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-11-01  | Unknown             | Unknown               |

### \$.properties.flowAnalyticsConfiguration.networkWatcherFlowAnalyticsConfiguration.workspaceRegion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-11-01  | Unknown             | Unknown               |

### \$.properties.format.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Default* ("JSON")   | No Swagger            |
| 2019-11-01  | Default* ("JSON")   | Unknown               |

### \$.properties.format.version

| API version | Detected noise type | Determined noise type                                |
| ----------- | ------------------- | ---------------------------------------------------- |
| 2019-09-01  | Default* (1)        | No Swagger, Default (0) (inheritted from 2019-11-01) |
| 2019-11-01  | Default* (1)        | Default (0)                                          |

### \$.properties.storageId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-11-01  | Unknown             | Unknown               |

### \$.properties.targetResourceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-11-01  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-11-01  | Unknown             | Unknown               |

## networkWatchers

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-07-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-07-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Unknown             | Unknown               |

## p2sVpnGateways

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.p2SConnectionConfigurations[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.p2SConnectionConfigurations[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.vpnServerConfigurationLocation

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-11-01  | Unknown             | No Swagger            |

## privateDnsZones/a

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-09-01  | Unknown             | No Swagger            |

### \$.properties.aRecords[*].ipv4Address

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-09-01  | Unknown             | No Swagger            |

### \$.properties.copy

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-09-01  | Unknown             | No Swagger            |

## privateDnsZones/virtualNetworkLinks

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-09-01  | Unknown             | Unknown               |

## privateDnsZones

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-09-01  | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-09-01  | Unknown             | Unknown               |

## privateEndpoints

![17.65%25](https://img.shields.io/badge/17.65%25-%E2%98%85★%E2%98%86☆☆☆☆☆☆☆-orange)

### \$.properties.manualPrivateLinkServiceConnections

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |

### \$.properties.manualPrivateLinkServiceConnections[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.manualPrivateLinkServiceConnections[*].properties.privateLinkServiceConnectionState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.privateLinkServiceConnections

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | Unknown               |

### \$.properties.privateLinkServiceConnections[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.privateLinkServiceConnections[*].properties.privateLinkServiceConnectionState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.resourceGuid

| API version | Detected noise type | Determined noise type                              |
| ----------- | ------------------- | -------------------------------------------------- |
| 2019-02-01  | Unknown             | No Swagger, Read-only (inheritted from 2019-04-01) |
| 2019-04-01  | Unknown             | Read-only                                          |
| 2019-07-01  | Unknown             | Read-only                                          |

### \$.properties.subnet.name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Unknown               |

## privateLinkServices

![23.81%25](https://img.shields.io/badge/23.81%25-%E2%98%85★%E2%98%86☆☆☆☆☆☆☆-orange)

### \$.properties.enableProxyProtocol

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.primary

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Default (true)      | No Swagger            |
| 2019-04-01  | Default (true)      | No Swagger            |
| 2019-06-01  | Default (true)      | No Swagger            |

### \$.properties.ipConfigurations[*].properties.privateIPAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.privateIPAddressVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Default ("IPv4")    | No Swagger            |
| 2019-09-01  | Default ("IPv4")    | No Swagger            |

### \$.properties.privateEndpointConnections

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |

### \$.properties.resourceGuid

| API version | Detected noise type | Determined noise type                              |
| ----------- | ------------------- | -------------------------------------------------- |
| 2019-02-01  | Unknown             | No Swagger, Read-only (inheritted from 2019-04-01) |
| 2019-04-01  | Unknown             | Read-only                                          |
| 2019-06-01  | Unknown             | Read-only                                          |
| 2019-07-01  | Unknown             | Read-only                                          |
| 2019-09-01  | Unknown             | Read-only                                          |

## publicIpAddresses

![64.17%25](https://img.shields.io/badge/64.17%25-%E2%98%85★★★★★%E2%98%86☆☆☆-yellowgreen)

### \$.properties.dnsSettings

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |
| 2015-06-15         | Unknown             | Unknown               |
| 2016-03-30         | Unknown             | Unknown               |
| 2017-03-01         | Unknown             | Unknown               |
| 2017-04-01         | Unknown             | No Swagger            |
| 2017-06-01         | Unknown             | Unknown               |
| 2017-08-01         | Unknown             | Unknown               |
| 2017-11-01         | Unknown             | Unknown               |
| 2018-01-01         | Unknown             | Unknown               |
| 2018-08-01         | Unknown             | Unknown               |
| 2018-11-01         | Unknown             | Unknown               |
| 2019-02-01         | Unknown             | Unknown               |
| 2019-04-01         | Unknown             | Unknown               |

### \$.properties.dnsSettings.domainNameLabel

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |
| 2015-06-15         | Unknown             | Unknown               |
| 2018-11-01         | Unknown             | Unknown               |

### \$.properties.dnsSettings.fqdn

| API version        | Detected noise type | Determined noise type                              |
| ------------------ | ------------------- | -------------------------------------------------- |
| 2015-05-01-preview | Unknown             | Read-only                                          |
| 2015-06-15         | Unknown             | Read-only                                          |
| 2016-03-30         | Unknown             | Read-only                                          |
| 2016-09-01         | Unknown             | Read-only                                          |
| 2016-10-01         | Unknown             | No Swagger, Read-only (inheritted from 2017-03-01) |
| 2017-03-01         | Unknown             | Read-only                                          |
| 2017-04-01         | Unknown             | No Swagger, Read-only (inheritted from 2017-06-01) |
| 2017-06-01         | Unknown             | Read-only                                          |
| 2017-08-01         | Unknown             | Read-only                                          |
| 2017-09-01         | Unknown             | Read-only                                          |
| 2017-10-01         | Unknown             | Read-only                                          |
| 2017-11-01         | Unknown             | Read-only                                          |
| 2018-01-01         | Unknown             | Read-only                                          |
| 2018-02-01         | Unknown             | Read-only                                          |
| 2018-03-01         | Unknown             | No Swagger, Read-only (inheritted from 2018-04-01) |
| 2018-04-01         | Unknown             | Read-only                                          |
| 2018-06-01         | Unknown             | Read-only                                          |
| 2018-07-01         | Unknown             | Read-only                                          |
| 2018-08-01         | Unknown             | Read-only                                          |
| 2018-10-01         | Unknown             | Read-only                                          |
| 2018-11-01         | Unknown             | Read-only                                          |
| 2018-12-01         | Unknown             | Read-only                                          |
| 2019-02-01         | Unknown             | Read-only                                          |
| 2019-04-01         | Unknown             | Read-only                                          |
| 2019-06-01         | Unknown             | Read-only                                          |
| 2019-07-01         | Unknown             | Read-only                                          |
| 2019-08-01         | Unknown             | Read-only                                          |
| 2019-09-01         | Unknown             | Read-only                                          |
| 2019-11-01         | Unknown             | Read-only                                          |
| 2020-03-01         | Unknown             | No Swagger                                         |

### \$.properties.dnsSettings.recordId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Read-only             |

### \$.properties.idleTimeoutInMinutes

| API version        | Detected noise type | Determined noise type                                |
| ------------------ | ------------------- | ---------------------------------------------------- |
| 2015-05-01-preview | Default (4)         | Default (4)                                          |
| 2015-06-15         | Default (4)         | Default (4)                                          |
| 2016-03-30         | Default (4)         | Default (4)                                          |
| 2016-09-01         | Default (4)         | Default (4)                                          |
| 2017-03-01         | Default (4)         | Default (4)                                          |
| 2017-04-01         | Default (4)         | No Swagger, Default (4) (inheritted from 2017-06-01) |
| 2017-06-01         | Default (4)         | Default (4)                                          |
| 2017-08-01         | Default (4)         | Default (4)                                          |
| 2017-10-01         | Default (4)         | Default (4)                                          |
| 2018-01-01         | Default (4)         | Default (4)                                          |
| 2018-02-01         | Default (4)         | Default (4)                                          |
| 2018-03-01         | Default (4)         | No Swagger, Default (4) (inheritted from 2018-04-01) |
| 2018-04-01         | Default (4)         | Default (4)                                          |
| 2018-06-01         | Default (4)         | Default (4)                                          |
| 2018-07-01         | Default (4)         | Default (4)                                          |
| 2018-08-01         | Default (4)         | Default (4)                                          |
| 2018-10-01         | Default (4)         | Default (4)                                          |
| 2018-11-01         | Default (4)         | Default (4)                                          |
| 2018-12-01         | Default (4)         | Default (4)                                          |
| 2019-02-01         | Default (4)         | Default (4)                                          |
| 2019-04-01         | Default (4)         | Default (4)                                          |
| 2019-07-01         | Default (4)         | Default (4)                                          |
| 2019-08-01         | Default (4)         | Default (4)                                          |
| 2019-09-01         | Default (4)         | Default (4)                                          |

### \$.properties.ipAddress

| API version        | Detected noise type | Determined noise type                              |
| ------------------ | ------------------- | -------------------------------------------------- |
| 2015-05-01-preview | Unknown             | Read-only                                          |
| 2015-06-15         | Unknown             | Read-only                                          |
| 2016-03-30         | Unknown             | Read-only                                          |
| 2016-09-01         | Unknown             | Read-only                                          |
| 2016-10-01         | Unknown             | No Swagger, Read-only (inheritted from 2017-03-01) |
| 2017-03-01         | Unknown             | Read-only                                          |
| 2017-04-01         | Unknown             | No Swagger, Read-only (inheritted from 2017-06-01) |
| 2017-06-01         | Unknown             | Read-only                                          |
| 2017-08-01         | Unknown             | Read-only                                          |
| 2017-09-01         | Unknown             | Read-only                                          |
| 2017-10-01         | Unknown             | Read-only                                          |
| 2017-11-01         | Unknown             | Read-only                                          |
| 2018-01-01         | Unknown             | Read-only                                          |
| 2018-02-01         | Unknown             | Read-only                                          |
| 2018-03-01         | Unknown             | No Swagger, Read-only (inheritted from 2018-04-01) |
| 2018-04-01         | Unknown             | Read-only                                          |
| 2018-06-01         | Unknown             | Read-only                                          |
| 2018-07-01         | Unknown             | Read-only                                          |
| 2018-08-01         | Unknown             | Read-only                                          |
| 2018-10-01         | Unknown             | Read-only                                          |
| 2018-11-01         | Unknown             | Read-only                                          |
| 2018-12-01         | Unknown             | Read-only                                          |
| 2019-02-01         | Unknown             | Read-only                                          |
| 2019-04-01         | Unknown             | Read-only                                          |
| 2019-06-01         | Unknown             | Read-only                                          |
| 2019-07-01         | Unknown             | Read-only                                          |
| 2019-08-01         | Unknown             | Read-only                                          |
| 2019-09-01         | Unknown             | Read-only                                          |
| 2019-11-01         | Unknown             | Read-only                                          |
| 2020-03-01         | Unknown             | No Swagger                                         |

### \$.properties.ipConfiguration

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Read-only             |
| 2015-06-15         | Unknown             | Read-only             |
| 2016-03-30         | Unknown             | Read-only             |

### \$.properties.ipReservation

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Read-only             |

### \$.properties.migrationPhase

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Read-only             |

### \$.properties.natGateway

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.publicIPAddressVersion

| API version | Detected noise type | Determined noise type                                     |
| ----------- | ------------------- | --------------------------------------------------------- |
| 2016-03-30  | Default ("IPv4")    | Default ("IPv4")                                          |
| 2016-09-01  | Default ("IPv4")    | Default ("IPv4")                                          |
| 2016-10-01  | Default ("IPv4")    | No Swagger, Default ("IPv4") (inheritted from 2017-03-01) |
| 2017-03-01  | Default ("IPv4")    | Default ("IPv4")                                          |
| 2017-04-01  | Default ("IPv4")    | No Swagger, Default ("IPv4") (inheritted from 2017-06-01) |
| 2017-06-01  | Default ("IPv4")    | Default ("IPv4")                                          |
| 2017-08-01  | Default ("IPv4")    | Default ("IPv4")                                          |
| 2017-09-01  | Default ("IPv4")    | Default ("IPv4")                                          |
| 2017-10-01  | Default ("IPv4")    | Default ("IPv4")                                          |
| 2017-11-01  | Default ("IPv4")    | Default ("IPv4")                                          |
| 2018-01-01  | Default ("IPv4")    | Default ("IPv4")                                          |
| 2018-02-01  | Default ("IPv4")    | Default ("IPv4")                                          |
| 2018-03-01  | Default ("IPv4")    | No Swagger, Default ("IPv4") (inheritted from 2018-04-01) |
| 2018-04-01  | Default ("IPv4")    | Default ("IPv4")                                          |
| 2018-06-01  | Default ("IPv4")    | Default ("IPv4")                                          |
| 2018-07-01  | Default ("IPv4")    | Default ("IPv4")                                          |
| 2018-08-01  | Default ("IPv4")    | Default ("IPv4")                                          |
| 2018-10-01  | Default ("IPv4")    | Default ("IPv4")                                          |
| 2018-11-01  | Default ("IPv4")    | Default ("IPv4")                                          |
| 2019-02-01  | Default ("IPv4")    | Default ("IPv4")                                          |
| 2019-04-01  | Default ("IPv4")    | Default ("IPv4")                                          |
| 2019-06-01  | Default ("IPv4")    | Default ("IPv4")                                          |
| 2019-07-01  | Default ("IPv4")    | Default ("IPv4")                                          |
| 2019-09-01  | Default ("IPv4")    | Default ("IPv4")                                          |
| 2019-11-01  | Default ("IPv4")    | Default ("IPv4")                                          |

### \$.properties.publicIPAllocationMethod

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | Default ("Dynamic")   |
| 2018-01-01  | Unknown             | Default ("Dynamic")   |
| 2019-02-01  | Unknown             | Default ("Dynamic")   |

### \$.properties.publicIpAddressVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | Default ("IPv4")      |
| 2017-08-01  | Unknown             | Default ("IPv4")      |
| 2019-02-01  | Unknown             | Default ("IPv4")      |

### \$.properties.usmlName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Read-only             |

### \$.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-08-01  | Unknown             | Unknown               |
| 2017-09-01  | Unknown             | Unknown               |
| 2017-10-01  | Unknown             | Unknown               |
| 2017-11-01  | Unknown             | Unknown               |
| 2018-01-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | Unknown               |
| 2018-06-01  | Unknown             | Unknown               |
| 2018-07-01  | Unknown             | Unknown               |
| 2018-08-01  | Unknown             | Unknown               |
| 2018-10-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2018-12-01  | Unknown             | Unknown               |
| 2019-02-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-06-01  | Unknown             | Unknown               |
| 2019-07-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Unknown               |
| 2019-11-01  | Unknown             | Unknown               |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |
| 2016-03-30         | Unknown             | Unknown               |
| 2016-09-01         | Unknown             | Unknown               |
| 2017-04-01         | Unknown             | No Swagger            |
| 2017-10-01         | Unknown             | Unknown               |
| 2018-01-01         | Unknown             | Unknown               |
| 2018-02-01         | Unknown             | Unknown               |
| 2018-08-01         | Unknown             | Unknown               |
| 2018-11-01         | Unknown             | Unknown               |
| 2019-02-01         | Unknown             | Unknown               |
| 2019-04-01         | Unknown             | Unknown               |
| 2019-07-01         | Unknown             | Unknown               |
| 2019-09-01         | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-08-01  | Unknown             | Unknown               |
| 2017-10-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2019-02-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-06-01  | Unknown             | Unknown               |
| 2019-07-01  | Unknown             | Unknown               |

## publicipprefixes

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.ipPrefix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | Unknown               |
| 2018-08-01  | Unknown             | Unknown               |

### \$.properties.natGateway

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.publicIPAddressVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Unknown             | Unknown               |

### \$.properties.publicIPAddresses

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Unknown             | Unknown               |

### \$.properties.publicIPaddressVersion

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Unknown             | Unknown               |

### \$.sku.tier

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |

## routeFilters

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Unknown               |

## routeTables/routes

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.hasBgpOverride

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Default (false)     | No Swagger            |
| 2019-11-01  | Default (false)     | No Swagger            |

### \$.properties.nextHopIpAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | Unknown               |

## routeTables

![48.21%25](https://img.shields.io/badge/48.21%25-%E2%98%85★★★★%E2%98%86☆☆☆☆-yellow)

### \$.properties

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Unknown               |
| 2018-08-01  | Unknown             | Unknown               |
| 2019-11-01  | Unknown             | Unknown               |

### \$.properties.disableBgpRoutePropagation

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | Default (false)       |
| 2018-01-01  | Unknown             | Default (false)       |
| 2018-02-01  | Unknown             | Default (false)       |
| 2018-06-01  | Unknown             | Default (false)       |
| 2018-11-01  | Unknown             | Default (false)       |
| 2019-02-01  | Unknown             | Default (false)       |
| 2019-04-01  | Unknown             | Default (false)       |
| 2019-09-01  | Unknown             | Default (false)       |

### \$.properties.resourceGuid

| API version | Detected noise type | Determined noise type                              |
| ----------- | ------------------- | -------------------------------------------------- |
| 2015-06-15  | Unknown             | Read-only                                          |
| 2016-03-30  | Unknown             | Read-only                                          |
| 2016-10-01  | Unknown             | No Swagger, Read-only (inheritted from 2017-06-01) |
| 2017-06-01  | Unknown             | Read-only                                          |
| 2017-08-01  | Unknown             | Read-only                                          |
| 2017-10-01  | Unknown             | Read-only                                          |
| 2018-01-01  | Unknown             | Read-only                                          |
| 2018-02-01  | Unknown             | Read-only                                          |
| 2018-04-01  | Unknown             | Read-only                                          |
| 2018-06-01  | Unknown             | Read-only                                          |
| 2018-08-01  | Unknown             | Read-only                                          |
| 2018-10-01  | Unknown             | Read-only                                          |
| 2018-11-01  | Unknown             | Read-only                                          |
| 2019-02-01  | Unknown             | Read-only                                          |
| 2019-04-01  | Unknown             | Read-only                                          |
| 2019-06-01  | Unknown             | Read-only                                          |
| 2019-08-01  | Unknown             | Read-only                                          |
| 2019-09-01  | Unknown             | Read-only                                          |
| 2019-11-01  | Unknown             | Read-only                                          |

### \$.properties.routes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2019-02-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Unknown               |
| 2019-11-01  | Unknown             | Unknown               |

### \$.properties.routes[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.routes[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |

### \$.properties.routes[*].properties.addressPrefix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.properties.routes[*].properties.hasBgpOverride

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Default (false)     | No Swagger            |
| 2019-11-01  | Default (false)     | No Swagger            |

### \$.properties.routes[*].properties.nextHopIpAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.subnets

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Unknown               |
| 2016-03-30  | Unknown             | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Unknown             | Unknown               |
| 2019-02-01  | Unknown             | Unknown               |
| 2019-08-01  | Unknown             | Unknown               |
| 2019-11-01  | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-04-01  | Unknown             | Unknown               |
| 2018-10-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-06-01  | Unknown             | Unknown               |

## trafficManagerProfiles/azureEndpoints

!> No Swagger.

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-11-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.properties.endpointLocation

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-11-01  | Unknown             | No Swagger            |
| 2017-05-01  | Unknown             | No Swagger            |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.properties.endpointMonitorStatus

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-11-01  | Unknown             | No Swagger            |
| 2017-05-01  | Unknown             | No Swagger            |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.properties.priority

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-11-01  | Unknown             | No Swagger            |
| 2017-05-01  | Unknown             | No Swagger            |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.properties.target

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-11-01  | Unknown             | No Swagger            |
| 2017-05-01  | Unknown             | No Swagger            |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.properties.weight

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-11-01  | Unknown             | No Swagger            |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-11-01  | Unknown             | No Swagger            |

## trafficManagerProfiles/externalEndpoints

!> No Swagger.

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-05-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.endpointLocation

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.properties.endpointMonitorStatus

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-05-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.properties.priority

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Default* (1)        | No Swagger            |
| 2018-08-01  | Default* (1)        | No Swagger            |

### \$.properties.target

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.weight

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-05-01  | Default* (1)        | No Swagger            |
| 2018-04-01  | Default* (1)        | No Swagger            |
| 2018-08-01  | Default* (1)        | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-05-01  | Unknown             | No Swagger            |

## trafficManagerProfiles/nestedEndpoints

!> No Swagger.

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.properties.endpointLocation

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-11-01  | Unknown             | No Swagger            |

### \$.properties.endpointMonitorStatus

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-11-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.properties.minChildEndpoints

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Default* (1)        | No Swagger            |

### \$.properties.priority

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-11-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.properties.target

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-11-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |

## trafficManagerProfiles

![14.67%25](https://img.shields.io/badge/14.67%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-orange)

### \$.properties.dnsConfig.fqdn

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-11-01  | Unknown             | Unknown               |
| 2017-03-01  | Unknown             | Unknown               |

### \$.properties.dnsConfig.relativeName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-11-01  | Unknown             | Unknown               |
| 2017-03-01  | Unknown             | Unknown               |
| 2017-05-01  | Unknown             | Unknown               |
| 2018-04-01  | Unknown             | Unknown               |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.properties.empty

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.endpoints

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-11-01  | Unknown             | Unknown               |
| 2017-03-01  | Unknown             | Unknown               |
| 2017-05-01  | Unknown             | Unknown               |
| 2018-04-01  | Unknown             | Unknown               |

### \$.properties.endpoints[*].condition

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.endpoints[*].dependsOn

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.endpoints[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-11-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.properties.endpoints[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.properties.endpoints[*].properties.endpointLocation

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-11-01  | Unknown             | No Swagger            |
| 2017-05-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.properties.endpoints[*].properties.endpointMonitorStatus

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-05-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.properties.endpoints[*].properties.endpointStatus

| API version | Detected noise type  | Determined noise type |
| ----------- | -------------------- | --------------------- |
| 2017-05-01  | Default* ("Enabled") | No Swagger            |
| 2018-04-01  | Default* ("Enabled") | No Swagger            |

### \$.properties.endpoints[*].properties.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-05-01  | Unknown             | No Swagger            |

### \$.properties.endpoints[*].properties.minChildEndpoints

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-05-01  | Default* (1)        | No Swagger            |

### \$.properties.endpoints[*].properties.priority

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-11-01  | Unknown             | No Swagger            |
| 2017-05-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.properties.endpoints[*].properties.target

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-11-01  | Unknown             | No Swagger            |
| 2017-05-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.properties.endpoints[*].properties.targetResourceId

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.properties.endpoints[*].properties.trafficRoutingMethod

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.properties.endpoints[*].properties.weight

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-11-01  | Default (1)         | No Swagger            |
| 2017-05-01  | Default (1)         | No Swagger            |
| 2018-04-01  | Default (1)         | No Swagger            |
| 2018-08-01  | Default (1)         | No Swagger            |

### \$.properties.endpoints[*].tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-11-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.endpoints[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-11-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.mode

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.properties.monitorConfig.intervalInSeconds

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-05-01  | Default (30)        | Default (30)          |
| 2018-04-01  | Default (30)        | Default (30)          |
| 2018-08-01  | Default (30)        | No Swagger            |

### \$.properties.monitorConfig.profileMonitorStatus

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-05-01  | Unknown             | Read-only             |
| 2018-02-01  | Unknown             | Read-only             |
| 2018-04-01  | Unknown             | Read-only             |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.properties.monitorConfig.protocol

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-11-01  | Unknown             | Unknown               |

### \$.properties.monitorConfig.timeoutInSeconds

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-05-01  | Default (10)        | Default (10)          |
| 2018-04-01  | Default (10)        | Default (10)          |
| 2018-08-01  | Default (10)        | No Swagger            |

### \$.properties.monitorConfig.toleratedNumberOfFailures

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-05-01  | Default (3)         | Default (3)           |
| 2018-04-01  | Default (3)         | Default (3)           |
| 2018-08-01  | Default (3)         | No Swagger            |

### \$.properties.profileStatus

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-05-01  | Default ("Enabled") | Default ("Enabled")   |
| 2018-04-01  | Default ("Enabled") | Default ("Enabled")   |
| 2018-08-01  | Default ("Enabled") | No Swagger            |

### \$.properties.trafficViewEnrollmentStatus

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-04-01  | Unknown             | Unknown               |
| 2018-08-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-11-01  | Unknown             | Unknown               |
| 2017-05-01  | Unknown             | Unknown               |
| 2018-04-01  | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | Unknown               |

## virtualHubs

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.expressRouteGateway

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | Unknown               |
| 2019-11-01  | Unknown             | Unknown               |

### \$.properties.p2SVpnGateway

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-11-01  | Unknown             | Unknown               |

### \$.properties.routeTable

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | Unknown               |

### \$.properties.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | Unknown               |

### \$.properties.virtualNetworkConnections[*].properties.allowRemoteVnetToUseHubVnetGateways

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Default* (true)     | No Swagger            |

### \$.properties.vpnGateway

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | Unknown               |

## virtualNetworkGateways

![9.09%25](https://img.shields.io/badge/9.09%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-red)

### \$.properties.activeActive

| API version        | Detected noise type | Determined noise type                                    |
| ------------------ | ------------------- | -------------------------------------------------------- |
| 2015-05-01-preview | Default (false)     | No Swagger, Default (false) (inheritted from 2017-10-01) |
| 2015-06-15         | Default (false)     | No Swagger, Default (false) (inheritted from 2017-10-01) |
| 2016-03-30         | Default (false)     | No Swagger, Default (false) (inheritted from 2017-10-01) |
| 2017-10-01         | Default (false)     | Default (false)                                          |
| 2018-08-01         | Default (false)     | Default (false)                                          |
| 2019-02-01         | Default (false)     | Default (false)                                          |
| 2019-04-01         | Default (false)     | Default (false)                                          |

### \$.properties.bgpSettings

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | Unknown               |
| 2017-06-01         | Unknown             | Unknown               |
| 2017-10-01         | Unknown             | Unknown               |
| 2018-02-01         | Unknown             | Unknown               |
| 2018-04-01         | Unknown             | Unknown               |
| 2018-07-01         | Unknown             | Unknown               |
| 2018-08-01         | Unknown             | Unknown               |
| 2018-10-01         | Unknown             | Unknown               |
| 2019-02-01         | Unknown             | Unknown               |
| 2019-04-01         | Unknown             | Unknown               |
| 2019-06-01         | Unknown             | Unknown               |
| 2019-07-01         | Unknown             | Unknown               |
| 2019-09-01         | Unknown             | Unknown               |
| 2019-11-01         | Unknown             | Unknown               |

### \$.properties.bgpSettings.bgpPeeringAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | Unknown               |
| 2017-03-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |

### \$.properties.bgpSettings.bgpPeeringAddresses

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2017-03-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.bgpSettings.peerWeight

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Default (0)         | Default (0)           |
| 2017-03-01  | Default (0)         | Default (0)           |
| 2018-02-01  | Default (0)         | Default (0)           |
| 2019-02-01  | Default (0)         | Default (0)           |
| 2019-04-01  | Default (0)         | Default (0)           |

### \$.properties.customRoutes

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.enableBgp

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |
| 2015-06-15         | Unknown             | Unknown               |
| 2016-03-30         | Unknown             | Unknown               |
| 2017-03-01         | Unknown             | Unknown               |
| 2017-10-01         | Unknown             | Unknown               |
| 2018-04-01         | Unknown             | Unknown               |
| 2018-07-01         | Unknown             | Unknown               |
| 2018-08-01         | Unknown             | Unknown               |
| 2019-02-01         | Unknown             | Unknown               |
| 2019-04-01         | Unknown             | Unknown               |

### \$.properties.enablePrivateIpAddress

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Default (false)     | No Swagger            |
| 2015-06-15         | Default (false)     | No Swagger            |
| 2016-03-30         | Default (false)     | No Swagger            |
| 2017-03-01         | Default (false)     | No Swagger            |
| 2017-06-01         | Default (false)     | No Swagger            |
| 2017-10-01         | Default (false)     | No Swagger            |
| 2018-02-01         | Default (false)     | No Swagger            |
| 2018-04-01         | Default (false)     | No Swagger            |
| 2018-07-01         | Default (false)     | No Swagger            |
| 2018-08-01         | Default (false)     | No Swagger            |
| 2018-10-01         | Default (false)     | No Swagger            |
| 2019-02-01         | Default (false)     | No Swagger            |
| 2019-04-01         | Default (false)     | No Swagger            |
| 2019-06-01         | Default (false)     | No Swagger            |
| 2019-07-01         | Default (false)     | No Swagger            |
| 2019-09-01         | Default (false)     | No Swagger            |
| 2019-11-01         | Default (false)     | No Swagger            |

### \$.properties.ipConfigurations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | Unknown               |
| 2018-08-01  | Unknown             | Unknown               |
| 2019-02-01  | Unknown             | Unknown               |

### \$.properties.ipConfigurations[*].etag

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | No Swagger            |
| 2017-06-01         | Unknown             | No Swagger            |
| 2017-10-01         | Unknown             | No Swagger            |
| 2018-02-01         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2018-07-01         | Unknown             | No Swagger            |
| 2018-08-01         | Unknown             | No Swagger            |
| 2018-10-01         | Unknown             | No Swagger            |
| 2019-02-01         | Unknown             | No Swagger            |
| 2019-04-01         | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |
| 2019-07-01         | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].id

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | No Swagger            |
| 2017-06-01         | Unknown             | No Swagger            |
| 2017-10-01         | Unknown             | No Swagger            |
| 2018-02-01         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2018-07-01         | Unknown             | No Swagger            |
| 2018-08-01         | Unknown             | No Swagger            |
| 2018-10-01         | Unknown             | No Swagger            |
| 2019-02-01         | Unknown             | No Swagger            |
| 2019-04-01         | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |
| 2019-07-01         | Unknown             | No Swagger            |
| 2019-09-01         | Unknown             | No Swagger            |
| 2019-11-01         | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.Subnet

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.privateIPAllocationMethod

| API version | Detected noise type  | Determined noise type |
| ----------- | -------------------- | --------------------- |
| 2015-06-15  | Default* ("Dynamic") | No Swagger            |

### \$.properties.ipConfigurations[*].properties.privateIpAllocationMethod

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.provisioningState

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.publicIPAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.publicIPAddress.sku

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.publicIpAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.subnet

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.subnet.etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].properties.subnet.type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations[*].type

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | No Swagger            |
| 2017-06-01         | Unknown             | No Swagger            |
| 2017-10-01         | Unknown             | No Swagger            |
| 2018-02-01         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2018-07-01         | Unknown             | No Swagger            |
| 2018-08-01         | Unknown             | No Swagger            |
| 2018-10-01         | Unknown             | No Swagger            |
| 2019-02-01         | Unknown             | No Swagger            |
| 2019-04-01         | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |
| 2019-07-01         | Unknown             | No Swagger            |
| 2019-09-01         | Unknown             | No Swagger            |
| 2019-11-01         | Unknown             | No Swagger            |

### \$.properties.packetCaptureDiagnosticState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.remoteVirtualNetworkPeerings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.sku

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |

### \$.properties.sku.capacity

| API version        | Detected noise type | Determined noise type                                |
| ------------------ | ------------------- | ---------------------------------------------------- |
| 2015-05-01-preview | Default (2)         | No Swagger, Default (2) (inheritted from 2015-06-15) |
| 2015-06-15         | Default (2)         | Default (2)                                          |
| 2017-10-01         | Default (2)         | Default (2)                                          |
| 2018-08-01         | Default (2)         | Default (2)                                          |
| 2019-02-01         | Default (2)         | Default (2)                                          |
| 2019-04-01         | Default (2)         | Default (2)                                          |

### \$.properties.vpnClientConfiguration

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | Unknown               |
| 2017-10-01         | Unknown             | Unknown               |
| 2018-07-01         | Unknown             | Unknown               |
| 2018-10-01         | Unknown             | Unknown               |

### \$.properties.vpnClientConfiguration.vpnClientConnectionHealth

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.vpnClientConfiguration.vpnClientConnectionHealth.allocatedIpAddresses

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.vpnClientConfiguration.vpnClientConnectionHealth.totalEgressBytesTransferred

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Default* (0)        | No Swagger            |

### \$.properties.vpnClientConfiguration.vpnClientConnectionHealth.totalIngressBytesTransferred

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Default* (0)        | No Swagger            |

### \$.properties.vpnClientConfiguration.vpnClientConnectionHealth.vpnClientConnectionsCount

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Default* (0)        | No Swagger            |

### \$.properties.vpnClientConfiguration.vpnClientProtocols

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | Unknown               |
| 2019-06-01  | Unknown             | Unknown               |

### \$.properties.vpnClientConfiguration.vpnClientProtocols[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.vpnClientConfiguration.vpnClientRevokedCertificates[*].etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.vpnClientConfiguration.vpnClientRevokedCertificates[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.vpnClientConfiguration.vpnClientRevokedCertificates[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.vpnClientConfiguration.vpnClientRootCertificates[*].etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.vpnClientConfiguration.vpnClientRootCertificates[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.vpnClientConfiguration.vpnClientRootCertificates[*].properties.provisioningState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.vpnClientConfiguration.vpnClientRootCertificates[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.vpnGatewayGeneration

| API version | Detected noise type      | Determined noise type |
| ----------- | ------------------------ | --------------------- |
| 2019-07-01  | Default* ("Generation1") | Unknown               |
| 2019-11-01  | Default* ("Generation1") | Unknown               |

### \$.properties.vpnType

| API version | Detected noise type      | Determined noise type |
| ----------- | ------------------------ | --------------------- |
| 2015-06-15  | Default* ("PolicyBased") | Unknown               |
| 2017-10-01  | Default* ("PolicyBased") | Unknown               |
| 2019-02-01  | Default* ("PolicyBased") | Unknown               |
| 2019-04-01  | Default* ("PolicyBased") | Unknown               |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-02-01  | Unknown             | Unknown               |

## virtualNetworks/subnets

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.location

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | Unknown               |
| 2016-03-30         | Unknown             | Unknown               |
| 2017-03-01         | Unknown             | Unknown               |
| 2017-10-01         | Unknown             | Unknown               |
| 2018-02-01         | Unknown             | Unknown               |
| 2018-03-01         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | Unknown               |
| 2018-06-01         | Unknown             | Unknown               |
| 2018-08-01         | Unknown             | Unknown               |
| 2018-10-01         | Unknown             | Unknown               |
| 2018-11-01         | Unknown             | Unknown               |
| 2019-02-01         | Unknown             | Unknown               |
| 2019-04-01         | Unknown             | Unknown               |
| 2019-06-01         | Unknown             | Unknown               |
| 2019-07-01         | Unknown             | Unknown               |
| 2019-09-01         | Unknown             | Unknown               |

### \$.properties.applicationGatewayIPConfigurations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2018-01-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.delegations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.delegations[*].etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.delegations[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.delegations[*].properties.actions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.delegations[*].properties.actions[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.delegations[*].properties.provisioningState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.delegations[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.ipConfigurations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Unknown               |

### \$.properties.networkIntentPolicies

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.networkSecurityGroup

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | Unknown               |

### \$.properties.privateEndpointNetworkPolicies

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-06-01  | Unknown             | Unknown               |
| 2019-07-01  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Unknown               |
| 2019-11-01  | Unknown             | Unknown               |

### \$.properties.privateLinkServiceNetworkPolicies

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-06-01  | Unknown             | Unknown               |
| 2019-07-01  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Unknown               |
| 2019-11-01  | Unknown             | Unknown               |

### \$.properties.purpose

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.resourceNavigationLinks

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | Unknown               |
| 2018-10-01  | Unknown             | Unknown               |
| 2019-02-01  | Unknown             | Unknown               |

### \$.properties.routeTable

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | Unknown               |

### \$.properties.serviceAssociationLinks

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | Unknown               |

### \$.properties.serviceAssociationLinks[*].etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.serviceAssociationLinks[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.serviceAssociationLinks[*].properties.allowDelete

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.serviceAssociationLinks[*].properties.provisioningState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.serviceEndpoints

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |

### \$.properties.serviceEndpoints[*].locations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-09-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.serviceEndpoints[*].locations[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.serviceEndpoints[*].service

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Unknown               |

## virtualNetworks/virtualNetworkPeerings

![29.36%25](https://img.shields.io/badge/29.36%25-%E2%98%85★★%E2%98%86☆☆☆☆☆☆-orange)

### \$.location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.allowForwardedTraffic

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Default (false)       |
| 2017-06-01  | Unknown             | Default (false)       |
| 2017-10-01  | Unknown             | Default (false)       |
| 2018-08-01  | Unknown             | Default (false)       |
| 2019-04-01  | Unknown             | Default (false)       |
| 2019-07-01  | Unknown             | Default (false)       |
| 2019-09-01  | Unknown             | Default (false)       |

### \$.properties.allowGatewayTransit

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Unknown               |
| 2017-06-01  | Unknown             | Unknown               |
| 2017-10-01  | Unknown             | Unknown               |
| 2018-08-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-07-01  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Unknown               |

### \$.properties.allowVirtualNetworkAccess

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Unknown               |
| 2017-06-01  | Unknown             | Unknown               |
| 2017-10-01  | Unknown             | Unknown               |
| 2018-08-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-07-01  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Unknown               |

### \$.properties.doNotVerifyRemoteGateways

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Default (false)     | No Swagger            |
| 2017-03-01  | Default (false)     | No Swagger            |
| 2017-06-01  | Default (false)     | No Swagger            |
| 2017-10-01  | Default (false)     | No Swagger            |
| 2018-02-01  | Default (false)     | No Swagger            |
| 2018-04-01  | Default (false)     | No Swagger            |
| 2018-06-01  | Default (false)     | No Swagger            |
| 2018-07-01  | Default (false)     | No Swagger            |
| 2018-08-01  | Default (false)     | No Swagger            |
| 2018-10-01  | Default (false)     | No Swagger            |
| 2018-11-01  | Default (false)     | No Swagger            |
| 2018-12-01  | Default (false)     | No Swagger            |
| 2019-04-01  | Default (false)     | No Swagger            |
| 2019-06-01  | Default (false)     | No Swagger            |
| 2019-07-01  | Default (false)     | No Swagger            |
| 2019-09-01  | Default (false)     | No Swagger            |
| 2019-11-01  | Default (false)     | No Swagger            |
| 2020-03-01  | Default (false)     | No Swagger            |

### \$.properties.peeringState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Read-only             |
| 2017-06-01  | Unknown             | Read-only             |
| 2017-10-01  | Unknown             | Read-only             |
| 2018-02-01  | Unknown             | Read-only             |
| 2018-07-01  | Unknown             | Read-only             |
| 2018-08-01  | Unknown             | Read-only             |
| 2018-10-01  | Unknown             | Read-only             |
| 2018-11-01  | Unknown             | Read-only             |
| 2019-04-01  | Unknown             | Read-only             |
| 2019-07-01  | Unknown             | Read-only             |
| 2019-09-01  | Unknown             | Read-only             |

### \$.properties.remoteAddressSpace

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2017-03-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-04-01  | Unknown             | Unknown               |
| 2018-06-01  | Unknown             | Unknown               |
| 2018-07-01  | Unknown             | Unknown               |
| 2018-08-01  | Unknown             | Unknown               |
| 2018-10-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2018-12-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-06-01  | Unknown             | Unknown               |
| 2019-07-01  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Unknown               |
| 2019-11-01  | Unknown             | Unknown               |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.remoteGateways

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.resourceGuid

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Read-only             |
| 2017-06-01  | Unknown             | Read-only             |
| 2017-10-01  | Unknown             | Read-only             |
| 2018-02-01  | Unknown             | Read-only             |
| 2018-04-01  | Unknown             | Read-only             |
| 2018-07-01  | Unknown             | Read-only             |
| 2018-08-01  | Unknown             | Read-only             |
| 2018-10-01  | Unknown             | Read-only             |
| 2018-11-01  | Unknown             | Read-only             |
| 2018-12-01  | Unknown             | Read-only             |
| 2019-04-01  | Unknown             | Read-only             |
| 2019-07-01  | Unknown             | Read-only             |
| 2019-09-01  | Unknown             | Read-only             |
| 2019-11-01  | Unknown             | Read-only             |

### \$.properties.useRemoteGateways

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Unknown               |
| 2017-06-01  | Unknown             | Unknown               |
| 2017-10-01  | Unknown             | Unknown               |
| 2018-08-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-07-01  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Unknown               |

## virtualNetworks

![13.41%25](https://img.shields.io/badge/13.41%25-%E2%98%85%E2%98%86☆☆☆☆☆☆☆☆-orange)

### \$.properties.addressSpace.addressPrefixes[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.containsRouteService

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.dhcpOptions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-01-01  | Unknown             | Unknown               |

### \$.properties.enableDdosProtection

| API version | Detected noise type | Determined noise type                                    |
| ----------- | ------------------- | -------------------------------------------------------- |
| 2017-08-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2017-09-01) |
| 2017-09-01  | Default (false)     | Default (false)                                          |
| 2017-10-01  | Default (false)     | Default (false)                                          |
| 2017-11-01  | Default (false)     | Default (false)                                          |
| 2018-01-01  | Default (false)     | Default (false)                                          |
| 2018-02-01  | Default (false)     | Default (false)                                          |
| 2018-03-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2018-04-01) |
| 2018-04-01  | Default (false)     | Default (false)                                          |
| 2018-07-01  | Default (false)     | Default (false)                                          |
| 2018-08-01  | Default (false)     | Default (false)                                          |
| 2018-10-01  | Default (false)     | Default (false)                                          |
| 2018-11-01  | Default (false)     | Default (false)                                          |
| 2018-12-01  | Default (false)     | Default (false)                                          |
| 2019-02-01  | Default (false)     | Default (false)                                          |
| 2019-04-01  | Default (false)     | Default (false)                                          |
| 2019-06-01  | Default (false)     | Default (false)                                          |
| 2019-07-01  | Default (false)     | Default (false)                                          |
| 2019-08-01  | Default (false)     | Default (false)                                          |
| 2019-09-01  | Default (false)     | Default (false)                                          |

### \$.properties.enableVmProtection

| API version | Detected noise type | Determined noise type                                    |
| ----------- | ------------------- | -------------------------------------------------------- |
| 2017-08-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2017-09-01) |
| 2017-09-01  | Default (false)     | Default (false)                                          |
| 2017-10-01  | Default (false)     | Default (false)                                          |
| 2017-11-01  | Default (false)     | Default (false)                                          |
| 2018-01-01  | Default (false)     | Default (false)                                          |
| 2018-02-01  | Default (false)     | Default (false)                                          |
| 2018-03-01  | Default (false)     | No Swagger, Default (false) (inheritted from 2018-04-01) |
| 2018-04-01  | Default (false)     | Default (false)                                          |
| 2018-07-01  | Default (false)     | Default (false)                                          |
| 2018-08-01  | Default (false)     | Default (false)                                          |
| 2018-10-01  | Default (false)     | Default (false)                                          |
| 2018-11-01  | Default (false)     | Default (false)                                          |
| 2018-12-01  | Default (false)     | Default (false)                                          |
| 2019-02-01  | Default (false)     | Default (false)                                          |
| 2019-04-01  | Default (false)     | Default (false)                                          |
| 2019-07-01  | Default (false)     | Default (false)                                          |
| 2019-08-01  | Default (false)     | Default (false)                                          |
| 2019-09-01  | Default (false)     | Default (false)                                          |

### \$.properties.migrationPhase

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.paaSVMScaleSets

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-12-01  | Unknown             | No Swagger            |

### \$.properties.routeServiceVip

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.subnets

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-12-01-preview | Unknown             | No Swagger            |
| 2015-05-01-preview | Unknown             | Unknown               |
| 2015-06-15         | Unknown             | Unknown               |
| 2016-03-30         | Unknown             | Unknown               |
| 2016-12-01         | Unknown             | Unknown               |
| 2017-03-01         | Unknown             | Unknown               |
| 2017-06-01         | Unknown             | Unknown               |
| 2017-10-01         | Unknown             | Unknown               |
| 2017-11-01         | Unknown             | Unknown               |
| 2018-02-01         | Unknown             | Unknown               |
| 2018-03-01         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | Unknown               |
| 2018-06-01         | Unknown             | Unknown               |
| 2018-07-01         | Unknown             | Unknown               |
| 2018-08-01         | Unknown             | Read-only             |
| 2018-10-01         | Unknown             | Read-only             |
| 2018-11-01         | Unknown             | Read-only             |
| 2018-12-01         | Unknown             | Read-only             |
| 2019-04-01         | Unknown             | Read-only             |
| 2019-07-01         | Unknown             | Read-only             |
| 2019-08-01         | Unknown             | Read-only             |
| 2019-09-01         | Unknown             | Read-only             |
| 2019-11-01         | Unknown             | Read-only             |

### \$.properties.subnets[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].location

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].name

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-12-01-preview | Unknown             | No Swagger            |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2018-08-01         | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |
| 2019-11-01         | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.addressPrefix

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-12-01-preview | Unknown             | No Swagger            |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2018-08-01         | Unknown             | No Swagger            |
| 2019-04-01         | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |
| 2019-11-01         | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.addressPrefixes

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.addressprefix

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.applicationGatewayIPConfigurations

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-06-01         | Unknown             | No Swagger            |
| 2016-12-01         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | No Swagger            |
| 2017-04-01         | Unknown             | No Swagger            |
| 2017-06-01         | Unknown             | No Swagger            |
| 2017-10-01         | Unknown             | No Swagger            |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-02-01         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2018-07-01         | Unknown             | No Swagger            |
| 2018-08-01         | Unknown             | No Swagger            |
| 2018-10-01         | Unknown             | No Swagger            |
| 2018-11-01         | Unknown             | No Swagger            |
| 2018-12-01         | Unknown             | No Swagger            |
| 2019-02-01         | Unknown             | No Swagger            |
| 2019-04-01         | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |
| 2019-07-01         | Unknown             | No Swagger            |
| 2019-08-01         | Unknown             | No Swagger            |
| 2019-09-01         | Unknown             | No Swagger            |
| 2019-11-01         | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.delegations[*].etag

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.delegations[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.delegations[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.delegations[*].properties.actions

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.delegations[*].properties.actions[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.delegations[*].properties.provisioningState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.delegations[*].properties.serviceName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.delegations[*].properties.servicename

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.delegations[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.ipConfigurationProfiles

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.ipConfigurations

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-12-01-preview | Unknown             | No Swagger            |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.natGateway

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.networkIntentPolicies

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.networkSecurityGroup

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2014-12-01-preview | Unknown             | No Swagger            |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2015-06-15         | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2016-12-01         | Unknown             | No Swagger            |
| 2017-03-01         | Unknown             | No Swagger            |
| 2017-04-01         | Unknown             | No Swagger            |
| 2017-08-01         | Unknown             | No Swagger            |
| 2018-01-01         | Unknown             | No Swagger            |
| 2018-02-01         | Unknown             | No Swagger            |
| 2018-03-01         | Unknown             | No Swagger            |
| 2018-04-01         | Unknown             | No Swagger            |
| 2018-06-01         | Unknown             | No Swagger            |
| 2018-08-01         | Unknown             | No Swagger            |
| 2018-12-01         | Unknown             | No Swagger            |
| 2019-04-01         | Unknown             | No Swagger            |
| 2019-06-01         | Unknown             | No Swagger            |
| 2019-09-01         | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.networkSecurityGroup.id

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | No Swagger            |
| 2016-03-30         | Unknown             | No Swagger            |
| 2017-08-01         | Unknown             | No Swagger            |
| 2018-08-01         | Unknown             | No Swagger            |
| 2019-11-01         | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.privateEndpointNetworkPolicies

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-08-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.privateLinkServiceNetworkPolicies

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |
| 2019-08-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.purpose

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-07-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.resourceNavigationLinks

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-03-30  | Unknown             | No Swagger            |
| 2016-06-01  | Unknown             | No Swagger            |
| 2016-12-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.routeTable

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.serviceAssociationLinks

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-07-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.serviceEndpoints

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-04-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.serviceEndpoints[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.serviceEndpoints[*].locations

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-12-01  | Unknown             | No Swagger            |
| 2017-06-01  | Unknown             | No Swagger            |
| 2017-08-01  | Unknown             | No Swagger            |
| 2017-09-01  | Unknown             | No Swagger            |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.serviceEndpoints[*].locations[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2017-10-01  | Unknown             | No Swagger            |
| 2018-02-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | No Swagger            |
| 2018-06-01  | Unknown             | No Swagger            |
| 2018-07-01  | Unknown             | No Swagger            |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-11-01  | Unknown             | No Swagger            |
| 2019-02-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.serviceEndpoints[*].provisioningState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-12-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.serviceEndpoints[*].service

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Unknown             | No Swagger            |
| 2018-10-01  | Unknown             | No Swagger            |
| 2018-12-01  | Unknown             | No Swagger            |
| 2019-04-01  | Unknown             | No Swagger            |
| 2019-06-01  | Unknown             | No Swagger            |
| 2019-09-01  | Unknown             | No Swagger            |
| 2019-11-01  | Unknown             | No Swagger            |

### \$.properties.subnets[*].properties.usmlName

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.subnets[*].tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | No Swagger            |

### \$.properties.virtualNetworkPeerings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2016-06-01  | Unknown             | Unknown               |
| 2016-09-01  | Unknown             | Unknown               |
| 2016-12-01  | Unknown             | Unknown               |
| 2017-06-01  | Unknown             | Unknown               |
| 2017-08-01  | Unknown             | Unknown               |
| 2017-10-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-04-01  | Unknown             | Unknown               |
| 2018-06-01  | Unknown             | Unknown               |
| 2018-08-01  | Unknown             | Unknown               |
| 2018-10-01  | Unknown             | Unknown               |
| 2018-11-01  | Unknown             | Unknown               |
| 2018-12-01  | Unknown             | Unknown               |
| 2019-02-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-06-01  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Unknown               |
| 2019-11-01  | Unknown             | Unknown               |
| 2020-03-01  | Unknown             | No Swagger            |

### \$.properties.virtualNetworkPeerings[*].properties.doNotVerifyRemoteGateways

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Default* (false)    | No Swagger            |

### \$.properties.virtualNetworkPeerings[*].properties.peeringState

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.virtualNetworkPeerings[*].properties.remoteAddressSpace.addressPrefixes[*]

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.virtualNetworkPeerings[*].properties.resourceGuid

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.tags

| API version        | Detected noise type | Determined noise type |
| ------------------ | ------------------- | --------------------- |
| 2015-05-01-preview | Unknown             | Unknown               |
| 2016-03-30         | Unknown             | Unknown               |
| 2016-09-01         | Unknown             | Unknown               |
| 2017-04-01         | Unknown             | No Swagger            |
| 2018-02-01         | Unknown             | Unknown               |
| 2018-04-01         | Unknown             | Unknown               |
| 2018-08-01         | Unknown             | Unknown               |
| 2018-10-01         | Unknown             | Unknown               |
| 2018-11-01         | Unknown             | Unknown               |
| 2019-06-01         | Unknown             | Unknown               |
| 2019-09-01         | Unknown             | Unknown               |
| 2019-11-01         | Unknown             | Unknown               |

### \$.tags.*

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2015-06-15  | Unknown             | Unknown               |
| 2017-04-01  | Unknown             | No Swagger            |
| 2017-08-01  | Unknown             | Unknown               |
| 2017-10-01  | Unknown             | Unknown               |
| 2018-02-01  | Unknown             | Unknown               |
| 2018-03-01  | Unknown             | No Swagger            |
| 2018-04-01  | Unknown             | Unknown               |
| 2018-10-01  | Unknown             | Unknown               |
| 2018-12-01  | Unknown             | Unknown               |
| 2019-04-01  | Unknown             | Unknown               |
| 2019-09-01  | Unknown             | Unknown               |

## virtualWans

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.allowBranchToBranchTraffic

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Default* (true)     | Unknown               |

### \$.properties.allowVnetToVnetTraffic

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Default* (false)    | Unknown               |

### \$.properties.disableVpnEncryption

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Default* (false)    | Unknown               |

## vpnGateways

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.bgpSettings

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | Unknown               |

### \$.properties.bgpSettings.peerWeight

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Default* (0)        | Unknown               |

### \$.properties.connections[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.connections[*].properties.enableBgp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Default* (false)    | No Swagger            |

### \$.properties.connections[*].properties.enableInternetSecurity

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Default* (false)    | No Swagger            |

### \$.properties.connections[*].properties.enableRateLimiting

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Default* (false)    | No Swagger            |

### \$.properties.connections[*].properties.routingWeight

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Default* (0)        | No Swagger            |

### \$.properties.connections[*].properties.useLocalAzureIpAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Default* (false)    | No Swagger            |

### \$.properties.connections[*].properties.usePolicyBasedTrafficSelectors

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Default* (false)    | No Swagger            |

### \$.properties.connections[*].properties.vpnConnectionProtocolType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Default* ("IKEv2")  | No Swagger            |

### \$.properties.connections[*].properties.vpnLinkConnections[*].id

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.connections[*].properties.vpnLinkConnections[*].properties.connectionBandwidth

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Default* (10)       | No Swagger            |

### \$.properties.connections[*].properties.vpnLinkConnections[*].properties.enableBgp

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Default* (false)    | No Swagger            |

### \$.properties.connections[*].properties.vpnLinkConnections[*].properties.enableRateLimiting

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Default* (false)    | No Swagger            |

### \$.properties.connections[*].properties.vpnLinkConnections[*].properties.routingWeight

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Default* (0)        | No Swagger            |

### \$.properties.connections[*].properties.vpnLinkConnections[*].properties.useLocalAzureIpAddress

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Default* (false)    | No Swagger            |

### \$.properties.connections[*].properties.vpnLinkConnections[*].properties.usePolicyBasedTrafficSelectors

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Default* (false)    | No Swagger            |

### \$.properties.connections[*].properties.vpnLinkConnections[*].properties.vpnConnectionProtocolType

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Default* ("IKEv2")  | No Swagger            |

### \$.properties.connections[*].type

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Unknown             | No Swagger            |

### \$.properties.vpnGatewayScaleUnit

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-09-01  | Default* (1)        | Unknown               |

## vpnSites

![0.00%25](https://img.shields.io/badge/0.00%25-%E2%98%86☆☆☆☆☆☆☆☆☆-red)

### \$.properties.deviceProperties.linkSpeedInMbps

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Default* (0)        | Unknown               |

### \$.properties.isSecuritySite

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2018-08-01  | Default* (false)    | Unknown               |
| 2019-06-01  | Default* (false)    | Unknown               |
| 2019-09-01  | Default* (false)    | Unknown               |

### \$.properties.vpnSiteLinks[*].name

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | No Swagger            |

### \$.tags

| API version | Detected noise type | Determined noise type |
| ----------- | ------------------- | --------------------- |
| 2019-06-01  | Unknown             | Unknown               |
