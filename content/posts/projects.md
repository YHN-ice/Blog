---
title: "Projects"
date: 2023-12-06T14:08:58-05:00
tags: [résumé]
hidden: true
---

> << [Curriculum Vitae](/posts/cv)
## [Fortran to C++ Translator](https://github.com/YHN-ice/CFortranTranslator)
Apr 2022 - Dec 2022 <span style="float:right;"> Fudan University, Shanghai, China </span>
: Developed on an open-source project CFortranTranslator, in collaboration with Department of Aeronautics and Astronautics, Fudan University.
- Developed on a lexer using FSA in `C++` to support more Fortran syntaxes including line continuation, data statement, pointers
- Designed and implemented facilities for translating the Module program unit in Fortran using yacc rules and productions in `C++`
- Fixed missing syntactic parsing and `C++` code generator to involve more Fortran statements and other grammar rules (use, format...)
- Wrote comprehensive development documents to communicate on requirements from department of Aeronautics and Astronautics


## [Lambda Calculus Parser](https://github.com/YHN-ice/LambdaCalculusParser)
Nov 2022 - Jun 2023 <span style="float:right;"> Fudan University, Shanghai, China </span>
: An interpreter for Lambda Calculus introduced by the mathematician *Alonzo Church*.
- Developed a lexer using flex from scratch to support lexical tokenization of all terms in simple lambda calculus system
- Built evaluation backend entry for application in lambda calculus with reduced and conflict-free syntax analytical rules in pure bison
- Implemented efficient beta-reduction with strategy of normal-order reduction in object-oriented modeling using `C++`
- Integrated with LLVM tool chain to support interpretation of `C++` pure functions through custom attribute and Rewriter API
## Library Management System
Mar 2021 - Jun 2021 <span style="float:right;">Fudan University, Shanghai, China</span>
: A library information management system using Spring Boot 
- Implemented a reliable and secure authentication filter chain in the Spring Security framework and JSON web tokens
- Refactored the project into microservices with decoupling and modularization in system and API design, gaining 3x throughput boost
- Deployed on scalable cloud servers with Docker Image and Docker Compose with a single configuration file
- Collaborated with others through weekly meeting, well-documented API design and pair programming
## Zookeeper-mini
Jun 2022
: Developed a minimal distributed database conforming with the Zab protocol.
+ Implemented Discovery, Synchronization, and Broadcast phases in the Zab protocol 
+ Developed Heartbeat and Election mechanisms to achieve recovery from failure
## Single Cycle Processor using Chisel3
Apr 2022 - May 2022
: Designed a single-cycle processor supporting RISC-V RV32I.
## Unix Shell
May 2022
: Built a tiny shell on top of UNIX system call interface with built-in commands, IO redirection, pipe, and environment variables.
## Lottery Predictive Model in Hidden Markov Model
Dec 2021
: Implemented the Baum–Welch algorithm to learn parameters from history of lottery numbers.
## Age Classifier by Voice
May 2021
: Constructed a classifier built on composite RNNs.
+ Preprocessed and feature engineered on audio samples from [*mozilla.org common voice*](https://commonvoice.mozilla.org) dataset 
+ Built models composed of different RNNs and compare their respective performances
## Huffman Compression Program
Sep 2020 - Nov 2020
: Built a program to compress directories and/or files with wide-ranging sizes and types using Huffman coding.
