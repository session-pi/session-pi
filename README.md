# session-pi
A session-typed pi-calculus interpreter

## Setup

1. Install nix:
```
$ run curl -L https://nixos.org/nix/install | sh
```

2. Initialize the nix environment
```
$ nix-shell
```

3. To build/run
```
$ dune exec --display quiet sessionPi
```

4. To run type-checker tests
```
$ dune exec test
```
make sure to run this command in the top-level directory

## Main Paper
- [Subtyping for session types in the pi calculus](https://link.springer.com/article/10.1007/s00236-005-0177-z)

## Resources we may look into:

#### Fundamental
- [Introduction to Session Types](https://www.dcs.gla.ac.uk/research/betty/summerschool2016.behavioural-types.eu/programme/DardhaIntroBST.pdf/at_download/file.pdf?fbclid=IwAR3y7zPu9lMhcSWXWkncGkSnyW5UjzWcBQEmWta0icQ0fvZHQAuvYuRbK-g)
- [Linear Type Theory for Asynchronous Session Types](https://www.cambridge.org/core/journals/journal-of-functional-programming/article/linear-type-theory-for-asynchronous-session-types/605DA26DDDE9B1CCD35D33D0D62DF20C) (we should probably read this; seems very foundational)
- [Foundations of Session Types and Behavioral Contracts](https://dl.acm.org/doi/pdf/10.1145/2873052)
- [Linearity, session types and pi-calculus](https://www.cambridge.org/core/journals/mathematical-structures-in-computer-science/article/linearity-session-types-and-the-pi-calculus/C636B85EFB70566E982277957504396C) 
- [Fundamentals of Session Types](https://www.di.fc.ul.pt/~vv/papers/vasconcelos_fundamental-sessions.pdf)
- [Behavioral Types in Programming Languages](https://ebjohnsen.org/publication/16-ftpl/16-ftpl.pdf)

#### Session Types + Deadlock Freedom
- [Manifest Deadlock-freedom for Shared Session Types](https://dl.acm.org/doi/pdf/10.1145/2873052)
- [Deadlock-Free Session Types in Linear Haskell](https://dl.acm.org/doi/pdf/10.1145/3471874.3472979)
- [A new type system for deadlock-free processes](https://link.springer.com/chapter/10.1007/11817949_16)
- [A Static Verification Framework for Message Passing in Go using Behavioral Types](http://mrg.doc.ic.ac.uk/publications/a-static-verification-framework-for-message-passing-in-go-using-behavioural-types/draft.pdf)
- [Multiparty GV: Functional Multiparty Session Types with Certified Deadlock Freedom (2022!!!!)](https://iris-project.org/pdfs/2022-icfp-multiparty.pdf)
