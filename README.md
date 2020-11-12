# Compiler-benchmark-suites
A list of benchmark suites (and some loose kernels) used in the research related to compilers, program performance, scientific computations etc.

## Benchmark suites

| Benchmark                                                                                                                  | Lang                      | Platform | Published in        | Content          | Additional info                                                                                                                                                                                                                                        |
|----------------------------------------------------------------------------------------------------------------------------|---------------------------|----------|---------------------|------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [BEEBS](https://beebs.mageec.org/)|C|Embedded|[_Pallister2013_]|10 benchmarks|For analysis of energy consumption on embedded platforms|
| [Embench™](https://embench.org/)|C|Embedded|[_Patterson2019_]| 19 benchmarks|Modern benchmarks for performance analysis built on top of selected [BEEBS](https://beebs.mageec.org/) benchmarks|
| [LCALS v1.0.2](https://computation.llnl.gov/projects/co-design/download/lcals-v1.0.2.tgz)                                  | C                         | CPU      | [_Hornung2013_]     | 32 loops         | For analysis of compiler optimisations; modern extension to _Livermore loops_; [more information](https://computation.llnl.gov/projects/co-design/lcals)                                                                                               |
| [Livermore loops (LFK)](https://www.netlib.org/benchmark/livermore)                                                        | FORTRAN                   | CPU      | [_McMahon1986_]     | 24 loops         | For performance analysis                                                                                                                                                                                                                               |
| [Livermore loops](https://www.netlib.org/benchmark/livermorec)                                                             | C                         | CPU      | 1992                | 24 loops         | Port to C                                                                                                                                                                                                                                              |
| [Mälardalen WCET Benchmarks](http://www.mrtc.mdh.se/projects/wcet/benchmarks.html)|C|CPU|[_Gustafsson2010_]|35 benchmarks|For Worst-Case Execution Time (WCET) analysis|
| [PolyBench/C 4.2](https://sourceforge.net/projects/polybench/files/polybench-c-4.2.tar.gz/download)                        | C                         | CPU      | 2010                | 30 kernels       | For the analysis of performance and compiler optimisations (especially related to polyhedra compilation); [more information](http://web.cse.ohio-state.edu/~pouchet.2/software/polybench/); [SourceForge](https://sourceforge.net/projects/polybench/) |
| [PolyBench/Fortran 1.0](http://web.cse.ohio-state.edu/~pouchet.2/software/polybench/download/polybench-fortran-1.0.tar.gz) | FORTRAN                   | CPU      | 2011                | 30 kernels       | Port to FORTRAN; [more information](http://web.cse.ohio-state.edu/~pouchet.2/software/polybench/polybench-fortran.html)                                                                                                                                |
| [PolyBench/GPU 1.0](http://www.cse.ohio-state.edu/~pouchet/software/polybench/download/polybench-gpu-1.0.tar.gz)           | C, CUDA, OpenCL, OpenHMPP | CPU, GPU | [_Grauer-Gray2012_] | 15 kernels       | Port to heterogeneous architectures; [more information](http://web.cse.ohio-state.edu/~pouchet.2/software/polybench/GPU/index.html)                                                                                                                    |
| [TSVC](https://www.netlib.org/benchmark/vectord)                                                                           | FORTRAN                   | CPU      | [_Callahan1988_]    | 135 loops        | For testing automatic vectorizing compilers; [Single precision version](https://www.netlib.org/benchmark/vectors)                                                                                                                                      |
| [TSVC](http://polaris.cs.uiuc.edu/~maleki1/TSVC.tar.gz)                                                                    | C                         | CPU      | [_Maleki2011_]      | 151 loops        | Extended port to C                                                                                                                                                                                                                                     |
| [TSVC 2](https://github.com/UoB-HPC/TSVC_2)                                                                                | C                         | CPU      | 2015                | 151 loops        | Update to TSVC in C                                                                                                                                                                                                                                    |
| [UTDSP](http://www.eecg.toronto.edu/~corinna/DSP/infrastructure/UTDSP.tar.gz)                                              | C                         | CPU      | 1992                | 6 loops, 12 apps | For testing compilers on Digitial Signal Processing (DSP) applications; [more information](http://www.eecg.toronto.edu/~corinna/DSP/infrastructure/UTDSP.html)                                                                                         |

### Full names

* BEEBS — Bristol/Embecosm Embedded Benchmark Suite
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
* [_Grauer-Gray2012_] Scott Grauer-Gray, Lifan Xu, Robert Searles, Sudhee Ayalasomayajula, and John Cavazos. Auto-tuning a High-Level Language Targeted to GPU Codes. Proceedings of Innovative Parallel Computing (InPar '12), 2012. https://doi.org/10.1109/InPar.2012.6339595
* [_Gustafsson2010_] Jan Gustafsson, Adam Betts, Andreas Ermedahl, and Björn Lisper. The Mälardalen WCET benchmarks: Past, present and future. 10th International Workshop on Worst-Case Execution Time Analysis, WCET 2010, July 6, 2010, Brussels, Belgium. https://doi.org/10.4230/OASIcs.WCET.2010.136
* [_Hornung2013_] Richard D. Hornung and Jeffrey A. Keasler, “A Case for Improved C++ Compiler Support to Enable Performance Portability in Large Physics Simulation Codes”, LLNL-TR-635681 (2013). https://computing.llnl.gov/projects/co-design/compilersupportwhitepaper_tr-635681_cover.pdf
* [_Patterson2019_] David Patterson, Jeremy Bennett, Palmer Dabbelt, Cesare Garlati, G. S. Madhusudan and Trevor Mudge. Embench™: An Evolving Benchmark Suite for Embedded IoT Computers from an Academic-Industrial Cooperative: Towards the Long Overdue and Deserved Demise of Dhrystone (2019). https://riscv.org/wp-content/uploads/2019/06/9.25-Embench-RISC-V-Workshop-Patterson-v3.pdf
* [_Pallister2013_] James Pallister, Simon Hollis, Jeremy Bennett (2013). BEEBS: Open Benchmarks for Energy Measurements on Embedded Platforms
http://arxiv.org/abs/1308.5174.
* [_Maleki2011_] Maleki, S., Gao, Y., Garzarán, M. J., Wong, T., & Padua, D. A. (2011). An evaluation of vectorizing compilers. Parallel Architectures and Compilation Techniques - Conference Proceedings, PACT, 7, 372–382. https://doi.org/10.1109/PACT.2011.68
* [_McMahon1986_] F. H. McMahon. Livermore fortran kernels: A computer test of numerical performance range. Technical Report UCRL-53745, Lawrence Livermore National Laboratory, Livermore, CA, December 1986; __COMMENT__: no PDF on the web.