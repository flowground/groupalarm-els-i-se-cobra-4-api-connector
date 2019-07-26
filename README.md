# ![LOGO](logo.png) groupalarm ELS iSE-Cobra 4 API **flow**ground Connector

## Description

A generated **flow**ground connector for the groupalarm ELS iSE-Cobra 4 API API (version 1.15.0).

Generated from: https://app.groupalarm.com/api/v1/els-cobra<br/>
Generated at: 2019-07-26T13:59:33+03:00

## API Description

The ELS iSE-Cobra 4 service implements all iSE-Cobra 4 functions for GroupAlarm<br/>
<br/>
# Authentication<br/>
<br/>
<!-- ReDoc-Inject: <security-definitions> --><br/>

## Authorization

Supported authorization schemes:
- API Key
- API Key

## Actions

### GetCertificate
> Returns the requested certificate for the given organizationID<br/>

*Tags:* `certificate`

#### Input Parameters
* `organizationID` - _required_ - organization to query<br/>

### StoreCertificate
> Store the given certificate for the given organizationID<br/>

*Tags:* `certificate`

#### Input Parameters
* `organizationID` - _required_ - organization to query<br/>

### DeleteCertificate
> Delete the certificate for the given organizationID<br/>

*Tags:* `certificate`

#### Input Parameters
* `organizationID` - _required_ - organization to query<br/>

### GetCredentials
> Returns all or the requested credentials for the given organizationID (and serviceName)<br/>

*Tags:* `credentials`

#### Input Parameters
* `organizationID` - _required_ - organization to query<br/>
* `serviceName` - _optional_ - service name to query<br/>

### StoreCredentials
> Store the given credentials for the given organizationID and serviceName<br/>

*Tags:* `credentials`

#### Input Parameters
* `organizationID` - _required_ - organization to query<br/>
* `serviceName` - _required_ - service name to query<br/>

### DeleteCredentials
> Delete the login for the given organizationID and serviceName<br/>

*Tags:* `credentials`

#### Input Parameters
* `organizationID` - _required_ - organization to query<br/>
* `serviceName` - _required_ - service name to query<br/>

### GetKeywords
> Returns the requested KeywordList for the given organizationID<br/>

*Tags:* `keyword`

#### Input Parameters
* `organizationID` - _required_ - organization to query<br/>

### StoreKeywords
> Store the given KeywordList for the given organizationID<br/>

*Tags:* `keyword`

#### Input Parameters
* `organizationID` - _required_ - organization to query<br/>

### DeleteKeywords
> Delete the KeywordList for the given organizationID<br/>

*Tags:* `keyword`

#### Input Parameters
* `organizationID` - _required_ - organization to query<br/>

### GetLogin
> Returns the requested login for the given organizationID<br/>

*Tags:* `login`

#### Input Parameters
* `organizationID` - _required_ - organization to query<br/>

### StoreLogin
> Store the given login for the given organizationID<br/>

*Tags:* `login`

#### Input Parameters
* `organizationID` - _required_ - organization to query<br/>

### DeleteLogin
> Delete the login for the given organizationID<br/>

*Tags:* `login`

#### Input Parameters
* `organizationID` - _required_ - organization to query<br/>

## License

**flow**ground :- Telekom iPaaS / groupalarm-els-i-se-cobra-4-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
