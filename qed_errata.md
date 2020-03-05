---
title: Errata for QED at Large
---

The table below contains corrections to the original manuscript. When further explanation is warranted,
it is provided below the table, and linked to within the first column. 
Pending additions to the errata can be found in [Github issues](https://github.com/proofengineering/proofengineering.github.io/issues).

A note on omissions: The survey paper often lists a non-exhaustive sample of work in a domain. This is to some degree necessary. 
Still, this page lists omissions as relevant, especially when particularly influential work is missing or when sampled work is biased toward particular interactive theorem provers.

# Corrections

Page references are for printed line numbers (in the range 103 to 281).

Abbreviations for different types of corrections:

- Cor - correction of language
- Cpltf - change of page layout or text format
- Fct - factual correction
- Cit - correction or addition of citation
- Cod - correction of code
- Clar - clarification

| Page/Line/Footnote/Explanation        | Original text           | (type of correction) Corrected text | Acknowledgement | 
| ------------------------- | ----------------------- | ----------------------------------- | --------------- | 
| 108/16//                   | "... a _regular language_ ..." | (Fct) "... a _language_ ..." | Virgil Serbanuta | 
| 112/18//[5](#exp5) | | (Cit) missing CompCertTSO and Crellvm | Peter Sewell |
| 121/17//                   | "For example, mst papers ..."  | (Cor) "For example, most papers ... " | Mukesh Tiwari | 
| 135/1//[4](#exp4) | | (Cit) missing early work on definitional mechanisms in HOL | Peter Sewell|
| 154/27// | "mush = ..." | (Cod) [see code fix](http://github.com/proofengineering/proofengineering.github.io/issues/4) | Joomy Korkut |
| 163/22//[3](#exp3) | "Note that the extra spacing is necessary ... " | (Fct) omit---inaccurate | Peter Sewell |
| 163/24// | "The more general proof assistant-agnostic specification language Lem" | (Fct) "The proof assistant-agnostic specification language Lem" | Peter Sewell |
| 163/30// | | (Cit) missing citation for [Specware](http://www.specware.org/) in refinement | Matthew Wilson |
| 164/9// | "This relation can also be stated and proven ... " | (Clar) "This relation can also be proven ... " | Tej Chajed |
| 164/30// | | (Clar) It is a stretch to include proof and program refinement in the same section | Tej Chajed |
| 170/1// | "more the more" | (Cor) "the more" | Christoph Baumann |
| 176/13//[6](#exp6) | | (Cit) missing early simulation citations | Peter Sewell |
| 176/16//[8](#exp8) | | (Clar) CompCert simulation terminology is confusing (see note) | Tej Chajed |
| 176/30//[7](#exp7) | "Together, a forward and a backward simulation establish indistinguishability" | (Fct) not always---see note | Peter Sewell |
| 179/18// | "defied" | (Cor) "defined" | Anton Trunov |
| 182/19// | "his can" | (Cor) "this can" | Christoph Baumann |
| 183/30// | "dedicate" | (Cor) "dedicated" | Anton Trunov |
| 184/28//[1](#exp1)                   | | (Cit) missing citation for universe polymorphism | Bob Harper |
| 190/15//[2](#exp2)         |  | (Cit) missing citations for cubical type theory |	Bob Harper |
| 191/27// | | (Clar) "REPL" is first used here, but defined later on page 196 | Christoph Baumann |
| 238/2// | "The End of History:" | (Cit) "The End of History?" | Anton Trunov |

# Explanations

<a name="exp1">1</a>: The universe polymorphism algorithm in Coq that we cite is based on [Type Checking with Universes](https://doi.org/10.1016/0304-3975(90)90108-T) by Robert Harper and Randy Pollack. The DOI that we link to was published in 1991, though the algorithm surfaced in a draft from 1989 that is also available online [here](https://doi.org/10.1007/3-540-50940-2_39).

<a name="exp2">2</a>: There are at least two flavors of cubical type theory, and we cite only one. The missing citation can be found in [Computational Higher-Dimensional Type Theory](https://doi.org/10.1145/3009837.3009861) by Carlo Angiuli, Robert Harper, and Todd Wilson.

<a name="exp3">3</a>: From Peter: "The grammar productions need spacing between tokens, to let Ott infer what the tokens are, but that spacing is not needed in the symbolic terms in inductive rules."

<a name="exp4">4</a>: See, for example, [The HOL Logic Extended with Quantification over Type Variables](https://doi.org/10.1007/BF01383982) by Thomas F. Melham,
and [A Package For Inductive Relation Definitions In HOL](https://doi.org/10.1109/hol.1991.596299), also by Thomas F. Melham.

<a name="exp5">5</a>: For CompCertTSO, see [Verifying Fence Elimination Optimisations](https://doi.org/10.1007/978-3-642-23702-7_14) by Viktor Vafeiadis and Francesco Zappa Nardelli,
[Relaxed-Memory Concurrency and Verified Compilation](https://doi.org/10.1145/1926385.1926393) by Jaroslav Ŝevčik _et al._, 
and [CompCertTSO: A Verified Compiler for Relaxed-Memory Concurrency](https://doi.org/10.1145/2487241.2487248) by Jaroslav Ŝevčik _et al._
For Crellvm, see [Crellvm: Verified Credible Compilation for LLVM](https://doi.org/10.1145/3192366.3192377) by Jeehoon Kang _et al._

<a name="exp6">6</a>: We cite a tech report explaining simulation when we introduce the concept, but this dates back at least to Milner's [process calculus](https://dl.acm.org/citation.cfm?id=539036) work more than a decade before the cited report.

<a name="exp7">7</a>: The coverage of simulation in this survey is a bit simplified. Much of the simulation literature defines simulation in terms of _observable behavior_.
The truth of this particular comment about indistinguishability depends on the definition of "observable behavior."

<a name="exp8">8</a>: While CompCert is one of the most well-known modern uses of simulation, the term "backward simulation" as used by CompCert is not
the same as "backward simulation" as used by other sources like the cited tech report and [Butler Lampson's lecture notes](https://web.mit.edu/6.826/www/notes/HO8.pdf).
In those sources, "backward simulation" refers to induction in reverse execution order.

