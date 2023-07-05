# fleet-ui-extensions

This Fleet-ifies:

* Enabling the UI Extensions Operator on Rancher's `local` cluster.
* Adding the repo to have point-and-click install of other extensions (Kubewarden, Elemental, etc.)
* Install `stigatron-ui` extension onto Rancher.

## Installation

1. Log into Rancher as an admin user.
2. Select the `local` cluster from Explore Cluster.
3. In the upper-right hand, select the `Import YAML` file.
4. Copy the contents of [gitrepo.yaml](./gitrepo.yaml) into the box and click `Okay`.
