---
layout: reference
permalink: /reference/
root: ..
---

## Glossary

{:auto_ids}
additive color model
:   A way to represent colors as the sum of contributions from primary colors
    such as [red, green, and blue](#rgb).

argument
:   A value given to a function or program when it runs.
    The term is often used interchangeably (and inconsistently) with [parameter](#parameter).

assertion
:   An expression which is supposed to be true at a particular point in a program.
    Programmers typically put assertions in their code to check for errors;
    if the assertion fails (i.e., if the expression evaluates as false),
    the program halts and produces an error message.
    See also: [invariant](#invariant), [precondition](#precondition),
    [postcondition](#postcondition).

assign
:   To give a value a name by associating a variable with it.

body
:   (of a function): the statements that are executed when a function runs.

call stack
:   A data structure inside a running program that keeps track of active function calls.

case-insensitive
:   Treating text as if upper and lower case characters of the same letter were the same.
    See also: [case-sensitive](#case-sensitive).

case-sensitive
:   Treating text as if upper and lower case characters of the same letter are different.
    See also: [case-insensitive](#case-insensitive).

comment
:   A remark in a program that is intended to help human readers understand what is going on,
    but is ignored by the computer.
    Comments in Python, R, and the Unix shell start with a `#` character and
    run to the end of the line;
    comments in SQL start with `--`,
    and other languages have other conventions.

compose
:   To apply one function to the result of another, such as `f(g(x))`.

conditional statement
:   A statement in a program that might or might not be executed
    depending on whether a test is true or false.

comma-separated values
:   (CSV) A common textual representation for tables
    in which the values in each row are separated by commas.

default value
:   A value to use for a [parameter](#parameter) if nothing is specified explicitly.

defensive programming
:   The practice of writing programs that check their own operation
    to catch errors as early as possible.

delimiter
:   A character or characters used to separate individual values,
    such as the commas between columns in a [CSV](#comma-separated-values) file.

docstring
:   Short for "documentation string",
    this refers to textual documentation embedded in Python programs.
    Unlike comments, docstrings are preserved in the running program
    and can be examined in interactive sessions.

documentation
:   Human-language text written to explain what software does,
    how it works, or how to use it.

dotted notation
:   A two-part notation used in many programming languages
    in which `thing.component` refers to the `component` belonging to `thing`.

empty string
:   A character string containing no characters,
    often thought of as the "zero" of text.

encapsulation
:   The practice of hiding something's implementation details
    so that the rest of a program can worry about *what* it does
    rather than *how* it does it.

floating-point number
:   A number containing a fractional part and an exponent.
    See also: [integer](#integer).

for loop
:   A loop that is executed once for each value in some kind of set, list, or range.
    See also: [while loop](#while-loop).
