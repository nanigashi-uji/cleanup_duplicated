# cleanup_duplicated
Script to clean up Download folder by removing duplicated files.

Please try dry-run ( with `-n` option ) and check the file list to be removed.

```
%  ./cleanup_duplicated -h
[Usage] % cleanup_duplicated [options]
[Options]
           -d path   : Set target directory
           -D depth  : Set search depth (defalut: 2)
           -i        : invoke rm with -i optiond
           -n        : "Dryrun"-mode
           -v        : Show verbose output
           -m num    : Set possible maximum index
           -h        : Show Help (this message)
```
