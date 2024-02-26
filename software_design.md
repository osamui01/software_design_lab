###What do we mean by coupling and cohesion when discussing structured design?

Coupling and cohesion are 2 concepts used to evaulate the quality of software design. Coupling focuses on the relationships and interactions between modules, cohesion focuses on the internal unity and organization within a module.

###What is the difference between top-down and bottom-up design? 

Top-down design starts from a broad view, breaking down into smaller components. Bottom-up design starts with individual components, assembling into a larger system. Function-oriented design emphasizes breaking down tasks into functions. Bottom-up aligns more with object-oriented, while top-down aligns with structured programming.

###Which best describes a function oriented design?

A design system where each function is organzied to handle a different task within an application. The benefits include better code reusability and modularity.

###In which design methodology would a class diagram be most useful?

UML class diagrams are used to visualize the structure of a system by using class. Class diagrams are most useful in OOP. 

###What are the four pillars of object oriented programming? 


The four pillars of object-oriented programming are:

**Encapsulation:** Bundling of data and methods that operate on the data into a single unit, often called a class, while hiding the internal implementation details from the outside world.

**Inheritance:** Mechanism by which a class can inherit properties and behavior from another class, promoting code reuse and establishing a hierarchy of classes.

**Polymorphism:** Ability for objects of different classes to be treated as objects of a common superclass, allowing methods to behave differently based on the object's type or class.

**Abstraction:** Process of simplifying complex systems by focusing on essential characteristics while hiding unnecessary details, achieved through abstract classes or interfaces.

###What is the strategy pattern? How would its implementation differ between a functional and object oriented system?

The strategy pattern is a behavioral software design pattern that enables selecting an algorithm at runtime. Instead of implementing a single algorithm directly, code receives run-time instructions as to which in a family of algorithms to use.

In a functional system, the strategy pattern uses functions to represent different algorithms, chosen at runtime using instructions.

In an object-oriented system, the strategy pattern uses classes to represent algorithms, allowing them to be swapped at runtime based on instructions.

###Imagine your is creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.

OOP - so class system can be utilised in design and production. This would allow better process mapping and code maintenance as the features would be clearly deisgned. Moreover, some function orientated design would prove helpful.