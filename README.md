# Hi!🖐️ i am **yinlei** from China💕

I used to work on China Unicom Company.

```go 
package main 
import "fmt"

func main() {
    done := make(chan int, 1)
    go func() {
        fmt.Println("Hello, World!") 
        done <- 1 
    }()
    <-done
}
```

