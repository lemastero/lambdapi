## [A Tutorial Implementation of a Dependently Typed Lambda Calculus](http://www.andres-loeh.de/LambdaPi/)
by Andres Löh, Conor McBride and Wouter Swierstra

### Simply Typed Lambda Calculus
[Chapter 2](https://www.andres-loeh.de/LambdaPi/LambdaPi.pdf#page=2)
```
cabal configure
cabal build
./dist/build/st/st
:load prelude.st
```

### Dependently Typed Lambda Calculus
[Chaptera 3-5](https://www.andres-loeh.de/LambdaPi/LambdaPi.pdf#page=12)
```
cabal configure
cabal build
./dist/build/lp/lp

:load prelude.lp
```

### Links
Haskell System FC
* [The Glasgow Haskell Compiler](https://www.aosabook.org/en/ghc.html), by Simon Marlow, Simon Peyton-Jones
* [Type Theory Behind the Glasgow Haskell Compiler Internals](https://www.youtube.com/watch?v=oRTlbblqxWU&list=PL7DZ7q3nEWhyyC0_uA2fhXyLJGpCAcd9P&index=1), by Vitaly Bragilevsky (Lambda Calculus, STLC)
* Adventure with Types in Haskell - Simon Peyton Jones (Lecture 3), by Simon Peyton-Jones [video](https://www.youtube.com/watch?v=2IZQx7WNOMs),[slides](https://www.cs.uoregon.edu/research/summerschool/summer13/lectures/FC_in_GHC_July13.pdf)

* [Barendregt’s Lambda Cube](https://ncatlab.org/nlab/show/pure+type+system#lambda_cube)
[Introduction to generalized type systems](http://patryshev.com/books/barendregt.pdf), Henk Barendregt, 1991
* [System F omega in Haskell](https://gist.github.com/phadej/f491dfc7fe2d3e0a2f040915f7310fb0) by Oleg Grenrus
* [calculus of constructions](https://ncatlab.org/nlab/show/calculus+of+constructions) (most advanced type system used in Coq)
* [Cubical Type Theory in Agda](https://my-agda.readthedocs.io/en/latest/language/cubical.html)
