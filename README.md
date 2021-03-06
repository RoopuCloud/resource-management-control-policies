# Alibaba Cloud Resource Management Control Policies

In this repository you will find Alibaba Cloud Resource Management Control Policies.

## List of Control Policies
* It is forbidden to modify and delete RAM users, RAM user groups, and RAM roles --> [delete_ram_users_roles.json](Policies/delete_ram_users_roles.json)
* It is forbidden to modify the ResourceDirectoryAccountAccessRole role and its permissions --> [modify_resource_directory_role.json](Policies/modify_resource_directory_role.json)
* It is forbidden to modify and delete the specified RAM user --> [delete_ram_user.json](Policies/delete_ram_user.json)
* Prohibit opening the console login of any RAM user --> [deny_opening_console.json](dPolicies/eny_opening_console.json)
* RAM users or RAM roles must use multi-factor authentication (MFA) when deleting certain resources --> [mfa_required.json](Policies/mfa_required.json)
* It is forbidden to modify user SSO configuration --> [user_sso_configuration.json](Policies/user_sso_configuration.json)
* It is forbidden to modify the role SSO configuration --> [role_sso_configuration.json](Policies/role_sso_configuration.json)
* It is forbidden to modify the delivery address of the operation audit and disable the delivery function --> [modify_actiontrail.json](Policies/modify_actiontrail.json)
* Forbid access to some network services --> [modify_networking.json](Policies/modify_networking.json)
* It is forbidden to create network resources with public network access capabilities, including EIP and NAT gateways --> [public_networking.json](Policies/public_networking.json)
* Prohibit access to network services connected to resources under the cloud --> [hybrid_cloud.json](Policies/hybrid_cloud.json)
* Forbid access to some functions of the cost center --> [cost_center.json](Policies/cost_center.json)
* It is forbidden to modify cloud monitoring configuration --> [monitoring_configuration.json](Policies/monitoring_configuration.json)
* Prohibition of purchasing reserved instance coupons --> [reserved_instances.json](Policies/reserved_instances.json)
* It is forbidden to create ECS instances in non-specified VPCs --> [ecs_instance_vpc.json](Policies/ecs_instance_vpc.json)
* Purchase of domain names is prohibited --> [domain_names.json](Policies/domain_names.json)
* Access to the cloud marketplace is forbidden --> [cloud_marketplace.json](Policies/cloud_marketplace.json)
* Prevent access to the ticket system --> [ticket_system.json](Policies/ticket_system.json)

## Contact
You can contact us [here](https://roopu.cloud/contact).
