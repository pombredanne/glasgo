# Go Static Analysis Tool

## Project

This is a static analysis tool written in Go for Go code.  It will find security and some correctness issues that may have a 
security implication.

## Compiling

To compile the tool, be sure to have the Go compiler first.

1. Use `Go build` for a local binary
2. Use `Go install` to compile and install in Go Path

## Using the tool

For now, all tests are run.

~~~
Go-Tool directory1, directory2
~~~

or

~~~
Go-Tool file1.go, file2.go
~~~

`Note:` The tool does not run on both directories and individual files

## Architecture

tbd

## Tests

* `error` - errors ignored

## Design Choices

see the wiki

## Updates

Initial wave of tests have been uploaded and checked on test data

More tests to come

## to do

* add tests
* document tests
* document design choices

