# NumGo
**NumGo** is a Go library imitate *NumPy* in Python. We using this library do lots of science compute in Golang just as numpy does in Python.

⛳️⛳️⛳️ **NumGo** still under construct, will be release soon, but current progress can be used. 🚧🚧🚧 

# Modules
**NumGo** consist of various modules to achieve our purpose. Such as:
- random: all random functions;
- array: consist of 2-D array;
- math: all mathematic functions;
- matlib: mat library do matrix compute;
- ...

# Simple Usage
To using numgo is also quite simple:
```go
import (
    "jinfagang.github.com/numgo"
)

func main() {
    for _, v := range numgo.N(10){
        fmt.Println(v)
    }
}
```
Quite simple.

# Copyright
**NumGo** build by *Lucas Jin* with ❤️. Under Apache License.