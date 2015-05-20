### Prototype-1: Normal Workstation & Server
1. Use [rpm-ostree-toolbox](https://github.com/projectatomic/rpm-ostree-toolbox) to create a compose tree from the official Fedora 21 Workstation [kickstart file](https://git.fedorahosted.org/cgit/spin-kickstarts.git/tree/fedora-install-workstation.ks). It is likely that [Brent Baude's](http://developerblog.redhat.com/author/bbaude/) articles[^1][^2] on [RHT Developer Blog](http://developerblog.redhat.com/) will be helpful to this work.
1. Create a VM and install the ostree-based Fedora Workstation
1. Ensure that normal operation performs correctly, aside from installing new things
1. Repeat steps for Fedora Server
