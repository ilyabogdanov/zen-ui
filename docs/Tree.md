# [Zen UI](../README.md) &#x25B8; Tree

Adds tree, which is multifunctional component.
Main purpose is to display hierarchical tabular data.
In combination with links, buttons and other controls,
can create complex navigational component.
Consists of the following components:

* `Tree` is root element, which is responsible for basic properties,
such as first column alignment and column divider.
* `TreeBranch` and `TreeBranchlet` contain each other to create hierarchy.
Each branch is a container for any number of sibling branchlets, and
each branchlet may contain a branch of children.
* `TreeLeaf` and `TreeLeafColumn` which basically are just
[Horizontal Layout](HorizontalLayout.md). All content takes place inside leaf columns.

#### First Column Alignment

With each sub-level, the first column shifts to the right.
In some cases tree looks better without such shift.
FCA feature aligns first column at all levels
