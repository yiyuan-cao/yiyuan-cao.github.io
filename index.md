---
layout: cv
title: Yiyuan Cao's Homepage
---
# Yiyuan Cao
PhD student in Programming Languages.

<div id="webaddress">
<a href="cyy9447@pku.edu.cn">cyy9447@pku.edu.cn</a>
</div>

## About me

I’m Yiyuan, a fifth-year PhD student in the [Programming Languages Lab](https://pl.cs.pku.edu.cn/en/) at the School of Computer Science, Peking University. My advisor is Prof. [Zhenjiang Hu](https://zhenjiang888.github.io).

My research interest is in _programming languages_ and _program proofs_ in general. I am particularly interested in how to develop _verifiably_ safe, correct, and efficient programs in a _productive_ manner, with the help of programming language techniques.

## Education

`2017 - 2022`
__Peking University, Beijing, China.__

Bachelor of Science in Computer Science.

`2022 - now`
__Peking University, Beijing, China.__

PhD student in Programming Languages.

## Research experiences

`Feb 2024 - July 2024`
__National Institute of Informatics, Japan.__

Research intern, supervised by Prof. Taro Sekiyama.
Topic: type-based temporal property verification.

## Publications

`2026`
Zixun Guo\*, _Yiyuan Cao_\*, Di Wang, Zhenjiang Hu, __Extracting Functional Properties from Verified Imperative Programs__, APLAS 2026. (\* equal contribution) [[PDF]](media/APLAS26.pdf)

_Yiyuan Cao_, Jiayi Zhuang, Jinkai Fan, Di Wang, Zhenjiang Hu, __A HOL Theorem Proving Interface for C__, [TASE 2026](https://link.springer.com/chapter/10.1007/978-3-032-30693-7_8). [[PDF]](media/TASE26.pdf)

_Yiyuan Cao_, Jinkai Fan, Houjin Chen, Jiayi Zhuang, Zixun Guo, Zhiyi Wang, Wenbo Xu, Di Wang, Qinxiang Cao, Haiyan Zhao, Zhenjiang Hu, __Live Verification in C via In-Situ Proof Code__. (Manuscript) [[PDF]](media/liveverif-in-c.pdf)

`2025`
_Yiyuan Cao_, Taro Sekiyama, __Type-Based Temporal Resource Usage Analysis__. (Manuscript) [[PDF]](media/POPL26.pdf)

_Yiyuan Cao_, Wenbo Xu, Jinkai Fan, Jiayi Zhuang, Zixun Guo, Di Wang, Qinxiang Cao, Haiyan Zhao, Zhenjiang Hu, __A Proof-Integrated Low-Level Programming Language with Local, Operational, and Extensible Reasoning__. (Manuscript) [[PDF]](media/PLDI26-cstar.pdf)

`2024`
Zhichao Guan, _Yiyuan Cao_, Tailai Yu, Ziheng Wang, Di Wang, Zhenjiang Hu, __Semantics Lifting for Syntactic Sugar__, OOPSLA 2024.

`2023`
_Yiyuan Cao_, Zhichao Guan, Yushuo Xiao, Haiyan Zhao, Zhenjiang Hu, __Development of Domain-specific Languages: Status and Prospects__, _Science and Technology Foresight_, 2023, 2(1): 46-61. (in Chinese)

## Talks

`2026`
_Yiyuan Cao_, __C\*：Towards Proof-Integrated Systems Programming in C__. [PLChina 2026](https://pl.cs.pku.edu.cn/pl-china-2026/program/). [[Slides]](media/CStar-PLChina26-final.pdf)

`2025`
_Yiyuan Cao_, Taro Sekiyama, __Temporal Resource Typing: Enriching Substructural Typing for Liveness Reasoning__. IWACO 2025. [[Extended Abstract]](media/IWACO25.pdf) [[Slides]](media/IWACO25-slides.pdf)

## Teaching

`2023`
_Teaching Assistant._ [Software Foundations](https://xiongyingfei.github.io/SF/2023/), Peking University, Spring 2023.

_Teaching Assistant._ [Introduction to Functional Programming](https://zhenjiang888.github.io/FP/2023/), Peking University, Fall 2023.

## Research projects

__Proof-Integrated System-level Programming Language.__

A verification system usually needs three major components: a programming language, a specification language, and a proof language. _Can we have a system-level language where programming, specification, and proof seamlessly coexist?_

The goal of this project is to merge specification and proof capabilities into a low-level programming language. We are implementing a prototype language C\*. We extend the C language with explicit proof code and ghost variables that labels static information, supporting explicit reasoning at the language level.

__Semantics Lifting for Syntactic Sugar.__

_Syntactic sugar plays a crucial role in engineering programming languages._ It offers convenient syntax and higher-level abstractions, as witnessed by its pervasive use in both general-purpose and domain-specific contexts.

Unfortunately, the traditional approach of translating programs containing syntactic sugars into the host language can lead to abstraction leakage, breaking the promise of convenience and hindering program comprehension.

To address this challenge, we introduce the idea of semantics lifting that aims to statically derive self-contained evaluation rules for syntactic sugars. In this way, we get correctly-abstracted semantics for sugar-based DSLs at a low price.

__Building Resource-Aware Programming Languages in F\*.__

_How well does your program perform? We need more than functional correctness._ Resource consumption (e.g., time, memory, and energy) is a crucial aspect of the behavior of programs in real-world applications.

While significant efforts have been made in the domains of automatic resource analysis (e.g., [AARA](https://doi.org/10.1017/S0960129521000487)) and manual resource verification (e.g., [Separation Logic with time credits](https://doi.org/10.1007/s10817-017-9431-7)) for program resource bounds, there remains a notable gap in the integration of resource consumption information into programming language design.

To address this gap, we are implementing a prototype in F\*, a proof-oriented programming language, as a first step towards specifying and verifying resource bounds within a language-integrated framework. One of the key features of our approach is the ability to incorporate existing automatic resource analysis as automatable lemma libraries while retaining the expressiveness and flexibility to specify and verify complex resource bounds with more user intervention.

__Type-Based Temporal Resource Usage Analysis.__

Ensuring the valid use of resources (e.g., a file must be opened before read, a lock must be eventually released) is a critical aspect of program correctness. Previous work in this area either focuses on the verification of general temporal properties (including liveness) of a global trace or handles multiple resource traces but only addresses safety properties.

Our project tries to bridge this gap by presenting a type-based method for the compositional verification of temporal properties of traces generated by each resource. The target language is a higher-order functional language that includes primitives for dynamic resource creation, event-raising, and deallocation.

## Awards

`2025`
Huawei Scholarship.

`2019`
China National Scholarship.

`2016`
National Olympiad in Informatics (CCF NOI 2016), Silver Medal.

## Languages
Mandarin Chinese: native.

English: fluent as a working language.