# Q1 Coupling and cohesion in structured design

**Coupling and cohesion** are very important principles in strucuted design. 
## 1. Cohesion
- Cohesion refers to how closely the responsibilities and functionality within a module or component are related to each other. 
    - Basically, how closely the functions within a module are related to each other. 

***Higher cohesion is better and means that the functions are tightly focused on a single, well defined task.***

## 2. Coupling 

- Coupling relates to the interdependence between modules.
    - Basically, it measures how closely one module is connected to or relies on another. 

***Lower coupling is better and indicates that modules are relatively independent, reducing the impact of changes in one module on others.*** 



# Q2 Top-down and Bottom-up design and which best describes functin oriented design?

## Top-down 
>Top-down starts with a high-level view of a system. It breaks it down into smaller components.
- you start with a high-level view of the system or software and then break it down into smaller, more detailed components or modules.
- You begin with defining the overall structure, architecture, or main components of the system.
- This approach is often associated with designing the system from the user's perspective and understanding the main functionalities it should offer.
- ***It is a more abstract and conceptual approach, focusing on the "big picture" first.***
## Bottom-up
>Bottom-up design starts with individual components and asssembles them into a complete system. 
- In bottom-up design, you start with individual components or modules and gradually build them up to create the complete system.
- You begin with the implementation of small, self-contained units and gradually combine them to form more complex structures.
- This approach is often used when you have pre-existing components, libraries, or modules that need to be integrated into a larger system.
- ***It is a more detailed and specific approach, focusing on individual building blocks.***

## What approach best describes functional design? *Neither!*

>Function-oriented design is a specific approach that can be used in both top-down or bottom-up design methodologies.

The choice between these approaches depends on the specific needs of the project.

Function-oriented design is often used in structured programming, where you break down the system into functions or subroutines, defining their purpose and interfaces. 

So, looking at the project from a top-down or bottom-up is not specific to functional programming. 

# Q3 Which design methodology would benefit most from a class diagram?

>As object-oriented programming is the coding paradigm which focuses on the use of classes/objects it is clear that the design methodology that would benefit the most is **object-oriented design.**

Class diagrams are used to help in defining classes, their attributes, and their methods, as well as showing how classes are related to one another through associations, inheritance, and other relationships.

**In contrast,** *function-oriented design* and *structured design *typically focus on breaking down a system into functions or modules and specifying how they interact with each other. 

***These design approaches do not emphasize the use of classes and objects, which are central to object-oriented design.***


# Q4 What are the four pillars of object oriented programming?

## Encapsulation

It is the concept of bundling data (attributes) and methods (functions) that operate on that data into a single unit, or "object," and restricting access to certain parts of the object to control its behavior (i.e. using a the private keyword with getters and setters).

## Abstraction

Abstraction involves simplifying complex systems by modeling classes based on real-world entities, emphasizing the essential characteristics while hiding unnecessary details.

## Inheritance

Inheritance allows a class (a blueprint for an object) to inherit properties and behaviors from another class, facilitating code reuse and the creation of specialized classes based on existing ones.

## Polymorphism

Polymorphism enables objects of different classes to be treated as objects of a common base class, allowing for method overriding and providing flexibility in how different objects can respond to the same method call.

# Q5 What is a stratagy pattern? How would its implementation differ between a functional and object oriented system?

***The Strategy Pattern is a design pattern in software engineering that falls under the category of behavioral patterns.***

It's used to define a family of algorithms, encapsulate each one of them, and make them **interchangeable.** 
This allows you to select an algorithm at runtime, without altering the client code that uses the algorithm.

- Using an online shoping cart example.
    - **With using objected-oriented design** there would be seperate classes for different payment methods. All of the classes would share a common interface. The interface would then determine how to pay. The shopping care can then use any of the different payment methods by switching when needed.

    - **With using functional design** the payment methods would be implemented as functions. Switching between them would be done by passing the appropriate functino to the checkout function. 



# Q6 What design methodology to create a payment system and why?

***All three methods mentioned could be used to create this payment system but I personally would use the Object-oriented design methodology as opposed to the other two.*** 
## The reasons why:

1. The use of object-oriented design would allow the compartmentalisation of complex problems that would be found in the payment processor business. Breaking the program into smaller solvable objects would help in the making of the program.
2. Using object-oriented design would facillitate future feature expansion allowing for the addition of newer payment types.
3. Object-oriented design encourages modularity and the creation of reusable components which promotes maintainability and will help the adaptation or integratino of various parts into a larger system in the future. 
4. Familiarity with the approach. Object-oriented design is a well known and widely used methodology that would not restrict development on the payment processor as opposed to say, structured design.