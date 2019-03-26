# AddSwiftCodeToReadmeFile

Add Swift Code To Readme File with only one instruction on command line.

## Example:

``` bash
ls -1 | sort -r | while read file; do echo "\`\`\` swift"; cat $file; echo "\`\`\`; echo ""; done >> README.md
```

- ls -1 : Display one entry per line. 
- sort -r : Sort in reverse order.
- while read file : it creates file variable, read it and do it while read it.
- use for each line of bash code a ; 

