# ![LOGO](logo.png) Relay **flow**ground Connector

## Description

A generated **flow**ground connector for the Relay API (version 2017-04-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/relay/2017-04-01/swagger.json<br/>
Generated at: 2019-05-07T17:38:44+03:00

## API Description

Use these API to manage Azure Relay resources through Azure Resource Manager.

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all available Relay REST API operations.

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - Client API version.

### Check the specified namespace name availability.

*Tags:* `Namespaces`

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists all the available namespaces within the subscription regardless of the resourceGroups.

*Tags:* `Namespaces`

#### Input Parameters
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists all the available namespaces within the ResourceGroup.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes an existing namespace. This operation also removes all associated resources under the namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Returns the description for the specified namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates a namespace. Once created, this namespace's resource manifest is immutable. This operation is idempotent.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Create Azure Relay namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Authorization rules for a namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes a namespace authorization rule.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Authorization rule for a namespace by name.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates an authorization rule for a namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Primary and secondary connection strings to the namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Regenerates the primary or secondary connection strings to the namespace.

*Tags:* `Namespaces`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists the hybrid connection within the namespace.

*Tags:* `HybridConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes a hybrid connection.

*Tags:* `HybridConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `hybridConnectionName` - _required_ - The hybrid connection name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Returns the description for the specified hybrid connection.

*Tags:* `HybridConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `hybridConnectionName` - _required_ - The hybrid connection name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates a service hybrid connection. This operation is idempotent.

*Tags:* `HybridConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `hybridConnectionName` - _required_ - The hybrid connection name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Authorization rules for a hybrid connection.

*Tags:* `HybridConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `hybridConnectionName` - _required_ - The hybrid connection name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes a hybrid connection authorization rule.

*Tags:* `HybridConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `hybridConnectionName` - _required_ - The hybrid connection name.
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Hybrid connection authorization rule for a hybrid connection by name.

*Tags:* `HybridConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `hybridConnectionName` - _required_ - The hybrid connection name.
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates an authorization rule for a hybrid connection.

*Tags:* `HybridConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `hybridConnectionName` - _required_ - The hybrid connection name.
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Primary and secondary connection strings to the hybrid connection.

*Tags:* `HybridConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `hybridConnectionName` - _required_ - The hybrid connection name.
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Regenerates the primary or secondary connection strings to the hybrid connection.

*Tags:* `HybridConnections`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `hybridConnectionName` - _required_ - The hybrid connection name.
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Lists the WCF relays within the namespace.

*Tags:* `WCFRelays`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes a WCF relay.

*Tags:* `WCFRelays`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `relayName` - _required_ - The relay name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Returns the description for the specified WCF relay.

*Tags:* `WCFRelays`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `relayName` - _required_ - The relay name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates a WCF relay. This operation is idempotent.

*Tags:* `WCFRelays`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `relayName` - _required_ - The relay name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Authorization rules for a WCF relay.

*Tags:* `WCFRelays`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `relayName` - _required_ - The relay name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Deletes a WCF relay authorization rule.

*Tags:* `WCFRelays`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `relayName` - _required_ - The relay name.
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Get authorizationRule for a WCF relay by name.

*Tags:* `WCFRelays`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `relayName` - _required_ - The relay name.
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Creates or updates an authorization rule for a WCF relay.

*Tags:* `WCFRelays`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `relayName` - _required_ - The relay name.
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Primary and secondary connection strings to the WCF relay.

*Tags:* `WCFRelays`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `relayName` - _required_ - The relay name.
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

### Regenerates the primary or secondary connection strings to the WCF relay.

*Tags:* `WCFRelays`

#### Input Parameters
* `resourceGroupName` - _required_ - Name of the Resource group within the Azure subscription.
* `namespaceName` - _required_ - The namespace name
* `relayName` - _required_ - The relay name.
* `authorizationRuleName` - _required_ - The authorization rule name.
* `api-version` - _required_ - Client API version.
* `subscriptionId` - _required_ - Subscription credentials which uniquely identify the Microsoft Azure subscription. The subscription ID forms part of the URI for every service call.

## License

**flow**ground :- Telekom iPaaS / azure-com-relay-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
