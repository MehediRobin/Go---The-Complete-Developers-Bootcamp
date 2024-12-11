﻿# Go---The-Complete-Developers-Bootcamp

##A-few-go-command

go build - Compiles a bunch of go source code files
go run - Compiles and execute one or two files
go fmt - Formats all the code in each file
go install - Compiles and "installs" a package
go get - Downloads the raw source code of someone else's package
go test - Runs any tests associated with the current project

##Go-package

Package = Project == Workspace

A package is a collection of common source code files. A package consists of many files. Every file must declare the name of the package it belongs to in the very first line.

Two types of packages

Executable package - Generates a file that can be run. They are packages that can be compiled and then executed. They must have a func called main.

Reusable package - Code dependencies, libraries that we don't execute but use as helpers and put reusable logic 
