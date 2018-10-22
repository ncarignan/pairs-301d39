# 301d39 Random Pair Generator

This application was forked from [John Cokos' Version](https://codesandbox.io/s/6ym681kr43)

- Base Features
  - Randomly select from an array of names to generate a single student names
  - Randomly select from an array of names to generate a list of pairs
- Features Added
  - Store a history of pairings in state and local storage
  - Store a history of single picked students in state and local storage
  - prevent repeats until all students have been picked the same amount of times
  - prevent students from being paired with each other more than once until all other students have been paired together
  - allow for weighting students so they get picked more often
  