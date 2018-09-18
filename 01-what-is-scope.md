# What is scope?



###Question:
Check your understanding so far. Make sure to play the part of Engine and have a “conversation” with Scope:

```
function foo(a) {    
    var b = a;    
    return a + b; 
}

var c = foo( 2 ); 
```

1. Identify all the LHS look-ups (there are 3!). 
2. Identify all the RHS look-ups (there are 4!).

### Answer:

1. 'c = ', 'b = ', 'a = '
2. '= foo(2)', '= a', '= 2', 'a + b'