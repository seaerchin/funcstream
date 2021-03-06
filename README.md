# Functional programming with Haskell

This is an exploration of a beautiful programming language Haskell and functional programming.
I am learning from several books and documenting the learning here.
Sources used are

### Books
  * [A type of programming](https://atypeofprogramming.com/)
  * [Learn you a Haskell for Greater Good](http://learnyouahaskell.com/)
  * Richard Bird: Thinking Functionally with Haskell
  * Graham Hutton: Programming in Haskell
  * Simon Thompson: Haskell - The Craft of Functional Programming
  * Allen/Moronuki: Haskell From First Principles
  * Will Kurt: Get Programming with Haskell
  * Hudak/Quick: The Haskell School of Music
  * David S. Touretzky: Common Lisp: A Gentle Introduction to Symbolic Computation 
  * Alejandro Serrano Mena: Practical Haskell - A Real World Guide to Programming
  * [Phil Freeman: Purescript by example](https://leanpub.com/purescript)
  * [Discrete Mathematics using a computer](http://www.x.edu.uy/inet/Springer.pdf)


### Online courses
  * [Bartosz Milewski Super Awesome Category Theory Lectures!](https://www.youtube.com/user/DrBartosz/playlists)
  * [Functional programming in Haskell: Supercharge your coding](https://www.futurelearn.com/courses/functional-programming-haskell)
  * [Bartosz Milewski - School of Haskell](https://www.schoolofhaskell.com/user/bartosz)
  * [Functional programming in Haskell](https://www.youtube.com/playlist?list=PLJ5C_6qdAvBFJP1RiUrUUJI4GEhnJhgQw)
  * [C9 Lectures: Dr. Erik Meijer - Functional Programming Fundamentals](https://youtu.be/UIUlFQH4Cvo)

### Talks

  * [Why is Haskell so Hard to Learn and How to Deal With It](https://youtu.be/RvRVn8jXoNY)
  * [Stop Treading Water: Learning to Learn](https://youtu.be/j0XmixCsWjs)
  * [Why algebraic data types are important - Bartosz Milewski ](https://youtu.be/LkqTLJK2API)
  * [PureScript: Tomorrow's JavaScript Today](https://youtu.be/5AtyWgQ3vv0)
  * [LambdaConf 2015 - Learn Functional Programming with PureScript John A De Goes](https://youtu.be/LqYfdmb0eUU)
  * [Adventures with Types - SPJ](https://youtu.be/6COvD8oynmI)
  
### Papers
 * [Ralf Hinze collection of papers](https://www.cs.ox.ac.uk/people/ralf.hinze/publications/index.html)
 * [Graham Hutton: Universality and expressiveness of fold](http://www.cs.nott.ac.uk/~pszgmh/fold.pdf) 
 * [Eugenio Moggi: Notions of computation and monads](https://person.dibris.unige.it/moggi-eugenio/ftp/ic91.pdf)
 * [Raul Rojas: A Tutorial Introduction to the Lambda Calculus](https://arxiv.org/pdf/1503.09060.pdf)
 * [Why calculating is better than scheming](https://www.cs.kent.ac.uk/people/staff/dat/miranda/wadler87.pdf)

### Other:

* [Steve Yegge - Execution in The Kingdom of Nouns](http://steve-yegge.blogspot.com/2006/03/execution-in-kingdom-of-nouns.html)
> Hello, world! Today we're going to hear the story of Evil King Java and his quest for worldwide verb stamp-outage.
Caution: This story does not have a happy ending. It is neither a story for the faint of heart nor for the critical of mouth. If you're easily offended, or prone to being a disagreeable knave in blog comments, please stop reading now.
* [Monday Morning Haskell](https://mmhaskell.com/)
> At Monday Morning Haskell, we have tutorials for all levels of programmers! If you're new to Haskell, take a look at our Beginners series. If you have some experience with the language already, we've got some more Advanced material so you can get started on real world projects! Either way, come back every Monday morning for some new material on the Blog!
* [Why are partial functions (as in `head`, `tail`) bad?](https://www.reddit.com/r/haskell/comments/5n51u3/why_are_partial_functions_as_in_head_tail_bad/?utm_source=share&utm_medium=web2x)
>The problem with partial functions is that they're liars. Consider head: its type is [a] -> a, which means "give me a list of as and I'll give you an a". So I give it [] - does it give me an a? No, it doesn't, it throws an exception instead.
And when functions start lying about the things they return, you can no longer reason about them.
 * [Applied Haskell Syllabus](https://tech.fpcomplete.com/haskell/syllabus)
 > Applied Haskell is a commercial training program focusing on teaching intermediate Haskell. The goal is to help someone move from knowing Haskell basics to being able to write commercial software, with enough knowledge to pick up any new skills needed on demand.
 * [Haskell Learn - FPComplete](https://tech.fpcomplete.com/haskell/learn)
 * [An introduction to recursion schemes](https://blog.sumtypeofway.com/posts/introduction-to-recursion-schemes.html)
> Because nested structures appear in almost every problem domain and programming environment, from databases to 3D graphics to filesystems, the act of iterating through these structures is common, so common that most programmers barely notice when they’re doing it. As such, generalizing the act of recursive traversals provides immediate real-world benefits: our new generalized traversal can replace a host of type-specific traversal functions. In addition, by decoupling how a function recurses over data from what the function actually does, we reduce cognitive overhead and can focus entirely on the core behavior of our recursive functions. 
 * [The Road to Proficient Haskell](https://williamyaoh.com/posts/2020-01-11-road-to-proficient.html)
 * [Getting started with Haskell](https://stackoverflow.com/questions/1012573/getting-started-with-haskell/1016986#1016986)
 * [You Could Have Invented Monads](http://blog.sigfpe.com/2006/08/you-could-have-invented-monads-and.html)
 > In fact, I hope to get you to invent them now if you haven't already. It's then a small step to notice that all of these solutions are in fact the same solution in disguise. And after reading this, you might be in a better position to understand other documents on monads because you'll recognise everything you see as something you've already invented.
 * [How To Do Basic Error Handling Logging](https://williamyaoh.com/posts/2019-10-12-how-to-basic-error-handling-logging.html)
 * [Basic Haskell: An Examination of a Todo List](https://www.benlopatin.com/basic-haskell-todo/)
 * [Standardized ladder of functional programming](https://pbs.twimg.com/media/CydL5EYUsAAI-61.jpg:large)
 * [Sum Types](https://www.schoolofhaskell.com/school/to-infinity-and-beyond/pick-of-the-week/sum-types)
 * [How Laziness works](https://two-wrongs.com/how-laziness-works)
 > What I'm about to describe is completely useless to learn how to write Haskell, but if you're like me and like poking at things under the hood, by all means join in.
 * [Space Leak Zoo](http://blog.ezyang.com/2011/05/space-leak-zoo/)
 > There are a few different types of space leak here, but they are quite different and a visitor would do well not to confuse them (the methods for handling them if encountered in the wild vary, and using the wrong technique could exacerbate the situation).
 * [Money in the type system where it belongs](https://ren.zone/articles/safe-money)
 > Notwithstanding the value civilization gives to a particular currency, the amount of said currency one owns can't spontaneously increase nor decrease in number. As programmers, we do play a crucial role in ensuring amounts of currency are never made up nor lost. In this article we will explore how we can leverage types, functional programming, and in particular the safe-money Haskell library to ensure that our software deals with monetary values and world currencies as carefully as civilization requires. Mostly, we will be exploring the type system and learning how to reason through types.
 * [Embedding Linear Lambda Calculus, Quickly and Easily](https://blog.functorial.com/posts/2017-08-05-Embedding-Linear-Lambda-Calculus.html)
  > Suppose you want to create an embedded DSL based on the linear lambda calculus. Why might you want to do this? Well, you might want to control access to some resource, or perhaps you've heard that linear types can change the world and now you'd like to compile your EDSL to some target language and optimize things using mutable data structures.
 * [Imperative Haskell](https://vaibhavsagar.com/blog/2017/05/29/imperative-haskell/)
  > I was working through Tim Roughgarden’s Algorithms 1 (which has now been replaced by two smaller courses) and attempting to do all the exercises in Haskell when I bumped up against an uncomfortable truth. 
 * [An Opiniated Guide to Haskell in 2018](https://lexi-lambda.github.io/blog/2018/02/10/an-opinionated-guide-to-haskell-in-2018/)
 > In the meantime, in the interest of both sharing with others the small amount of wisdom I’ve gained and preserving it for my future self, I’ve decided to write a long, rather dry overview of a few select parts of the Haskell workflow I developed and the ecosystem I settled into. 
 * [Functor-Oriented Programming](http://r6.ca/blog/20171010T001746Z.html)
 > My style of Haskell programming has been evolving over the 15 years that I have been working with it. It is turning into something that I would like to call “functor oriented programming”. The traditional use of typed functional programming focuses on data types. One defines data types to model the data structures that your program operates on, and one writes functions to transform between these structures. One of the primary goals in this traditional methodology is to create data structures that exclude erroneous states to the extent that is reasonably possible. As long as one ensures that pattern matching is complete, then the type system catches many errors that would otherwise lead to these erroneous states, which have been crafted to be unrepresentable. Functor oriented programming is a refinement of this traditional focus on data types. 

### Haskell Code

 * [Lambda launcher](https://github.com/balsoft/lambda-launcher)
 * [Input Output](https://github.com/input-output-hk)
 * [Input Output/Plutus](https://github.com/input-output-hk/plutus)
 * [Awesome Haskell List](https://github.com/krispo/awesome-haskell)
 * 
### Inspirational (poems etc..)

* [Wallace Stevens - Thea idea of order at Key West](https://www.poetryfoundation.org/poems/43431/the-idea-of-order-at-key-west)
>  The sea was not a mask. No more was she.   
The song and water were not medleyed sound   
Even if what she sang was what she heard,   
Since what she sang was uttered word by word.
It may be that in all her phrases stirred   
The grinding water and the gasping wind;   
But it was she and not the sea we heard.

