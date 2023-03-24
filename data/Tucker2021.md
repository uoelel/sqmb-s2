# Details: Tucker (2021)

## Summary

From [Tucker et al. (2019)](https://link.springer.com/article/10.3758/s13428-018-1056-1): "The Massive Auditory Lexical Decision (MALD) database is an end-to-end, freely available auditory and production data set for speech and psycholinguistic research, providing time-aligned stimulus recordings for 26,793 words and 9592 pseudowords, and response data for 227,179 auditory lexical decisions from 231 unique monolingual English listeners."

(We are using subset of this dataset.)


## Variables

- `Subject`: ID of the experimental participant.
- `Item`: The item participants judge the lexical status of.
- `IsWord`: `TRUE` if the target is an English word, `FALSE` if it is a non-English word (i.e., a pseudoword).
- `RT`: Reaction time in milliseconds of the lexical judgement.
- `Duration`: Duration in milliseconds of the item's audio recording.
- `NumPhones`: Number of phones in the item.


## Dimensions

- Rows: 20,000
- Columns: 6


## Source

<https://era.library.ualberta.ca/items/3344343b-2b4a-4b8c-af8e-8bd829c76472>

