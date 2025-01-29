# Technical Writing Assignment

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/fullstack-curriculum/how-tos/working-with-assignments#how-to-work-on-assignments).

## Prompt 1

Say you were to create a short lesson to explain and demonstrate the concept of inheritance. In your response provide the following:

* What is inheritance?
* What is a parent and child class?
* Provide a code snippet that:
  * Has two classes where one is the parent class and one is the child class.
  * Create an instance of the child class and reference/invoke a property/method of the parent class.

### Response 1

## Prompt 2

In JavaScript, the prototype chain is the underlying concept that enables inheritance. Understanding how it works is crucial for writing efficient and maintainable code, especially when working with object-oriented programming (OOP). Read this [article](https://developer.mozilla.org/en-US/docs/Learn_web_development/Extensions/Advanced_JavaScript_objects/Object_prototypes) and in your own words provide the following:

* Describe a mental model of what a prototype is.
* What is the Prototype Chain, and when does it stop?
* Do you think we need to know how the prototype chain works in order to implement inheritance? Why?

### Response 2

## Prompt 3

In JavaScript, methods can be defined as instance methods or static methods. Understanding the difference between these two types of methods is crucial for writing effective object-oriented code.

Use the following code snippet and identify the instance methods or static methods. Then, explain how we might decide to make a particular method an instance method or a static method.

```js
class Person {
  // implementation details are hidden
}

const gonzalo = new Person(36, "gonzalo")

gonzalo.speak()

gonzalo.sleep()

gonzalo.birthday()

Person.getPeople()

Person.totalPeople()

Person.listMethods()
```

### Response 3

## Prompt 4

In the same article from before, it goes over the topic of shadowing. Explain what shadowing is and then the similarities and differences between shadowing and polymorphism in JavaScript.

### Response 4

## Prompt 5

In OOP, there are different types of relationships. Compare "is-a" and the "has-many belongs-to" relationships and give an example of each.

### Response 5
