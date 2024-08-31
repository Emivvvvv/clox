# clox

clox is a bytecode interpreter written in C from the book [Crafting Interpreters](https://craftinginterpreters.com/).

> You can see my rust implementations of the two interpreter from [here](https://github.com/Emivvvvv/rlox)

# clox roadmap

|         Chapter          | Status |
|:------------------------:|:------:|
|    Chunks of Bytecode    |   ✅    |
|    A Virtual Machine     |   ⏳    |
|    Scanning on Demand    |   ⏳    |
|  Compiling Expressions   |   ⏳    |
|     Types of Values      |   ⏳    |
|         Strings          |   ⏳    |
|       Hash Tables        |   ⏳    |
|     Global Variables     |   ⏳    |
|     Local Variables      |   ⏳    |
|  Jumping Back and Forth  |   ⏳    |
|   Calls and Functions    |   ⏳    |
|         Closures         |   ⏳    |
|    Garbage Collection    |   ⏳    |
|  Classes and Instances   |   ⏳    |
| Methods and Initializers |   ⏳    |
|       Superclasses       |   ⏳    |
|       Optimization       |   ⏳    |

# benchmark

```lox
fun fib(n) {
  if (n < 2) return n;
  return fib(n - 1) + fib(n - 2);
}

var before = clock();
print fib(40);
var after = clock();
print after - before;
```

clox:
```shell
STILL ON DEVELOPMENT.
```
rclox:
```shell
STILL ON DEVELOPMENT.
```
