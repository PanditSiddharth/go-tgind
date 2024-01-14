# go-tgind
Fully featured and Simplest go Telegram bot api for creating best telegram bots easily.

(in progress...)

## Install and use
```sh
go mod init yourpackagename
go get -u github.com/PanditSiddharth/go-tgind
```

### Add in go.mod file
require "github.com/PanditSiddharth/go-tgind"  v1.0.2

create main.go file
```go
package main

import "github.com/PanditSiddharth/go-tgind"

func main() {
    tgind.SayHello()
}
```

run by command
```sh
go run nain.go
```
