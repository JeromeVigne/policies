# policies
A repo to develop Azure policies.

Least overhead would be when defining a restrciting tule (such as no netwrok peering), to add an exception when it is added.

Policies:
* no public access to Azure SQL DBs 
enforcing encryption on storage - https://docs.microsoft.com/en-us/azure/governance/policy/samples/require-storage-account-encryption
* no on-prem data gateway
* no vnet peering - done
* no VPN Gateways
* no ER Gateways
* no Pips on VM - see samples
* Enforce Route Tables: https://github.com/Azure/azure-policy/tree/master/samples/Network/enforce-route-table-on-subnet


