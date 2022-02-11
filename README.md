# go-logger
Loggs your data to stdout and log folder in sutable for Elastic search format


## Usage
package main

```
import "github.com/appio-go/logger"

func main(){
	var l logger.Logger
	l.Print("Logname", "info", "/your/request/url", "192.168.0.1", "User identifier", "Hello world, im logger")
}
```
