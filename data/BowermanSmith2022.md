# Details: Bowerman & Smith (2022)

## Summary

From [Bowerman & Smith (2022)](https://escholarship.org/content/qt3x3398ct/qt3x3398ct.pdf): "Semantic extension plays a key role in language change and grammaticalisation. 
Here we use a dyadic interaction paradigm to study semantic extension of novel labels in controlled circumstances. 
We ask whether participants will be able to (i) use highly accessible associations in the perceptual environment (colour-shape associations) to converge on a meaning for the novel labels, and (ii) extend these meanings to apply to both concrete targets (objects) and abstract targets (emotions)."

In the subset of the data we're looking at, we'll only consider objects, not emotions.

In the fixed associations condition, participants saw a shape always appear as the same colour (e.g., hexagons were always red, squares always grey, etc.)
This common ground might be a foundation for further semantic extension.
In contrast, in the random associations condition, every shape had a randomly generated colour in every trial, so no common ground based on colour was available.


## Variables

- `pair_id`: The pair of experimental participants who created this data.
- `condition`: Experimental condition (`fixed`, for fixed association, or `random`, for random association).
- `block_n`: The block of the experiment that the data comes from (2 or 3).
- `object`: The target object for participants to choose.
- `object_selected`: The object that participants actually selected.
- `score`: 0 if the participants' chosen object was incorrect, 1 if their chosen object was correct.
- `rt`: How long it took participants to select an object in milliseconds.


## Dimensions

- Rows: 6848
- Columns: 7


## Source

<https://github.com/kennysmithed/SemanticExtension>

