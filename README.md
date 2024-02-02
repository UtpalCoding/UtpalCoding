<h5 align="center"><b>MY INFORMATION</b></h5>

```go
package main

import "fmt"

type Person struct {
  name string
  username string
  age int
  hobbies []string
  job string
}

func main() {
  var me = new(Person)
  
  me.name     = "U7P4L 1N"
  me.username = "U7P4L-IN"
  me.age      = "20"
  me.job      = "ai developer | web developer"
  me.hobbies  = []string{"code", "anime", "music"," singing"}
  
  fmt.Println(me)
}
```
