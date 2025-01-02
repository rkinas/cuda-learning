Plan for becoming profesional CUDA (Deep Learning focused) programmer. CUDA from Zero to Hero.

## LEARNING PATH
1. C - if you are not familiar with C programming. Before we jump into C++ basic knowledge of C is mandatory.
   - 🇵🇱 [Podstawy programowania. Język C](https://www.udemy.com/course/podstawy-programowania-jezyk-c)
   - 🇵🇱 [Zaawansowane programowanie w języku C](https://www.udemy.com/course/zaawansowane-programowanie-w-jezyku-c)
   - The C programming language (ANSI C) - Brian Kernighan i Dennis Ritchie
2. Data Structures
   - [C++ Data Structures & Algorithms + LEETCODE Exercises](https://www.udemy.com/course/data-structures-algorithms-cpp/)
   - [Data Structures and Alghorithms](https://github.com/sachuverma/DataStructures-Algorithms) ->> [Leetcode](https://leetcode.com/)
   - 🇵🇱 Algorytmy, struktury danych i techniki programowania. Paweł Wróblewski.
   - 🇵🇱 C++. Algorytmy i struktury danych. Adam Drozdek 
3. C++
   - [Beginning C++ Programming - From Beginner to Beyond](https://www.udemy.com/course/beginning-c-plus-plus-programming/) or in Polish [C++ od Podstaw do Eksperta](https://www.udemy.com/course/c-od-podstaw-do-eksperta/)
   - 🇵🇱 Books: Język C++ kompendium wiedzy.
4. Parallel Computing
   - [GPU Computing](https://www.youtube.com/playlist?list=PLRRuQYjFhpmubuwx-w8X964ofVkW1T8O4)
   - 🇵🇱 [Programowanie równolegle z wykorzystaniem wspólczesnych architektur komputerowych z pamiecia wspóldzielona](https://icis.pcz.pl/~khalbiniak/OpenMP/)
   - 🇵🇱 [Algorithms for Modern Hardware](https://en.algorithmica.org/hpc/)
5. CUDA
   - 🇵🇱 [CUDA - Tomasz Jasiukiewicz](https://www.youtube.com/watch?v=LNA_CYZbDtY&list=PLoHYlZuJfhOGHKKEwt4tn8KUTJvbbtRL_)
   - [CUDA Parallel Programming on NVIDIA GPUs - HW and SW](https://www.udemy.com/course/cuda-parallel-programming-on-nvidia-gpus-hw-and-sw/?couponCode=KEEPLEARNING)
   - [CUDA samples](https://github.com/NVIDIA/cuda-samples)
   - [CUDA Programming Course – High-Performance Computing with GPUs](https://www.youtube.com/watch?v=86FAWCzIe_4)
   - Programming Massively Parallel Processors
6. Triton
   - [Remek's Triton repo](https://github.com/rkinas/triton-resources)
  
7. GPU architecture and glossary
   - [GPU Glossary](https://modal.com/gpu-glossary)

8. C/C++ sample LLM implementation (inference, training, kernels)
   - [llm.c](https://github.com/karpathy/llm.c)
   - [Fast LLM Inference From Scratch](https://andrewkchan.dev/posts/yalm.html)


## GPU programming resources
1. Communities
   - [Nvidia CUDA](https://forums.developer.nvidia.com/c/accelerated-computing/cuda/206)
2. GPU Architectures 
   - [Ampere](https://developer.nvidia.com/blog/nvidia-ampere-architecture-in-depth/)
   - [Ada](https://images.nvidia.com/aem-dam/en-zz/Solutions/technologies/NVIDIA-ADA-GPU-PROVIZ-Architecture-Whitepaper_1.1.pdf)
   - [Hooper](https://developer.nvidia.com/blog/nvidia-hopper-architecture-in-depth/)
   - [Grace-Hooper](https://developer.nvidia.com/blog/nvidia-grace-hopper-superchip-architecture-in-depth/)
   - [GPUs Go Brrr](https://hazyresearch.stanford.edu/blog/2024-05-12-tk)
3. Tutorials
   - [How to Accurately Time CUDA Kernels in Pytorch](https://www.speechmatics.com/company/articles-and-news/timing-operations-in-pytorch)
4. Courses
  - [Parallel Computing Using Cuda-C](https://github.com/CisMine/Parallel-Computing-Cuda-C?tab=readme-ov-file)
  - [CUDA-course](https://github.com/Infatoshi/cuda-course)
  - [CUDA Tutorial Code Samples](https://github.com/CUDA-Tutorial/CodeSamples)
  - [CUDA Tutorial](https://cuda-tutorial.github.io/)
5. Videos
 - [Programming Massively Parallel Processors](https://www.youtube.com/playlist?list=PLRRuQYjFhpmubuwx-w8X964ofVkW1T8O4)
 - [Simon Oz - GPU Programming](https://www.youtube.com/playlist?list=PL5XwKDZZlwaY7t0M5OLprpkJUIrF8Lc9j)
 - [CUDA programming](https://www.youtube.com/playlist?list=PLU0zjpa44nPXddA_hWV1U8oO7AevFgXnT)
 - [george hotz archive](https://www.youtube.com/@geohotarchive/videos) 
6. Example implementations
- CPU Matmul [Beating OpenBLAS in FP32 Matrix Multiplication: A Full Walkthrough](https://salykova.github.io/matmul-cpu)
- CPU Matmul [Fast Multidimensional Matrix Multiplication on CPU from Scratch](https://siboehm.com/articles/22/Fast-MMM-on-CPU)
- Matmul Ampere [How to Optimize a CUDA Matmul Kernel for cuBLAS-like Performance: a Worklog](https://siboehm.com/articles/22/CUDA-MMM)
- Matmul Ada [Implementing a fast Tensor Core matmul on the Ada Architecture](https://www.spatters.ca/mma-matmul)
- Matmul [Outperforming cuBLAS on H100: a Worklog](https://cudaforfun.substack.com/p/outperforming-cublas-on-h100-a-worklog)
- Matmul [Matrix Multiplication Background User's Guide](https://docs.nvidia.com/deeplearning/performance/dl-performance-matrix-multiplication/index.html)
 - [mnist CUDA](https://github.com/Infatoshi/mnist-cuda)
 - Softmax [Szymon Ożóg - Softmax](https://github.com/SzymonOzog/FastSoftmax)
 - Inference [yalm (Yet Another Language Model) is an LLM inference implementation in C++/CUDA](https://github.com/andrewkchan/yalm/tree/main) and article [Fast LLM Inference From Scratch](https://andrewkchan.dev/posts/yalm.html) 
 - Inference [This is an implementation of language model inference, aiming to get maximum single-GPU single-batch hardware utilization for LLM architectures with a minimal implementation and no dependencies](https://github.com/zeux/calm)
 - Training + inference [llm.cpp](https://github.com/karpathy/llm.c/tree/master)
 - [CUTLASS Tutorial: Fast Matrix-Multiplication with WGMMA on NVIDIA® Hopper™ GPUs](https://research.colfax-intl.com/cutlass-tutorial-wgmma-hopper/)
7. Kernel Leaderboard
   - [kernel leaderboard](https://scalingintelligence.stanford.edu/KernelBenchLeaderboard/)
   - [kernel bench](https://scalingintelligence.stanford.edu/blogs/kernelbench/) oraz [KernelBench - Can LLMs Write GPU Kernels?](https://scalingintelligence.stanford.edu/blogs/kernelbench/)
8. Benchmarking
 - [MI300X vs H100 vs H200 Benchmark Part 1: Training – CUDA Moat Still Alive](https://semianalysis.com/2024/12/22/mi300x-vs-h100-vs-h200-benchmark-part-1-training/)
 - [Forecasting GPU Performance for Deep Learning Training and Inference](https://arxiv.org/pdf/2407.13853)
 - [Benchmarking and Dissecting the Nvidia Hopper GPU Architecture](https://arxiv.org/pdf/2402.13499v1)
 - Example of 4090 (48GB) benchmark workflow [Testing the 4090 48GB](https://main-horse.github.io/posts/4090-48gb/)
 - Benchmarking FLOPS [Maximum Achievable Matmul FLOPS Finder](https://github.com/stas00/ml-engineering/tree/master/compute/accelerator/benchmarks) ogólnie fajna książka też w PDF [Machine Learning Engineering Open Book](https://github.com/stas00/ml-engineering)
- FLOPS [THOP: PyTorch-OpCounter](https://github.com/ultralytics/thop/tree/main/thop)
- FLOPS [calflops: a FLOPs and Params calculate tool for neural networks](https://github.com/MrYxJ/calculate-flops.pytorch/)
- FLOPS [DeepSpeed Flops Profiler](https://www.deepspeed.ai/tutorials/flops-profiler/)
- FLOPS [Flop Counter for PyTorch Models](https://github.com/facebookresearch/fvcore/blob/main/docs/flop_count.md)
- FLOPS [torch_flops](https://github.com/zugexiaodui/torch_flops)
- FLOPS [torchanalyse](https://github.com/HaoKang-Timmy/torchanalyse)
- FLOPS [FLOPS counter](https://gist.github.com/soumith/5f81c3d40d41bb9d08041431c656b233)
- FLOPS https://arxiv.org/abs/2407.13853
- MODEL-INFO [torchinfo](https://github.com/TylerYep/torchinfo)
9. Patterns and alghorithms
 - [HPC Matmul](https://en.algorithmica.org/hpc/algorithms/matmul/)
10. Article
   - [The GPU is not always faster](https://cowfreedom.de/#dot_product/introduction/)
11. CUDA Frameworks
   - [ThunderKittens](https://github.com/HazyResearch/ThunderKittens)
12. Papers
 - [The Case for Co-Designing Model Architectures with Hardware](https://arxiv.org/pdf/2401.14489)
13. Tools
   - [The Kernel Tuner](https://kerneltuner.github.io/kernel_tuner/stable/contents.html)

## Parallel computing
- [Programming Parallel Computers](https://ppc.cs.aalto.fi/)

## C++
  1. Courses
     - [Beginning C++ Programming - From Beginner to Beyond](https://www.udemy.com/course/beginning-c-plus-plus-programming/)
     - [Back to Basics](https://www.youtube.com/playlist?list=PLHTh1InhhwT4TJaHBVWzvBOYhp27UO7mI) i ogólnie kanał [CppCon](https://www.youtube.com/@CppCon)
2. Threading
   - [Learn Multithreading with Modern C++](https://www.udemy.com/course/learn-modern-cplusplus-concurrency/)
