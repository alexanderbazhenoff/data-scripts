## Backup scripts

A tiny infrastructure-ready tools for backup, restore and maintenance your data.

- [**backup_lxc_and_filesystem_path**](backup/backup_lxc_and_filesystem_path/README.md) - backup, encrypt and
restore filesystem path to remote drives with UID/GUI storing (especially for containers) on Linux systems.
- [**bareos_pool_operations**](backup/bareos_pool_operations/README.md) - batch process to remove and clean-up
[Bareos](https://www.bareos.com/) volumes in the pool.
- [**calculate_and_check_md5**](backup/calculate_and_check_md5) - calculate and check md5 of required folder.
- [**gitlab_dump_and_restore**](backup/gitlab_dump_and_restore/README.md) - create GitLab dump and restore gitlab from 
a dump.
- [**kvm_vm_backup**](backup/kvm_vm_backup/README.md) - backup running or stopped
[Kernel Virtual Machine (KVM)](https://www.linux-kvm.org/page/Main_Page) instance(s) on Linux systems.

## Network scripts

Configure and collect network settings on linux systems.

- [**get_dhcp_leases**](network/get_dhcpd_leases/README.md) - get leases info from isc-dhcp server including client, 
expiration and client vendor.
- [**inner_vps_bridge**](network/inner_vps_bridge/README.md) - example how to organize the network inside your VPS by
linux bridge.
- [**vlan_filtered_bridges**](network/vlan_filtered_bridges/README.md) - systemd unit and script to create bridge with
VLAN filtering to prevent MAC-table overflow on the host. Actually this is an example how to organize linux bridges by
script.

## Visualization scripts

Visualization and stats scripts.

- [**traffic_item_stat_and_graph**](visualization/traffic_item_stat_and_graph/README.md) - script that build traffic
item  statistics on the graph from [IxNetwork server](https://support.ixiacom.com/version/ixnetwork-916) CSV results
file.
