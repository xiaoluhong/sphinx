---
title: Removing Rancher
weight: 5000
---

When you deploy Rancher and use it to provision clusters, Rancher installs its components on the nodes you use. This section features instructions on how to remove Rancher's components from your nodes that you no longer want to use with Rancher. 

There are two contexts in which you'd remove Rancher from a Kubernetes cluster node.

- [Removing Rancher Components from Rancher Launched Kubernetes Clusters]({{< baseurl >}}/rancher/v2.x/en/admin-settings/removing-rancher/user-cluster-nodes/)

    In this context, you are removing Rancher components from Kubernetes clusters that you [launched using Rancher]({{< baseurl >}}/rancher/v2.x/en/cluster-provisioning/rke-clusters/).

- [Removing Rancher from Your Rancher Server Nodes]({{< baseurl >}}/rancher/v2.x/en/admin-settings/removing-rancher/rancher-cluster-nodes/)

    In this context, you are removing Rancher from the Kubernetes cluster that you configured for your [Rancher installation]({{< baseurl >}}/rancher/v2.x/en/installation/ha/).
