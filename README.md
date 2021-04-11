# SM3SUM(2)
## sm3sum Parallel Implementation written in Go
### Chinese National Standard
#### GM/T 0004-2012 - SM3 Message digest algorithm. 256-bit hash value.

#### Usage:
<PRE>
SM3 Hash Algorithm Tool - ALBANESE Lab (c) 2020-2021

Usage of sha3sum:
sm3sum [-v] [-b N] [-c &lt;hash.ext&gt;] [-r] -t &lt;file.ext&gt;

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
