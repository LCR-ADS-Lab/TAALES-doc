---
sort: 5
---

## Contextual distinctiveness

### Definition
Contextual distinctiveness refers to how many different psychological, lexical, or semantic contexts a word typically appears in. Words that are more contextually distinct—appearing in fewer, more specific contexts—are often considered more difficult or advanced (Berger et al., 2017).

### Methodology
Several approaches are used to capture contextual distinctiveness:
- EAT: Variety of responses to a word in free association (Kiss et al., 1973)
- USF: Number of different stimuli that elicit a word in free association (Nelson, McEvoy, & Schreiber, 1998)
- McD: Probability of co-occurrence with frequent words in a narrow window (McDonald & Shillcock, 2001)
- Sem_D: Semantic variability across contextual environments in large corpora (Hoffman, Ralph, & Rogers, 2013)
- LSA: Hidden (latent) semantic structures beyond keywords (Laundauer et al., 2014)

### Corpus used
- EAT (Edinburgh Associative Thesaurus), written 
- USF Free Association Norms, written
- BNC (British National Corpus), written & spoken
- TASA (Touchstone Applied Sciences Associates), written

### Register
- Written (EAT, USF, BNC, TASA)  
- Spoken (BNC: Co-occurrence)

### Calculated indices

#### Free association response types (EAT)
- **Indices**:
  - EAT_types_AW  
  - EAT_types_CW  
  - EAT_types_FW   

#### Free association stimuli elicited (USF)
- **Indices**:
  - USF_AW  
  - USF_CW  
  - USF_FW  

#### Co-occurrence probability (McD)
- **Methodology**: Kullback-Leibler divergence (relative entropy)
- **Indices**:
  - McD_CD_AW  
  - McD_CD_CW  
  - McD_CD_FW  

#### Semantic distinctiveness (Sem_D)
- **Methodology**: Variability of contexts in which a word appears across 1,000-word text sections; Reversed natural log of mean LSA cosine similarity across chunks
- **Indices**:
  - Sem_D_AW  
  - Sem_D_CW  
  - Sem_D_FW  

#### Latent semantic analysis (LSA)
- **Indices**:
	- lsa_average_top_three_cosine
	- lsa_max_similarity_cosine
	- lsa_average_all_cosine

---

### References
- Berger, C., Crossley, S. & Kyle, K. (2017). Using Native-Speaker Psycholinguistic Norms to Predict Lexical Proficiency and Development in Second-Language Production. *Applied Linguistics*, 40(1), 22–42. https://doi.org/10.1093/applin/amx005
- BNC Consortium. (2007). British national corpus. *Oxford Text Archive Core Collection*.
- Hoffman, P., Lambon Ralph, M.A. & Rogers, T.T. (2013). Semantic diversity: A measure of semantic ambiguity based on variability in the contextual usage of words. *Behav Res* 45, 718–730. https://doi.org/10.3758/s13428-012-0278-x
- Kiss, G. R. (1973). Grammatical word classes: A learning process and its simulation. In *Psychology of learning and motivation* (Vol. 7, pp. 1-41). Academic Press. https://doi.org/10.1016/S0079-7421(08)60064-X
- Landauer, T. K., Foltz, P. W., & Laham, D. (1998). An introduction to latent semantic analysis. *Discourse processes, 25*(2-3), 259-284. https://doi.org/10.1080/01638539809545028
- McDonald, S. A., & Shillcock, R. C. (2001). Rethinking the Word Frequency Effect: The Neglected Role of Distributional Information in Lexical Processing. *Language and Speech*, 44(3), 295-322. https://doi.org/10.1177/00238309010440030101
- Nelson, D. L., McEvoy, C. L., & Schreiber, T. A. (2004). The University of South Florida free association, rhyme, and word fragment norms. *Behavior Research Methods, Instruments, & Computers, 36*(3), 402-407. https://doi.org/10.3758/BF03195588