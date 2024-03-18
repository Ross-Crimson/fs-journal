# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > let, var and const

02. What is the definition of a function?

    > A subprogram designed to perform a specific task.

03. What are the `SOLID` principles?

    > S - single responsibility - try to break down functions to serving one purpose and refactoring extra work into another function

      o - open/closed principle - keep a class structured to be extended from rather than going back through and having to re-factor and test previous code to check for breaks. Essentially simplifying what one class does and building on that rather than making one huge super class

      l - liskov substitution principle - if you can extract peices of code into seperate classes or functions without hindering operation, then you should.

      i - interface segregation - don't force code to impliment any interfaces it doesn't need.
      
      d - dependency inversion - avoid having two seperate functions ability to work based on each other. One function can follow into another for a math solution, but that solution should look back at the first function to work.

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > fruit.filter('pineapple')

05. Given these two objects: How could you add each to the others friends arrays?

    ```js
    let you = {
        name: "You",
        hair: true,
        friends: []
    }
    let them = {
        name: "Them",
        hair: false,
        friends: []
    }
    ```

    > you.friends.append(them.name)
      friends.you.append(you.name)

06. Give an example of a JavaScript `Conditional`:

    > if(sky.color == blue) return true;

07. What is the main difference between `parameters` and `arguments`?

    > Parameters are the values a function receives and arguments are the variables being sent to a function.

    For example: function doThing(theVariable){}
                 
                 doThing(thingToDo);
    
    The parameter 'theVariable' is declared in the parenthesis of the function "doThing". Then later when calling said function, the argument "thingToDo" is sent to "doThing".

08. Instead of writing everything to the console, what is a better way to debug your code?

    > Use a breakpoint to step through your code as it runs step by step or to stop your code at the moment you want with a line-breakpoint.

09. What is the difference between a `primitive` value and a `reference` value?

    > A primitive only sends the value, but in a reference the value and original reference are passed.

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > for(i = -100; i <= 100; i++)
    {
        console.log(i);
    }
