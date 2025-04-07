---
sort: 6
---

## Ngram frequency

### Definition
Ngram frequency refers to how often sequences of *n* words (e.g., bigrams, trigrams) occur in a corpus. High-frequency ngrams reflect conventional multiword patterns (e.g., *a lot of*), while low-frequency ngrams may indicate less typical or more sophisticated usage (e.g., *is about being*).

### Methodology
Mean, log-transformed, and proportional frequency scores are computed by comparing target texts with reference corpora using bigram and trigram frequencies.

### Corpus used
- BNC
- COCA
- TOEFL11

### Register
- Academic, Fiction, Magazine, News, Spoken, Written

### Calculated indices
- Replace `[ ]` with register (e.g., *academic*, *fiction*) and `[10k–100k]` with threshold size (e.g., 10k, 20k, ..., 100k)

#### BNC
British National Corpus (BNC) is a 100-million-word collection of samples from a wide range of written and spoken British English from the late 20th century (BNC, 2007).

**Raw frequency**
- **Indices**:
  - BNC_[ ]_Bigram_Freq_Normed  
  - BNC_[ ]_Trigram_Freq_Normed  

**Logarithmic frequency**
- **Indices**:
  - BNC_[ ]_Bigram_Freq_Normed_Log  
  - BNC_[ ]_Trigram_Freq_Normed_Log  

**Proportional frequency**
- **Indices**:
  - BNC_[ ]_Bigram_Proportion  
  - BNC_[ ]_Trigram_Proportion  

#### COCA
The Corpus of Contemporary American English (COCA) includes more than one billion words from spoken, fiction, magazine, newspaper, and academic texts, offering frequency data for a variety of registers (Davies, 2009).

**Raw frequency**
- **Indices**:
  - COCA_[ ]_Bigram_Frequency  
  - COCA_[ ]_Trigram_Frequency  

**Logarithmic frequency**
- **Indices**:
  - COCA_[ ]_Bigram_Frequency_Log  
  - COCA_[ ]_Trigram_Frequency_Log  

**Proportional frequency**
- **Indices**:
  - COCA_[ ]_bi_prop_[10k–100k]  
  - COCA_[ ]_tri_prop_[10k–100k]  

#### TOEFL11
The TOEFL11 Corpus is a learner corpus containing essays written by English language learners categorized by proficiency levels and L1 background (Blanchard et al., 2013). The TOEFL11 L2 corpus comprises 12,000 essays, each written by a different learner taking the TOEFL iBT test. These essays were produced under timed conditions (30 minutes) for an independent writing task that mirrors first-year college writing. The corpus features responses from learners with eleven different native language backgrounds, written on eight different essay prompts. Expert raters assigned each essay a holistic score on a scale from 1.0 to 5.0, resulting in 1,201 essays rated as low proficiency, 5,964 as medium, and 3,835 as advanced. In total, the corpus contains 3,509,001 words (Monterio et al., 2020, p. 286).

**Raw frequency**
- **Indices**:
  - NNS_Raw_Bigram_Freq_[High/Med/Low/WC]_AW  
  - NNS_Raw_Trigram_Freq_[High/Med/Low/WC]_AW
  - *WC* stands for "whole corpus".

**Logarithmic frequency**
- **Indices**:
  - NNS_Raw_Bigram_Freq_[High/Med/Low/WC]_AW_log  
  - NNS_Raw_Trigram_Freq_[High/Med/Low/WC]_AW_log  

---

### References
- Blanchard, D., Tetreault, J., Higgins, D., Cahill, A., & Chodorow, M. (2013). TOEFL11: A corpus of non‐native English. *ETS Research Report Series, 2013*(2), i-15. https://doi.org/10.1002/j.2333-8504.2013.tb02331.x
- BNC Consortium. (2007). British national corpus. *Oxford Text Archive Core Collection*.
- Davies, M. (2009). The 385+ million word Corpus of Contemporary American English (1990–2008+): Design, architecture, and linguistic insights. *International journal of corpus linguistics, 14*(2), 159-190. https://doi.org/10.1075/ijcl.14.2.02dav
- Monteiro, K. R., Crossley, S. A., & Kyle, K. (2020). In search of new benchmarks: Using L2 lexical frequency and contextual diversity indices to assess second language writing. *Applied Linguistics, 41*(2), 280-300. https://doi.org/10.1093/applin/amy056
