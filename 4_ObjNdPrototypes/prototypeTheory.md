Method	                          Description
Object.create(proto)	  -         Creates an object with a specific prototype.
Object.getPrototypeOf(obj)  -	        Gets the prototype of an object.
Object.setPrototypeOf(obj, proto) -	Sets a new prototype for an object.
obj.hasOwnProperty(prop)	       -   Checks if a property exists on the object (not prototype).


Key Takeaways
✔ Every object in JavaScript has a prototype.
✔ Prototype chain enables property and method inheritance.
✔ Constructor functions use .prototype to share methods.
✔ Object.create() sets up prototypal inheritance.
✔ ES6 class simplifies inheritance with extends and super().
✔ Prefer Object.getPrototypeOf(obj) instead of __proto__.