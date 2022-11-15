# Errata
There are a few errors in the axioms of the publication.

For convenience, we use manchester syntax instead of the description logic glpyhs.

The following axioms are malformed scoped domain axioms. For a node-edge-node construct in a schema diagram (`A R B`), the axiom that would state that the domain of `R`, when scoped by `B` is `A`, should read as: `R some B SubclassOf: A`.

* Axiom 14 should read: `mapsOnto some Concept SubclassOf: MappingRelation`
* Axiom 20 should read: `definedAs some Definition SubclassOf: Concept`
* Axiom 22 should read: `describedAs some Description SubclassOf: Concept`