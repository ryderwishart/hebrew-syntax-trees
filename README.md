# BHSA Hebrew Syntax Trees

XML trees generated from the BHSA data via TextFabric

## Elements

These tree have `wg` (word group) and `w` (word) elements. I have tried to pull the relevant features from the BHSA trees (documented [here](https://etcbc.github.io/bhsa/)) for every given element.

The `canonical/` trees should have all of the text in canonical order (I haven't confirmed this).

The `nested/` trees reorder children with an `@mother` attribute to reside beneath the element with the ID corresponding to the `@mother` value. (In other words, every "child" goes with its "mother".)

There is a stylesheet in this repo (`treedown.css`), but it is very rough and simple to help give you a general idea of the syntactic structure.

## TODO

- Improve the stylesheet
