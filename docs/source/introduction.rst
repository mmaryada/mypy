Introduction
============

Mypy is a static type checker for Python. If you sprinkle your code
with type annotations, mypy can type check your code and find common bugs.
As mypy is a static analyzer, or a lint-like tool, your code's type
annotations are just hints and don't interfere when running your program.
You run your program with a standard Python interpreter, and the annotations
are treated primarily as comments.

Using the Python 3 function annotation syntax (using the PEP 484 notation) or
a comment-based annotation syntax for Python 2 code, you will be able to
efficiently annotate your code and use mypy to check the code for common
errors. Mypy has a powerful, easy-to-use, type system with modern features
such as type inference, generics, function types, tuple types and
union types.

As a developer, you decide how to use mypy in your workflow. You can always
escape to dynamic typing as mypy's approach to static typing doesn't restrict
what you can do in your programs. Using mypy will make your programs easier to
debug, maintain, and understand.

This documentation provides a short introduction to mypy. It will help you
get started writing statically typed code. Knowledge of Python and a
statically typed object-oriented language, such as Java, are assumed.

.. note::

   Mypy is still experimental. There will be changes
   that break backward compatibility.
