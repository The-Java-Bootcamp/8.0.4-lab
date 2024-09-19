# Lab: 8.0.4

**Objective:**

- Understand the concept and importance of creating classes in Java development.
- Learn how to implement classes with public and private members.
- Explore practical applications of access modifiers in real-world Java projects.
- Identify common pitfalls and best practices when working with public and private members.
- Gain hands-on experience with a complete Java example that demonstrates class creation and member access.

**Prerequisites:**

- Basic understanding of Java programming.
- Familiarity with basic Java syntax and data types.

**What You'll Achieve:**

- Develop a solid understanding of class creation in Java.
- Implement practical examples of public and private members.
- Enhance your skills in object-oriented programming concepts.

**Assignment Details**

In this assignment, you will create a simple `BankAccount` class to demonstrate the use of public and private members.
Follow these steps:

1. Create a `BankAccount` class with the following private members:
    - `accountNumber (String)`
    - `balance (double)`
    - `ownerName (String)`
2. Implement public methods to:
    - Get the account number
    - Get the current balance
    - Get the owner's name
    - Deposit money
    - Withdraw money
3. In the main method:
    - Create two `BankAccount` objects
    - Perform operations like depositing and withdrawing money
    - Print out the account details before and after these operations

**Example Output**

```
Account 1 Details:
Account Number: 1001
Owner: John Doe
Balance: $1000.0

Account 2 Details:
Account Number: 1002
Owner: Jane Smith
Balance: $500.0

After transactions:
Account 1 Balance: $1500.0
Account 2 Balance: $300.0
```

**Starter Code**

The `BankAccountAssignment.java` file contains the following starter code:

```java
package academy.javapro.lab;

public class BankAccountAssignment {
    public static void main(String[] args) {
        // Your code here
    }
}

class BankAccount {
    // Declare private members here

    // Implement public methods here
}

```

**Hints**

- Use the `private` keyword for member variables to encapsulate data.
- Use the `public` keyword for methods that need to be accessed from outside the class.
- Remember to validate inputs in your deposit and withdraw methods (e.g., no negative amounts).
- Use meaningful variable names and add comments to explain your code.

**Submission Instructions**

1. Fork the repository
2. Clone your fork
3. Navigate into the repository
4. Implement the required functionality in the `TextAnalyzer.java` file
5. Test your implementation with various inputs
6. Git add, commit, and push to your fork
7. Submit a pull request
    - Set the title of the pull request to your first name and last name
    - In the comment, briefly explain your implementation approach and any challenges you faced

Remember, the goal is to learn and have fun! Don't hesitate to ask for help if you get stuck.