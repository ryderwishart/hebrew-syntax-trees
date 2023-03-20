# BHSA Hebrew Syntax Trees

XML trees generated from the BHSA data via TextFabric

## Elements

These tree have `wg` (word group) and `w` (word) elements. I have tried to pull the relevant features from the BHSA trees (documented [here](https://etcbc.github.io/bhsa/)) for every given element.

This arrangement should be in canonical order.

There is a stylesheet in this repo (`treedown.css`), but it is very rough and simple to help give you a general idea of the syntactic structure.

## TODO

- Improve the stylesheet
- Compare with reordered (non-canonical) trees, where `@Rela` attributes are used to move children beneath the ID in their `@mother` attribute.
