---
sort: 11
---

## Word frequency

### Definition
Word frequency refers to the number of times a word occurs in a corpus of texts. Less frequent words in a reference corpus (e.g., *edifice*, *cuisine*, *egregious*) are considered more sophisticated than frequently occurring words (e.g., *building*, *food*, *bad*). 

### Methodology
Word frequency indices are calculated as the mean frequency score of words in a given text, using various reference corpora. Frequencies can be represented in several forms:
- Raw frequency: The sum of word frequency counts divided by the number of words in the text.
- Logarithmic frequency: A log transformation is applied to raw frequency scores to reduce the influence of extremely frequent words and normalize the distribution.
- Lemma frequency: Frequencies are computed based on the base (dictionary) form of words, rather than surface forms (e.g., run, runs, and ran are counted as run).
- Lemma type frequency: Frequency values are calculated based on unique lemma types in the text, rather than tokens.

Each index can be also computed for the following options: All words; Content words (CW); Function words (FW).

### Corpus used
- BNC
- KF
- COCA
- HAL
- Brown
- TL
- SUBTLEXus
- TOEFL11

### Calculated indices
- Replace `[ ]` with register (e.g., *academic*, *fiction*, *spoken*, *written*) 

#### BNC
British National Corpus (BNC) is a 100-million-word collection of samples from a wide range of written and spoken British English from the late 20th century.

**Raw frequency**
- **Indices**:
  - BNC_[ ]_Freq_AW  
  - BNC_[ ]_Freq_CW  
  - BNC_[ ]_Freq_FW

**Logarithmic frequency**
- **Indices**:
  - BNC_[ ]_Freq_AW_Log  
  - BNC_[ ]_Freq_CW_Log  
  - BNC_[ ]_Freq_FW_Log

#### KF
Kucera-Francis (KF) Corpus is based on the Brown Corpus and provides frequency norms from American English texts published around 1961.

**Raw frequency**
- **Indices**:
  - KF_Freq_AW  
  - KF_Freq_CW  
  - KF_Freq_FW

**Logarithmic frequency**
- **Indices**:
  - KF_Freq_AW_Log  
  - KF_Freq_CW_Log  
  - KF_Freq_FW_Log

#### COCA
The Corpus of Contemporary American English (COCA) includes more than one billion words from spoken, fiction, magazine, newspaper, and academic texts, offering frequency data for a variety of registers.

**Raw frequency**
- **Indices**:
  - COCA_[ ]_Frequency_AW  
  - COCA_[ ]_Frequency_CW  
  - COCA_[ ]_Frequency_FW

**Logarithmic frequency**
- **Indices**:
  - COCA_[ ]_Frequency_Log_AW  
  - COCA_[ ]_Frequency_Log_CW  
  - COCA_[ ]_Frequency_Log_FW

**Lemma frequency**
- **Indices**:
  - COCA_[ ]_lemma_frequency_AW  
  - COCA_[ ]_lemma_frequency_CW  
  - COCA_[ ]_lemma_frequency_FW

**Logarithmic lemma frequency**
- **Indices**:
  - COCA_[ ]_lemma_frequency_Log_AW  
  - COCA_[ ]_lemma_frequency_Log_CW  
  - COCA_[ ]_lemma_frequency_Log_FW

**Lemma type frequency**
- **Indices**:
  - COCA_[ ]_lemma_frequency_AW_TP  
  - COCA_[ ]_lemma_frequency_CW_TP  
  - COCA_[ ]_lemma_frequency_FW_TP

**Logarithmic lemma type frequency**
- **Indices**:
  - COCA_[ ]_lemma_frequency_Log_AW_TP  
  - COCA_[ ]_lemma_frequency_Log_CW_TP  
  - COCA_[ ]_lemma_frequency_Log_FW_TP

#### HAL
Hyperspace Analogue to Language (HAL) is a large-scale co-occurrence-based corpus providing frequency and contextual diversity measures for words based on their surrounding lexical context.

**Raw frequency**
- **Indices**:
  - Freq_HAL_AW  
  - Freq_HAL_CW  
  - Freq_HAL_FW

**Logarithmic frequency**
- **Indices**:
  - Log_Freq_HAL_AW  
  - Log_Freq_HAL_CW  
  - Log_Freq_HAL_FW

