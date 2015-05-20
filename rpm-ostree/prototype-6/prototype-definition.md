### Prototype-6:  Use dnf to "host" compose-trees
1. Leveraging a dnf plugin, likely the same one as from Prototype-5, create and manage a location on disk to manage ostrees.
2. Using the dnf plugin and the compose-tree from Prototype-5, setup the compose-tree to be a target for rebasing of the local system
3. Use the new compose-tree to rebase
4. Rebase back to the old compose-tree
