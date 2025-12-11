## Exercise 1: Generate Unit test cases

Create simple unit tests using NUnit for the ExpenseTracker user registration functionality. 

Requirements:

1. Test the RegisterViewModel validation using hardcoded data only
2. Use NUnit 4.x framework with Assert.That() syntax (not Assert.AreEqual)
3. No mocking, no complex dependencies, no AccountController testing
4. Focus only on model validation and basic object creation
5. Include these specific test cases:
   - Valid registration data passes validation
   - Empty required fields fail validation
   - Invalid email format fails validation

Generate complete test class with proper NUnit setup, test methods, and Assert.That() validation statements. Include package references for NUnit 4.x and any required dependencies.


## Exercise 2: Code Review with Github Copilot

In this exercise, you will learn how to leverage Github Copilot to perform code reviews on your codebase. This can help you identify potential issues, suggest improvements, and ensure that your code adheres to best practices.

2. Open any file in this workspace and ask Github Copilot to help you with a code review. You can do this by typing a comment like `// Please review this code for potential issues and *improvements` above a function or block of code. or right click and select Generate code -> Review option

3.  Run this Prompt and Get Code review for uncommitted changes in the Source Control panel

```
Create a plan to implement a new enhancement: The dashboard should present a consolidated summary of all data in the “This Year” section. For recurring expenses, the system must annualize the amounts — for example, a monthly $50 expense should be calculated as 12 × $50 = $600, and a weekly $50 expense should be calculated as 52 × $50.
```
*