# google-search [![GoDoc](http://godoc.org/github.com/rocketlaunchr/google-search?status.svg)](http://godoc.org/github.com/rocketlaunchr/google-search)[![Go Report Card](https://goreportcard.com/badge/github.com/rocketlaunchr/google-search)](https://goreportcard.com/report/github.com/rocketlaunchr/google-search)

Quickly scrape Google Seach Results.

⭐ **the project to show your appreciation.**

## Example

```go
package main

import (
	"context"
	"fmt"
	"github.com/rocketlaunchr/google-search"
)

func main() {
	ctx := context.Background()
	fmt.Println(googlesearch.Search(ctx, "optometrist"))
}
```


Other useful packages
------------

- [dataframe-go](https://github.com/rocketlaunchr/dataframe-go) - Statistics and data manipulation
- [dbq](https://github.com/rocketlaunchr/dbq) - Zero boilerplate database operations for Go
- [electron-alert](https://github.com/rocketlaunchr/electron-alert) - SweetAlert2 for Electron Applications
- [igo](https://github.com/rocketlaunchr/igo) - A Go transpiler with cool new syntax such as fordefer (defer for for-loops)
- [mysql-go](https://github.com/rocketlaunchr/mysql-go) - Properly cancel slow MySQL queries
- [react](https://github.com/rocketlaunchr/react) - Build front end applications using Go
- [remember-go](https://github.com/rocketlaunchr/remember-go) - Cache slow database queries
