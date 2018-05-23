# `go_licenses`
A tiny library to return standard licenses as a string.

## Installation
`go get github.com/warrenhodg/go_licenses`

## Usage example
```
package main

import (
    "fmt"
    "github.com/warrenhodg/go_licenses"
)

func main() {
    var copyrightYear = 2018
    var copyrightHolder = "Warren Hodgkinson"
    fmt.Printf(license.Mit(copyrightYear, copyrightHolder))
}
```
