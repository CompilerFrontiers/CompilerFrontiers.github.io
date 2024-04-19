---
layout: base
---

# Program

May 9, 2024 (all times are CEST)

| Time          | Title | **Authors** |
| ------------- | ----- | ------- |
| 11:45-12:00   | Opening Remarks | - |
| 12:00-12:30   | A General Purpose Analog Computer to Population Protocol Compiler | Xiang Huang and Andrei Miguno |
| 12:30-13:00   | Compile-Time Optimization of the Energy Consumption of Numerical Computations | Dorra Ben Khalifa and Matthieu Martel |
| 13:00-14:30   | Lunch Break | - |
| 14:30-13:45   | Effective HPC Programming via Domain-Specific Abstractions and Compilation | Gokcen Kestor |
| 14:45-15:15   | High-level synthesis for complex applications: the Bambu approach | Fabrizio Ferrandi |
| 15:15-15:45   | Closing Remarks | - |


## Papers (11:45-13:00)

### Opening Remarks

Chairs: Antonino Tumeo, PNNL, US, Kristian Rietveld, Leiden University, NL


### Title: A General Purpose Analog Computer to Population Protocol Compiler

**Authors**: Xiang Huang and Andrei Miguno

**Abstract**: The General-Purpose Analog Computer (GPAC) is a model of computation
due to Shannon, based on Bush's differential analyzer, that has both
circuit-based and ordinary differential equation (ODE) characterizations. Real
numbers are computed by this model as the limits of the solutions of the ODE
system. GPACs are Turing-complete and are closely related to Chemical Reaction
Networks (CRNs) and sub-models of these such as population protocols (PPs).
CRNs, especially, are a popular programming language for molecular and
nanotechnology applications. Berenbrink et. al. introduced a batched simulator
for PPs, recently implemented by Doty et. al. as ppsim. We introduce a compiler,
based on the work of Huang and Huls, which transforms bounded GPACs into PPs
that can then be simulated quickly using ppsim, or executed physically using
techniques such as DNA strand displacement cascades.

**Duration**: 30 minutes


### Title: Compile-Time Optimization of the Energy Consumption of Numerical Computations

**Authors**: Dorra Ben Khalifa and Matthieu Martel

**Abstract**: Over the past decade, precision tuning has become one of the key
techniques for achieving significant gains in performance and energy efficiency.
This process consists of substituting smaller data types to the original data
types assigned to floating-point variables in numerical programs in such a way
that accuracy requirements remain fulfilled. In this article, we discuss the
time and energy savings achieved using our precision tuning tool, POPiX.  We
validate our results on a  set of numerical benchmarks covering  various fields.

**Duration**: 30 minutes


## Invited Talks (14:30-15:45)

### Title: Effective HPC Programming via Domain-Specific Abstractions and Compilation

**Speaker**: Gokcen Kestor

**Abstract**: Programming heterogeneous systems has become increasingly complicated.
On one side, extracting high performance out of modern accelerators requires
using vendor-specific compiler toolchains; on the other side, there is a
proliferation of domain-specific programming languages that increase
productivity, especially in the realm of AI. Reconciling these semantically rich
languages with low-level architectural features requires proper abstractions and
composable compiler toolchains.

In this talk, we will demonstrate how COMET, a multi-level compiler framework
for sparse and dense tensor algebra, can be used to lower high-level programs,
e.g., NumPy or SciPy,  to a variety of heterogeneous devices, including GPUs and
FPGAs. We will follow the lowering steps and analyze the domain-specific,
general, and architecture-specific optimizations employed to achieve high
performance. We will show how the approach taken increases the reusability of
the compiler optimizations passes,  lowers collaboration barriers and
maintainability, and favors code portability across very different
architectures.

**Duration**: 30 minutes


### Title: High-level synthesis for complex applications: the Bambu approach

**Speaker**: Fabrizio Ferrandi

**Abstract**: This talk presents the Bambu as a comprehensive HLS research and
development platform. Bambu is a versatile environment for exploring innovative
ideas in HLS, encompassing high-level verification, debugging, FPGA/ASIC design,
design flow space exploration, and parallel hardware accelerator design.  Key
highlights include Bambu's capability to accept standard C/C++ specifications
and compiler intermediate representations (IRs) from leading compilers like
Clang/LLVM and GCC. This flexibility empowers electronic design automation (EDA)
community researchers to explore and integrate new transformations and
optimizations.  Bambu's modular and easily extendable nature incorporates
numerous optimizations and HLS benchmarks, facilitating the evaluation of its
Quality of Results (QoR) against existing approaches. Integration with synthesis
and verification backends, both commercial and open-source, allows researchers
to rapidly test new findings and obtain performance and resource usage metrics.
Moreover, Bambu supports various FPGA devices from major vendors like
AMD/Xilinx, Intel/Altera, Lattice Semiconductor, and NanoXplore, ensuring
portability across diverse hardware platforms.

**Duration**: 30 minutes


### Closing Remarks

Chair: Antonino Tumeo, PNNL, US, Kristian Rietveld, Leiden University, NL