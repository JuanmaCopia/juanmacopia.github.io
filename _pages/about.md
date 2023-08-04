---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I'm a PhD student at [IMDEA Software Institute](https://software.imdea.org/), under the supervision of [Alessandra Gorla](https://software.imdea.org/~alessandra.gorla/). My main research interests are Software Testing and Program Analysis. In my previous works, I mostly focused on Symbolic Execution.


## Publications

<p>
<b>Precise Lazy Initialization for Programs with Complex Heap Inputs</b> Juan Manuel Copia, Facundo Molina, Nazareno Aguirre, Marcelo Frias, Alessandra Gorla, and Pablo Ponzio. <em> To appear in the 34th IEEE International Symposium on Software Reliability Engineering (ISSRE '22), Florence, Italy</em>, October 2023.
</p>

<p>
<b>LISSA: Lazy Initialization with Specialized Solver Aid</b> Juan Manuel Copia, Pablo Ponzio, Nazareno Aguirre, Alessandra Gorla, and Marcelo Frias. <em> In the 37th IEEE/ACM International Conference on Automated Software Engineering (ASE '22), Oakland Center, Michigan, USA</em>, October 2022.
[
<a href="https://doi.org/10.1145/3551349.3556965">https</a>&nbsp;|
<a href="https://juanmacopia.github.io/files/lissa2022.pdf">.pdf</a>&nbsp;
]
</p>

<p>
<b>Use of test doubles in Android testing: an in-depth investigation</b> Mattia Fazzini, Chase Choi, Juan Manuel Copia, Gabriel Lee, Yoshiki Kakehi, Alessandra Gorla, and Alessandro Orso. <em> In Proceedings of the 44th International Conference on Software Engineering (ICSE '22), Pittsburgh, USA</em>, May 2022.
[
<a href="https://doi.org/10.1145/3510003.3510175">https</a>&nbsp;|
<a href="https://dl.acm.org/doi/pdf/10.1145/3510003.3510175">.pdf</a>&nbsp;
]
</p>


## Software Artifacts

<p>
<b>LISSA and PLI</b> are both symbolic execution techniques whose purpose is to improve symbolic analysis of programs with complex heap-allocated inputs and complex preconditions.
[
<a href="https://github.com/JuanmaCopia/spf-pli">code</a>&nbsp;
]
</p>

<p>
<b>SymSolve</b> is an efficient bounded exhaustive solver for symbolic structures with complex representation invariants. SymSolve was built to decide the satisfiability of structural constraints of partially symbolic heaps that arise during symbolic execution using lazy initialization.
[
<a href="https://github.com/JuanmaCopia/SymSolve">code</a>&nbsp;
]
</p>

<p>
<b>PySEAT</b> is a symbolic execution engine for Python programs. PySEAT also implements lazy initialization to support symbolic representation of heap-allocated objects and is able to automatically generate tests for these programs. PySEAT was part of my Master's thesis.
[
<a href="https://github.com/JuanmaCopia/PySEAT">code</a>&nbsp;|
<a href="https://juanmacopia.github.io/files/pyseat2020.pdf">.pdf</a>&nbsp;
]
</p>


## Research Team

* [Alessandra Gorla](https://software.imdea.org/~alessandra.gorla/) (IMDEA Software Institute, Spain)
* Pablo Ponzio (UNRC, Argentina)
* [Facundo Molina](https://facumolina.github.io/) (IMDEA Software Institute, Spain)
* [Nazareno Aguirre](https://dc.exa.unrc.edu.ar/staff/naguirre) (UNRC, Argentina)














<!--
## Projects

<table style="border-collapse: collapse; border: none; font-size:100%">
	<tr style="border: none;">
		<td style="width:30%; border: none;">
			<div class="card-img" style="text-align: left;">
				<img src="{{ site.url }}{{ site.baseurl }}/images/specfuzzer-pic.png">
			</div>
		</td>
		<td align="justify" style="border: none"><a href="https://sites.google.com/view/specfuzzer">SpecFuzzer</a> is a technique that automatically infers test oracles in the form of class specifications (postconditions, invariants). SpecFuzzer uses a fuzzer as a generator of candidate assertions derived from a grammar that is automatically obtained from the class definition; a dynamic invariant detector –Daikon– to filter out assertions invalidated by a test suite; and a mutation-based mechanism to cluster and rank assertions, so that similar constraints are grouped and then the stronger prioritized.
		</td>
	</tr>
	<tr style="border: none;">
		<td style="width:30%; border: none;">
			<div class="card-img" style="text-align: left;">
				<img src="{{ site.url }}{{ site.baseurl }}/images/evospex-pic.png">
			</div>
		</td>
		<td align="justify" style="border: none;">Software reliability analyses requires a specification of the intended behavior of the software under analysis. Unfortunately, software many times lacks such specifications, or only provides them for scenario-specific behaviors. This issue seriously diminishes the analyzability of software with respect to its reliability. <a href="https://github.com/facumolina/evospex">EvoSpex</a> is a tool that, given a Java method, uses an evolutionary algorithm to produce a specification of the method's current behavior, in the form of postcondition assertions.</td>
	</tr>
	<tr style="border: none;">
		<td style="width:30%; height: 30%; border: none;">
			<div class="card-img" style="text-align: left;">
				<img src="{{ site.url }}{{ site.baseurl }}/images/nn-proj-all-2.png">
			</div>
		</td>
		<td align="justify" style="border: none;">As expressing class specifications, such as class invariants, can be a very challenging task, and they are often absent accompanying code, in the <a href="https://sites.google.com/site/learninginvariants">Training Binary Classifiers as Data Structures Invariants</a> project we explore the use of artificial neural networks (binary classifiers) as class invariants of data structure implementations, i.e., we train these models to learn to distinguish valid/invalid instances of data structures. The obtained classifier can then be used in order to attempt to identify (in)correct behaviors in programs manipulating the class.</td>
	</tr>
</table> -->





