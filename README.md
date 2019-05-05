# MLPolyR

This is a ML dialect with first-class cases (first-class pattern matching) and row-polymorphism
that solves the expression problem directly with language features.

## Build

Install SML/NJ, tested with v110.75 and v110.87 on Linux (make sure it has ML-lex)
and build with this command:

```
make
```

and that's it.

## Usage

a PDF manual is in `doc/`.

There are also a [language spec][spec], a [paper][fc-c] and a [PhD thesis][tse] about MLPolyR.

 [spec]: https://people.cs.uchicago.edu/~blume/classes/spr2005/cmsc22620/docs/langspec.pdf
 [tse]: https://arxiv.org/abs/0910.2654
 [fc-c]: https://people.cs.uchicago.edu/~blume/papers/icfp06.pdf