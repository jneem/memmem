memmem
======

This is a crate for substring searching (with functionality similar to the
`memmem` function in C). So far, it only contains a copy of the two-way search
implementation from rust's standard library (but with an API that allows
searching in `&[u8]`). Eventually, we plan to provide other searching
algorithms, and possibly also some heuristics to choose a good searching
algorithm based on the substring we are looking for.
