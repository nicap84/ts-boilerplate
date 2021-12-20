# What will we do?
##FizzBuzz

* Given a list of numbers from 1 to n
  * If a number is divisible by 3 should be replaced with Fizz
  * If a number is divisible by 5 should be replaced with Buzz
  * If a number is divisible by 3 and by 5 should be replaced with FizzBuzz

# Exercise 1
* Given a list of numbers from 1 to n
  * If a number is divisible by 3 should be replaced with Fizz

# Exercise 2
* Given a list of numbers from 1 to n
    * If a number is divisible by 5 should be replaced with Buzz

# Exercise 3
* Given a list of numbers from 1 to n
    * If a number is divisible by 3 and by 5 should be replaced with FizzBuzz

# How will we do it?
## TDD
* Make use of Test Driven Development
  * Create a failing test
  * Make the test pass with the minimum
  * Refactor

### Documentation
* [Test Driven Development: By Example](https://www.amazon.es/Driven-Development-Example-Addison-Wesley-Signature/dp/0321146530)

# We are done, what an easy exercise, what's next?
## SOLID
* Refactor the code making use of some software development principles known as SOLID
  * Single Responsibility
  * Open Closed
  * Liskov Substitution
  * Interface Segregation
  * Dependency Inversion

### (Bonus) Exercise 4
* **Domain** challenge
  * Given a list of numbers from 1 to n
      * If a number is divisible by 7 should be replaced with Fazz
* **Technical** challenge
  * Make use of the **Single Responsibility** principle
      * Right now our class have 2 reasons to change
          * Generate a list of numbers
          * Generate replacements for each number based on rules
      * Refactor the class so every resulting class have only one reason to change 
  * Make use of the **Open Closed** principle
      * Make your code closed for modification
      * Make your code open for extension
  * Make use of the **Dependency Inversion** principle
    * Make your code depend on abstractions (interfaces, abstract classes...)

### (Bonus) Exercise 5
* **Domain** challenge
    * Given a list of numbers from 1 to n
        * If a number is divisible by 9 should be replaced with Bazz
* **Technical** challenge
    * Analyze the differences between adding new domain challenges with and without SOLID principles applied

### Documentation
* [The S.O.L.I.D Principles in Pictures](https://medium.com/backticks-tildes/the-s-o-l-i-d-principles-in-pictures-b34ce2f1e898)

# JSDoc and TypeScript
## (Bonus) Exercise 6
* For every class, method or function written in TypeScript
  * Make use of JSDoc to document them
  * Analyze the differences (or lack of differences) between JSDoc and TypeScript
  * Refactor your JSDoc comments, so they only use the TypeScript syntax
  * Think on how this can we used for our existing projects
# What's the goal of this code kata
* Improve our testing skills
* Work with and learn about TypeScript in a controlled environment
* Enhance our software development design skills via TDD
* Continue improving on refactoring
* Get to know SOLID principles and start thinking on them
