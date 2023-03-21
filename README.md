## String and File Manipulation

### Trim whitespaces from the end of every line in a file
`sed 's/^[ \t]*//;s/[ \t]*$//' < file`

### Redirect output to a file and stdout
`bash script.sh | tee output.file`

## Javascript

### Duplicate an array

Let array `greetings` contain a single string called `Hello`. I want to test for when `greetings` contains 10 strings.

`[...greetings, ...greetings, ...greetings, ...greetings, ...greetings, ...greetings, ...greetings, ...greetings, ...greetings, ...greetings]`
