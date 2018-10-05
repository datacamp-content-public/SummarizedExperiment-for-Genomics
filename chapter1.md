---
title: 'Template Chapter 1'
description: 'This is a template chapter.'
---

## Anatomy of SummarizedExperiment

```yaml
type: NormalExercise
key: c909bf2ad2
lang: r
xp: 100
skills: 1
```

SummarizedExperiment is a container of
- rowData, which contain features e.g. genes, exons, transcripts
- colData, which contain sample descriptions
- assays, which contain one or more assays
- metadata, which contain project information
In this exercise, you are given a SummarizedExperiment 

`@instructions`
- Instruction 1
- Instruction 2
- Instruction 3

`@hint`
- Here is the hint for this setup problem. 
- It should get students 50% of the way to the correct answer.
- So don't provide the answer, but don't just reiterate the instructions.
- Typically one hint per instruction is a sensible amount.

`@pre_exercise_code`
```{r}
# Load the SummarizedExperiment package
library(SummarizedExperiment)
# Load the airway data
data(airway, package="airway")
```

`@sample_code`
```{r}
# 
```

`@solution`
```{r}
# Answer goes here
# Make sure to match the comments with your sample code
# to help students see the differences from solution
# to given.
```

`@sct`
```{r}
# Update this to something more informative.
success_msg("Some praise! Then reinforce a learning objective from the exercise.")
```
