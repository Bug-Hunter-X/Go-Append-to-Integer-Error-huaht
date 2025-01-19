# Go Append to Integer Error

This repository demonstrates a common error in Go: attempting to append to an integer variable.  The code in `bug.go` attempts to append the value `1` to an integer variable, which is invalid in Go. The correct approach is shown in `bugSolution.go`, where a slice is used instead of an integer.

## How to Reproduce
1. Clone the repository.
2. Run `go run bug.go`. This will produce a compile-time error.
3. Run `go run bugSolution.go`. This will execute successfully, printing `[1]`
