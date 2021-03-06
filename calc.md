
# How to follow and explain in three?

Often an explanation divided into three parts feels inuitively easy to grasp. After all we all have some sort of idea of a beginning, a middle and an end, or left, right and center. But there is so much more! The number three reminds us of a triangle which consists of three points. One point by itself signifies something which is difficult to identify in time and space, it is something very basic, we can only be aware of a point but what we notice is that it is difficult to know about the point since we cannot relate the point to anything in the universe except the universe itself. If we imagine seeing just two points we can immediatelly feel a dimension where we understand some notion of betweeness, an interval, thus giving some meaning to this relation, witnessing its direction, measuring its distance, or like in music, where hearing the distance between two tones we call an interval. In math, we could draw a line through these two points and then calculate the segment. My point is that effective explanations often have a tree like structure where branching spreads in three ways and then each branch again repeats the same process. It feels like zooming into a single branch and again seeing three branches which in turn again if we zoom in we witness another three branches. This could be compared to buiding a house where three floors have three rooms and each room has three floors where each floor has three rooms and so on.. 

Notice the structure of explaining the workings of a calculator (by [Bartosz Milewski in his School of Haskell](https://www.schoolofhaskell.com/school/starting-with-haskell/basics-of-haskell/4-symbolic-calculator-recursion):

At the very high level, the calculator is a loop that gets a line of text from the user and then calculates and displays the result.
  
* The calculation is done in three steps:
  * **Lexical analysis**: The string is converted to tokens
  * **Parsing**: Building an expression tree
  * **Evaluation**: The expression is evaluated

We are immediatelly following a style of thinking. Which style would that be? At its essence it seems simple because we are defining largest reasonable building blocks our program solves, and yet we are not concerned with the technicalities of how the program should be implemented. This might resemble a top-down approach which consists of splitting the whole problem into two or more parts, in our case three (lexing, parsing, evaluating) with a general higher 3-level description of the calculating process of what this program actually does (getting a line from the user, calculating and then displaying the result). Notice the symmetry between and how the right side further describes the process. Also compare the idea of lexing with reading, parsing with understanding and evaluating with expressing one self by saying something in return.:

* Get input from the user - **Lexical analysis**
  * Lexical analysis, lexing or tokenization is the process of converting a sequence of characters into a sequence of tokens with an assigned and thus identified meaning. The lexer basically segments the input into syntactic units, or distinct words, and then gives meanings to tokens. This might be understood as simply reading a sentence.
  
```
tokenize :: String -> [Token]
tokenize = undefined

--tokenize is a function taking a string and returning a list of tokens
```

* Calculate the input - **Parsing**
  * Parsing is a process  of analyzing a string of symbols, conforming to the rules of some formal grammar. This might be understood as simply understanding a sentence after and while we are reading it, for example understanding subjects and predicates and so on. 

```
parse :: [Token] -> Expression
parse = undefined

--the parsing function takes a list of tokens and returns an expression
```
* Display the output - **Evaluation**
  * Evaluation is returning an output, making some form of judgement, finding a value of an expression, or intuitively based on what we read and understand. 
  
 ```
 evaluate :: Expression -> Double
 evaluate = undefined
 
 -- evaluate takes an expression and returns a double (a type or a number)
  ```

Writing a Haskell programs seems like exploring an infinite structure of trees where a well defined root explanation gives birth to a family of sub explanation and where each of the sub nodes gives birth to a new family of child nodes which in turn become a parent to yet another family of child nodes all the way until the problem at hand solves itself. Instead of just solving something we first try to explain it with well defined sentences which give meaning to our problem and motivate us and guide us in returning more well defined sentences or definitions. The best part or payoff is that one composes these definitions in chains from the most general one to the most tiny one after which we begin to implement the solution. The wonderful thing about Haskell is that the explanations themselves are expressed as code. I keep thinking of the famous Lisp idea of code is data and data is code and while technically speaking I am probably wrong in comparing this to Haskell, explanation as code and code as an explanation seems very nice and liberating to me. After all what is data and what is code?
