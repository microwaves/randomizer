# Randomizer

Randomizer generates random stuff. To use it, install the package:

[![Build Status](https://travis-ci.org/microwaves/randomizer.svg?branch=master)](https://travis-ci.org/microwaves/randomizer)

```
$ go get [-u] vvoid.pw/randomizer
```

Then, import on your code:

```golang
package main

import (
    "fmt"
    
    "vvoid.pw/randomizer"
)

func main() {
    // random strings
    // n is the amount of chars for the output
    n := 10
    fmt.Println(randomizer.GenerateRandomString(n))

    // random and cute UUIDs based on /dev/urandom
    fmt.Println(randomizer.GenerateUUID())
}
```

## Author

Stephano Zanzin <sz@shitty.pizza>

## License

Please, refer to the [LICENSE](LICENSE) file.
