Randomly assigns the incidents to users on call (requires shift management) and users on call.
See for more information:  
[XSOAR 6.13](https://docs-cortex.paloaltonetworks.com/r/Cortex-XSOAR/6.13/Cortex-XSOAR-Administrator-Guide/Shift-Management)  
[XSOAR 8](https://docs-cortex.paloaltonetworks.com/r/Cortex-XSOAR/8/Cortex-XSOAR-Cloud-Documentation/Manage-roles-in-the-Cortex-XSOAR-tenant)

Incident Ids should be passed in as a comma separated list.

## Permissions
---

This automation runs using the default Limited User role, unless you explicitly change the permissions.
For more information, see the section about permissions here: For XSOAR 6, see the https://docs-cortex.paloaltonetworks.com/r/Cortex-XSOAR/6.x/Cortex-XSOAR-Playbook-Design-Guide/Automations. For XSOAR 8, see the https://docs-cortex.paloaltonetworks.com/r/Cortex-XSOAR/8/Cortex-XSOAR-Cloud-Documentation/Create-a-script.

## Script Data
---

| **Name** | **Description** |
| --- | --- |
| Script Type | python3 |
| Tags |  |
| Cortex XSOAR Version | 6.0.0 |

## Inputs
---

| **Argument Name** | **Description** |
| --- | --- |
| incident_id | The Incident IDs to reassign, can be a comma separated list \(e.g. 1,2,3,4\) |

## Outputs
---
There are no outputs for this script.
