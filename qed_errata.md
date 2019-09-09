---
title: Errata for QED at Large
---

The table below contains corrections to the original manuscript. When further explanation is warranted,
it is provided below the table, and linked to within the first column. 
Pending additions to the errata can be found in [Github issues](https://github.com/proofengineering/proofengineering.github.io/issues).

# Corrections

Page references are for printed line numbers (in the range 103 to 281).

Abbreviations for different types of corrections:

- Cor - correction of language
- Cpltf - change of page layout or text format
- Fct - factual correction
- Cit - correction or addition of citation
- Cod - correction of code

| Page/Line/Footnote/Explanation        | Original text           | (type of correction) Corrected text | Acknowledgement | 
| ------------------------- | ----------------------- | ----------------------------------- | --------------- | 
| 108/16//                   | "... a _regular language_ ..." | (Fct) "... a _language_ ..." | Virgil Serbanuta | 
| 121/17//                   | "For example, mst papers ..."  | (Cor) "For example, most papers ... " | Mukesh Tiwari | 
| 184/28//[1](#exp1)                   | "universe polymorphism" | (Cit) "universe polymorphism (Harper and Pollack, 1991)"  | Bob Harper |
| 190/15//[2](#exp2)         | "Cohen et al., 2018"  | (Cit) "Angiuli et al., 2017; Cohen et al., 2018" |	Bob Harper |
| 154/27// | "mush = ..." | (Cod) [see code fix](http://github.com/proofengineering/proofengineering.github.io/issues/4) | Joomy Korkut |

# Explanations

<a name="exp1">1</a>: The universe polymorphism algorithm in Coq that we cite is based on [Type Checking with Universes](https://doi.org/10.1016/0304-3975(90)90108-T) by Robert Harper and Randy Pollack. The DOI that we link to was published in 1991, though the algorithm surfaced in a draft from 1989 that is also available online [here](https://doi.org/10.1007/3-540-50940-2_39).

<a name="exp2">2</a>: There are two flavors of cubical type theory, and we cite only one. The missing citation can be found in [Computational Higher-Dimensional Type Theory](https://doi.org/10.1145/3009837.3009861) by Carlo Angiuli, Robert Harper, and Todd Wilson.
