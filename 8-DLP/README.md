## Data Level Parallelism:

core: SIMD (Single Instruction, Multiple Data), used in both CPUs and GPUs



#### SIMD in CPUs

1. moderate levels of parallelism, vector registers are limited in size
2. The size of SIMD registers in CPUs and the supported SIMD instruction sets can vary significantly between different CPU architectures.

> SSE (Streaming SIMD Extensions), AVX (Advanced Vector Extensions), and NEON are SIMD (Single Instruction, Multiple Data) instruction set extensions **used in CPUs** to enhance performance by processing multiple data elements simultaneously, particularly useful in tasks like graphics processing, scientific computations, and multimedia handling.

3. Programming Model: involves using specific compiler flags for automatic vectorization or writing code using intrinsic functions or assembly to explicitly utilize SIMD instructions



#### SIMD in GPUs

1. high levels of parallelism
2. SIMD units in GPUs, often referred to as shader cores or CUDA cores in NVIDIA GPUs, are typically optimized for specific types of parallel operations common in graphics and scientific calculations.
3. Programming Model: involves using specialized APIs and languages like CUDA or OpenCL

> GPUs will be discussed in the next lecture.