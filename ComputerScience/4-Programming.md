# Table of contents

- [Algorithms](#algorithms)
  - [Explain how an insertion sort puts a set of data into ascending order](#explain-how-an-insertion-sort-puts-a-set-of-data-into-ascending-order)
  - [Features that a recursive algorithm must include](#features-that-a-recursive-algorithm-must-include)
  - [How stack used during execution of a recursive procedure](#how-stack-used-during-execution-of-a-recursive-procedure)
  - [What is meant by a `null pointer` in a linked list](#what-is-meant-by-a-null-pointer-in-a-linked-list)
- [Abstract Data Types](#abstract-data-types)
  - [`Stack`](#stack)
  - [`Queue`](#queue)
  - [`Binary Tree`](#binary-tree)
  - [`Class`](#class)
  - [`Hash table`](#hash-table)
- [PERT charts](#pert-charts)
  - [What is meant by `critical path` in a PERT chart](#what-is-meant-by-critical-path-in-a-pert-chart)
- [GANTT charts](#gantt-charts)
  - [Describe `GANTT` chart](#describe-gantt-chart)
- [Decision tables](#decision-tables)
  - [Describe the purpose of a decision table](#describe-the-purpose-of-a-decision-table)
  - [Decision tables](#decision-tables)
- [JSP Diagrams](#jsp-diagrams)
  - [Features of JSP diagram](#features-of-jsp-diagram)
- [Testing](#testing)
  - [Methods of testing](#methods-of-testing)
  - [Items that can include in a test plan](#items-that-can-include-in-a-test-plan)
- [Programming](#programming)
  - [Pseudocode hints](#pseudocode-hints)
  - [Python hints](#python-hints)
  - [Read file using Pseudocode](#read-file-using-pseudocode)
  - [File organization](#file-organization)
- [Programming Paradigm](#programming-paradigm)
  - [Define `programming paradigm`](#define-programming-paradigm)
  - [`programming paradigm`s](#programming-paradigms)
  - [What is meant by `imperative programming`](#what-is-meant-by-imperative-programming)
- [Object-oriented Programming](#object-oriented-programming)
  - [What is meant by `containment`](#what-is-meant-by-containment)
  - [What is meant by `inheritance`](#what-is-meant-by-inheritance)
  - [What is meant by `polymorphism`](#what-is-meant-by-polymorphism)
  - [Why fields are `private`](#why-fields-are-private)
- [Exceptions](#exceptions)
  - [What is meant by an `exception`](#what-is-meant-by-an-exception)
  - [Situations where exception handling is required](#situations-where-exception-handling-is-required)
  - [The benefits of using exception handling](#the-benefits-of-using-exception-handling)
  - [Why software may not perform as expected](#why-software-may-not-perform-as-expected)



Algorithms
----------

### Explain how an insertion sort puts a set of data into ascending order
> w20 43 Q5 \[4\]

- Uses a sorted *and* unsorted list
- Takes first value and makes it sorted list
- Takes next value and compare with previous one,
- ... to find location of next value in the sorted list
- Insert it into correct position in sorted list
- Repeat until all items are in the sorted list

### Features that a recursive algorithm must include
> s20 43 Q2 \[2\]

- General case
- Base case
- It calls itself

### How stack used during execution of a recursive procedure
> s15 43 Q6.b

- Before procedure call is executed current state of the registers/local variables is saved onto the stack
- When returning from a procedure call the registers/local variables are re-instated

### What is meant by a `null pointer` in a linked list
> w20 42 Q6 \[1\]

- End of list.

Abstract Data Types
-------------------
> w20 42 Q5 \[4\]

### `Stack`
- Linear structure.
- LIFO.
- Uses push to add items to top of stack.
- Uses pop to remove items from t op of stack.

### `Queue`
- Linear structure.
- FIFO.
- Can be circular.
- Uses enqueue to add item to end of queue.
- Uses dequeue to add item to end of queue.

### `Binary Tree`

- Parent node is above, and child nodes follow.
- Each node can have up to two children.
- Has a root node.
- Can have leaf nodes.
- Can be ordered or unordered.
- *Examples of ordering*

### `Class`
- A class represents an object.
- Objects are instances of classes.
- Has attributes and methods.
- Classes can be inherited.

### `Hash table`
- Key calculated from value.
- Key represents a location.
- *Description of managing collisions*

PERT charts
-----------

### What is meant by `critical path` in a PERT chart
> w19 43 Q1 \[1\]

- The shortest time to complete the project.

GANTT charts
------------

### Describe `GANTT` chart
> w19 43 Q1 \[2\]

- A table that has time across the top and activities on the left,
  boxes are coloured to show dependencies and find critical path.


Decision tables
---------------

### Describe the purpose of a decision table
> w19 43 Q1 \[2\]

- Way of modelling logic.
- Show all possible outputs
- ... based on the inputs.
- Determine which action to take in specific condition.

### Decision tables

Example questions:

> s20 43 Q7

- All the blocks in the table should be filled with `Y` or `N`.

JSP Diagrams
------------

### Features of JSP diagram
> s20 42 Q4 \[2\]

- Selection: `o`
- Iteration: `*`
- Sequence


Testing
-------


### Methods of testing
> w20 43 Q2 \[4\]

| Statement                                                   | Integration | Acceptance | Alpha | Beta |
|:------------------------------------------------------------|:-----------:|:----------:|:-----:|:----:|
| Software is tested in-house by dedicated testers            |      √      |            |   √   |  √   |
| Software is tested by the client before it is signed off    |             |     √      |       |      |
| Software is tested by combining previously working modules  |      √      |            |       |      |
| Software is tested using normal, abnormal and boundary data |      √      |     √      |   √   |  √   |
| Software is tested by releasing it to selected customers    |             |            |       |  √   |

### Items that can include in a test plan
> w20 42 Q4 \[2\]

- Example test data
- Test number
- Type of test
- Test description
- Expected outcome

Programming
-----------

### Pseudocode hints
- Call procedure: `CALL ProcedureName()`
- Index starts from 0
- Declare array typed `STRING` of size 100: `DECLARE Name : ARRAY[0:99] OF STRING`
- Assignment is `<-`
- Substring: `MID(str, index, length)`

### Python hints
- Remainder operator: `%`
- Devision to int: `//`
- Random int: `random.randint(min, max)` (inclusive)

### Read file using Pseudocode
> w18 43 Q2 \[8\]

```
Filename <- "myBooks.dat"
OPENFILE Filename FOR RANDOM
RecordLocation <- Hash(ISBN)
SEEK FileName, RecordLocation
GETRECORD FileName, BookInfo
CLOSEFILE FileName
```

### File organization
> s20 42 Q8 \[3\]

| Statement                      | Serial | Sequential | Random |
|:-------------------------------|:------:|:----------:|:------:|
| Hashing algorithm              |        |            |   √    |
| No *key* field                 |   √    |            |        |
| Collisions can occur           |        |            |   √    |
| Least efficient for large data |   √    |            |        |
| Most efficient for large data  |        |            |   √    |

Programming Paradigm
--------------------

### Define `programming paradigm`
> w18 43 Q1 \[1\]

- A programming style

### `programming paradigm`s
> w18 43 Q1 \[2\]
>
> Given object-oriented and tell two others.

- Procedural
- Low-level
- Object-oriented

### What is meant by `imperative programming`
> w20 42 Q4 \[2\]

- Writing program as a sequence of steps
- ... to get a result.
- Statements in program manipulates the data.
- Example is procedural programming.

Object-oriented Programming
---------------------------

### What is meant by `containment`
> w20 43 Q3 \[2\]  
> s20 42 Q6 \[3\]

- ***A class contains objects of another classes**
- *an example from the question*
- **Aggregation**
- ...: the contained object can exist outside its super class.
- **Composition**
- ...: object is declared and exists within its super class


### What is meant by `inheritance`
> w20 43 Q3 \[2\]  
> w20 42 Q4 \[2\]

- A child class can **use** methods from the parent class
- *XX class inherits from the class XX*


### What is meant by `polymorphism`
> w20 43 Q3 \[2\]  
> w20 42 Q4 \[2\]

- A child class can override from the parent class
- *Function XX in XX class is overridden with function XX in class XX*

### Why fields are `private`
> w18 43 Q5 \[2\]  
> w20 42 Q4 \[2\]

- Limits access to given methods only.
- Use of set method allows for validation
- ... and ensures attribute is valid.
- Ensure encapsulation.

Exceptions
----------

### What is meant by an `exception`
> s20 43 Q1 \[1\]

- An unwanted event


### Situations where exception handling is required
> s20 43 Q1 \[3\]

- Division by zero
- Invalid array index
- Runtime error
- Invalid input
- Hardware error
- Stack overflow
- Memory leakage

### The benefits of using exception handling
> s20 43 Q1 \[2\]

- The program will not crash
- Result does not cause further errors
- Appropriate error message
- Improve readability
- Exceptional conditions are identified

### Why software may not perform as expected
> w19 43 Q3 \[3\]

- Logic error
- Error in design
- Runtime error
- Not adequately tested

