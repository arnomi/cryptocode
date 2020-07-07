# Cryptocode
The cryptocode package provides a set of macros to ease the typesetting of pseudocode, algorithms and protocols. In addition it comes with a wide range of tools to typeset cryptographic papers. This includes simple predefined commands for concepts such as a security parameter or advantage terms but also flexible and powerful environments to layout game-based proofs or black-box reductions.

# Installation

Extract the *cryptocode.sty* file via

    pdflatex cryptocode.ins

# Documentation

Create the documentation via

    pdflatex cryptocode.dtx
    pdflatex cryptocode.dtx
    makeindex -s gind.ist -o cryptocode.idx cryptocode
    makeindex -s gglo.ist -o cryptocode.gls cryptocode.glo
    pdflatex cryptocode.dtx

# Contribution

Contributions to *cryptocode* are very welcome. 