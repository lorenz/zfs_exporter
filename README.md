# ZFS exporter

_ZFS metrics exporter for Prometheus_

:warning: **This is unstable and the exported metrics will definitely still change. It might also be
abandoned completely and merged into node_exporter**

## Notes

This currently exposes all basic stats (vdev_stats) and most extended stats (vdev_stats_ex) on a
vdev-level. It doesn't expose per-disk or per-zpool stats, even though these are also available from
the underlying API.
