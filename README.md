# Hippomenes Tree

This is a pure Veryl implementation of an arbitration tree intended for the [Hippomenes](https://github.com/perlindgren/hippomenes) NCLIC interrupt controller.

The tree takes an array of signals, and returns the *index* of the smallest/largest value. If only the actual underlying value is of interest,
one could remove the index tracking, slightly improving the design, however, for our use case this is out of scope.

The original SystemVerilog implementation is available [here](https://github.com/onsdagens/hippomenes-tree).
