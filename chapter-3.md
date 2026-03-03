# Chapter 3 Exercises

### 3.1 Suppose I show you a call stack like this. What information can you give me, just based on this call stack?
`Greet is called, call greet2, that will run first, greet2 will be completed and greet will be completed after greet2`
### 3.2 Suppose you accidentally write a recursive function that runs forever. As you saw, your computer allocates memory on the stack for each function call. What happens to the stack when your recursive function runs forever?
`It will throw out of bounds error`