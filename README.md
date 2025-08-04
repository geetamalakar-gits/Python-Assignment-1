# Task 1: Python program to perform basic mathematical operations  
It takes two numbers from the user and performs basic math operations: **addition, subtraction, multiplication,** and **division**. Then it shows the results on the screen.
Step-by-Step Explanation:
1. User Input:
   * The program asks the user to enter **two numbers**.
   * `float()` is used so the user can enter decimal numbers (like 5.5 or 10.0), not just whole numbers.
2. Performing Calculations:
    * The program adds, subtracts, and multiplies the two numbers and stores the results in different variables.
3. Handling Division Carefully:
   * Before dividing, it checks if the second number is **not zero**.
   * If it’s not zero, it divides the first number by the second.
   * If it **is zero**, it shows a message instead of dividing, because dividing by zero causes an error.
4. Displaying the Results:
   * It prints all the results in a clean and readable format.


# Task 2: Python program to Create a Personalized Greeting
It **asks the user for their first and last name**, then **joins them together**, and finally **prints a greeting message** using their full name.
Step-by-step Explanation:
1. Input the First Name:
   → It shows a message on the screen asking the user to type their first name.
   → Whatever the user types is saved in a variable called `first_name`.

2. Input the Last Name:
   → Now, the user is asked to enter their last name.
   → The input is saved in another variable called `last_name`.

3. Join the First and Last Name:
   → Then it joins the first and last names with a space in between.
   → The result is stored in a new variable called `full_name`.

4. **Print a Greeting:**
   → It then prints a friendly message using the full name.
   → The `{full_name}` part is replaced with the user's full name.
