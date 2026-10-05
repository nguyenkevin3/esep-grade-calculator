# ESEP Grade Calculator

The ESEP Grade Calculator is a simple utility to calculate your final grade from the weighted average of assignments, exams, and essays. The numerical grade is then converted to a letter grade based on a grade scale.

## Runtime requirements:

Golang 1.24+

## Files:

go.mod: Defines module path and Go version

grade_calculator.go: Implements functionality for the calculator

grade_calculator_test.go: Unit tests for the calculator

## Run unit tests:

```
cd grade_calculator/
go test ./...
```

## Run unit tests with code coverage:

```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```
