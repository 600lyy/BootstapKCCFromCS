# Install Config Sync
Config Sync will be installed to your GKE clusters by runnning `install.sh`. Before that, you need to update the cluster name and zone location in the file.

`apply-spec.yaml` includes the initial configurations that config sync will use, in particulr, the root repo to watch

