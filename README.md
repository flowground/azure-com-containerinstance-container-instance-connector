# ![LOGO](logo.png) ContainerInstanceManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the ContainerInstanceManagementClient API (version 2017-10-01-preview).

Generated from: https://api.apis.guru/v2/specs/azure.com/containerinstance-containerInstance/2017-10-01-preview/swagger.json<br/>
Generated at: 2019-05-07T17:37:51+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### List the operations for Azure Container Instance service.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - Client API version

### Get a list of container groups in the specified subscription.

> Get a list of container groups in the specified subscription. This operation returns properties of each container group including containers, image registry credentials, restart policy, IP address type, OS type, state, and volumes.

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API version

### Get a list of container groups in the specified subscription and resource group.

> Get a list of container groups in a specified subscription and resource group. This operation returns properties of each container group including containers, image registry credentials, restart policy, IP address type, OS type, state, and volumes.

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API version
* `resourceGroupName` - _required_ - The name of the resource group.

### Delete the specified container group.

> Delete the specified container group in the specified subscription and resource group. The operation does not delete other resources provided by the user, such as volumes.

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API version
* `resourceGroupName` - _required_ - The name of the resource group.
* `containerGroupName` - _required_ - The name of the container group.

### Get the properties of the specified container group.

> Gets the properties of the specified container group in the specified subscription and resource group. The operation returns the properties of each container group including containers, image registry credentials, restart policy, IP address type, OS type, state, and volumes.

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API version
* `resourceGroupName` - _required_ - The name of the resource group.
* `containerGroupName` - _required_ - The name of the container group.

### Create or update container groups.

> Create or update container groups with specified configurations.

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API version
* `resourceGroupName` - _required_ - The name of the resource group.
* `containerGroupName` - _required_ - The name of the container group.

### Get the logs for a specified container instance.

> Get the logs for a specified container instance in a specified resource group and container group.

#### Input Parameters
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.
* `api-version` - _required_ - Client API version
* `resourceGroupName` - _required_ - The name of the resource group.
* `containerGroupName` - _required_ - The name of the container group.
* `containerName` - _required_ - The name of the container instance.
* `tail` - _optional_ - The number of lines to show from the tail of the container instance log. If not provided, all available logs are shown up to 4mb.

## License

**flow**ground :- Telekom iPaaS / azure-com-containerinstance-container-instance-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
