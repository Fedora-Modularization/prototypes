### Prototype-5: Investigate using dnf to create a new compose tree
In order to execute on this prototype in a reasonable way, we will need to declare a couple of tenets which, arguably, invalidate the test, but are still a good prototype while we devise a prototype that will test the tenets. 

First off, we are just going to be writing the new compose-tree to disk with some mechanism to verify its quality. In a later protoype we can worry about moving the compose-tree to "someplace" which could host a rebase to that tree.

Second, the ability of the existing compose-tree to meet the dependency graph of the new rpm may prove problematic. While the compose-tree installed on the local system should have an rpm database that can be used for the dependency walk, the rpm coming from an external repository may have new dependencies, or, perhaps more likely, new versions of existing dependencies. For this prototype, it is recommended that we just carefully select the rpms to avoid this problem.

1. Write a dnf plugin to front-end "rpm-ostree-toolbox." However, the input should be the existing compose-tree from the user's box and an rpm from a normal repo
2. The plugin should generate a new compose-tree including the existing components, the rpm selected, and dependencies walking the new rpm's dependency tree
