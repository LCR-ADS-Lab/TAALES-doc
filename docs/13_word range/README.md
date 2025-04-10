---
sort: 13
---

## Word range

### Definition
Word range refers to the number of texts in a corpus in which a particular word occurs. While word frequency is closely linked to language proficiency, it can be inflated by technical terms concentrated in a few documents. Word range helps mitigate this inflation and more accurately represents an individual's likely exposure to specific words.

### Methodology
Word range is calculated as the number of documents or categories in which a word appears, often aggregated as a mean score per word in a text. Several corpora are used to derive these indices, and transformations such as log-scaling or lemma-based calculations are applied for normalization or variant types.

### Corpus used
- BNC
- KF  
- COCA 
- SUBTLEXus  
- TOEFL11 Corpus

### Register
Varies by corpus, including written/spoken registers, academic/non-academic texts, and proficiency levels.

### Calculated indices
- Replace `[ ]` with register (e.g., *academic*, *fiction*, *spoken*, *written*)

#### BNC
British National Corpus (BNC) is a 100-million-word collection of samples from a wide range of written and spoken British English from the late 20th century.

**Raw range**
- **Indices**:
  - BNC_[ ]_Range_AW  
  - BNC_[ ]_Range_CW  
  - BNC_[ ]_Range_FW  

#### KF
Kucera-Francis (KF) Corpus is based on the Brown Corpus and provides frequency norms from American English texts published around 1961.

- **Indices**:
  - KF_Ncats_AW  
  - KF_Ncats_CW  
  - KF_Ncats_FW  
  - KF_Nsamp_AW  
  - KF_Nsamp_CW  
  - KF_Nsamp_FW  

#### COCA
The Corpus of Contemporary American English (COCA) includes more than one billion words from spoken, fiction, magazine, newspaper, and academic texts, offering frequency data for a variety of registers.

**Raw range**
- **Indices**:
  - COCA_[ ]_Range_AW
  - COCA_[ ]_Range_CW
  - COCA_[ ]_Range_FW

**Logarithmic range**
- **Indices**:
  - COCA_[ ]_Range_Log_AW  
  - COCA_[ ]_Range_Log_CW  
  - COCA_[ ]_Range_Log_FW

**Lemma range**
- **Indices**:
  - COCA_[ ]_lemma_range_AW  
  - COCA_[ ]_lemma_range_CW  
  - COCA_[ ]_lemma_range_FW

**Logarithmic lemma range**
- **Indices**:
  - COCA_[ ]_lemma_range_Log_AW  
  - COCA_[ ]_lemma_range_Log_CW  
  - COCA_[ ]_lemma_range_Log_FW

**Lemma type range**
- **Indices**:
  - COCA_[ ]_lemma_range_AW_TP  
  - COCA_[ ]_lemma_range_CW_TP  
  - COCA_[ ]_lemma_range_FW_TP

**Logarithmic lemma type range**
- **Indices**:
  - COCA_[ ]_lemma_range_Log_AW_TP  
  - COCA_[ ]_lemma_range_Log_CW_TP  
  - COCA_[ ]_lemma_range_Log_FW_TP

#### SUBTLEXus
SUBTLEXus is a subtitle-based corpus capturing word usage in spoken American English, ideal for understanding conversational frequency.

**Raw range**
- **Indices**:
  - SUBTLEXus_Range_AW  
  - SUBTLEXus_Range_CW  
  - SUBTLEXus_Range_FW

**Logarithmic range**
- **Indices**:
  - SUBTLEXus_Range_AW_Log  
  - SUBTLEXus_Range_CW_Log  
  - SUBTLEXus_Range_FW_Log  

#### TOEFL11
The TOEFL11 Corpus is a learner corpus containing essays written by English language learners categorized by proficiency levels and L1 background.

**Raw range**
- **Indices**:
  - NNS_Raw_Range_[High/Med/Low/WC]_AW  
  - NNS_Raw_Range_[High/Med/Low/WC]_CW  
  - NNS_Raw_Range_[High/Med/Low/WC]_FW

**Logarithmic range**
- **Indices**:
  - NNS_Raw_Range_[High/Med/Low/WC]_AW_log  
  - NNS_Raw_Range_[High/Med/Low/WC]_CW_log  
  - NNS_Raw_Range_[High/Med/Low/WC]_FW_log

**Lemma range**
- **Indices**:
  - NNS_Lemma_Range_[High/Med/Low/WC]_AW  
  - NNS_Lemma_Range_[High/Med/Low/WC]_CW  
  - NNS_Lemma_Range_[High/Med/Low/WC]_FW

**Logarithmic lemma range**
- **Indices**:
  - NNS_Lemma_Range_[High/Med/Low/WC]_AW_log  
  - NNS_Lemma_Range_[High/Med/Low/WC]_CW_log  
  - NNS_Lemma_Range_[High/Med/Low/WC]_FW_log

**Lemma type range**
- **Indices**:
  - NNS_Lemma_Range_Types_[High/Med/Low/WC]_AW  
  - NNS_Lemma_Range_Types_[High/Med/Low/WC]_CW  
  - NNS_Lemma_Range_Types_[High/Med/Low/WC]_FW

**Logarithmic lemma type range**
- **Indices**:
  - NNS_Lemma_Range_Types_[High/Med/Low/WC]_AW_log  
  - NNS_Lemma_Range_Types_[High/Med/Low/WC]_CW_log  
  - NNS_Lemma_Range_Types_[High/Med/Low/WC]_FW_log


---

### References
- Eguchi, M., & Kyle, K. (2020). Continuing to explore the multidimensional nature of lexical sophistication: The case of oral proficiency interviews. *The Modern Language Journal, 104*(2), 381-400.
- Kyle, K., & Crossley, S. A. (2015). Automatically assessing lexical sophistication: Indices, tools, findings, and application. *Tesol Quarterly, 49*(4), 757-786.



---

#### to-do-list
- Find/update all the references on this page. (alphabetical order) >>> Zeinab: please check this!
- Can you double check whether TP refers to top proportion or type frequency?
