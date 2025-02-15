# Objective-C NSDateFormatter Parsing Issue

This repository demonstrates a potential issue in Objective-C related to the `NSDateFormatter` class and its handling of date string parsing.  Incorrect date formats can result in unexpected behavior, silent failures, or crashes, making debugging a challenge.

The `bug.m` file contains code that reproduces the issue.  The `bugSolution.m` file provides a more robust solution that handles potential parsing errors gracefully.

## How to Reproduce

1. Clone this repository.
2. Open the project in Xcode.
3. Build and run the project.
4. Observe the console output for unexpected results or crashes.

## Solution

The solution involves using more robust error handling and checking the result of the `dateFromString:` method.  The improved code handles possible parsing errors effectively.