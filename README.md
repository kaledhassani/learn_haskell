# Just a project to learn Haskell in

## References

http://learnyouahaskell.com/introduction

## Setup

Download core platform from: https://www.haskell.org/platform/ (210MB)

## Running Code

## Interactive Mode

> ghci

If you've defined some functions in a file you can load them by

> :l functions.hs

## Definitions

Infix function - a function that's sandwiched by two numbers such as + - or *

Prefix function - where the function name precedes the argument/s

## Functions

* You can use ' in a function name, it has no special meaning in Haskell

* Spaces are used for function application, not necessarily parenthesis, e.g bar( bar 3), here bar is first applied to 3 then bar is applied to the result of that

* Function names can't begin with upper case letters

* When a function doesn't take a parameter, it's called a definition

### In-Built
succ - takes something with predefined value and returns next one
min / max - as stated

## Shortcuts

If a prefix function takes two parameters, we can call it as an infix function by backticking it e.g 92 `div` 10

## Conditionals

If statements must include an else, if statements are an expression because they always return a value, you could take the expression and pass it or use it in another expression

## Lists

Lists in Haskell are homogenous, that is they contain the same type in each element

In ghci you can set a list using the let keyword e.g let lostNumbers = [4,8,15,16,23,42]
In a .hs file, define it without the let keyword
To print the list, just use the name, e.g lostNumbers

Strings are lists of characters, because of this we can use list functions on strings

Put two lists together by using ++, do it with numbers or strings, do it on lists !

++ gets dangerous for humungous lists, but adding to start of list using : (cons) is fast, e.g 'A':" Small Cat"

Get an element out of a list using its index using !!, e.g "Steve Buscemi" !! 6 return 'B' or [9,10,11] !! 1 returns 10

Lists can contain lists that can contain lists ! BUT they must be of the same type

## Notes
