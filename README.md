config
======

Package config provides convenient access methods to configuration
stored as JSON or YAML.

Original version you cat find at [godoc.org](http://godoc.org/github.com/moraes/config).

This version extends the functionality of the original without losing compatibility.
Major features added:

- `Set(path string, value interface{})` method
- `Env()` method, for OS environment variables parsing
- `Flag()` method, for command line arguments parsing

Example and more information you can get [here](http://godoc.org/github.com/olebedev/config).
