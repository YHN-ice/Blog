---
title: "Projects"
date: 2023-12-06T14:08:58-05:00
tags: [résumé]
cv: true
hidden: true
---

> << [Curriculum Vitae](/posts/cv)
## [Lambda Calculus Interpreter]("https://github.com/YHN-ice/LambdaCalculusParser")
November 2022 -- June 2023
: Software Developer, built an interpreter for Lambda Calculus introduced by _Alonzo Church_ 
: Fudan University, Shanghai, China 
- Developed a lexer with Flex to facilitate the lexical tokenization of all terms in a simple Lambda Calculus system
- Built reduction driver for applying function to arguments with reduced and conflict-free syntax analytical rules in Bison 
- Optimized beta-reduction using a normal-order reduction strategy in an object-oriented model, implemented in C++
- Integrated with LLVM tool chain to support interpretation of C++ pure functions through custom attribute and `Rewriter` API

## [Fortran to C++ Translator]("https://github.com/YHN-ice/CFortranTranslator") 
April -- December 2022
: Software Developer, developed on an open-source project CFortranTranslator 
: Fudan University, Shanghai, China 
- Enhanced a lexer using Finite State Automata in C++ to incorporate missing Fortran syntaxes, including line continuation and pointers
- Completed the syntactic parsing and C++ code generation to include additional Fortran statements, such as `USE` and `FORMAT`
- Extended the existing tool by designing and implementing functionality for translating the `Module` program unit in Fortran, utilizing YACC rules and C++ production operations
- Authored detailed development documentation to communicate requirements from the Department of Aeronautics and Astronautics

## Library Management System
March -- June 2021
: Software Developer, a library information management system using Spring Boot 
: Fudan University, Shanghai, China 
- Implemented a reliable, robust, and secure authentication filter chain in the Spring Security framework, integrating JSON Web Tokens for enhanced security
- Refactored the project architecture into microservices, focusing on decoupling and modularization in both system and API design, which resulted in a threefold increase in throughput
- Configured and deployed the application on scalable cloud servers, employing Docker Image and Docker Compose to streamline deployment with a unified configuration file
- Utilized the Eureka module in Spring Cloud to facilitate load balancing and automatic service discovery for scalable microservices
- Collaborated with team members through weekly meetings, RESTful API design and requirement documentation, and pair programming

## Zookeeper-mini
June 2022
: Developed a minimal distributed database conforming with the Zab protocol.
+ Implemented Discovery, Synchronization, and Broadcast phases in the Zab protocol 
+ Developed Heartbeat and Election mechanisms to achieve recovery from failure
## Single Cycle Processor using Chisel3
April -- May 2022
: Designed a single-cycle processor supporting RISC-V RV32I.
## Unix Shell
May 2022
: Built a tiny shell on top of UNIX system call interface with built-in commands, IO redirection, pipe, and environment variables.
## Lottery Predictive Model in Hidden Markov Model
December 2021
: Implemented the Baum–Welch algorithm to learn parameters from history of lottery numbers.
## Age Classifier by Voice
May 2021
: Constructed a classifier built on composite RNNs.
+ Preprocessed and feature engineered on audio samples from [*mozilla.org common voice*](https://commonvoice.mozilla.org) dataset 
+ Built models composed of different RNNs and compare their respective performances
## Huffman Compression Program
September -- November 2020
: Built a program to compress directories and/or files with wide-ranging sizes and types using Huffman coding.
