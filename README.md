# crawler# Hybrid Bridge (Providers → NetBox → Ansible)

Source of truth: NetBox. Discovery: Azure, VMware, Proxmox. Automation: Ansible (NetBox inventory plugin).
This repo tracks the product roadmap, issues, and docs.

## Architecture
Providers → (Connectors) → NetBox (CMDB/IPAM) → Ansible (dynamic inventory) → Playbooks (patch/compliance)

## Links
- NetBox inventory plugin: netbox.netbox.nb_inventory
- Primary fields we standardize: ext_id, ext_provider, env/role/provider/os tags
