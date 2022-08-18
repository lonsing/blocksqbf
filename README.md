# BlocksQBF

BlocksQBF is a generator for random quantified boolean formulae (QBF)
in QDIMACS format [1]. In essence, it is an implementation of the
model described in [2].

To compile the generator, unpack the sources and run `make`. Call
`./blocksqbf -h` for usage information and an example. BlocksQBF
writes the generated formula to `stdout`, where it prepends its
configuration used for generating the formula as QDIMACS comments.

## Resources:

- Paper published at [SAT 2010](https://iew.technion.ac.il/~ofers/SAT10/): [Automated Testing and Debugging of SAT and QBF Solvers](http://www.florianlonsing.com/papers/BrummayerLonsingBiere-SAT10.pdf)

- Talk presented at [SAT 2010](https://iew.technion.ac.il/~ofers/SAT10/): [http://fmv.jku.at/brummayer/talks/Brummayer-SAT10-talk.pdf](http://fmv.jku.at/brummayer/talks/Brummayer-SAT10-talk.pdf)

## References:

1. [QDIMACS Standard](http://www.qbflib.org/qdimacs.html)

2. [Hubie Chen, Yannet Interian: A Model for Generating Random
    Quantified Boolean Formulas. IJCAI 2005: 66-71](https://www.ijcai.org/Proceedings/05/Papers/0633.pdf)
