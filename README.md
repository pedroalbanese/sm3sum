# SM3SUM(2)
[![ISC License](http://img.shields.io/badge/license-ISC-blue.svg)](https://github.com/pedroalbanese/sm3sum/blob/master/LICENSE.md) 
[![GitHub downloads](https://img.shields.io/github/downloads/pedroalbanese/sm3sum/total.svg?logo=github&logoColor=white)](https://github.com/pedroalbanese/sm3sum/releases)
[![GoDoc](https://godoc.org/github.com/pedroalbanese/sm3sum?status.png)](http://godoc.org/github.com/pedroalbanese/sm3sum)
[![Go Report Card](https://goreportcard.com/badge/github.com/pedroalbanese/sm3sum)](https://goreportcard.com/report/github.com/pedroalbanese/sm3sum)
[![GitHub go.mod Go version](https://img.shields.io/github/go-mod/go-version/pedroalbanese/sm3sum)](https://golang.org)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/pedroalbanese/sm3sum)](https://github.com/pedroalbanese/sm3sum/releases)
### GM/T 0004-2012 SM3 Recursive Hasher
<PRE>
Usage of sm3sum:
sm3sum [-c &lt;hash.ext&gt;] [-r] &lt;file.ext&gt;
  -c string
        Check hashsum file
  -r    Process directories recursively
</PRE>
  
### Examples:

#### Generate hashsum list:
```sh
$ ./sm3sum [-r] "*.*" > hash.txt
```

#### Check hashsum file:
```sh
$ ./sm3sum -c hash.txt
$ echo $?
```

## License

This project is licensed under the ISC License.
##### Copyright (c) 2020-2022 Pedro F. Albanese - ALBANESE Research Lab.
