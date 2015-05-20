### Prototype-7: Update existing compose-tree and add new rpm
The need for this prototype is to address the second tenet in Prototype-5. We may discover in the work to do Prototype-5 that the composition of rpms in to the new compose-tree just as easily uses the upstream repository directly as using the locally installed tree. If so, then this prototype is unnecessary or "marked complete" based on those results.
1. Leveraging the work from Prototypes 5 & 6, identify an rpm that has changed or updated dependencies in the upstream repository
2. As part of the update to the compose, layer in the changed rpm dependencies and the new rpm and its dependencies
3. Host the compose-tree per Prototype-6
4. Rebase to the new compose-tree 
5. Rebase back to the old compose-tree
