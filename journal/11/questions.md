# A bit more CSharp and SQL
1. What does ***inheritance*** accomplish for us in C#?

  > Inheritance allows us to inheret variables and methods, preventing us from having to duplicate code.

2. How does ***member inheritance*** work in C#? Does a `Class` inherit all members of the base `Class`?

  > Ihe class inheriting will inherit all public and protected methods and variables from the inherited class. A "class" itself doesn't have an functionality, it's what is written inside.

3. How does ***accessibility*** affect inheritance?

  > If something is private it will not be inherited.

4. What is the difference between a `PRIMARY KEY` and a `FOREIGN KEY`

  > PRIMARY KEY is the identity of the table item and FOREIGN KEY references the identity of an item at another table.

5. What is an ***alias***?

  > A temporary name for a table or item.

6. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

  ```SQL
  CREATE TABLE doctors (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patients (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patient_doctors (
    id INT NOT NULL AUTO_INCREMENT,
    doctorId INT NOT NULL,
    patientId INT NOT NULL,

    FOREIGN KEY (doctorId)
      REFERENCES doctors(id),
    FOREIGN KEY (patientId)
      REFERENCES patients(id),
  )

  ```

  > SELECT
>   doctors*.,
>   patients*.,
>   patient_doctors*.
>   FROM
>   doctors
>   JOIN patients ON patients.id = patient_doctors.patientId
>   JOIN doctors ON doctors.id = patient_doctors.doctorId
