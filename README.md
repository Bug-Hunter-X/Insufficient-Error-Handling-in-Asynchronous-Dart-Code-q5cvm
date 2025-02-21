# Insufficient Error Handling in Asynchronous Dart Code

This repository demonstrates a common error in asynchronous Dart code: insufficient error handling. The `fetchData` function fetches data from a remote API. The `try-catch` block handles exceptions, but the error handling within the `catch` block is minimal. This could lead to unexpected application behavior and make debugging difficult.

The `bug.dart` file shows the buggy code.  The `bugSolution.dart` file offers a more robust solution.

## How to run
1. Clone this repository.
2. Open the project in your preferred Dart IDE.
3. Run `bug.dart` and `bugSolution.dart` to compare the outputs.