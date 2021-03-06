
# Module `resources/azure/governance/user-assigned-identity`

Core Version Constraints:
* `>= 0.12`

Provider Requirements:
* **azurerm:** `~> 1.32.0`

## Input Variables
* `resource_group` (required): The name of the target resource group
* `uai_name` (required): The name of the user assigned identity. Changing this forces a new identity to be created.

## Output Values
* `uai_client_id`
* `uai_id`
* `uai_name`
* `uai_principal_id`

## Managed Resources
* `azurerm_user_assigned_identity.base` from `azurerm`

## Data Resources
* `data.azurerm_resource_group.base` from `azurerm`

