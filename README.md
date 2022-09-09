# Install Config Sync
Config Sync will be installed to your GKE clusters by runnning `install.sh`. Before that, you need to update the cluster name and zone location in the file.
Besides Config Sync, `install.sh` also generates a secret that's linked to your git token to authenticate the config sync to your repos

`apply-spec.yaml` includes the initial configurations that config sync will use. The installation will automatically create a RootSync syncing from the repo/dir sepcified in the `apply-spec.yaml`. 
In this example, https://github.com/600lyy/BootstapKCCFromCS/cluster is the central root repo.

Should you need more RootSync, creat a RootSync object with a unique name and place the yaml spec in the central root repo.

