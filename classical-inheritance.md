##Classical Inheritance

~~~
function Person(id){
  this.id = id;
}

Person.prototype.getId = function(){
   return this.id;
}

function Employee(name, id){
   Person.call(this, name);
   this.id = id;
}

Employee.prototype = Object.create(Person.prototype);

Employee.prototype.getId = function(){
  return this.id;
}

var employee = new Employee("name", "123");

employee instanceOf Employee => true
employee instanceOf Person => true
