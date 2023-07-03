# Higher Structures in Homotopy Type Theory

## Abstract

The definition of algebraic structures on arbitrary types in homotopy type theory (HoTT)
has proven elusive so far. This is due to types being spaces instead of plain sets in
general, and equalities of elements of a type behaving like homotopies. Equational laws of
algebraic structures must therefore be stated coherently. However, in set-based
mathematics, the presentation of this coherence data relies on set-level algebraic
structures such as operads or presheaves which are thus not subject to additional
coherence conditions. Replicating this approach in HoTT leads to a situation of circular
dependency as these structures must be defined coherently from the beginning.

In this thesis, we break this situation of circular dependency by extending type theory
with a universe of cartesian polynomial monads which, crucially, satisfy their laws
definitionally. This extension permits the presentation of types and their higher
structures as opetopic types which are infinite collections of cells whose geometry is
described by opetopes. Opetopes are geometric shapes originally introduced by Baez and
Dolan in order to give a definition of n-categories. The constructors under which our
universe of cartesian polynomial monads is closed allow us to define, in particular, the
Baez-Dolan slice construction on which is based our definition of opetopic type.

Opetopic types then enable us to define coherent higher algebraic structures, among which
infinity-groupoids and (infinity, 1)-categories. Crucially, their higher structure is
univalent in that it coincides with the one induced by their identity types. We then
establish some expected results in order to motivate our definitions.

## Notes

This is a preliminary version of my PhD thesis missing the acknowledgements
