# Multiple Mutable References in Rust
This repository demonstrates a common error in Rust: creating multiple mutable references to the same variable.  Rust's strict borrowing rules prevent this to ensure memory safety.  This example shows the error and how to solve it using different approaches.

## Bug
The `bug.rs` file contains code that attempts to create two mutable references to the same variable. This results in a compile-time error or undefined behavior at runtime.

## Solution
The `bugSolution.rs` file provides a corrected version of the code, demonstrating techniques to avoid multiple mutable references.

## How to Run
1. Clone this repository.
2. Navigate to the repository directory.
3. Compile and run the files using `rustc bug.rs && ./bug` and `rustc bugSolution.rs && ./bugSolution` respectively. Observe the differences in their outputs and behavior.