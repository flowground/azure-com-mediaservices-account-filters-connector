# ![LOGO](logo.png) Azure Media Services **flow**ground Connector

## Description

A generated **flow**ground connector for the Azure Media Services API (version 2018-07-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/mediaservices-AccountFilters/2018-07-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:21+03:00

## API Description

This Swagger was generated by the API Framework.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### List Account Filters

> List Account Filters in the Media Services account.

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Delete an Account Filter.

> Deletes an Account Filter in the Media Services account.

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `filterName` - _required_ - The Account Filter name
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Get an Account Filter.

> Get the details of an Account Filter in the Media Services account.

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `filterName` - _required_ - The Account Filter name
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Update an Account Filter

> Updates an existing Account Filter in the Media Services account.

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `filterName` - _required_ - The Account Filter name
* `api-version` - _required_ - The Version of the API to be used with the client request.

### Create or update an Account Filter

> Creates or updates an Account Filter in the Media Services account.

#### Input Parameters
* `subscriptionId` - _required_ - The unique identifier for a Microsoft Azure subscription.
* `resourceGroupName` - _required_ - The name of the resource group within the Azure subscription.
* `accountName` - _required_ - The Media Services account name.
* `filterName` - _required_ - The Account Filter name
* `api-version` - _required_ - The Version of the API to be used with the client request.

## License

**flow**ground :- Telekom iPaaS / azure-com-mediaservices-account-filters-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
