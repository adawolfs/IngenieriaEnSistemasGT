# Exercises

### Browser consoles and the Node.js REPL display values when you enter statements. What values are displayed for the following kinds of statements?

- An expression statement
- A variable declaration
- A block statement with at least one statement inside
- An empty block statement
- A while, do, or for loop whose body is executed at least once
- A loop whose body is never executed
- An if statement
- A try statement that completes normally
- A try statement whose catch clause is executed

### What is wrong with the statement

```
let x = 0
if (x === 0) console.log('zero') else console.log('nonzero')
```
How do you fix the problem?

### Consider a statement
```
let x = a
```
Which tokens could start the next line that prevent a semicolon to be inserted? Which ones can realistically occur in an actual program?

### What are the results of comparing `undefined, null, 0, and ''` values with the operators `< <= ==?` Why?

### Is `a || b` always the same as `a ? a : b`, no matter what type `a` and `b` are? Why or why not? Can you express `a && b` in a similar way?

### Use the three kinds of for loop for finding the largest value in an array of numbers.

### Consider this code snippet:

```
let arr = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12]
for (i in arr) { if (i + 1 === 10) console.log(a[i]) }
```

Why doesn’t it print anything?

### Implement a switch statement that converts digits 0 through 9 to their English names 'zero' through 'nine'. How can you do this easily without a switch? What about the reverse conversion?

### Suppose n is a number between 0 and 7 and you are supposed to set the array elements `arr[k] through arr[k + n - 1]` to zero. Use a switch with fallthrough.


### Consider the problem of finding the first position in which an array b occurs as a subsequence of an array `a`. Write two nested loops:

```
let result = undefined
for (let i = 0; i < a.length - b.length; i++) {
  for (let j = 0; j < b.length; j++) {
    if (a[i + j] != b[j]) . . .
  }
  . . .
}
```

Complete with labeled break and continue statements. Then rewrite without break or continue.