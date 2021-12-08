# SM3SUM(2)
[![ISC License](http://img.shields.io/badge/license-ISC-blue.svg)](https://github.com/pedroalbanese/sm3sum/blob/master/LICENSE.md) 
[![GoDoc](https://godoc.org/github.com/pedroalbanese/sm3sum?status.png)](http://godoc.org/github.com/pedroalbanese/sm3sum)
[![Go Report Card](https://goreportcard.com/badge/github.com/pedroalbanese/sm3sum)](https://goreportcard.com/report/github.com/pedroalbanese/sm3sum)
[![GitHub go.mod Go version](https://img.shields.io/github/go-mod/go-version/pedroalbanese/sm3sum)](https://golang.org)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/pedroalbanese/sm3sum)](https://github.com/pedroalbanese/sm3sum/releases)
### GM/T 0004-2012 - SM3 Hashsum Tool
<PRE>
Usage of sha3sum:
sm3sum [-v] [-c &lt;hash.ext&gt;] [-r] &lt;file.ext&gt;
  -c string
        Check hashsum file
  -r    Process directories recursively
  -v    Verbose mode (for CHECK command)
</PRE>
  
### Examples:

#### Generate hashsum list:
```sh
$ ./sm3sum [-r] "*.*" > hash.txt
```
##### Always works in binary mode. 

#### Check hashsum file:
```sh
$ ./sm3sum [-v] -c hash.txt
```
##### Exit code is always 0 in vebose mode. 

## License

This project is licensed under the ISC License.
##### Copyright (c) 2020-2021 Pedro Albanese - ALBANESE Lab.
