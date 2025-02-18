# ARC Memory Management Issue in Objective-C
This repository demonstrates a common error related to memory management in Objective-C when using Automatic Reference Counting (ARC).

The problem involves the premature deallocation of a custom class instance because it's not properly retained.

## How to Reproduce
1. Clone this repository.
2. Open the project in Xcode.
3. Run the application. Observe the crash.

## Solution
The solution involves explicitly retaining the `MyObject` instance, preventing premature deallocation. See `MyObjectSolution.m` for the correction. 