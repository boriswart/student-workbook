# What is the purpose of Encapsulation?

Encapsulation is one of the fundamental concepts in object-oriented programming (OOP). It describes the idea of bundling data and methods that work on that data within one unit, e.g., a class in Java. This concept is also often used to hide the internal representation, or state, of an object from the outside.


# What were some of the problems with closures and the underscore prefix?

Encapsulation tries to hide internal code representations within the javs script class structure. If there is data that can become public it should be accessed via the class supported methods. Since JS supports encapsulation of data underscore prefixes only serves to communicate the intention of the code designer but does nothing to prevent their access.  


# How do we create private variables in a ES6 Class? Why would you do this?

the proxy: E.G.

const handler = {
  get: function() {
    console.log('A value has been accessed');
  }
}

const initialObj = {
  id: 1,
  name: 'Foo Bar'
}

const proxiedObj = new Proxy(initialObj, handler);

console.log(proxiedObj.name); 

Daily :  vending-machine...

https://github.com/boriswart/vending-machine


