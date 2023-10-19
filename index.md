---
layout: cv
title: Yiyuan Cao's CV
---
# Yiyuan Cao
PhD student in Programming Languages. Spicy food lover.

<div id="webaddress">
<a href="cyy9447@pku.edu.cn">cyy9447@pku.edu.cn</a>
| +86 18810917939
</div>

## About me

I’m Yiyuan, a second-year PhD student in the [Programming Language Lab](https://pl.cs.pku.edu.cn/en/) at the School of Computer Science, Peking University. My advisor is Prof. [Zhenjiang Hu](https://zhenjiang888.github.io).

My research interest is in _programming languages_ and _program proofs_ in general. I maintain a list of learning resources for these topics as a [Gist](https://gist.github.com/yiyuan-cao/fe3186ef85f70cef970ee221b2936548). I am particularly interested in how to develop _verifiably_ safe, correct, and efficient programs in a _productive_ manner, with the help of programming language techniques.

## Education

`2017 - 2022`
__Peking University, Beijing, China.__

Bachelor of Science in Computer Science.

`2022 - now`
__Peking University, Beijing, China.__

PhD student in Programming Languages.

## Publications

`2023`
_Yiyuan Cao_, Zhichao Guan, Yushuo Xiao, Haiyan Zhao, Zhenjiang Hu, __Development of Domain-specific Languages: Status and Prospects__, _Science and Technology Foresight_, 2023, 2(1): 46-61. (in Chinese)

Zhichao Guan, _Yiyuan Cao_, Di Wang, Zhenjiang Hu, __Semantics Lifting for Syntactic Sugar__. (in submission)

## Teaching

`2023`
_Teaching Assistant._ [Software Foundations](https://xiongyingfei.github.io/SF/2023/), Peking University, Spring 2023.

_Teaching Assistant._ [Introduction to Functional Programming](https://zhenjiang888.github.io/FP/2023/), Peking University, Fall 2023.

## Research projects
__Semantics Lifting for Syntactic Sugar.__

_Syntactic sugar plays a crucial role in engineering programming languages._ It offers convenient syntax and higher-level abstractions, as witnessed by its pervasive use in both general-purpose and domain-specific contexts.

Unfortunately, the traditional approach of translating programs containing syntactic sugars into the host language can lead to abstraction leakage, breaking the promise of convenience and hindering program comprehension.

To address this challenge, we introduce the idea of semantics lifting that aims to statically derive self-contained evaluation rules for syntactic sugars. In this way, we get correctly-abstracted semantics for sugar-based DSLs at a low price.

__Building Resource-aware Programming Languages in F\*.__ (ongoing)

_How well does your program perform? We need more than functional correctness._ Resource usage (e.g., time, memory, and energy) is critical for ensuring the correct behavior of programs in real-world applications.

While significant efforts have been made in the domains of automatic resource analysis (e.g., [AARA](https://doi.org/10.1017/S0960129521000487)) and manual resource verification (e.g., [Separation Logic with time credits](https://doi.org/10.1007/s10817-017-9431-7)) for program resource bounds, there remains a notable gap in the integration of resource usage as a core element of programming language design.

To address this gap, we are implementing a prototype in F\*, a proof-oriented programming language, as a first step towards specifying and verifying resource bounds within a language-integrated framework. One of the key features of our approach is the ability to incorporate existing automatic resource analysis as automatable lemma libraries while retaining the expressiveness and flexibility to specify and verify complex resource bounds with more user intervention.

__Proof-integrated System-level Programming Language.__ (ongoing)

A verification system usually needs three major components: a programming language, a specification language, and a proof language. _Can we have a system-level language where programming, specification, and proof seamlessly coexist?_

The goal of this project is to merge specification and proof capabilities into a system-level programming language, resulting in more readable specifications that resemble tests and more intuitive proof manipulation akin to symbolic execution. This approach has the potential to reduce the needed expertise for doing verification and bridge the communication gaps between proof engineers and program developers, which is often perceived as a significant obstacle to the broader adoption of verification practices.

We are implementing a prototype language with C-like syntax. By translating to Coq definitions and VST proof scripts, we offer a foundational correctness guarantee for free (with respect to the CompCert C semantics).

## Awards

`2016`
National Olympiad in Informatics (NOI), Silver medal.

`2019`
National Scholarship.

## Languages
Mandarin Chinese: native.

English: fluent as a working language. (CET-6 score: 607)

Coq: finished Software Foundations Vol. 1, Vol. 2, and most of Vol. 6.

Other languages I speak: C, F\*, OCaml, Haskell.
