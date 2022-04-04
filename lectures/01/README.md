# What is computation?

- ## What does a computation do?

  - Perform calculations.
  - Store data in memory.

- ## Types of knoweledge

  - Declative kowledge: statement of fact.
  - Imperative knowledge: "how to".

- ## What is a simple a receipe/algorithm?

  - Steps.
  - Flow of control.
  - Stop case.

- ## Types of computers?

  - Fixed computers: it can only do one thing.
  - Stored program computers: it can store and execute a sequence of instructions.

- ## Basic computer architecture

  - Memory
  - ALU
  - I/O
  - CONTROL UNIT

- ## You can program a computer using the following 6 primitives shown by Turing

  1. move right
  2. move left
  3. read
  4. write
  5. scan
  6. do nothing

  Using those 6 instructions, programming languages come about to be
  . In theory, a computer program wrtitten in one high level programming language can be translated to another programming language.

- ## Aspects of a programming languages

  - Syntax: both syntactically and semantically correct.
  - Semantics: instructions only have one meaning and it not be on what you wanted hence debbuging.

- ## Types of errors

  - Syntax errors: most common errors and easily caught.
  - Static semantic errors: some languages check for static errors i.e Go, Java, C++, etc. Can cause unpredictable behaviour.

  - Non-static errors
    - program crashes, stop running.
    - program run forever.
    - get an output but different from expected.

- ## Programming in Python

  In Python, everything is an object. Programs manipulate data objects. Objects have a type that defines the kinds of things programs can do to them. Objects are scalar (cannot be subdivided) or non-scalar (have internal structure that can be accessed).

- ### Scalar objects in Python

  - int: represent integers, ex. 5.
  - float: represent real numbers, ex. 3.27
  - bool: represent Boolean values True and False
  - NoneType: special and has one value, None
  - can use type() to see the type of an object

```py
print(type(5))  # int
print(type(3.0)) # float
```

- ### Type conversion

  Can convert object of one type to another. float(3) converts integer 3 to float 3.0; int(3.9) truncates float 3.9 to integer 3.

- ### Expressions

  Combine objects and operators to form expressions. An expression has a value, which has a type.

  - Syntax for a simple expression
    - \<object> \<operator> \<object>

- ### OPERATORS ON ints and floats

  - i+j : the sum.
  - i-j : the difference.
  - i\*j : the product.
  - i/j : division, if both are ints, result is int ; if either or both are floats, result is float.
  - i%j : the remainder when i is divided by j.
  - i\*\*j: i to the power of j.

- ### ABSTRACTING EXPRESSIONS

  Reuse names instead of values

  ```py
    pi = 3.14159265
    radius = 2.2
    area = pi * (radius * * 2)
    print(area) # 15.205308426000004
  ```
