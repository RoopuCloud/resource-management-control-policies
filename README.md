# Alibaba Cloud Resource Management Control Policies

In this repository you will find Alibaba Cloud Resource Management Control Policies.

## List of Control Policies
* It is forbidden to modify and delete RAM users, RAM user groups, and RAM roles --> [delete_ram_users_roles.json](Policies/delete_ram_users_roles.json)
* It is forbidden to modify the ResourceDirectoryAccountAccessRole role and its permissions --> [modify_resource_directory_role.json](modify_resource_directory_role.json)
* It is forbidden to modify and delete the specified RAM user --> [delete_ram_user.json](delete_ram_user.json)
* Prohibit opening the console login of any RAM user --> [deny_opening_console.json](deny_opening_console.json)
* RAM users or RAM roles must use multi-factor authentication (MFA) when deleting certain resources --> [mfa_required.json](mfa_required.json)
* It is forbidden to modify user SSO configuration --> [user_sso_configuration.json](user_sso_configuration.json)
* It is forbidden to modify the role SSO configuration --> [role_sso_configuration.json](role_sso_configuration.json)
* It is forbidden to modify the delivery address of the operation audit and disable the delivery function --> [modify_actiontrail.json](modify_actiontrail.json)
* Forbid access to some network services --> [modify_networking.json](modify_networking.json)
* It is forbidden to create network resources with public network access capabilities, including EIP and NAT gateways --> [public_networking.json](public_networking.json)
* Prohibit access to network services connected to resources under the cloud --> [hybrid_cloud.json](hybrid_cloud.json)
* Forbid access to some functions of the cost center --> [cost_center.json](cost_center.json)
* It is forbidden to modify cloud monitoring configuration --> [monitoring_configuration.json](monitoring_configuration.json)
* Prohibition of purchasing reserved instance coupons --> [reserved_instances.json](reserved_instances.json)
* It is forbidden to create ECS instances in non-specified VPCs --> [ecs_instance_vpc.json](ecs_instance_vpc.json)
* Purchase of domain names is prohibited --> [domain_names.json](domain_names.json)
* Access to the cloud marketplace is forbidden --> [cloud_marketplace.json](cloud_marketplace.json)
* Prevent access to the ticket system --> [ticket_system.json](ticket_system.json)

## Contact
You can contact us [here](https://roopu.cloud/contact).
