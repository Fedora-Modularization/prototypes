### Prototype-2: Normal Workstation & Server update
1. Using the VM and compose tree from the "Normal Workstation" use case, introduce an updated rpm in to the tree
1. Ensure that "[rpm-ostree upgrade](https://github.com/projectatomic/rpm-ostree/blob/master/doc/administrator-handbook.md)" (or "[atomic host upgrade](https://github.com/projectatomic/atomic/blob/master/docs/atomic-host.1.md)") successfully update the system with the new rpm.
1. Ensure that the rpm can be reverted by executing a "rpm-ostree rollback" (or "atomic host rollback")
1. Repeat steps for Fedora Server
