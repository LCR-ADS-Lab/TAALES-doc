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
British National Corpus (BNC) is a 100-million-word collection of samples from a wide range of written and spoken British English from the late 20th century.

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
The Corpus of Contemporary American English (COCA) includes more than one billion words from spoken, fiction, magazine, newspaper, and academic texts, offering frequency data for a variety of registers.

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
The TOEFL11 Corpus is a learner corpus containing essays written by English language learners categorized by proficiency levels and L1 background.

**Raw frequency**
- **Indices**:
  - NNS_Raw_Bigram_Freq_[High/Med/Low/WC]_AW  
  - NNS_Raw_Trigram_Freq_[High/Med/Low/WC]_AW  

**Logarithmic frequency**
- **Indices**:
  - NNS_Raw_Bigram_Freq_[High/Med/Low/WC]_AW_log  
  - NNS_Raw_Trigram_Freq_[High/Med/Low/WC]_AW_log  

---

### References
- Davies, 2009
- BNC Consortium, 2007
- Blanchard et al. (2013)
- Monteiro et al. (2020)

---

#### to-do-list
- Find/update all the references on this page. (alphabetical order)
- Please add what `WC` means. (maybe also in range?)
- maybe need to add information about the high/med/low for the TOEFL11 corpus?