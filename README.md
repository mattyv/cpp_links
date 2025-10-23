# cpp_links
[Top-Down performance analysis methodology](https://easyperf.net/blog/2019/02/09/Top-Down-performance-analysis-methodology) - Formal methodology (TMAM) for identifying performance bottlenecks using Intel's performance monitoring tools. Two-step iterative process: identify problem type (Frontend/Backend Bound, Bad Speculation, Retiring), then locate exact code location using PEBS.

[Swar Library](https://programming.sirrida.de/swar.html) - Comprehensive C++ template library for SIMD/SWAR (SIMD Within A Register) operations. Provides classes for bit operations, parallel arithmetic, shifts, rotations, shuffles, and compress/expand operations on integers from 8 to 128 bits.

[Bit Twiddling Hacks](https://graphics.stanford.edu/~seander/bithacks.html) - Collection of public domain bit manipulation techniques covering sign computation, bit counting, parity, swapping, bit reversal, modulus division, logarithms, trailing zeros, power of 2 rounding, and bit interleaving. Includes operation counts and performance notes.

[llvm-mca - LLVM Machine Code Analyzer](https://llvm.org/docs/CommandGuide/llvm-mca.html) - Performance analysis tool that statically measures machine code throughput and resource consumption using LLVM scheduling models. Estimates IPC, identifies bottlenecks via timeline/resource pressure views, supports custom regions with markers, and provides detailed pipeline simulation for processors with LLVM scheduling models.

[Hash Functions (CS 312)](https://www.cs.cornell.edu/courses/cs312/2008sp/lectures/lec21.html) - Overview of hash table implementation focusing on hash function design for uniform distribution. Covers client vs. implementer responsibilities, clustering measurement, and techniques including modular hashing, multiplicative hashing, CRCs, and cryptographic hash functions. Emphasizes achieving injection and diffusion properties.
