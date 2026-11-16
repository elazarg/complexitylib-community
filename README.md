# cslib-frontier subset for GameTheory

This branch keeps only the modules of
[cslib-frontier](https://github.com/cslib-community/cslib-frontier) that
[GameTheory](https://github.com/elazarg/GameTheory)'s optional complexity package
imports, with their transitive `CslibFrontier` imports. It builds against released
Lean, Mathlib and CSLib v4.36.0.

Modules keep their upstream paths, namespaces and declarations. Changes beyond
deleting unused modules are limited to what the released dependencies require; see
the commit history.

GameTheory maintains this subset only until the definitions it uses are available
in CSLib itself. It does not track cslib-frontier and is not a general fork: do not
add modules GameTheory does not import.

Licensed under Apache 2.0, as upstream; see `LICENSE` and `NOTICE`.
