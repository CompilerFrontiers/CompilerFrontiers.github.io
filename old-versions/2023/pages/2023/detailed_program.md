---
layout: base
---

# Program

May 10, 2023 (all times are CEST)

## Invited Talk

### Title: Application-Level Architecture Design
Speaker: John Leidel
Time: 15:15-15:40

Abstract: Recent advancements in compiler infrastructures have yielded malleable frameworks to explore data and target optimization using language agnostic approaches.  In this talk, we will explore the latest efforts in the compiler and architecture communities to construct frameworks for architecture exploration using traditional language and compiler workflows.


## Papers

### Clever DAE: Compiler Optimizations for Digital Twins at Scale 
Authors: Michele Scuttari, Nicola Camillucci, Daniele Cattaneo, Giovanni Agosta, Francesco Casella, Stefano Cherubin and Federico Terraneo
Time: 15:40-16:05

Abstract: Modeling and simulation are fundamental activities in engineering to facilitate prototyping, verification, and maintenance. Declarative modeling languages allow to simulate physical phenomena by expressing them in terms of Differential and Algebraic Equations (DAE) systems. Due to the declarative nature of such languages, a different compilation pipeline is required compared to imperative programming languages. In this paper, we focus on the problem of generating code for performing the numerical integration of the model equations, and in particular on the overhead introduced by external numerical solver libraries. We propose a novel methodology for minimizing the amount of equations which require to be solved through an external solver library, together with the number of computations that are required to computed the Jacobian matrix of the system. Through a prototype LLVM-based compiler, we demonstrate how this approach achieves a linear speed-up in simulation time with respect to the baseline. 

### Compiler-Injected SIHFT for Embedded Operating Systems 
Authors: Davide Baroffio and Federico Reghenzani
Time: 16:05-16:30

Abstract: Random hardware faults are a major concern for critical systems, especially when they are employed in high-radiation environments such as aerospace applications. While specialized hardware already exists for implementing fault tolerance, software solutions, named Software-Implemented Hardware Fault Tolerance (SIHFT), offer higher flexibility at a lower cost. This work describes a compiler-based approach for inserting instruction-level fault detection mechanisms in both the application code and the operating system. An experimental evaluation on a STM32 board running FreeRTOS shows the effectiveness of the proposed approach in detecting faults.
