# pointer

Get pointers to objects of built-in Golang types.

### Example
```go
package main

import "github.com/IamFaizanKhalid/pointer"

func main() {
    strPtr := pointer.String("my-string")
    intPtr := pointer.Int(1)
	...
}
```


<hr>

Based on [github.com/aws/aws-sdk-go](https://raw.githubusercontent.com/aws/aws-sdk-go/main/aws/convert_types.go).
