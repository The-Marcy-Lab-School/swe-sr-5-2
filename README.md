# Technical Writing Assignment

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/fullstack-curriculum/how-tos/working-with-assignments#how-to-work-on-assignments).

## Prompt 1

Write a short lesson to explain and demonstrate the concept of inheritance. In your response, include the following:
- What is inheritance? Use the terms "subclass" and "superclass" somewhere in your definition.
- Provide a code snippet that:
  - Has two classes where one is the superclass and one is the subclass.
  - Creates an instance of the subclass and references a property or invokes a method of the superclass.

### Response 1

## Prompt 2

In JavaScript, the prototype chain is the underlying concept that enables inheritance. Understanding how it works is crucial for writing efficient and maintainable code, especially when working with object-oriented programming (OOP). Read this MDN article on [Object Prototypes](https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Advanced_JavaScript_objects/Object_prototypes) and provide the following in your own words:

- Provide a mental model or analogy that helps explain what a prototype is.
- What is the Prototype Chain, and when does it stop?
- Is it necessary to know how the prototype chain works in order to implement inheritance? Why or why not?

### Response 2

## Prompt 3

In JavaScript, methods can be defined as instance methods or static methods. Understanding the difference between these two types of methods is crucial for writing effective object-oriented code.

Use the following code snippet and identify the instance methods and static methods. Then, explain how we might decide to make a particular method an instance method or a static method.

```js
const gonzalo = new Person(36, "gonzalo")
const ben = new Person(29, "ben")
Person.getPeople();   // prints [ Person { name: "gonzalo", age: 36 }, Person { name: "ben", age: 29 } ]
gonzalo.speak();      // prints "hello my name is gonzalo"
gonzalo.sleep();      // prints "good night"
ben.birthday();       // prints "I'm turning 30!"
Person.totalPeople(); // prints 2
```

### Response 3

## Prompt 4

In the article on [Object Prototypes](https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Advanced_JavaScript_objects/Object_prototypes), it goes over the topic of shadowing. Explain what shadowing is and then explain the similarities and differences between shadowing and polymorphism in JavaScript.

### Response 4

## Prompt 5

In OOP, there are different types of relationships. Compare and contrast "is-a" and "has-many / belongs-to" relationships. Give an example of each.

### Response 5
