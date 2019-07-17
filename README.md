# Compiler-benchmark-suites
A list of benchmark suites (and some loose kernels) used in the research related to compilers, program performance, scientific computations etc.

## Benchmark suites

| Benchmark                                                                                                                  | Lang                      | Platform | Published in        | Content          | Additional info                                                                                                                                                                                                                                        |
|----------------------------------------------------------------------------------------------------------------------------|---------------------------|----------|---------------------|------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [LCALS v1.0.2](https://computation.llnl.gov/projects/co-design/download/lcals-v1.0.2.tgz)                                  | C                         | CPU      | [_Hornung2013_]     | 32 loops         | For analysis of compiler optimisations; modern extension to _Livermore loops_; [more information](https://computation.llnl.gov/projects/co-design/lcals)                                                                                               |
| [Livermore loops (LFK)](https://www.netlib.org/benchmark/livermore)                                                        | FORTRAN                   | CPU      | [_McMahon1986_]     | 24 loops         | For performance analysis                                                                                                                                                                                                                               |
| [Livermore loops](https://www.netlib.org/benchmark/livermorec)                                                             | C                         | CPU      | 1992                | 24 loops         | Port to C                                                                                                                                                                                                                                              |
| [PolyBench/C 4.2](https://sourceforge.net/projects/polybench/files/polybench-c-4.2.tar.gz/download)                        | C                         | CPU      | 2010                | 30 kernels       | For the analysis of performance and compiler optimisations (especially related to polyhedra compilation); [more information](http://web.cse.ohio-state.edu/~pouchet.2/software/polybench/); [SourceForge](https://sourceforge.net/projects/polybench/) |
| [PolyBench/Fortran 1.0](http://web.cse.ohio-state.edu/~pouchet.2/software/polybench/download/polybench-fortran-1.0.tar.gz) | FORTRAN                   | CPU      | 2011                | 30 kernels       | Port to FORTRAN; [more information](http://web.cse.ohio-state.edu/~pouchet.2/software/polybench/polybench-fortran.html)                                                                                                                                |
| [PolyBench/GPU 1.0](http://www.cse.ohio-state.edu/~pouchet/software/polybench/download/polybench-gpu-1.0.tar.gz)           | C, CUDA, OpenCL, OpenHMPP | CPU, GPU | [_Grauer-Gray2012_] | 15 kernels       | Port to heterogeneous architectures; [more information](http://web.cse.ohio-state.edu/~pouchet.2/software/polybench/GPU/index.html)                                                                                                                    |
| [TSVC](https://www.netlib.org/benchmark/vectord)                                                                           | FORTRAN                   | CPU      | [_Callahan1988_]    | 135 loops        | For testing automatic vectorizing compilers; [Single precision version](https://www.netlib.org/benchmark/vectors)                                                                                                                                      |
| [TSVC](http://polaris.cs.uiuc.edu/~maleki1/TSVC.tar.gz)                                                                    | C                         | CPU      | [_Maleki2011_]      | 151 loops        | Extended port to C                                                                                                                                                                                                                                     |
| [TSVC 2](https://github.com/UoB-HPC/TSVC_2)                                                                                | C                         | CPU      | 2015                | 151 loops        | Update to TSVC in C                                                                                                                                                                                                                                    |
| [UTDSP](http://www.eecg.toronto.edu/~corinna/DSP/infrastructure/UTDSP.tar.gz)                                              | C                         | CPU      | 1992                | 6 loops, 12 apps | For testing compilers on Digitial Signal Processing (DSP) applications; [more information](http://www.eecg.toronto.edu/~corinna/DSP/infrastructure/UTDSP.html)                                                                                         |

### Full names

* LCALS — Livermore Compiler Analysis Loop Suite
* LFK — Livermore FORTRAN Kernels
* PolyBench — The Polyhedral Benchmark Suite
* TSVC — Test Suite for Vectorizing Compilers

## Collections of benchmarks

* [Benchmark@Netlib.org](http://www.netlib.org/benchmark/)
* [Benchmarks by Nikolaos Kavvadias](http://www.nkavvadias.com/benchmarks.html#benchmarks)

## Collections of loose kernels

* [RRZE-HPC/Kerncraft](https://github.com/RRZE-HPC/kerncraft/tree/master/examples/kernels)
* [ucb-bar/opencl-kernels](https://github.com/ucb-bar/opencl-kernels)

## References

* [_Callahan1988_] Callahan, D., Dongarra, J., & Levine, D. (1988). Vectorizing compilers: a test suite and results. In Proceedings. SUPERCOMPUTING ’88 (pp. 98–105). IEEE Comput. Soc. Press. https://doi.org/10.1109/SUPERC.1988.44642
* [_Grauer-Gray2012_] Scott Grauer-Gray, Lifan Xu, Robert Searles, Sudhee Ayalasomayajula, and John Cavazos. Auto-tuning a High-Level Language Targeted to GPU Codes. Proceedings of Innovative Parallel Computing (InPar '12), 2012.
* [_Hornung2013_] Richard D. Hornung and Jeffrey A. Keasler, “A Case for Improved C++ Compiler Support to Enable Performance Portability in Large Physics Simulation Codes”, LLNL-TR-635681 (2013).
* [_Maleki2011_] Maleki, S., Gao, Y., Garzarán, M. J., Wong, T., & Padua, D. A. (2011). An evaluation of vectorizing compilers. Parallel Architectures and Compilation Techniques - Conference Proceedings, PACT, 7, 372–382. https://doi.org/10.1109/PACT.2011.68
* [_McMahon1986_] F. H. McMahon. Livermore fortran kernels: A computer test of numerical performance range. Technical Report UCRL-53745, Lawrence Livermore National Laboratory, Livermore, CA, December 1986; __COMMENT__: no PDF on the web.