# cpp_links
[Top-Down performance analysis methodology](https://easyperf.net/blog/2019/02/09/Top-Down-performance-analysis-methodology) - Formal methodology (TMAM) for identifying performance bottlenecks using Intel's performance monitoring tools. Two-step iterative process: identify problem type (Frontend/Backend Bound, Bad Speculation, Retiring), then locate exact code location using PEBS.

[Swar Library](https://programming.sirrida.de/swar.html) - Comprehensive C++ template library for SIMD/SWAR (SIMD Within A Register) operations. Provides classes for bit operations, parallel arithmetic, shifts, rotations, shuffles, and compress/expand operations on integers from 8 to 128 bits.

[Bit Twiddling Hacks](https://graphics.stanford.edu/~seander/bithacks.html) - Collection of public domain bit manipulation techniques covering sign computation, bit counting, parity, swapping, bit reversal, modulus division, logarithms, trailing zeros, power of 2 rounding, and bit interleaving. Includes operation counts and performance notes.

[llvm-mca - LLVM Machine Code Analyzer](https://llvm.org/docs/CommandGuide/llvm-mca.html) - Performance analysis tool that statically measures machine code throughput and resource consumption using LLVM scheduling models. Estimates IPC, identifies bottlenecks via timeline/resource pressure views, supports custom regions with markers, and provides detailed pipeline simulation for processors with LLVM scheduling models.

[Hash Functions (CS 312)](https://www.cs.cornell.edu/courses/cs312/2008sp/lectures/lec21.html) - Overview of hash table implementation focusing on hash function design for uniform distribution. Covers client vs. implementer responsibilities, clustering measurement, and techniques including modular hashing, multiplicative hashing, CRCs, and cryptographic hash functions. Emphasizes achieving injection and diffusion properties.

[Abstraction and the C++ Machine Model](https://www.stroustrup.com/abstraction-and-machine.pdf) - Bjarne Stroustrup's paper on C++ for systems and embedded programming. Explains zero-overhead abstraction principle, direct hardware mapping of types/operations, template-based generic programming for compile-time optimization, and real-world embedded applications. Demonstrates how classes, inheritance, and templates maintain performance while controlling complexity.

[Crafting Interpreters](https://craftinginterpreters.com) - Free online book teaching language implementation from scratch. Builds a full-featured scripting language with rich syntax, dynamic typing, garbage collection, lexical scope, first-class functions, closures, classes, and inheritance. Covers both high-level concepts (parsing, semantics) and low-level details (bytecode representation, garbage collection).

[SMHasher3](https://gitlab.com/fwojcik/smhasher3) - Comprehensive test suite for evaluating non-cryptographic hash functions. Focuses on output distribution, collision detection, and performance testing. Fork of Reini Urban's SMHasher with enhanced testing capabilities for hash tables, text hashing, and generic hash implementations including xxHash and other modern hash functions.
