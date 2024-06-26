<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >= 1.8.0 |
| <a name="requirement_proxmox"></a> [proxmox](#requirement\_proxmox) | 0.54.0 |

## Providers

No providers.

## Modules

| Name | Source | Version |
|------|--------|---------|
| <a name="module_NAS"></a> [NAS](#module\_NAS) | ./modules/cloud-init-vm | n/a |
| <a name="module_almalinux9"></a> [almalinux9](#module\_almalinux9) | ./modules/image | n/a |
| <a name="module_fedora40"></a> [fedora40](#module\_fedora40) | ./modules/image | n/a |
| <a name="module_testvm"></a> [testvm](#module\_testvm) | ./modules/cloud-init-vm | n/a |

## Resources

No resources.

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_nas_addr"></a> [nas\_addr](#input\_nas\_addr) | n/a | `string` | n/a | yes |
| <a name="input_password"></a> [password](#input\_password) | Proxmox Web UI password | `string` | n/a | yes |
| <a name="input_proxmox_endpoint"></a> [proxmox\_endpoint](#input\_proxmox\_endpoint) | Endpoint to Proxmox Web UI | `string` | n/a | yes |
| <a name="input_ssh_key"></a> [ssh\_key](#input\_ssh\_key) | Path to SSH private key for Proxmox node | `string` | n/a | yes |
| <a name="input_ssh_public_key"></a> [ssh\_public\_key](#input\_ssh\_public\_key) | Path to SSH public key for use in VM modules | `string` | n/a | yes |
| <a name="input_ssh_username"></a> [ssh\_username](#input\_ssh\_username) | SSH username for Proxmox node | `string` | n/a | yes |
| <a name="input_target_node"></a> [target\_node](#input\_target\_node) | n/a | `string` | n/a | yes |
| <a name="input_username"></a> [username](#input\_username) | Proxmox Web UI username | `string` | n/a | yes |
| <a name="input_vm_gw"></a> [vm\_gw](#input\_vm\_gw) | n/a | `string` | n/a | yes |
| <a name="input_vm_username"></a> [vm\_username](#input\_vm\_username) | Username for user in VM modules | `string` | n/a | yes |
| <a name="input_vm_vlan_id"></a> [vm\_vlan\_id](#input\_vm\_vlan\_id) | VLAN ID for VM subnet | `number` | n/a | yes |

## Outputs

No outputs.
<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
