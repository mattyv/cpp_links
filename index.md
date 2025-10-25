---
layout: default
title: Home
---

# C++ Links

A curated collection of C++ resources, tools, and articles.

## Table of Contents
- [Performance and Optimization](#performance-and-optimization)
- [Data Structures and Algorithms](#data-structures-and-algorithms)
- [Language Implementation](#language-implementation)
- [SIMD and Low-Level Optimization](#simd-and-low-level-optimization)
- [General Resources](#general-resources)

## Performance and Optimization
- [Top-Down performance analysis methodology](https://easyperf.net/blog/2019/02/09/Top-Down-performance-analysis-methodology) - Formal methodology (TMAM) for identifying performance bottlenecks using PMU events and metrics.
- [llvm-mca - LLVM Machine Code Analyzer](https://llvm.org/docs/CommandGuide/llvm-mca.html) - Performance analysis tool that statically measures machine code throughput and resource consumption using LLVM's scheduling models.
- [Erik Rigtorp](https://rigtorp.se) - Blog and resources on high-performance C++ and low-latency programming. Features posts on ring buffer optimization, spinlocks, virtual memory latency, huge pages.
- [High Performance Computing](https://en.algorithmica.org/hpc/) - Comprehensive guide to high-performance computing, covering CPU architecture, optimization techniques, and parallel programming.

## Data Structures and Algorithms
- [Hash Functions (CS 312)](https://www.cs.cornell.edu/courses/cs312/2008sp/lectures/lec21.html) - Overview of hash table implementation focusing on hash function design for uniform distribution.
- [SMHasher3](https://gitlab.com/fwojcik/smhasher3) - Comprehensive test suite for evaluating non-cryptographic hash functions. Focuses on output distribution, collision detection, and performance testing.
- [Bit Twiddling Hacks](https://graphics.stanford.edu/~seander/bithacks.html) - Collection of public domain bit manipulation techniques covering sign computation, bit counting, parity, swapping, bit reversal.

## Language Implementation
- [Crafting Interpreters](https://craftinginterpreters.com) - Free online book teaching language implementation from scratch. Builds a full-featured scripting language with rich syntax, dynamic typing.
- [Abstraction and the C++ Machine Model](https://www.stroustrup.com/abstraction-and-machine.pdf) - Bjarne Stroustrup's paper on C++ for systems and embedded programming. Explains zero-overhead abstraction principles.

## SIMD and Low-Level Optimization
- [Swar Library](https://programming.sirrida.de/swar.html) - Comprehensive C++ template library for SIMD/SWAR (SIMD Within A Register) operations. Provides classes for bit operations, parallel arithmetic.
- [SWAR Explained: Parsing Eight Digits](https://lemire.me/blog/2022/01/21/swar-explained-parsing-eight-digits/) - Detailed explanation of using SWAR (SIMD Within A Register) techniques for efficient digit parsing.
- [SIMD Demystified (PDF)](http://const.me/articles/simd/simd.pdf) - In-depth article explaining SIMD (Single Instruction, Multiple Data) concepts for C++ programmers, including practical examples.

## General Resources
- [Awesome Modern C++](https://awesomecpp.com) - Curated collection of resources for modern C++11/14/17/20. Includes books (Effective Modern C++, C++ Core Guidelines), community resources (CppCast).
