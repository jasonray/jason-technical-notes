# jason-technical-notes

# How to use mac OS zip

To compress:
```
zip -r archive_name.zip stuff_to_compress -x stuff_to_ignore
```

`-r`: recure/include sub-directories
`-x`: a list of stuff to not include

Examples:
zip single file:
```
zip app.zip index.html 
```

zip a directory, but ignore the `.git` config info (arg, I am not getting the syntax to ignore a subdirectory)
```
zip -r app.zip ./ -x .git/
```
