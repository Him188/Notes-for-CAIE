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

### File organization
> s20 42 Q8 \[3\]


| Statement                      | Serial | Sequential | Random |
|:-------------------------------|:------:|:----------:|:------:|
| Hashing algorithm              |        |            |   √    |
| No *key* field                 |   √    |            |        |
| Collisions can occur           |        |            |   √    |
| Least efficient for large data |   √    |            |        |
| Most efficient for large data  |        |            |   √    |

Design methods
--------------

### Decision tables

Example questions:

> s20 43 Q7

- All the blocks in the table should be filled with `Y` or `N`.

### Features of JSP diagram
> s20 42 Q4 \[2\]

- Selection: `o`
- Iteration: `*`
- Sequence

### Methods of testing
> w20 43 Q2 \[4\]

| Statement                                                   | Integration | Acceptance | Alpha | Beta |
|:------------------------------------------------------------|:-----------:|:----------:|:-----:|:----:|
| Software is tested in-house by dedicated testers            |      √      |            |   √   |  √   |
| Software is tested by the client before it is signed off    |             |     √      |       |      |
| Software is tested by combining previously working modules  |      √      |            |       |      |
| Software is tested using normal, abnormal and boundary data |      √      |     √      |   √   |  √   |
| Software is tested by releasing it to selected customers    |             |            |       |  √   |


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

- A child class can use methods from the parent class
- A child class can override methods from the parent class


### What is meant by `polymorphism`
> w20 43 Q3 \[2\]

- A child class can override from the parent class

### Why fields are `private`
> w18 43 Q5 \[2\]

- To restrict **direct** access to the property
- To make the program easier to debug
- To ensure data going in is valid

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

## The benefits of using exception handling
> s20 43 Q1 \[2\]

- The program will not crash
- Result does not cause further errors
- Appropriate error message
- Improve readability
- Exceptional conditions are identified
