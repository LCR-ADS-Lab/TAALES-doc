---
sort: 7
---

## Ngram range

### Definition
Ngram range refers to the distribution or spread of bigrams and trigrams across sections or registers in a corpus. It provides insights into how widely an ngram is used across various contexts, supporting analysis of generalizability and dispersion. A high range score indicates that the ngram appears in many different registers or text sections.

### Methodology
Mean range score for each text by summing the range values of ngrams (bigrams and trigrams) and dividing by the number of ngrams with valid range scores

### Corpus used
- COCA
- TOEFL11

---

### Calculated indices
- Replace `[ ]` with register (e.g., *academic*, *fiction*).

#### COCA

**Raw range**
- **Indices**:
  - COCA_[ ]_Bigram_Range  
  - COCA_[ ]_Trigram_Range  

**Logarithmic range**
- **Indices**:
  - COCA_[ ]_Bigram_Range_Log  
  - COCA_[ ]_Trigram_Range_Log  

#### TOEFL11
**Raw range**
- **Indices**:
  - NNS_Raw_Bigram_Range_[Low/Med/High/WC]_AW  
  - NNS_Raw_Trigram_Range_[Low/Med/High/WC]_AW  

**Logarithmic range**
- **Indices**:
  - NNS_Raw_Bigram_Range_[Low/Med/High/WC]_AW_log  
  - NNS_Raw_Trigram_Range_[Low/Med/High/WC]_AW_log  

---

#### Notes
- 

---

### References
- Davies, 2009
- BNC Consortium, 2007
- Blanchard et al. (2013)
- Monteiro et al. (2020)

---

#### to-do-list
- Find/update all the references on this page. (alphabetical order)
- Please explain the `valid range scores` in the methodology section.
- Please exlain what is low, med, high in NNS corpus in the notes section.