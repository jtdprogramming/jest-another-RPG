# jest-another-RPG

constructor example:
```
// Car() constructor - do NOT use arrow functions as they change how 'this' works**
function Car(make, model) {
  this.make = make;
  this.model = model;
}

// invoke Car() constructor by calling with 'new' keyword. Pass in values for make & model like a regular function
new Car('Honda', 'Civic');
```