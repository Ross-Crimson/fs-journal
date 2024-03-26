# Application Architecture, MVC Design Pattern
01. What are the Pillars of Object Oriented Programming (`OOP`)?
  
  > The 4 pillars are Extraction, encapsulation, abstraction, and polymorphism.
  -Extraction: As it sounds, extracting code normally to be injected with a new piece.
  -Encapsulation: protecting data, ensuring that it can only be directly handled internally through defined functions which can be made public
  -Abstraction: Writing code that remains abstract in context, allowing for more flexible code to be referenced or injected later.
  -Polymorphism: Having code take on structure of a differet piece that allows it to be more easily re-used. For example you might have a few objects/classes named Cat, Dog, Bear. These can all extend from a Animal class which can inject more information that the prior 3 would have in common as they're all animals.

02. How does `export` differ from `export default`?
  
  > When using `export`, the imported functions must be referenced using the imported script's name. `export default` allows you to rename the imported script reference like a variable.

03. What is Encapsulation?
  
  > Encapsulation restricts data from being altered externally and requires public functions referencing said data for it to be changed.

04. What are some of the benefits of the `Proxy` object that we are using in our structure for applications?
  
  > Proxies allow you to assign simple functions to an object's property through the get function.

05. What the difference between a `class` and an instance of a `class`?
  
  > A class is a blueprint for data, and a instance is a copy of that class and its data and functions.

06. What is a computed Property?
  
  > A property that has been calculated through a function.

07. What is the purpose of the `MVC` pattern?
  
  > The purpose of the `MVC` pattern is to break up an application into 3 simple pieces, the Model, View, and Controller.

08. What is the job of the `Controller` in the `MVC` Pattern?
  
  > The controller handles user input and updates the `view` in the MVC.

09. What is the job of the `Service` in `MVC`?
  
  > The Services pattern seperates business logic from the rest of the project.

10. What is the job of the `Model` in `MVC`?
  
  > To handle the representation of data.
