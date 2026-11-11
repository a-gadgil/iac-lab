# iac-lab

Infrastructure as Code on Azure, built with four tools side by side: Terraform, OpenTofu, Bicep and Pulumi.

## Layout

| Folder | Tool | Language |
|--------|------|----------|
| `terraform/` | Terraform | HCL |
| `opentofu/` | OpenTofu | HCL |
| `bicep/` | Bicep | Bicep |
| `pulumi/` | Pulumi | Python |

## Comparison

| | Terraform | OpenTofu | Bicep | Pulumi |
|---|---|---|---|---|
| Language | HCL | HCL | Bicep DSL | Python (and others) |
| Cloud support | Multi-cloud | Multi-cloud | Azure only | Multi-cloud |
| State | State file (remote backend) | State file (remote backend) | Managed by Azure | Pulumi Cloud or self-hosted backend |
| License | BUSL | MPL (open source) | MIT | Apache 2.0 |

## Notes

Add your own pros and cons for each tool here after working with them.