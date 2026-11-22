---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

👋 Hi! I'm **Juan Manuel Copia**, a software engineer and computer scientist based in Madrid, Spain.

I'm the founder of **[Strent](https://strent.dev)**, a developer tool that adds Stripe subscriptions to a SaaS without webhook code. I'm also a former **Software Development Engineer at Amazon** and a **PhD candidate in Computer Science** at [Universidad Politécnica de Madrid](https://www.upm.es/) and the [IMDEA Software Institute](https://software.imdea.org/), advised by [Alessandra Gorla](https://software.imdea.org/~alessandra.gorla/), defending my thesis in December 2026.

My work connects **industrial software engineering** with **research in program analysis and automated reasoning**: I build production systems, and I study how to make software more reliable through automated analysis.

---

## Strent

I'm building **[Strent](https://strent.dev)**: Stripe subscriptions in your SaaS with no webhook code. Stripe charges your customers through its hosted Checkout and Customer Portal, Strent keeps track of which plan each customer has, and your application decides what they can use. Your plans and prices stay in your own Stripe account, and it works with any login and any database.

I designed, built, and operate it end to end: a **TypeScript** monorepo with **Fastify** APIs, a background worker, **PostgreSQL**, and **React** apps, running on Railway, with a public HTTP API and a [Node.js SDK on npm](https://www.npmjs.com/package/@strent-dev/node). The [step-by-step guide](https://docs.strent.dev/add-stripe-subscriptions/) is written for coding agents: in our guide trials, an agent takes a Next.js starter to working paid access in about 15 minutes of its own work.

---

## Industry Experience

At **Amazon**, I designed, built, and deployed services with **React** and **AWS** (Lambda, S3, DynamoDB), with infrastructure as code in **AWS CDK (TypeScript)** and CloudFormation across multiple regions. I also:

* Contributed to CI/CD pipelines, improving reliability and shortening release cycles.
* Served in the team's **on-call rotation**, resolving production incidents to keep services reliable.
* Built **AI agent skills** that automate complex debugging workflows.
* Reviewed peers' code and mentored new hires as an onboarding buddy.

Earlier, I fuzz-tested internal software components at **McAfee**, uncovering crashes that made them more robust.

I currently teach **Programming in Python**, **Pandas**, and **Introduction to Data with Spreadsheets** to bachelor's students at **Albert School** in Madrid.

---

## Research

My PhD research focuses on **Software Analysis and Verification**. I build systems that combine **Symbolic Execution**, **Search-Based Optimization**, and **LLMs** to automatically infer program properties, detect flaws, and validate patch correctness. This work is published at top software engineering venues, including **ICSE**, **ASE**, **ISSRE**, and **ICST**, and every tool it produced is open source (see [Software Artifacts](#software-artifacts) below).

---

## Interests

I'm passionate about building **intelligent, agentic software** that can reason, adapt, and collaborate autonomously. My current interests span:

* **AI:** AI-assisted software engineering, AI agents and infrastructure for scalable, data-driven products.
* **Program Analysis & Lightweight Formal Methods:** Symbolic execution, Search-based optimization, Software reliability and automated testing.

---

## Publications

<p>
<b>Search-based Inference of Class Invariants: How far can Simulated Annealing take us?</b> J. M. Copia, F. Molina, N. Aguirre, M. Frias, A. Gorla, P. Ponzio. <em>In the 17th Symposium on Search-Based Software Engineering (SSBSE '25), Seoul, Republic of Korea</em>, November 2025.
</p>

<p>
<b>Search-based Inference of Class Invariants (Poster)</b> J. M. Copia, F. Molina, N. Aguirre, M. Frias, A. Gorla, P. Ponzio. <em>In 2025 Genetic and Evolutionary Computation Conference (GECCO '25), Malaga, Spain</em>.
[
<a href="https://doi.org/10.1145/3712255.3726698">https</a>
]
</p>

<p>
<b>Improving Patch Correctness Analysis via Random Testing and Large Language Models</b> Facundo Molina, Juan Manuel Copia, Alessandra Gorla. <em> In Proceedings of the 17th IEEE International Conference on Software Testing, Verification and Validation (ICST '24), Toronto, Canada</em>, May 2024.
[
<a href="https://doi.org/10.1109/ICST60714.2024.00036">https</a>&nbsp;|
<a href="https://juanmacopia.github.io/files/icst2024.pdf">.pdf</a>&nbsp;
]
</p>

<p>
<b>Precise Lazy Initialization for Programs with Complex Heap Inputs</b> Juan Manuel Copia, Facundo Molina, Nazareno Aguirre, Marcelo Frias, Alessandra Gorla, and Pablo Ponzio. <em> In the 34th IEEE International Symposium on Software Reliability Engineering (ISSRE '23), Florence, Italy</em>, October 2023.
[
<a href="https://doi.org/10.1109/ISSRE59848.2023.00080">https</a>&nbsp;|
<a href="https://juanmacopia.github.io/files/pli2023.pdf">.pdf</a>&nbsp;
]
</p>

<p>
<b>LISSA: Lazy Initialization with Specialized Solver Aid</b> Juan Manuel Copia, Pablo Ponzio, Nazareno Aguirre, Alessandra Gorla, and Marcelo Frias. <em> In the 37th IEEE/ACM International Conference on Automated Software Engineering (ASE '22), Oakland Center, Michigan, USA</em>, October 2022.
[
<a href="https://doi.org/10.1145/3551349.3556965">https</a>&nbsp;|
<a href="https://juanmacopia.github.io/files/lissa2022.pdf">.pdf</a>&nbsp;
]
</p>

<p>
<b>Use of Test Doubles in Android Testing: An In-Depth Investigation</b> Mattia Fazzini, Chase Choi, Juan Manuel Copia, Gabriel Lee, Yoshiki Kakehi, Alessandra Gorla, and Alessandro Orso. <em> In Proceedings of the 44th International Conference on Software Engineering (ICSE '22), Pittsburgh, USA</em>, May 2022.
[
<a href="https://doi.org/10.1145/3510003.3510175">https</a>&nbsp;|
<a href="https://dl.acm.org/doi/pdf/10.1145/3510003.3510175">.pdf</a>&nbsp;
]
</p>

---

## Software Artifacts

<p>
<b>Express</b> — A tool that automatically infers method preconditions and class invariants using search-based algorithms. It generates executable predicates (Java code) for complex heap-allocated objects.  
[
<a href="https://github.com/JuanmaCopia/express">code</a>
]
</p>

<p>
<b>FixCheck</b> — A tool for improving patch correctness analysis in Java. It integrates static analysis, random testing, and large language models (LLMs) to generate tests that highlight and explain potential patch inconsistencies.  
[
<a href="https://github.com/facumolina/fixcheck/">code</a>
]
</p>

<p>
<b>PLI</b> — A symbolic execution framework built on top of Java Symbolic PathFinder (JPF). It enhances symbolic reasoning for complex heap-allocated inputs, improving precision and scalability.  
[
<a href="https://github.com/JuanmaCopia/spf-pli">code</a>
]
</p>

<p>
<b>SymSolve</b> — A bounded exhaustive solver for symbolic structures with complex representation invariants. It determines the satisfiability of partially symbolic heaps via operational specifications.  
[
<a href="https://github.com/JuanmaCopia/SymSolve">code</a>
]
</p>

<p>
<b>PySEAT</b> — A symbolic execution engine for Python that applies lazy initialization to automate test generation and achieve high coverage in complex programs.  
[
<a href="https://github.com/JuanmaCopia/PySEAT">code</a>&nbsp;|
<a href="https://juanmacopia.github.io/files/pyseat2020.pdf">.pdf</a>
]
</p>

---

## Contact

<p>
<b>Email:</b> jmcopia96@gmail.com  
</p>

<p>
You can find my full CV <a href="https://juanmacopia.github.io/files/cv.pdf">here</a>.  
</p>
