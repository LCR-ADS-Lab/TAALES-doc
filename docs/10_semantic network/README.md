---
sort: 10
---

## Semantic network

### Definition
Semantic network indices capture lexical relationships such as polysemy (multiple meanings per word) and hypernymy (hierarchical relationships between general and specific terms, e.g., *flower* vs. *rose*).

### Methodology
TAALES calculates semantic network indices using path-based measures in WordNet. Scores reflect either the number of senses a word has (polysemy) or the distance between concepts in a semantic hierarchy (hypernymy). Indices are averaged across parts of speech and path combinations.

### Corpus Used
- WordNet (Fellbaum, 1998)

### Calculated indices

#### Polysemy

- **Indices**:  
  - content_poly
  - poly_noun
  - poly_verb
  - poly_adj
  - poly_adv

#### Hypernymy – Nouns

- **Indices**:  
  - hyper_noun_S1_P1 
  - hyper_noun_Sav_P1
  - hyper_noun_Sav_Pav

#### Hypernymy – Verbs

- **Indices**:  
  - hyper_verb_S1_P1  
  - hyper_verb_Sav_P1
  - hyper_verb_Sav_Pav

#### Hypernymy – Combined (Nouns & Verbs)

- **Indices**:  
  - hyper_verb_noun_s1_p1
  - hyper_verb_noun_Sav_P1
  - hyper_verb_noun_Sav_Pav

---

#### Notes

- S1: Uses the first (most frequent) sense of the word.  
- Sav: Averages across all senses of the word.  
- P1: Uses the first (most direct) path in the hypernym hierarchy.  
- Pav: Averages across all possible paths for the word.

---

### References:
- Fellbaum, C. (Ed.). (1998). *WordNet: An electronic lexical database*. MIT press.
