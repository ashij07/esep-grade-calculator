# ESEP Grade Calculator

This library is a simple utility to calculate your grades.

Installating Go for MacOS:
First install homebrew package manager
To check if it's already installed, run: brew --version 
Once homebrew is installed, to install go run the command: brew install go 

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