---
sort: 2
---

## Academic language

### Definition
Academic language contains academic-specific terms and expressions that are less frequent in everyday language use. The Academic Word List (AWL) consists of frequently occurring academic words (e.g., *significant*, *analyze*), while the Academic Formulas List (AFL) includes common multi-word expressions found in academic texts (e.g., *in light of*, *in terms of*).

### Methodology
TAALES identifies and calculates indices related to academic language using lexical matching techniques against predefined lists (AWL and AFL). Both lists are frequency-based and derived from large academic corpora. Scores are normalized by text length and can include top-proportion (TP) variants.

### Corpus used
- Academic Corpus (for AWL)
- Four Corpora: Simpson et al., 2002; BNC, 2006; Hyland, 2004 (for AFL)

### Calculated indices

#### Academic Word List (AWL)

##### AWL general normed scores
- **Methodology**: Frequency scores calculated across all AWL word families.
- **Index**: All_AWL_Normed

##### AWL sublist normed scores (Non-TP)
- **Methodology**: Frequencies calculated by sublist and normalized.
- **Indices**: AWL_Sublist_1–10_Normed

##### AWL general normed scores (TP)
- **Methodology**: Normalized scores focusing on high-frequency AWL items.
- **Index**: All_AWL_Normed_TP

##### AWL sublist normed scores (TP)
- **Methodology**: Calculated within top-proportion segments and normalized.
- **Indices**: AWL_Sublist_1-10_Normed_TP

#### Academic Formulas List (AFL)

##### AFL normed scores
- **Methodology**: Scores derived from AFL lists across four major academic corpora, categorized by mode (spoken vs. written) and type (core vs. general).
- **Indices**: 
  - All_AFL_Normed
  - Core_AFL_Normed
  - Spoken_AFL_Normed
  - Written_AFL_Normed

---

### References
- British National Corpus, 2006. Accessed 1 October 2007.
- Coxhead, A. (2000). A New Academic Word List. *TESOL Quarterly, 34*(2), 213–238. https://doi.org/10.2307/3587951
- Hyland, K. (2004). Disciplinary discourses, *Michigan classics ed.: Social interactions in academic writing*. University of Michigan Press.  
- Kyle, K., Crossley, S. A., & Berger, C. (2018). The Tool for the Analysis of Lexical Sophistication (TAALES): Version 2.0. *Behavior Research Methods, 50*(3), 1030–1046. https://doi.org/10.3758/s13428-017-0924-4
- Simpson-Vlach, R., & Ellis, N. C. (2010). An academic formulas list: New methods in phraseology research. *Applied Linguistics, 31*(4), 487–512. https://doi.org/10.1093/applin/amp058
- Simpson, R. C., Briggs, S. L., Ovens, J., & Swales, J. M. (2002). The Michigan corpus of academic spoken English. *Ann Arbor, MI: The Regents of the University of Michigan*.