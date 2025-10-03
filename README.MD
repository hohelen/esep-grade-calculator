# ESEP Grade Calculator

This project is a lightweight Go library that calculates a student's final grade. It takes in assignments, exams, and essays, and computes the weighted average. It converts the weighted average into a letter grade from A to F.

Within the repository are the following files:
- go.mod: Defines the module and Go version used
- grade_calculator.go: Implements the GradeCalculator with methods to add grades, calculate averages, apply weights, and return a letter grade
- grade_calculator_test.go: Contains unit tests that check whether the GradeCalculator returns the correct letter grade for different inputs

Runtime requirements:
Golang 1.24+

Run unit tests:
```
cd grade_calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```
