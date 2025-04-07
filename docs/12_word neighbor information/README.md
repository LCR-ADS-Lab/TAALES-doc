---
sort: 11
---

## Word neighborhood information

### Definition
Word neighborhood information refers to the way words are connected based on shared orthographic (spelling), phonological (sound), and phonographic (both spelling and sound) features (Peereman & Content, 1997). Words with many neighbors tend to be processed more quickly, while complex words with few neighbors are often found in high-quality writing and are processed more slowly.

In TAALES, this sub-construct is divided into three sub-categories: orthographic, phonological, and phonographic neighborhood information.

### Methodology
- Count of neighbors
- Levenshtein distance
- Mean (log) frequency of neighbors based on HAL

### Corpus used
- HAL (only for frequency-based indices)

### Calculated indices

#### Orthographic neighborhood
Orthographic neighborhood refers to the set of words that can be formed by changing a single letter in a given word, resulting in a new valid word.

- **Indices**:
    - Ortho_N_[AW/CW/FW]: Number of orthographic neighbors
    - Freq_N_[AW/CW/FW]: Mean HAL frequency of neighbors
    - OLD_[AW/CW/FW]: Average Levenshtein Distance of 20 closest neighbors
    - OLDF_[AW/CW/FW]: Average log HAL frequency of 20 closest neighbors

#### Phonological neighborhood
Phonological neighborhood refers to words that differ from a target word by one phoneme through addition, deletion, or substitution.

- **Indices**:
    - Phono_N_[AW/CW/FW]; Phono_N_H_[AW/CW/FW]: Number of phonological neighbors (excluding/including homophones)
    - Freq_N_P_[AW/CW/FW]; Freq_N_PH_[AW/CW/FW]: Mean HAL frequency of phonological neighbors (excluding/including homophones)
    - PLD: Average Levenshtein Distance of closest phonological neighbors
    - PLDF: Average log HAL frequency of closest phonological neighbors

#### Phonographic neighborhood
Phonographic neighborhood refers to words that are both orthographic and phonological neighbors of a target word.

- **Indices**:
    - OG_N_[AW/CW/FW]; OG_NH_[AW/CW/FW]
    - Freq_N_OG_[AW/CW/FW]; Freq_N_OGH_[AW/CW/FW]

---

### References
- Peereman, R., & Content, A. (1997). Orthographic and phonological neighborhoods in naming: Not all neighbors are equally influential in orthographic space. Journal of Memory and language, 37(3), 382-410. https://doi.org/10.1006/jmla.1997.2516
