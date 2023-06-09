# Integrated Profiler (IPro)

IPro is an integrated software tool for performance profiling and monitoring. It is integrated with STREAM, Caliper, Variorum, Thicket, RAJAPerf, and more to come.

STREAM is the de facto industry standard benchmark for measuring sustained memory bandwidth.
Documentation for STREAM is on the web at: http://www.cs.virginia.edu/stream/ref.html

Caliper is a library to integrate performance profiling capabilities into applications. To use Caliper, developers mark code regions of interest using Caliper's annotation API. Applications can then enable performance profiling at runtime with Caliper's configuration API. Alternatively, you can configure Caliper through environment variables or config files. Caliper can be used for lightweight always-on profiling or advanced performance engineering use cases, such as tracing, monitoring, and auto-tuning. It is primarily aimed at HPC applications, but works for any C/C++/Fortran program on Unix/Linux.
Documentation for Caliper is on the web at: https://llnl.github.io/Caliper/

Variorum is a platform-agnostic library exposing monitor and control interfaces for several features in hardware architectures.
Documentation for Variorum is on the web at: https://variorum.readthedocs.io

Thicket is a Python-based toolkit for analyzing ensemble performance data.
Documentation for Thicket is on the web at: https://thicket.readthedocs.io/en/latest/

The RAJA Performance Suite (RAJAPerf) is a companion project to the RAJA C++ performance portability abstraction library. The Performance Suite designed to eplore performance of loop-based computational kernels found in HPC applications. Specifically, it is used to assess and monitor runtime performance of kernels implemented using RAJA compare those to variants implemented using common parallel programming models, such as OpenMP and CUDA, directly.
Documentation for RAJAPerf is on the web at: (recent version) https://rajaperf.readthedocs.io and (older versions) https://readthedocs.org/projects/rajaperf/
