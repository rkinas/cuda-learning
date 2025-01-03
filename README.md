<div align="center"><img src="https://docs.nvidia.com/cuda/_static/Logo_and_CUDA.png" alt="CUDA" height="80"></div> 

## LEARNING PATH - From Basics to Advanced CUDA Programming

This structured learning path guides you through the essential steps required to become proficient in CUDA programming, starting from foundational programming knowledge to advanced GPU computing concepts. The path emphasizes building a strong base in programming, understanding data structures, mastering C++, and diving into GPU architecture and CUDA-specific optimizations. Resources include both English and Polish materials, offering flexibility based on language preference.

1. **C Programming**:  
   Begin with C programming if you are unfamiliar with it. A solid understanding of C is mandatory before transitioning to C++ programming.  
   - 🇵🇱 [Podstawy programowania. Język C](https://www.udemy.com/course/podstawy-programowania-jezyk-c)  
   - 🇵🇱 [Zaawansowane programowanie w języku C](https://www.udemy.com/course/zaawansowane-programowanie-jezyku-c)  
   - *The C Programming Language (ANSI C)* by Brian Kernighan and Dennis Ritchie  

2. **Data Structures**:  
   Learn essential data structures and algorithms, a prerequisite for effective problem-solving and programming.  
   - 🎥[C++ Data Structures & Algorithms + LEETCODE Exercises](https://www.udemy.com/course/data-structures-algorithms-cpp/)  
   - [Data Structures and Algorithms](https://github.com/sachuverma/DataStructures-Algorithms) -> [Leetcode](https://leetcode.com/)  
   - 🇵🇱 📖 *Algorytmy, struktury danych i techniki programowania* by Paweł Wróblewski  
   - 🇵🇱 📖 *C++. Algorytmy i struktury danych* by Adam Drozdek  

3. **C++ Programming**:  
   Master C++ programming as it serves as a foundation for CUDA development.  
   - 🎥 [Beginning C++ Programming - From Beginner to Beyond](https://www.udemy.com/course/beginning-c-plus-plus-programming/)  
   - 🇵🇱 🎥 [C++ od Podstaw do Eksperta](https://www.udemy.com/course/c-od-podstaw-do-eksperta/)
   - 🇵🇱 📖 [Opus magnum C++11](https://www.ifj.edu.pl/private/grebosz/opus.html)
   - 🇵🇱 📖 *Język C++ Kompendium Wiedzy* by Bjarne Stroustrup
   - 🎥 [Back to Basics](https://www.youtube.com/playlist?list=PLHTh1InhhwT4TJaHBVWzvBOYhp27UO7mI)

4. **Parallel Computing**:  
   Understand the basics of parallel computing and modern hardware architectures.  
   - 🎥 [GPU Computing](https://www.youtube.com/playlist?list=PLRRuQYjFhpmubuwx-w8X964ofVkW1T8O4)  
   - 🇵🇱 🎥 [Programowanie równolegle z wykorzystaniem współczesnych architektur komputerowych z pamięcią współdzieloną](https://icis.pcz.pl/~khalbiniak/OpenMP/)  
   - 🇵🇱 [Algorithms for Modern Hardware](https://en.algorithmica.org/hpc/)
   - 🎥 [Learn Multithreading with Modern C++](https://www.udemy.com/course/learn-modern-cplusplus-concurrency/)

5. **CUDA Programming**:  
   Dive into CUDA, learning GPU programming techniques, optimizations, and advanced performance tuning.  
   - [CUDA C++ Programming Guide](https://docs.nvidia.com/cuda/cuda-c-programming-guide/)
   - 🇵🇱 [CUDA - Tomasz Jasiukiewicz](https://www.youtube.com/watch?v=LNA_CYZbDtY&list=PLoHYlZuJfhOGHKKEwt4tn8KUTJvbbtRL_)  
   - 🎥 [CUDA Parallel Programming on NVIDIA GPUs - HW and SW](https://www.udemy.com/course/cuda-parallel-programming-on-nvidia-gpus-hw-and-sw/?couponCode=KEEPLEARNING)  
   - [CUDA Samples](https://github.com/NVIDIA/cuda-samples)  
   - 🎥 [CUDA Programming Course – High-Performance Computing with GPUs](https://www.youtube.com/watch?v=86FAWCzIe_4)  
   - 📖 *Programming Massively Parallel Processors* by  David B. Kirk, Wen-mei W. Hwu  

6. **Triton**:  
   Explore the Triton framework for GPU programming with efficient performance.  
   - [Remek's Triton Repo](https://github.com/rkinas/triton-resources)  

7. **GPU Architecture and Glossary**:  
   Familiarize yourself with GPU architecture and terminology to deepen your understanding of hardware capabilities.  
   - [GPU Glossary](https://modal.com/gpu-glossary)  

This comprehensive learning path equips you with the skills needed to progress from foundational programming to advanced CUDA development, paving the way for a career in GPU-accelerated computing.

## Matmul ##
This section focuses on understanding the fundamentals and optimization of matrix multiplication (Matmul), a cornerstone operation in CUDA programming and high-performance computing (HPC). The provided resources cover both CPU implementations and GPU optimizations, including the use of Tensor Cores on architectures like Ampere and Ada. These materials are essential for building a strong foundation in writing optimized CUDA code.

#### Contents:
- **Matmul on CPU**: Analysis of efficient matrix multiplication implementations on CPUs, with detailed examples of optimizations:
  - [Beating OpenBLAS in FP32 Matrix Multiplication: A Full Walkthrough](https://salykova.github.io/matmul-cpu)
  - [Fast Multidimensional Matrix Multiplication on CPU from Scratch](https://siboehm.com/articles/22/Fast-MMM-on-CPU)
- **CUDA Matmul Optimizations**:
  - Ampere Architecture: [How to Optimize a CUDA Matmul Kernel for cuBLAS-like Performance: a Worklog](https://siboehm.com/articles/22/CUDA-MMM)
  - Ada Architecture: [Implementing a fast Tensor Core matmul on the Ada Architecture](https://www.spatters.ca/mma-matmul)
  - GPU H100: [Outperforming cuBLAS on H100: a Worklog](https://cudaforfun.substack.com/p/outperforming-cublas-on-h100-a-worklog)
- **Theory and Basics**:
  - [Matrix Multiplication Background User's Guide](https://docs.nvidia.com/deeplearning/performance/dl-performance-matrix-multiplication/index.html)

These resources provide a comprehensive theoretical and practical foundation in matrix multiplication, enabling you to master CUDA learning and better understand algorithm optimization in GPU environments.

## GPU programming resources
### Description of the Section: GPU Programming Resources

This section provides a curated collection of resources for learning, exploring, and mastering GPU programming. It covers various aspects of GPU development, including community engagement, architectural insights, tutorials, example implementations, benchmarking, and advanced tools. These resources cater to developers at different expertise levels, offering a pathway to build and optimize high-performance GPU applications.

---

#### **1. Communities**  
Engage with fellow developers and experts in the field of GPU programming:  
- [NVIDIA CUDA Forum](https://forums.developer.nvidia.com/c/accelerated-computing/cuda/206)

---

#### **2. GPU Architectures**  
Understand the underlying architecture of GPUs to optimize code efficiently:  
- [Ampere Architecture](https://developer.nvidia.com/blog/nvidia-ampere-architecture-in-depth/)  
- [Ada Architecture](https://images.nvidia.com/aem-dam/en-zz/Solutions/technologies/NVIDIA-ADA-GPU-PROVIZ-Architecture-Whitepaper_1.1.pdf)  
- [Hopper Architecture](https://developer.nvidia.com/blog/nvidia-hopper-architecture-in-depth/)  
- [Grace-Hopper Architecture](https://developer.nvidia.com/blog/nvidia-grace-hopper-superchip-architecture-in-depth/)  
- [GPUs Go Brrr](https://hazyresearch.stanford.edu/blog/2024-05-12-tk)

---

#### **3. Tutorials**  
Learn the practical aspects of GPU programming with these tutorials:  
- [Accurate Timing of CUDA Kernels in PyTorch](https://www.speechmatics.com/company/articles-and-news/timing-operations-in-pytorch)

---

#### **4. Courses**  
Comprehensive courses to deepen your GPU programming skills:  
- [Parallel Computing Using CUDA-C](https://github.com/CisMine/Parallel-Computing-Cuda-C?tab=readme-ov-file)  
- [CUDA Course](https://github.com/Infatoshi/cuda-course)  
- [CUDA Tutorial Code Samples](https://github.com/CUDA-Tutorial/CodeSamples)  
- [CUDA Tutorial](https://cuda-tutorial.github.io/)

---

#### **5. Videos**  
Explore video tutorials and insights on GPU programming:  
- [Programming Massively Parallel Processors](https://www.youtube.com/playlist?list=PLRRuQYjFhpmubuwx-w8X964ofVkW1T8O4)  
- [Simon Oz - GPU Programming](https://www.youtube.com/playlist?list=PL5XwKDZZlwaY7t0M5OLprpkJUIrF8Lc9j)  
- [CUDA Programming](https://www.youtube.com/playlist?list=PLU0zjpa44nPXddA_hWV1U8oO7AevFgXnT)  
- [George Hotz Archive](https://www.youtube.com/@geohotarchive/videos)

---

#### **6. Example Implementations**  
Explore real-world examples and implementations:  
- [llm.c](https://github.com/karpathy/llm.c)  
- [Fast LLM Inference From Scratch](https://andrewkchan.dev/posts/yalm.html)  
- [MNIST CUDA](https://github.com/Infatoshi/mnist-cuda)  
- [Softmax](https://github.com/SzymonOzog/FastSoftmax)  
- [YALM: LLM Inference in C++/CUDA](https://github.com/andrewkchan/yalm/tree/main)  
- [llm.cpp: Training and Inference](https://github.com/karpathy/llm.c/tree/master)  
- [CUTLASS Tutorial: Fast Matrix Multiplication with WGMMA on Hopper GPUs](https://research.colfax-intl.com/cutlass-tutorial-wgmma-hopper/)

---

#### **7. Kernel Leaderboard**  
Track performance and benchmarks of GPU kernels:  
- [Kernel Leaderboard](https://scalingintelligence.stanford.edu/KernelBenchLeaderboard/)  
- [KernelBench Blog](https://scalingintelligence.stanford.edu/blogs/kernelbench/)

---

#### **8. Benchmarking**  
Compare GPU performance and analyze benchmarks:  
- [MI300X vs H100 vs H200 Training Benchmarks](https://semianalysis.com/2024/12/22/mi300x-vs-h100-vs-h200-benchmark-part-1-training/)  
- [Forecasting GPU Performance](https://arxiv.org/pdf/2407.13853)  
- [Benchmarking Nvidia Hopper GPU Architecture](https://arxiv.org/pdf/2402.13499v1)  
- [Maximum Achievable Matmul FLOPS Finder](https://github.com/stas00/ml-engineering/tree/master/compute/accelerator/benchmarks)

---

#### **9. Patterns and Algorithms**  
Understand key HPC algorithms like matrix multiplication:  
- [HPC Matmul Algorithms](https://en.algorithmica.org/hpc/algorithms/matmul/)

---

#### **10. Articles**  
Insights into GPU performance and its nuances:  
- [The GPU is Not Always Faster](https://cowfreedom.de/#dot_product/introduction/)
- [Series of articles explaining GPU programming](https://giahuy04.medium.com/) -> [Demystifying CPUs and GPUs: What You Need to Know](https://giahuy04.medium.com/demystifying-cpus-and-gpus-what-you-need-to-know-5bb423be726b), [How the way a computer works](https://giahuy04.medium.com/how-the-way-a-computer-works-a8b8d253da21), [Terminology in parallel programming](https://giahuy04.medium.com/terminology-in-parallel-programming-a2c4d7d062cf), [Hello world Cuda-C](https://giahuy04.medium.com/hello-world-cuda-c-ddfd7a8aeb8c), [The operational mechanism of CPU-GPU](https://giahuy04.medium.com/the-operational-mechanism-of-cpu-gpu-acf6e7723b2b), [Memory Types in GPU](https://ai.gopubby.com/memory-types-in-gpu-6373b7a0ca47), [Using GPU memory](https://giahuy04.medium.com/using-gpu-memory-a75e0fabe3f0), [Synchronization and Asynchronization](https://giahuy04.medium.com/synchronization-and-asynchronization-0024fe9e7329), [Unified memory](https://giahuy04.medium.com/unified-memory-81bb7c0f0270), [Pinned memory](https://giahuy04.medium.com/pinned-memory-5d408b72241d), [Streaming](https://giahuy04.medium.com/streaming-0fbc7b1a5fff), [Data Hazard](https://giahuy04.medium.com/data-hazard-cd0e9e50cce2), [Warp Scheduler](https://giahuy04.medium.com/warp-scheduler-f7318ef17920), [Global Memory Coalescing](https://giahuy04.medium.com/global-memory-coalescing-37a6f9d7e314), [Atomic Function](https://giahuy04.medium.com/atomic-function-9f5c5a414181),[Bandwidth — Throughput — Latency](https://giahuy04.medium.com/bandwidth-throughput-latency-935ada83d1ae),[Occupancy in GPU Part 1](https://giahuy04.medium.com/occupancy-in-gpu-ddb0b1f16b20), [Occupancy in GPU Part 2](https://giahuy04.medium.com/occupancy-part-2-7a5c671a1fb0)

---

#### **11. CUDA Frameworks**  
Explore CUDA-based frameworks for specific use cases:  
- [ThunderKittens Framework](https://github.com/HazyResearch/ThunderKittens)

---

#### **12. Papers**  
Explore state-of-the-art research in GPU programming:  
- [The Case for Co-Designing Model Architectures with Hardware](https://arxiv.org/pdf/2401.14489)

---

#### **13. Tools**  
Useful tools for tuning and analyzing GPU performance:  
- [Kernel Tuner](https://kerneltuner.github.io/kernel_tuner/stable/contents.html)

---

This resource list offers a comprehensive set of tools, tutorials, and materials to help developers advance their GPU programming expertise, from beginner to professional levels.

## Parallel computing
- [Programming Parallel Computers](https://ppc.cs.aalto.fi/)

