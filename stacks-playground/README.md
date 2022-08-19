# Stacks

From Data Structures and Algorithms in Swift, raywenderlich.com
Chapter 4 - Stacks

## Notes:

A stack's purpose is to limit the number of ways to access your data. Its structure is identical to a physical stack of objects (visualize a stack of pancakes). 

A stack has two essential operations: Add an element to the top of a stack (push) and remove the top element fo the stack (pop). This is known as LIFO (last-in-first-out).


## Things I learned:

* Element is a defined placeholder for structures. It is a type representing the sequence's elements.

* Swift provides a default debugging textual representation for any type.  String(reflecting: ) works on instances of any type. Adding CustomDebugStringConvertible conformance to custom types will allow Strin(reflecting: ) to return an instance's implemented debugDescription property value. [Apple Docs](https://developer.apple.com/documentation/swift/customdebugstringconvertible/)
