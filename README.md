# LinOps

[![Build Status](https://travis-ci.org/jagot/LinOps.jl.svg?branch=master)](https://travis-ci.org/jagot/LinOps.jl)

Very simple implementation of linear operators, that is, operations of
the kind y <- (αA + βB)x, designed to mutate y in-place, using
appropriate BLAS operations, where available. Should work with dense
and sparse arrays out-of-the box, and CUDA dense and sparse arrays, if
CUDArt, CUBLAS, and CUSPARSE are available.

For a more comprehensive support, but with other focus and not really
in-place mutation, see
[LinearOperators.jl](https://github.com/JuliaSmoothOptimizers/LinearOperators.jl).
