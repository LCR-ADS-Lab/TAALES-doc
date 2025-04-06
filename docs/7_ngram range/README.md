---
sort: 7
---

## Ngram range

### Definition
Ngram range refers to the distribution or spread of bigrams and trigrams across sections or registers in a corpus. It provides insights into how widely an ngram is used across various contexts, supporting analysis of generalizability and dispersion. A high range score indicates that the ngram appears in many different registers or text sections.

### Methodology
Mean range score for each text by summing the range values of ngrams (bigrams and trigrams) and dividing by the number of ngrams

### Corpus used
- COCA
- TOEFL11

### Calculated indices
- Replace `[ ]` with register (e.g., *academic*, *fiction*).

#### COCA 
The Corpus of Contemporary American English (COCA) includes more than one billion words from spoken, fiction, magazine, newspaper, and academic texts, offering frequency data for a variety of registers (Davies, 2009).

**Raw range**
- **Indices**:
  - COCA_[ ]_Bigram_Range  
  - COCA_[ ]_Trigram_Range  

**Logarithmic range**
- **Indices**:
  - COCA_[ ]_Bigram_Range_Log  
  - COCA_[ ]_Trigram_Range_Log  

#### TOEFL11
The TOEFL11 Corpus is a learner corpus containing essays written by English language learners categorized by proficiency levels and L1 background (Blanchard et al., 2013). The TOEFL11 L2 corpus comprises 12,000 essays, each written by a different learner taking the TOEFL iBT test. These essays were produced under timed conditions (30 minutes) for an independent writing task that mirrors first-year college writing. The corpus features responses from learners with eleven different native language backgrounds, written on eight different essay prompts. Expert raters assigned each essay a holistic score on a scale from 1.0 to 5.0, resulting in 1,201 essays rated as low proficiency, 5,964 as medium, and 3,835 as advanced. In total, the corpus contains 3,509,001 words (Monterio et al., 2020, p. 286).

**Raw range**
- **Indices**:
  - NNS_Raw_Bigram_Range_[Low/Med/High/WC]_AW  
  - NNS_Raw_Trigram_Range_[Low/Med/High/WC]_AW  

**Logarithmic range**
- **Indices**:
  - NNS_Raw_Bigram_Range_[Low/Med/High/WC]_AW_log  
  - NNS_Raw_Trigram_Range_[Low/Med/High/WC]_AW_log  

---

### References
- Davies, 2009
- BNC Consortium, 2007
- Blanchard et al. (2013)
- Monteiro et al. (2020)

---

#### to-do-list
- Find/update all the references on this page. (alphabetical order)