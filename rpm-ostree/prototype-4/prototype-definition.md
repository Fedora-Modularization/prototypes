### Prototype-4: Investigate using dnf to switch compose-trees
1. Create a plugin for dnf that front-ends "rpm-ostree rebase"
2. Create an alternate compose-tree with a significant component change. For example, tuned or a different version of Gnome
3. Attempt to rebase to the new compose tree using dnf
4. Attempt to rebase back to the old compose tree using dnf
