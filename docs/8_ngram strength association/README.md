---
sort: 8
---

## Ngram strength of association

### Definition
Ngram strength of association (SOA) measures how strongly the words in an ngram are connected based on their co-occurrence patterns.

### Methodology
TAALES calculates five statistical association measures for bigrams and trigrams across COCA subcorpora:
- **MI**: Mutual Information
- **MI²**: Mutual Information Squared
- **T**: T-score
- **DP**: Delta P (predictive association)
- **AC**: Approximate Collexeme (semantic co-occurrence)

### Corpus used
- BNC (BNC, 2007)
- COCA (Davies, 2009)
- TOEFL11 (NNS, Monterio et al., 2020)

### Register
- Academic, Fiction, Magazine, News, Spoken

### Calculated indices
- Replace `[ ]` with register (e.g., *academic*, *fiction*): e.g., COCA_academic_bi_MI, COCA_fiction_bi_MI.
- For COCA, you can choose the `lemma` option; however, for indices from BNC and TOEFL11, only the `raw` option is available.

#### Mutual information (MI)

- **Description**: Highlights rare but highly exclusive combinations. Sensitive to low-frequency ngrams.
- **Indices**:
  - BNC/COCA/NNS_[ ]_bi_MI  
  - BNC/COCA/NNS_[ ]_tri_MI  
  - BNC/COCA/NNS_[ ]_tri_2_MI  

#### Mutual information squared (MI²)

- **Description**: Modifies MI to reduce low-frequency bias by squaring the numerator. Favors exclusive, yet not extremely rare, combinations.
- **Indices**:
  - BNC/COCA/NNS_[ ]_bi_MI2  
  - BNC/COCA/NNS_[ ]_tri_MI2  
  - BNC/COCA/NNS_[ ]_tri_2_MI2  

#### T score (T)

- **Description**: Emphasizes more frequent word combinations with weaker associations. Often reflects formulaic or generic phrases.
- **Indices**:
  - BNC/COCA/NNS_[ ]_bi_T  
  - BNC/COCA/NNS_[ ]_tri_T  
  - BNC/COCA/NNS_[ ]_tri_2_T  

#### Delta P (DP)

- **Description**: Captures predictive strength in directional co-occurrence. A high DP score means one word strongly predicts the next.
- **Indices**:
  - BNC/COCA/NNS_[ ]_bi_DP  
  - BNC/COCA/NNS_[ ]_tri_DP  
  - BNC/COCA/NNS_[ ]_tri_2_DP  


#### Approximate collexeme (AC)

- **Description**: Measures how semantically cohesive a word pair is. High AC scores indicate formulaic or strongly related word sequences.
- **Indices**:
  - BNC/COCA/NNS_[ ]_bi_AC  
  - BNC/COCA/NNS_[ ]_tri_AC  
  - BNC/COCA/NNS_[ ]_tri_2_AC  

---

### Notes
- `tri_MI` measures treats the first word as item 1 and the following bigram (i.e., the next two words combined) as item 2.
- `tri_2_MI` considers the first bigram (i.e., the first two words combined) as item 1 and the remaining word as item 2.

---

### References
- BNC Consortium. (2007). British national corpus. *Oxford Text Archive Core Collection*.
- Davies, M. (2009). The 385+ million word Corpus of Contemporary American English (1990–2008+): Design, architecture, and linguistic insights. *International journal of corpus linguistics, 14*(2), 159-190. https://doi.org/10.1075/ijcl.14.2.02dav
- Monteiro, K. R., Crossley, S. A., & Kyle, K. (2020). In search of new benchmarks: Using L2 lexical frequency and contextual diversity indices to assess second language writing. *Applied Linguistics, 41*(2), 280-300. https://doi.org/10.1093/applin/amy056
