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

A prebuilt version of the documentation is available in the repository.

# Versioning

Cryptocode supports LaTeX' rollback mechanism. To load a particular version of cryptocode use

    \usepackage[options]{cryptocode}[=2018-11-11]

Besides the current version 0.43, the following deprecated versions are available via
the rollback mechanism.

- v0.32 (2020-04-24)
- v0.30 (2018-11-11)

# Contribution

Contributions to *cryptocode* are very welcome. 

# Attribution

If you use cryptocode in your work, consider starring the repository on GitHub and/or rating it on CTAN.

# License

[LaTeX Project Public License](http://www.latex-project.org/lppl.txt)

