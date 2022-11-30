# facul
function factorial in Java Script

- this is a recursiv function, means it calls itself multiple times

```Javascript
function factorial(n) {
  if(n == 0) {
    return 1;
  }
  return factorial(n - 1) * n;
}
```
