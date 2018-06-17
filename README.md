# CAST
CAST: an iterative algorithm for the complexity analysis of sequence tracts
See: http://structure.biol.ucy.ac.cy/CAST2

## Usage
./castv_v2.1 SequenceFile [options]

-help    ... print this text
-thr t   ... set the threshold score for reported regions
                              default is 40
                              t should be an integer number
-stat    ... outputs statistics information to file cast.stat
-tab     ... outputs tab delimited statistics information to file [SequenceFile].tab
-soft     ... soft mask the sequences (lowercase biased regions)                 
-skip s  ... skip residue type after that many levels of iterations
                              default is 0
                              s should be an intege                         
                 -matrix  ... use different mutation matrix (.mat) file
                 -verbose ... verbose mode prints filtering information to standard output
                 -stderr  ... verbose mode prints filtering information to standard error
