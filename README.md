# CAST
CAST: an iterative algorithm for the complexity analysis of sequence tracts
See: http://structure.biol.ucy.ac.cy/CAST2

## Usage
./castv_v2.1 SequenceFile [options]

-help    Print help text
-thr t   Set the threshold score for reported regions. Default is 40. Number should be an integer
-stat    Outputs statistics information to file cast.stat
-tab     Outputs tab delimited statistics information to file [SequenceFile].tab
-soft    Soft mask the sequences (lowercase biased regions)                 
-skip s  Skip residue type after that many levels of iterations. Default is 0. Number should be an integer                         
-matrix  Use different mutation matrix (.mat) file
-verbose Verbose mode prints filtering information to standard output
-stderr  Verbose mode prints filtering information to standard error
