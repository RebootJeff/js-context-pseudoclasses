This is ROUGH draft

# Pseudoclasses


# Context & Keyword "THIS"

**Extra Credit:** Write a function called `curry` that accepts a function as input and outputs a curried version of the function.
```JavaScript
function sum2(a, b) {
  return a + b;
}

function sum3(a, b, c) {
  return a + b + c;
}

var curriedSum2 = curry(sum2);
curriedSum2(4)(6) // result is 10

var curriedSum3 = curry(sum3);
curriedSum3(4)(6)(12) // result is 22
```

*Hint:* Use `Function.length` and maybe `call`, `apply`, or `bind`.
