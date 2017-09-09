# Fully-functional Scheme interpreter written in Haskell programming language
I'm interested in designing some interesting applications in different programming
languages (such as JavaScript, Java, Go, C#).

This project embodies my curiosity to Haskell programming language. Haskell is
different from any other programming languages. And it requires thinking differently.

I'm going to design and build an awesome compiler for C language.

## Prerequisites:
To get this build and run you should install Haskell programming language and
prepare GHC compiler.

You can also use any other Haskell compilers (such as Hugs), but this program
was not tested with this compilers and it can lead to some side-effects and bugs.
Use it at your own risk.

## Getting started:
Clone the repository:

`git clone https://github.com/technoboom/haskell-scheme-interpreter`.

## Build the project:
Use cabal-install and sandboxes:

`cabal sandbox init`

`cabal install -j`

## Run the project:

`.cabal-sandbox/bin/haskell-scheme-interpreter`

## Generate haddock documentation:
`cabal haddock`

## Install additional package:
`cabal install [package name]`

## Project structure:
- src/Main.hs - the main haskell source file
- haskell-scheme-interpreter.cabal - the cabal build description
- Setup.hs
- cabal.sandbox.config (only with Sandbox)
- ChangeLog.md - change log
- README - info
- LICENSE - license

## Stack:
- Haskell programming language
- Compiler: GHC
- Build system: Cabal
- Haddok for generating documentation from annotated Haskell source code
- Testing: HSpec (spec testing), HUnit (unit testing)
- Distribution: Hackage
- Lint: HLint package

## Libraries:
- Parsec

## Resources:
- Lisp documentation: http://lisp-lang.org/
- Scheme Language Standard: http://www.schemers.org/Documents/Standards/R5RS/HTML/
- Haskell documentation: https://www.haskell.org/documentation
- Cabal User Guide: http://www.haskell.org/cabal/users-guide/
- Haddok Doc: http://haskell.org/haddock/
- HSpec: http://hspec.github.io/
- HUnit: http://hackage.haskell.org/package/HUnit
- Hackage: http://hackage.haskell.org/packages/hackage.html
- Parsec: https://wiki.haskell.org/Parsec
