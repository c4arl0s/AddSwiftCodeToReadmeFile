# AddSwiftCodeToReadmeFile

Add Swift Code To Readme File

## Example:

``` bash
ls -1 | sort -r | while read file; do echo "\`\`\` swift"; cat $file; echo "\`\`\`; echo ""; done >> README.md
```

