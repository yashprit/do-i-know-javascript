#What is the difference between `null` and `undefined` in JavaScript?

The `undefined` value is a primitive value used when a variable has not been assigned a value.

The `null` value is a primitive value that represents the null, empty, or non-existent reference.

###undefined
undefined means a variable has been declared but has not yet been assigned a value
```
var myVariable;
console.log(myVariable); // undefined
console.log(typeof myVariable); //undefined
```

###null
null is an assignment value. It can be assigned to a variable as a representation of no value:

```
var myVariable = null;
console.log(myVariable); //null
console.log(typeof myVariable); //object
```
