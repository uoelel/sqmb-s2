# Details: Grafmiller (2023)

## Summary

From [Grafmiller (2023)](https://dataverse.no/dataset.xhtml?persistentId=doi:10.18710/R7HM8J): "The dataset includes an annotated dataset of N = 5098 tokens of English s-genitive (e.g. "the children's voices") and of-genitive (e.g. "the voices of the children") constructions extracted from 5 components an of the Brown and Frown corpora of published written American English. The Brown corpus was compiled in the early 1960s, and the parallel Frown corpus in the early 1990s. The tokens are annotated for 18 syntactic, semantic, phonological, and contextual features."

(We are only using a subset of these annotations.)


## Variables

- `Token`: ID of this observation from the corpora.
- `Corpus`: The corpus that this observation comes from (`Brown` or `Frown`).
- `Time`: The time period that the observation comes from (`1960` or `1990`).
- `Text`: ID of the text that the observation came from.
- `Genre`: Genre of the text (`Press`, `Non-fiction`, `Learned`, `General Fiction`, or `Adventure Fiction`).
- `Type`: The type of genitive used in this obseration (`s` or `of`).
- `Whole_Genitive`: The full genitive NP.
- `Possessor`: The possessor in the NP (i.e., the entity who is doing the possessing).
- `Possessum`: The possessum in the NP (i.e., the entity that is possessed)
- `Possessor_Length`: The number of words in the possessor.
- `Possessum_Length`: The number of words in the possessum.


## Dimensions

- Rows: 3677
- Columns: 11


## Source

<https://dataverse.no/dataset.xhtml?persistentId=doi:10.18710/R7HM8J>

