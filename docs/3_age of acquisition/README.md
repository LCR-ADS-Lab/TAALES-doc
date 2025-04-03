---
sort: 3
---

## Age of acquisition/exposure

### Definition
Age of acquisition (AoA) and/or age of exposure (AoE) indicate the average age a native speaker learns or first encounters a word.

### Corpus used
- **AoA**: N/A
- **AoE**: TASA (Touchstone Applied Sciences Associates)

### Register
- **AoA**: Written surveys  
- **AoE**: Educational texts

### Calculated indices

#### Age of acquisition (AoA)

- **Definition**: Age of acquisition (AoA) refers to the age at which a person is first expected to learn a particular word. This measure is based on AoA norms that were collected for 30,121 lemmas (Kuperman et al., 2012).
- **Description**: Average age of acquisition score
- **Methodology**: Mean; sum of AoA scores divided by the number of words in the text with AoA scores
- **Indices**:
  - Kuperman_AoA  
  - Kuperman_AoA_TP  
  - Kuperman_AoA_CW  
  - Kuperman_AoA_CW_TP  
  - Kuperman_AoA_FW  
  - Kuperman_AoA_FW_TP

#### Age of exposure (AoE)

- **Definition**: Age of exposure (AoE) refers to the age at which a person is first expected to encounter a particular word in an educational context. All AoE indices provide a measure of similarity based on words co-occurring in similar contexts.
- **Description**: Incremental score for words across 13 grade levels using LDA modeling
- **Methodology**: LDA (Latent Dirichlet Allocation) modeling
- **Indices**:
  - aoe_inverse_average  
  - aoe_inverse_average_TP  
  - aoe_inverse_linear_regression_slope  
  - aoe_inverse_linear_regression_slope_TP  
  - aoe_index_above_threshold_40  
  - aoe_index_above_threshold_40_TP  
  - aoe_inflection_point_polynomial  
  - aoe_inflection_point_polynomial_TP

---

#### Notes
- TP means type-based calculations, while all other indices are token-based.
- The Kuperman indices are calculated based on raw word tokens.

---

### References
- Dascalu, M., McNamara, D., Crossley, S., & Trausan-Matu, S. (2016, March). Age of exposure: A model of word learning. In *Proceedings of the AAAI Conference on Artificial Intelligence* (Vol. 30, No. 1). https://doi.org/10.1609/aaai.v30i1.10372
- Kuperman, V., Stadthagen-Gonzalez, H., & Brysbaert, M. (2012). Age-of-acquisition ratings for 30,000 English words. *Behavior research methods, 44*, 978-990. https://doi.org/10.3758/s13428-012-0210-4