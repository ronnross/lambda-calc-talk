# Basic The Lambda Calculus

Is a model of computation devised by Alonzo Church in the 1930s.

Why? Basis for all functional programming. The lambda calculus is implemented in nearly every language, such as, Java and JavaScript. Base model for evaluations and equivalent to turing machine. Numbers and bool logic within lambda calc

*Some language incorporate features into the language that aren't translatable into lambda expression. Haskell is a pure functional langauge, because it does not*

*pure can also mean referential transparency or given the same input set/domain you always return the same outputs/codomain*

## Simple rules
Everything is an expression.
Four different forms of expressions

- ID (variable) `ex. a`
- Abstraction `ex. ID.E | λa.a`
- Application `ex. E E | λa.a 1`

I think there should be four
- Disambiguation `ex. (λa.a) 1`

## Concrete
```js
x           // variable name
x => x      // Abstration / anonymous function
(x => x)(1) // Application is 1 applied to the function of is the function applied to 1??
```

A lambda term
`λa.a+1`
It consist of a head `λa` and a body `a+1`.
A variable named in the head is the parameter and binds to instances of that var in the body. `a` is said to be bound. Body always returns.

`a` is not semantically meaningful except in its role in that this single expression.


## Practice
We attempt to reduce/evaluated all expressions. This is called Beta Reduction.


