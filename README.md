# Task for a DevOps position

A simple MongoDB and MongoDB express cluster (with logging).

**NOTE:**

`no-provisioner` is something that shouldn't be used in production because it
does not support dynamic provisioning (doesn't scale), I was just asked to do
so. The proper way would be to use a cloud provider or set up a scalable network
filesystem and use one of Kubernetes' provided interfaces (like `GlusterFS` or `StorageOS`).
