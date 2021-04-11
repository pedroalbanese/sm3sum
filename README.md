# SM3SUM(2)
## sm3sum Parallel Implementation written in Go

<PRE>
SM3 Keccak Hashsum Tool - ALBANESE Lab (c) 2020-2021

Usage of sha3sum:
sha3sum [-v] [-b N] [-c &lt;hash.ext&gt;] [-r] -t &lt;file.ext&gt;

  -b int
        Bits: 224, 256, 384 and 512. (default 224)
  -c string
        Check hashsum file.
  -r    Process directories recursively.
  -t string
        Target file/wildcard to generate hashsum list.
  -v    Verbose mode. (The exit code is always 0 in this mode)
  </PRE>
  
### Examples:

#### Generate hashsum list:
<pre>
$ ./sm3sum [-r] -t "*.*" > hash.txt
</pre>
##### Always works in binary mode. 

#### Check hashsum file:
<pre>
$ ./sm3sum [-v] -c hash.txt
</pre>
##### Exit code is always 0 in vebose mode. 
