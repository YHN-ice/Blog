---
title: "Curriculum Vitae"
date: 2023-10-08T11:08:04+08:00
summary: "HNYe"
---
> Haoning Ye
# Skills

## Programming languages
- Rust, C/C++, Java, Python and Erlang

## Tech Skills & Frameworks
- Information Management System, Natural Language Processing, Distributed System
- LaTeX, Git, Linux, Emacs, Android, Docker
# Internship
## Sunde Info Inc.
Jun 2021 - Jul 2021 <span style="float:right;"> University Avenue, Shanghai, China</span>
: Developed query backend of large corpus for a exhibitive website 
- Developed responsive query (latency less than 100ms for 20000 documents) using Elasticsearch with customized word segmentation
- Reformatted 15000 records by reusable shell scripts to be adopted into a database for tens of thousands of structured documents
- Collaborated with a 10-member agile team to deliver new features, fixing bugs and improving performance through bi-weekly meeting
# PROJECTS
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

# EDUCATION
## University of Waterloo, Shanghai, China
  M.Eng in Electrical and Computer Engineering, Sep 2023 - August 2025 (Expected), Waterloo, ON, Canada
## Fudan University, Shanghai, China
  B.Eng in Software Engineering, Sep 2019 - Jun 2023, Shanghai, China
### Honors
+ Hhetea Freshmen Scholarship at Tengfei College, Fudan University(50/2000)
+ 2019~2020Third Prize of the Scholarship for Outstanding Students at Fudan University
+ 2021~2022Second Prize of the Scholarship for Outstanding Students at Fudan University

### Courses(A)
- Operating System I
- Computer Architecture
- Computer Network
- Software Engineering
- Compilers
- and 17 others

# WORK EXPERIENCE
## TA in *Programming in C for Freshmen*
Sep 2022 - Jan 2023 <span style="float:right;">Software School, Fudan University, Shanghai, China </span>
: Teaching assistant at a C programming language introduction course 
- Assisted in debugging students' code in projects and weekly assignment and project interviews
- Wrote official tutorial in LaTeX and stub code for weekly lab assignments that test students' familiarity with C programming language
- Designed with other assistants the midterm and final Projects for the semester, which include detailed instructions for freshman students to find the best strategy using Genetic Algorithm for a 2D game in book *Complexity: A Guided Tour by Mitchell, Melanie*

## TA at *Intro to Distributed System* 
Feb 2023 - Jun 2023  <span style="float:right;">Software School, Fudan University, Shanghai, China </span>
: Teaching assistant, an introduction to distributed system for undergraduates 
- Designed assignments monthly and wrote handout codes on topics of HDFS, HBase, Raft and other distributed system

# Research

## Towards Evaluating Knowledge Graph Value based on Corpus
Sep 2022 <span style="float:right;">Knowledge Works Research Laboratory at Fudan University, Shanghai, China</span>
: Research assistant, an evaluation on KG values using QAs derived from corpus
- Investigated Named Entity Recognition and Word Alignment methods in aid of Knowledge Graph evaluation by reproducing and tweaking existing works from related research

## [Xiezhi](https://arxiv.org/abs/2306.05783"): An Ever-Updating Benchmark for Holistic Domain Knowledge Evaluation
Apr 2023 <span style="float:right;"> Shanghai Key Laboratory of Data Science, School of Computer Science, Fudan University, Shanghai, China</span>
: Research assistant, researched various data source and contributed to a benchmark
- Collected 60000 data from various domains and transformed corpus in a desired format for building a benchmark of 28,000 QAs

## Structure-Rich Text Benchmark for Knowledge Inference Evaluation
Apr 2023 - Now  <span style="float:right;">Shanghai Key Laboratory of Data Science, School of Computer Science, Fudan University, Shanghai, China</span>
: Research assistant, researched various structured texts and built a benchmark
- Researched 9 structured texts and designed 32 tasks for a benchmark of 2512 QAs evaluating structure-based inference ability of LLMs
