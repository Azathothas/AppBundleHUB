### Portable AppBundles! For everyone!
- They are portable because they use an Alpine ROOTFS to which the desired program has been added & they use `bwrap` in order to execute it.
- Some are multicall because they are generated with the --multicall (or -c) flag of pelfCreator
- Other AppBundles here are simply AppImages based on Conty that are converted to the AppBundle format (thus getting rid of a lot of overhead)
- Other AppBundles may also be generated by pelfCreator but we get rid of their rootfs & container since they're not needed for a lot of purposes
