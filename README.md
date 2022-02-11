# go-logger
Logs your data to stdout and log folder in suitable for Elastic search format


## Usage
Add APP_NAME="Some name" to project .env file
Make sure you have ./logs directory

```
package main
import "github.com/appio-go/logger"

func main(){
	var l logger.Logger
	l.Print("Logname", "info", "/your/request/url", "192.168.0.1", "User identifier", "Hello world, im logger")
}
```
