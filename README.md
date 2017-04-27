# knowledge-database
This is a repo to define the problem I would like to attempt to solve. The License is explicitly left blank,
until I figure out what I want to with this problem.

## Problem Statement
Reading academic papers is hard. Authors do not have the time to provide all the backup materials that readers need to
understand their paper. Authors have differing writing styles. The quality of academic papers can usually be improved
by submitting them to a journal, and having them peer reviewed, but this also can suffer from politics. Academic
papers are extremely important to human knowledge, and I believe everyone should be able to read them.

Therefore, I would like to define academic papers themselves as a set of *attributes* and *references*, into a format that
can be easily indexable, searchable for people to read them and start using academic papers more often. I will
begin by focusing on mathematics related papers (maths, physics, computer science, etc.) and then this can maybe be expanded
to different fields of knowledge.

## Defintions

### Academic Paper
A maths paper usually has the following core structure:
- Definitions
- Axioms
- Sub proofs
- Proof
- References

The proof is the meat of the paper, but the definitions, axioms, sub proofs are the way we as peers can easily verify
if the proof is in fact correct, given our knowledge of logic.

One of the main issues with papers, is that authors can not possibly fill in all the axioms and definitions in the paper itself,
so authors often reference other papers and expect readers to have an understanding of those first. Ideally, this database
should present users with **all** the required background knowledge to be able to verify the proof.

The ingester could read a paper, determine the other axioms it is referencing, then cement them together with this paper.

### Definition
A definition is usually a statement that has the following structure as well:
- Name
- may have an Alias / Symbol
- Meaning
- may Reference and Restrict another Definition

For example, the following statements can be Definitions.

- The natural numbers &#8469; are the set of positive integers (&#8484;+), excluding zero.
- The set of positive integers (&#8484;+) are the set of integers, excluding all negative numbers.
- The set of integers (&#8484;) is a number without a fractional component.

### Axiom
TODO

### Sub Proof
TODO

### Proof
TODO

### Reference
TODO
