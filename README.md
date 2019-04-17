# Compiler-benchmark-suites
A list of benchmark suites used in the research related to compilers, program performance, scientific computations etc.

## Benchmark suites

| Benchmark                                                                                 | Lang    | Published in     | Content          | Additional info                                                                                                                                                |
|-------------------------------------------------------------------------------------------|---------|------------------|------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [LCALS v1.0.2](https://computation.llnl.gov/projects/co-design/download/lcals-v1.0.2.tgz) | C       | [_Hornung2013_]  | 32 loops         | For analysis of compiler optimisations; modern extension to _Livermore loops_                                                                                  |
| [Livermore loops (LFK)](https://www.netlib.org/benchmark/livermore)                       | FORTRAN | [_McMahon1986_]  | 24 loops         | For performance analysis                                                                                                                                       |
| [Livermore loops](https://www.netlib.org/benchmark/livermorec)                            | C       | 1992             | 24 loops         | Port to C                                                                                                                                                      |
| [TSVC](https://www.netlib.org/benchmark/vectord)                                          | FORTRAN | [_Callahan1988_] | 135 loops        | For testing automatic vectorizing compilers; [Single precision version](https://www.netlib.org/benchmark/vectors)                                              |
| [TSVC](http://polaris.cs.uiuc.edu/~maleki1/TSVC.tar.gz)                                   | C       | [_Maleki2011_]   | 151 loops        | Extended port to C                                                                                                                                             |
| [TSVC 2](https://github.com/UoB-HPC/TSVC_2)                                               | C       | 2015             | 151 loops        | Update to TSVC in C                                                                                                                                            |
| [UTDSP](http://www.eecg.toronto.edu/~corinna/DSP/infrastructure/UTDSP.tar.gz)             | C       | 1992             | 6 loops, 12 apps | For testing compilers on Digitial Signal Processing (DSP) applications; [more information](http://www.eecg.toronto.edu/~corinna/DSP/infrastructure/UTDSP.html) |

## Collections of benchmarks

* [Benchmark@Netlib.org](http://www.netlib.org/benchmark/)
* [Benchmarks by Nikolaos Kavvadias](http://www.nkavvadias.com/benchmarks.html#benchmarks)

## References

* [_Callahan1988_] Callahan, D., Dongarra, J., & Levine, D. (1988). Vectorizing compilers: a test suite and results. In Proceedings. SUPERCOMPUTING ’88 (pp. 98–105). IEEE Comput. Soc. Press. https://doi.org/10.1109/SUPERC.1988.44642
* [_Hornung2013_] Richard D. Hornung and Jeffrey A. Keasler, “A Case for Improved C++ Compiler Support to Enable Performance Portability in Large Physics Simulation Codes”, LLNL-TR-635681 (2013).
* [_Maleki2011_] Maleki, S., Gao, Y., Garzarán, M. J., Wong, T., & Padua, D. A. (2011). An evaluation of vectorizing compilers. Parallel Architectures and Compilation Techniques - Conference Proceedings, PACT, 7, 372–382. https://doi.org/10.1109/PACT.2011.68
* [_McMahon1986_] F. H. McMahon. Livermore fortran kernels: A computer test of numerical performance range. Technical Report UCRL-53745, Lawrence Livermore National Laboratory, Livermore, CA, December 1986; __COMMENT__: no PDF on the web.