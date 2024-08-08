# SuperLSH

## How to Install

`pip install superlsh`

## Motivation

Inspired by the use of super-feature sketching in deduplication candidate detection as implemented in [Finesse](https://www.usenix.org/system/files/fast19-zhang.pdf) deduplication and well summarized in a successor methodology [DeepSketch](https://www.usenix.org/system/files/fast22-park.pdf). 

Sometimes you just want to tell if two pieces of data are similar. Instead of jumping through the hoops of all the features of available LSH libraries, simply call `superlsh.lsh(data)` and likely receive an identical hash if the pieces of data only differ across limited segments.  

##
A one line python solution for locality sensitive hashing utilizing the superfeature approach.
