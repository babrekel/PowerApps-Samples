# Sample: Early-bound entity operations
This sample shows how to create, retrieve, update, and delete operations on an account using the early bound class. This sample uses the following common methods:

- [IOrganizationService.Create](https://docs.microsoft.com/en-us/dotnet/api/microsoft.xrm.sdk.iorganizationservice.create?view=dynamics-general-ce-9)
- [IOrganizationService.Retrieve](https://docs.microsoft.com/en-us/dotnet/api/microsoft.xrm.sdk.iorganizationservice.retrieve?view=dynamics-general-ce-9)
- [IOrganizationService.Update](https://docs.microsoft.com/en-us/dotnet/api/microsoft.xrm.sdk.iorganizationservice.update?view=dynamics-general-ce-9)
- [IOrganizationService.Delete](https://docs.microsoft.com/en-us/dotnet/api/microsoft.xrm.sdk.iorganizationservice.delete?view=dynamics-general-ce-9)

## How to run this sample

See [How to run samples](../../../README.md) for information about how to run this sample.

## What this sample does

The `IOrganizationService` message is intended to be used in a scenario where it provides programmatic access to the metadata and data for an organization.

## How this sample works

In order to simulate the scenario described in [What this sample does](#what-this-sample-does), the sample will do the following:

### Setup

1. Checks the current version of the org.
1. Creates the sample account records required for this sample.

### Demonstrate

1. Instantiate an account object.
1. Retrieves the account containing its attributes .
1. Retrieves the version number of the account.
1. Updates the account with postal1 code attribute. 


### Clean up

1. Display an option to delete the records created in the [Setup](#setup).

    The deletion is optional in case you want to examine the entities and data created by the sample. You can manually delete the records to achieve the same result.

