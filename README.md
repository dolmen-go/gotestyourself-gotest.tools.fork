# Go Test Yourself

A collection of packages compatible with `go test` to support common testing
patterns.

[![GoDoc](https://godoc.org/github.com/gotestyourself/gotestyourself?status.svg)](https://godoc.org/github.com/gotestyourself/gotestyourself)
[![CircleCI](https://circleci.com/gh/gotestyourself/gotestyourself/tree/master.svg?style=shield)](https://circleci.com/gh/gotestyourself/gotestyourself/tree/master)
[![Go Reportcard](https://goreportcard.com/badge/github.com/gotestyourself/gotestyourself)](https://goreportcard.com/report/github.com/gotestyourself/gotestyourself)


## Packages

* `fs` - create test files and directories
* `golden` - compare large multi-line strings
* `gotestsum` - a program to summarize `go test` output and test failures
* [icmd](http://godoc.org/github.com/gotestyourself/gotestyourself/icmd) -
  execute binaries and test the output
* `skip` - skip tests based on conditions


## Related

* [testify/assert](https://godoc.org/github.com/stretchr/testify/assert) and 
  [testify/require](https://godoc.org/github.com/stretchr/testify/require) -
  assertion libraries with common assertions
* [golang/mock](https://github.com/golang/mock) - generate mocks for interfaces
* [testify/suite](https://godoc.org/github.com/stretchr/testify/suite) - 
  group test into suites to share common setup/teardown logic
