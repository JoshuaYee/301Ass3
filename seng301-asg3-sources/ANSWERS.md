# SENG301 Assignment 1 (2020) - student answers


## Task 1 - Identify the patterns

### Pattern 1 -  Abstract Factory Pattern
Abstract Factory Pattern

- What pattern is it?  Abstract Factory Pattern
- What is its goal in the code? As shown in my UML Class diagram, the Abstract Factory Pattern
is used when preparing an order. preparingOrder.java uses the information provided by user to
choose what factory and egg type to use and produce, without the need of a specific egg or factory classes needing to be specified

- Name of UML Class diagram attached: '301 Ass3 Abstract Factory UML.pdf'
- Mapping to GoF pattern elements:

| GoF element           | Code element          |
|-----------------------|-----------------------|
|           AbstractCreator            |             ChocolateEggFactory.java          |
|           ConcreteCreator           |             StuffedEggFactory.java          |
|           ConcreteCreator           |             HollowEggFactory.java          |
|           AbstractProduct            |             ChocolateEgg.java          |
|           ConcreteProduct           |             StuffedChocolateEgg.java          |
|           ConcreteProduct           |             HollowChocolateEgg.java          |
|           FactoryMethod           |             createChocolateEgg(ChocolateType, boolean)          |

### Pattern 2 -  Command Pattern
Command Pattern

- What pattern is it? Command pattern
- What is its goal in the code?
App.java creates a counter object, which recieves order information and passes the order through 
to the Chocolatier.java. The Chocolatier then is able to create/execute the order using the methods
from PreparingOrder.java
- Name of UML Class diagram attached: '301 Ass3 Command UML.pdf'
- Mapping to GoF pattern elements:

| GoF element           | Code element          |
|-----------------------|-----------------------|
|          ConcreteCommand             |           Counter.java            |
|          Reciever             |           Chocolatier.java            |
|          Invoker             |           App.java            |

### Pattern 3 -  Facade

Facade
- What pattern is it?  Facade
- What is its goal in the code? In order to maximise abstraction, related classes are separated 
away from the main App.java (which contains basic implementation) in packages. This allows
for higher complexity to be shifted away from the App.java class, leaving it more readable.
- Name of UML Class diagram attached: '301 Ass3 Facade UML.pdf'
- Mapping to GoF pattern elements:

| GoF element           | Code element          |
|-----------------------|-----------------------|
|            Facade           |             App.java          |
|            Package           |             packaging          |
|            Package           |             order          |
|            Package           |             packaging          |
|            Package           |             ingredient          |
|            Package           |             egg          |

## Task 2 - Full UML Class diagram

- Name of file of full UML Class diagram attached: '301 Ass3 Full UML.pdf'
- More explanation (if needed):

## Task 3 - Implement new features

### Task 3.1 - balanced packaging 

- What pattern fulfils the need for the feature?
- What is its goal and why is it needed here?
- Name of UML Class diagram attached: 
- Mapping to GoF pattern elements:

| GoF element           | Code element          |
|-----------------------|-----------------------|
|                       |                       |

### Task 3.2 - fill in the packages with eggs

- What pattern fulfils the need for the feature?
- What is its goal and why is it needed here?
- Name of UML Class diagram attached: 
- Mapping to GoF pattern elements:

| GoF element           | Code element          |
|-----------------------|-----------------------|
|                       |                       |
