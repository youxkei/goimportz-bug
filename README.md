## How to reproduce
```bash
$ go run github.com/zchee/goimportz/cmd/goimportz a.go
package main

import (
	"example.com/hoge-a"
	hogea "example.com/hoge-a"
)

func f() {
	hogea.F()
}
```
