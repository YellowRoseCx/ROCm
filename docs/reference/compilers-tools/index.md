# ROCm compilers and tools

:::::{grid} 1 1 2 2
:gutter: 1

:::{grid-item-card} {doc}`ROCdbgapi <rocdbgapi:index>`

The AMD Debugger API is a library that provides all the support necessary for a
debugger and other tools to perform low level control of the execution and
inspection of execution state of AMD's commercially available GPU architectures.

* [GitHub](https://github.com/ROCm-Developer-Tools/ROCdbgapi/)

:::

:::{grid-item-card}
**[ROCmCC](../rocmcc/rocmcc.md)**

ROCmCC is a Clang/LLVM-based compiler. It is optimized for high-performance
computing on AMD GPUs and CPUs and supports various heterogeneous programming
models such as HIP, OpenMP, and OpenCL.

:::

:::{grid-item-card} {doc}`ROCgdb <rocgdb:index>`

This is ROCgdb, the ROCm source-level debugger for Linux, based on GDB, the GNU source-level debugger.

* [GitHub](https://github.com/ROCm-Developer-Tools/ROCgdb/)

:::

:::{grid-item-card} {doc}`ROCProfiler <rocprofiler:rocprof>`

ROC profiler library. Profiling with performance counters and derived metrics. Library supports GFX8/GFX9. Hardware specific low-level performance analysis interface for profiling of GPU compute applications. The profiling includes hardware performance counters with complex performance metrics.

* [GitHub](https://github.com/ROCm-Developer-Tools/rocprofiler/)

:::

:::{grid-item-card} {doc}`ROCTracer <roctracer:index>`

Callback/Activity Library for Performance tracing AMD GPUs

* [GitHub](https://github.com/ROCm-Developer-Tools/roctracer)

:::

:::::

## See also

* [Compiler disambiguation](../../conceptual/compiler-disambiguation.md)
