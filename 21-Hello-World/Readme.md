# Hello World

This folder will document everything necessary to create a simple console-based program in Purescript. It will explain:
- The philosophical foundations of FP programming
- The Prelude library (including Functor, Apply, Applicative, Bind, and Monad explanations)
- A simple "Hello World" program and other Effects
- Custom Compiler Warnings/Errors
- The difference between Local Mutable State vs Global Mutable State
- How to test code
- How to benchmark / profile code
- How to structure an FP application
- An overview of various type-level programming libraries
- A few console-based games written in Purescript (putting it all together)

In pursuing these goals, it will overview the following libraries:
- Basic
    - Prelude
    - Prim.TypeError
- Effects
    - Effect
    - Console
    - Random
    - Aff
- State
    - ST
    - Refs
- Testing
    - Spec
    - Quick Check
    - Quick Check Laws
- Benchmarking
    - Benchotron
- Advanced
    - Variant/VariantF
    - MTL
    - Free
    - Run
- UIs
    - Node ReadLine
    - Halogen

## Helpful Links

- [Pursuit - Docs for Purescript packages](http://pursuit.purescript.org/)


## Other Learning Resources

Besides this repo, we have a few choices in terms of understanding functional programming. These are not necessarily "either X or Y or Z" choices but could be "X supplemented by Y with a little bit of Z")

### Purescript

- The `Purescript By Example` book. (See `ROOT_FOLDER/Getting Started/Other Important Info.md` for links and clarifications around it)
- [Purescript Resources](https://purescript-resources.readthedocs.io/en/latest/index.html) - Justin Woo's Read the Docs (RTD) work

### Haskell

Since Purescript is heavily inspired by and very similar to Haskell, one can learn a lot about Purescript by learning from these Haskell learning resources. Note: the Haskell names and type classes do not always correspond to the Purescript versions.

| Action | Pros | Cons |
| --- | --- | --- |
| Read the documentation and source code for a type class and a few data types' implementations of said type classes | Free | Takes a lot of time; requires intuition to understand type class' usefulness / relation to others.
| Read the relevant chapters from [Learn You a Haskell for Great Good](http://learnyouahaskell.com/chapters) | Free | I read elsewhere that it's "outdated"
| Read through some of the free course materials taught by someone well informed about Haskell [here (you'll need to scroll towards the bottom)](https://github.com/bitemyapp/learnhaskell) | Free; more principled explanations | Looking at just slides without hearing someone teach using them is not usually as clear as when someone does teach using them or reading through a textbook on the same matter.
| Read through the extremely lengthy ["What I wish I knew when learning Haskell"](http://dev.stephendiehl.com/hask/) site | Free; provides a better overview of basic to advanced topics | Very long; not necessarily deep and clear in its explanations
| Read and do the exercises from [The Haskell Book](http://haskellbook.com/) | The "standard" for teaching Haskell and FP concepts in general: good explanations; good exercises; teaches "programming in the small" | Costs money; costs time; the exercises will stretch you
| Read and do the exercises from [Haskell Cookbook](https://leanpub.com/haskellcookbook), and then its follow up book [Haskell Cookbook 2](https://leanpub.com/haskellcookbook2) | Free/Cheap; simpler than the Haskell book; gets to ideas faster; teaches "programming in the large" | May be harder for a new beginner (I haven't read it yet)
| Watch the Intro to FP course on edX.org [here](https://www.edx.org/course/introduction-functional-programming-delftx-fp101x-0) | Free (or paid) | (Haven't done it so I don't know)

### Miscellaneous Links

- [LambdaConf YouTube Channel](https://www.youtube.com/channel/UCEtohQeDqMSebi2yvLMUItg)
