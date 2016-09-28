# 0.1.3

* FIX 63 using memory limit for function target algorithms (broken since 0.1.1)

# 0.1.2

* FIX 58 output of the final statistics
* FIX 56 using the command line target algorithms (broken since 0.1.1)
* FIX 50 as variance prediction, we use the average predicted variance across the instances

# 0.1.1

* NEW leading ones examples
* NEW raise exception if unknown parameters are given in the scenario file
* FIX 17/26/35/37/38/39/40/46
* CHANGE requirement of ConfigSpace package to 0.2.1
* CHANGE cutoff default is now None instead of 99999999999


# 0.1.0

* Moved to github instead of bitbucket
* ADD further unit tests
* CHANGE Stats object instead of static class
* CHANGE requirement of ConfigSpace package to 0.2.0
* FIX intensify runs at least two challengers
* FIX intensify skips incumbent as challenger
* FIX Function TAE runner passes random seed to target function
* FIX parsing of emtpy lines in scenario file

# 0.0.1

* initial release