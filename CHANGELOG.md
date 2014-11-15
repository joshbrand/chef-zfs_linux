zfs_linux Cookbook CHANGELOG
========================
This file is used to list changes made in each version of the zfs_linux cookbook.

v2.0.0 (2014-11-14)
------------------
- Remove attribute driven snapshot-pruning recipe; replaced with zfs_linux_snapshot resource.
  - Previous deployments of the snapshot-pruning recipe will need to manually remove stale /etc/cron.daily/zfs-auto-prune... files.
- Dropped RHEL support for now
