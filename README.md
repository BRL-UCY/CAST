# CAST
CAST: an iterative algorithm for the complexity analysis of sequence tracts.  
Web server: http://structure.biol.ucy.ac.cy/CAST2  

## Compiling source
To compile the source code use:
```
gcc -o castv2 cast_v2.1.c
```

## Usage
```
./castv2 SequenceFile [options]
```

| Option | Description |
| :--- | :--- |
| -help | Print help text |
| -thr t | Set the threshold score for reported regions. Default is 40. Number (t) should be an integer |
| -stat | Outputs statistics information to file cast.stat |
| -tab | Outputs tab delimited statistics information to file [SequenceFile].tab |
| -soft | Soft mask the sequences (lowercase biased regions) |
| -skip s | Skip residue type after that many levels of iterations. Default is 0. Number (s) should be an integer |
| -matrix | Use different mutation matrix (.mat) file |
| -verbose | Verbose mode prints filtering information to standard output |
| -stderr | Verbose mode prints filtering information to standard error |





## Support
For support and feedback contact cast[at]ucy.ac.cy.  
Developed by Vasilis J. Promponas @ [BRL](http://troodos.biol.ucy.ac.cy)
