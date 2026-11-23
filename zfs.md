# ZFS

- `zpool status -v`
- Snapshot: `zfs snapshot tank/data@$(date +%F)`
- Send/recv til NAS: `zfs send -i @gammel @ny | ssh nas zfs recv tank/backup`
