# Unhandled IllegalArgumentException in Scala

This repository demonstrates a common error in Scala: failing to handle exceptions properly within a class.  The `MyClass` attempts to prevent negative ages, but if a negative age is passed, the exception is unhandled and causes the program to crash.

The solution demonstrates how to use `try-catch` to gracefully handle the exception.