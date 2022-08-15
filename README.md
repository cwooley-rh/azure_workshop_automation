# azure_workshop_automation


## Pre Requisites

``` bash
az login
az account set --subscription <sub_name>
```

1. Create the new workshop Azure Tenant
*workshop.mobb.ninja*
1. Create/ Verify Resource Group policy
*az policy definition create*
1. Create the User RG's 
*azure_rm_resourcegroup*
1. Create the Users
1. Create the user roles (1 role/user) 
*azure.azcollection.azure_rm_roledefinition*
1. Assign users to their previously created roles
*azure.azcollection.azure_rm_roleassignment*
1. Be able to divy out the users
> nice to have a way 


# TODO

1. Iron out the details for Role and Tenant Definition/Creation
1. Re Factor the Role execution
1. Look into refactoring the execution workflow (block loop through the user-# squence for the relevant tasks)


