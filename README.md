## String and File Manipulation

### Trim whitespaces from the end of every line in a file
`sed 's/^[ \t]*//;s/[ \t]*$//' < file`

### Redirect output to a file and stdout
`bash script.sh | tee output.file`
