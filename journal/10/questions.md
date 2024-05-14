# CSharp and SQL Fundamentals
01. What is the purpose of a `namespace`?

  > namespace kind of creates a container where in order for something to be accessed inside that container, the item attempting to access either needs to also be in the namespace or import that namespace.

02. What is the difference between a `class` and an `interface`?

  > A class is the script itself and an interface is like a contract that is made that a script will inherit and essentially says "hey interface, i'm going to inheret all your functionality".

03. What is the method that returns an instance of a class, yet it has no return type?

  > Void

05. In the Car example what is the access modifier of the `Start()` method?

  ```c#
  abstract class Car
  {
    public string Start()
    {

      return "Vroooom";

    }
  }
  ```

  > start() has a Public modifier

06. In the Car example what is `string` an indication of?

  > `string` indicates the type of value that will be returned by the function.

07. In the Car example what is `abstract` preventing?

  > abstract is preventing new "cars" from being created from car and is forcing whatever wants access to be inhereting from the Car script.

08. In a SQL table, what is the difference between information in a row and information in a column?

  > A column would contain the type of information of all objects in the table and the row would represent an entire object and its data.

09. Demonstrate the necessary SQL for creating a table called `characters` with the values `name, age, description` as strings, and an `int` id.
```c#
  CREATE TABLE characters(
      id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
      name VARCHAR(255) NOT NULL,
      age INT NOT NULL,
      description VARCHAR(1000) NOT NULL
    );
```

10. In SQL how can you query more than a single table? Provide an example.

  > Yes you can
        SELECT * FROM table1 JOIN table2
