# Awesome Haskell articles/talks for beginners

A curated list of amazingly awesome Haskell articles and talks for beginners.

If you think a article/talk should be added, please create a new issue.

- [Learning Haskell](https://wiki.haskell.org/Learning_Haskell) - places where you can go if you want to learn Haskell
- [How to learn Haskell](https://github.com/bitemyapp/learnhaskell) - a recommended path for learning Haskell based on experience helping others
- [A list of Haskell articles on good design, good testing](https://williamyaoh.com/posts/2019-11-24-design-and-testing-articles.html)
- [Software Design and Architecture in Haskell](https://github.com/graninas/software-design-in-haskell/) - set of materials on how to build real-world applications in Haskell
- [A Glossary of Functional Programming](http://degoes.net/articles/fp-glossary)
- [The Haskell Cheatsheet](http://cheatsheet.codeslower.com) - references for syntax, concepts and advanced types

## Motivation

- [You are already smart enough to write Haskell](https://williamyaoh.com/posts/2019-10-05-you-are-already-smart-enough.html)
- [State of the Haskell ecosystem](https://github.com/Gabriel439/post-rfc/blob/master/sotu.md) - the current state of the Haskell ecosystem

## Base

- [What I Wish I Knew When Learning Haskell](http://dev.stephendiehl.com/hask)
- [An opinionated guide to Haskell in 2018](https://lexi-lambda.github.io/blog/2018/02/10/an-opinionated-guide-to-haskell-in-2018/) - overview of a few select parts of the Haskell workflow and the ecosystem
- [Typeclassopedia](https://wiki.haskell.org/Typeclassopedia) - a starting point for the student of Haskell wishing to gain a firm grasp of its standard type classes
- :speaker: [Data61 fp-course](https://www.youtube.com/watch?v=NzIZzvbplSM&list=PLly9WMAVMrayYo2c-1E_rIRwBXG_FbLBW) - Functional Programming Course 
- [Functors, Applicatives, And Monads In Pictures](http://adit.io/posts/2013-04-17-functors,_applicatives,_and_monads_in_pictures.html)
- [The wizard monoid](http://www.haskellforall.com/2018/02/the-wizard-monoid.html)
- [Phantom type](https://wiki.haskell.org/Phantom_type)

## Advanced

- [Haskell programming tips](https://wiki.haskell.org/Haskell_programming_tips) - several examples of how code can be improved
- [Haskell Style Guide](https://kowainik.github.io/posts/2019-02-06-style-guide) - a collection of best-practices inspired by commercial and free open source Haskell libraries and applications
- [Demystifying MonadBaseControl](https://lexi-lambda.github.io/blog/2019/09/07/demystifying-monadbasecontrol) - provide a complete survey of MonadBaseControl - how it works, how it’s designed, and how it can go wrong
- [Generalized algebraic data types](https://en.wikibooks.org/wiki/Haskell/GADT) - learn why GADTs are useful and how to declare your own
- [Introduction to Tagless Final](https://serokell.io/blog/tagless-final) - an introduction to tagless final encoding

### Monad Transformers

- [A Gentle Introduction to Monad Transformers](https://two-wrongs.com/a-gentle-introduction-to-monad-transformers)
- :speaker: [Next Level MTL - George Wilson - BFPG 2016-06](https://www.youtube.com/watch?v=GZPup5Iuaqw)
- [The State Monad: A Tutorial for the Confused?](http://brandon.si/code/the-state-monad-a-tutorial-for-the-confused/)
- [State monad comes to help sequential pattern matching](https://kowainik.github.io/posts/2018-11-18-state-pattern-matching) - combine monadic effects of StateT and Either to parse a list of values
- [Effectful Haskell: Reader, Transformers, Typeclasses](https://slpopejoy.github.io/posts/Effectful02.html)

## Design Patterns

- [Haskell Design Patterns: The Handle Pattern](https://jaspervdj.be/posts/2018-03-08-handle-pattern.html)
- [Designing Testable Components](http://felixmulder.com/writing/2019/10/05/Designing-testable-components.html) 
- [Functional architecture is Ports and Adapters](https://blog.ploeh.dk/2016/03/18/functional-architecture-is-ports-and-adapters/) Ports are your IO code and sit at the edge of the system. The core consist of pure functions.
- [The ReaderT Design Pattern](https://www.fpcomplete.com/blog/2017/06/readert-design-pattern) - large-scale application or library application design architecture
- [Three Layer Haskell Cake](https://www.parsonsmatt.org/2018/03/22/three_layer_haskell_cake.html) - application design architecture with roughly three layers
  - [holmusk/three-layer](https://github.com/Holmusk/three-layer) - Architecture of the Haskell web applications 

## Examples

- [kowainik/issue-wanted](https://github.com/kowainik/issue-wanted) - web application follows _Three Layer Cake_ architecture pattern
  - [GSoC 2019 - Building A Web Application with Haskell](https://rashadg1030.github.io/rashad-blog/6.html)
  - [Guide to Implementing Custom Monadic Effects in Issue-Wanted](https://rashadg1030.github.io/rashad-blog/7.html)

## Testing

- [An example of state-based testing in Haskell](https://blog.ploeh.dk/2019/03/11/an-example-of-state-based-testing-in-haskell/) - ... with the State monad
- [Mocking Effects using Constraints and Phantom Data Kinds](https://chrispenner.ca/posts/mock-effects-with-data-kinds) - writing multiple 'interpreters' for your monad stacks using mtl-style constraints

## Libraries

### Servant

- [Servant's type-level domain specific language](https://bradparker.com/content/posts/2019-10-05-servant-types.html)

