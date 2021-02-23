## Programming paradigms

- Paradigm – Approach to programming

- Based on a set of principles or theory 

- Different Paradigms – Different ways of Thinking

- Idioms – Patterns for using language features

- Types of Paradigms
  - Imperative : How to Solve (Procedural , Object Oriented)
  - Declarative : What to Solve ( Functional , Logic )



## Functional Programming

- based on  Lambda -calculus
- program: function application
- same inputs should produce same output (“pure”)
- function modifies context!side effect
- avoid mutation
- higher-order functions
- Function Closure
- Function Curry
- Monads

> Functional programming is a style of programming that enables you:
> - Re-use code (via function composition)
> - Eliminate bugs (via immutability)

> In Computer Science , functional programming is a programming paradigm , a style of building the structure and elements of computer programs, that  treats computation as the evaluation of mathematical **function**s and **avoids** changing state and **mutable data**. it is a **declarative** programming paradigm , which means programming is done with **expressions**



### Why Functional

---

- Expressiveness allows Programmers to write less code
- Code brevity and readability (Subjective)
- Concurrency and Synchronization
  - Parallelizing programs written with pure functions is trivial, because those functions don’t mutate anything
- Performance



### Multiple Paradigms

---

- functional languages with object-oriented features
  - Ocaml, F#, Scala
- imperative languages with functional features
  - Python, Ruby, C#, Java
- what makes a language functional or imperative?
  - Pure functions
  - higher-order functions
  - immutable data structures
  - recommended idioms in functional style





```
//Imperative Program
function  gcd(x, y){
r = 0
while y > 0:
r = x % y
x = y
y = r
return x
}

//Functional Program
function gcd(x, y){
if y == 0:
return x
else:
return gcd(y, x % y)

}

https://www.slideshare.net/LivePersonDev/functional-programming-with-java-8
https://1lib.in/book/3367330/c6d9c6?dsource=recommend
```

