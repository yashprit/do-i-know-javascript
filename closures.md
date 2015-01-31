##Closures

~~~
function foo(){
  this.prefix = 1; 
  return function bar(){
    return this.prefix++;
  }
}

var bar = foo();

bar()
1

bar()
2
~~~
