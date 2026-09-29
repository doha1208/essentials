# Running the Demo

## Prerequisites
- Git (to clone this repository)
- JDK 17 or later, with `java` and `javac` on your PATH
- Python 3.9 or later

## Command
From the repository root, run:

```text
python3 run.py demo
```

On Windows, use `py -3 run.py demo` if that is how you run Python 3.

## What the demo does
The demo compiles the Java library application into a temporary directory and runs a short scripted scenario on a fixed date. It prints the student and faculty borrowing limits, searches the catalog for a title, borrows a book for a member, shows the due date on the loan receipt, returns the book with its overdue fee, and prints the number of active loans afterward.
