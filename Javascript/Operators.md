## Conditional (Ternary) Operator (? :)
The ternary operator takes three operands: a condition follow by (`?`), then an expression to execute if the condition is truthy followed by (`:`) and then an expression to execute if the condition is falsy. It is frequently used and alternative to the if...else statement.

Syntax
```
condition ? exp1 : exp2
```

Example:
```
fee  = isMember ? '$2' : '$10'
```

---

## Nullish Coalescing Operator (??)

The nullish coalescing operator returns the first argument if it is not `null/undefined` otherwise it returns the second argument

Syntax
```
arg1 ?? arg2;
```

Example:
The result will equal a if it is defined, otherwise it will equal b
```
result = a ?? b;
```

---