#### Brown
The Brown Corpus is a pioneering corpus of American English texts published in 1961, offering a balanced range of genres for word frequency analysis.

**Raw frequency**
- **Indices**:
  - Brown_Freq_AW  
  - Brown_Freq_CW  
  - Brown_Freq_FW

**Logarithmic frequency**
- **Indices**:
  - Brown_Freq_AW_Log  
  - Brown_Freq_CW_Log  
  - Brown_Freq_FW_Log

#### TL
Thorndike-Lorge (TL) Corpus includes frequency counts based on popular magazine articles and printed materials, designed to inform readability and educational materials.

**Raw frequency**
- **Indices**:
  - TL_Freq_AW  
  - TL_Freq_CW  
  - TL_Freq_FW

**Logarithmic frequency**
- **Indices**:
  - TL_Freq_AW_Log  
  - TL_Freq_CW_Log  
  - TL_Freq_FW_Log

#### SUBTLEXus
SUBTLEXus is a subtitle-based corpus capturing word usage in spoken American English, ideal for understanding conversational frequency.

**Raw frequency**
- **Indices**:
  - SUBTLEXus_Freq_AW  
  - SUBTLEXus_Freq_CW  
  - SUBTLEXus_Freq_FW

**Logarithmic frequency**
- **Indices**:
  - SUBTLEXus_Freq_AW_Log  
  - SUBTLEXus_Freq_CW_Log  
  - SUBTLEXus_Freq_FW_Log

#### TOEFL11
The TOEFL11 Corpus is a learner corpus containing essays written by English language learners categorized by proficiency levels and L1 background.

**Raw frequency**
- **Indices**:
  - NNS_Raw_Freq_[High/Med/Low/WC]_AW  
  - NNS_Raw_Freq_[High/Med/Low/WC]_CW  
  - NNS_Raw_Freq_[High/Med/Low/WC]_FW

**Logarithmic frequency**
- **Indices**:
  - NNS_Raw_Freq_[High/Med/Low/WC]_AW_log  
  - NNS_Raw_Freq_[High/Med/Low/WC]_CW_log  
  - NNS_Raw_Freq_[High/Med/Low/WC]_FW_log

**Lemma frequency**
- **Indices**:
  - NNS_Lemma_Freq_[High/Med/Low/WC]_AW  
  - NNS_Lemma_Freq_[High/Med/Low/WC]_CW  
  - NNS_Lemma_Freq_[High/Med/Low/WC]_FW

**Logarithmic lemma frequency**
- **Indices**:
  - NNS_Lemma_Freq_[High/Med/Low/WC]_AW_log  
  - NNS_Lemma_Freq_[High/Med/Low/WC]_CW_log  
  - NNS_Lemma_Freq_[High/Med/Low/WC]_FW_log

**Lemma frequency types**
- **Indices**:
  - NNS_Lemma_Freq_Types_[High/Med/Low/WC]_AW  
  - NNS_Lemma_Freq_Types_[High/Med/Low/WC]_CW  
  - NNS_Lemma_Freq_Types_[High/Med/Low/WC]_FW

**Logarithmic lemma frequency types**
- **Indices**:
  - NNS_Lemma_Freq_Types_[High/Med/Low/WC]_AW_log  
  - NNS_Lemma_Freq_Types_[High/Med/Low/WC]_CW_log  
  - NNS_Lemma_Freq_Types_[High/Med/Low/WC]_FW_log

---

### References
- BNC Consortium, 2007
- Kucera & Francis, 1967
- Davies, 2009
- Balota et al., 2007
- Lund & Burgess, 1996
- Brown, 1984
- Svartvik & Quirk, 1980
- Thorndike & Lorge, 1944
- Brysbaert & New, 2009
- Blanchard et al., 2013
- Monteiro et al., 2020

---

#### to-do-list
- Find/update all the references on this page. (alphabetical order)
- Please add what `WC` means.
- maybe need to add information about the high/med/low for the TOEFL11 corpus?
- Can you double check whether TP refers to top proportion or type frequency? Based on the Index Guide sheet, it is said type frequency, but the previous markdown file consistently said it as top proportion... (please doulbe check TP in other sub-constructs as well.)