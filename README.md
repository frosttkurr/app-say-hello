# Learn how to use modules with different kind of version

Do not forget to use this line of code

go get <modules_url>
Example:
go get github.com/frosttkurr/go-say-hello
or
go get github.com/frosttkurr/go-say-hello/v2

Then, import modules on the projects
Example: 
import (
  go_say_hello "github.com/frosttkurr/go-say-hello/v2"
)
