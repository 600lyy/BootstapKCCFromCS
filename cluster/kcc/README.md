To bootstrp KCC, run setup-config-connector.sh. Before that, update the cluster name and zone location in the file.

To run KCC using namespaced mode, create a configconnnector.yaml and place it under cluster/kcc. Config Sync is syncing from this sub-folder and will apply this spec yaml to all clusters