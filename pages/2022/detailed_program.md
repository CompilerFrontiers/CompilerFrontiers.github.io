---
layout: base2022
---

# Program

May 18th, 2022 (all times are CET)




## Invited Talk

### Title: Community Research Priorities for Next-Generation Scientific Computing 

Speaker: Hal Finkel

Time: 16:30 - 17:00

Abstract: In this talk, Hal reviews recent work on programming systems sponsored by the U.S. Department of Energy’s Advanced Scientific Computing Research program and community research priorities for hardware/software co-design, scientific machine learning, data management, cybersecurity and privacy, and software development. Future work on programming systems is expected to have an impact on, and be impacted by, the progress in these important areas. Hal highlights specific aspects of the identified research directions related to programming systems. Finally, Hal discusses recent community input on software sustainability for scientific and high-performance computing, highlighting some of the requirements for future programming systems.

Bio: Hal is a program manager for computer-science research in the US Department of Energy Office of Science's Advanced Scientific Computing Research (ASCR) program. Prior to joining ASCR, Hal was the Lead for Compiler Technology and Programming Languages at Argonne’s Leadership Computing Facility. As part of DOE's Exascale Computing Project (ECP), Hal was a PathForward technical lead and PI/Co-PI of several multi-institution activities. Hal also helped develop the Hardware/Hybrid Accelerated Cosmology Code (HACC), a two-time IEEE/ACM Gordon Bell Prize finalist. He graduated from Yale University in 2011 with a Ph.D. in theoretical physics focusing on numerical simulation of early-universe cosmology.




## Papers

### Title: Noise-Adaptive Quantum Compilation Strategies Evaluated with Application-Motivated Benchmarks

Authors: Davide Ferrari and Michele Amoretti

Time: 17:00 - 17:25

Abstract: Quantum compilation is the problem of translating an input quantum circuit into the most efficient equivalent of itself, taking into account the characteristics of the device that will execute the computation. Compilation strategies are composed of sequential passes that perform placement, routing and optimization tasks. Noise adaptive compilers do take the noise statistics of the device into account, for some or all passes. The noise statistics can be obtained from calibration data and updated after each device calibration. In this paper, we propose a novel noise-adaptive compilation strategy that is computationally efficient. The proposed strategy assumes that the quantum device coupling map uses a heavy-hexagon lattice. Moreover, we present the application-motivated benchmarking of the proposed noise-adaptive compilation strategy, compared with some of the most advanced state-of-art approaches. The presented results seem to indicate that our compilation strategy is particularly effective for deep circuits and for square circuits.

### Title: Towards Neural Architecture-Aware Exploration Of Compiler Optimizations in a Deep Learning {Graph} Compiler

Authors: Gaurav Verma, Swetang Finviya, Abid M. Malik, Murali Emani and Barbara Chapman

Time: 17:25 - 17:50

Abstract: Deep Neural Networks (DNN) form the basis for many existing and emerging applications. Many DL compilers analyze the computation graphs and apply various optimizations at different stages. These high-level optimizations are applied using compiler passes before feeding the resultant computation graph for low-level and hardware-specific optimizations. With advancements in DNN architectures and backend hardware, the search space of compiler optimizations has grown manifolds. Also, the inclusion of passes without the knowledge of the computation graph leads to increased execution time with a slight influence on the intermediate representation. This paper presents preliminary results 1) summarizing the relevance of pass selection and ordering in a DL compiler, 2) neural architecture-aware selection of optimization passes, and 3) pruning search space for the phase selection problem in a DL compiler. We use TVM as a compiler to demonstrate the experimental results on Nvidia A100 and GeForce RTX 2080 GPUs, establishing the relevance of neural architecture-aware selection of optimization passes for DNNs DL compilers. Experimental evaluation with seven models categorized into four architecturally different classes demonstrated performance gains for most neural networks. For ResNets, the average throughput increased by 24% and 32% for TensorFlow and PyTorch frameworks, respectively. Additionally, we observed an average 15% decrease in the compilation time for ResNets, 45% for MobileNet, and 54% for SSD-based models without impacting the throughput. BERT models showed a dramatic improvement with a 92% reduction in the compile time.


### Title: Compilation On The GPU? A Feasibility Study

Authors: Robin Voetter, Marcel Huijben and Kristian Rietveld

Time: 17:50 - 18:15

Abstract: The emergence of highly parallel architectures has led to a renewed interest in parallel compilation. In particular, the widespread availability of GPU architectures raises the question whether compilation on the GPU is feasible. In this paper, we describe the first design and implementation of a parallel compiler from a simple imperative programming language to RISC-V machine code, that is fully executed on a GPU. To accomplish this, all stages from parsing to the generation of machine code were redesigned to exploit fine-grained parallelism. Experimental evaluation of the implemented prototype demonstrates our proposed parallel techniques to be effective and implementation of compilation on the GPU to be feasible. Finally, we propose a number of avenues for future work and hope to revitalize research into parallel compilation that was conducted in the 1980s.

