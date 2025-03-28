# writing-an-interpreter-in-go
my little interpreter project
# Monkey Interpreter in Go 

Hey there! 👋  This repo is my journey through Thorsten Ball's excellent "Writing an Interpreter in Go" book.  I'm building the Monkey programming language, step-by-step, following along with the book's examples and exercises.

## What's Monkey?

Monkey is a simple, dynamically typed programming language. It's designed to be easy to implement, making it a great project for learning about interpreters and language design.

## Goals

*   Successfully implement the Monkey interpreter as described in the book.
*   Gain a deeper understanding of interpreters, lexers, parsers, and ASTs.
*   Improve my Go programming skills.
*   Make it into my own language

## Current Status

I'm currently working through making the parser.  Check the commit history to see my progress!  I'm trying to commit regularly with meaningful messages.

## How to Run It

Now that the lexer is done, you can acess the REPL through running main.go with go run main.go

## Example Monkey Code

```monkey
let add = fn(x, y) {
    x + y;
};

add(5, 5); // Output: 10
```

Contributing

This is primarily a personal learning project, so I'm not actively seeking contributions right now. However, if you spot any glaring errors or have suggestions, feel free to open an issue! I appreciate any feedback.
The Book

This project is based on:

    "Writing an Interpreter in Go" by Thorsten Ball

You can find the book here: https://interpreterbook.com/
