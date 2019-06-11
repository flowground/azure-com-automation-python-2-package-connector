# ![LOGO](logo.png) AutomationManagement **flow**ground Connector

## Description

A generated **flow**ground connector for the AutomationManagement API (version 2018-06-30).

Generated from: https://api.apis.guru/v2/specs/azure.com/automation-python2package/2018-06-30/swagger.json<br/>
Generated at: 2019-06-11T18:13:26+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Retrieve a list of python 2 packages.

*Tags:* `Python2Package`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.

### Delete the python 2 package by name.

*Tags:* `Python2Package`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `packageName` - _required_ - The python package name.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.

### Retrieve the python 2 package identified by package name.

*Tags:* `Python2Package`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `packageName` - _required_ - The python package name.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.

### Update the python 2 package identified by package name.

*Tags:* `Python2Package`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `packageName` - _required_ - The name of python package.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.

### Create or Update the python 2 package identified by package name.

*Tags:* `Python2Package`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of an Azure Resource group.
* `automationAccountName` - _required_ - The name of the automation account.
* `packageName` - _required_ - The name of python package.
* `subscriptionId` - _required_ - Gets subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client Api Version.

## License

**flow**ground :- Telekom iPaaS / azure-com-automation-python-2-package-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
