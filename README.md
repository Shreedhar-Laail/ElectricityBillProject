# Electricity Billing System

The Electricity Billing System is a simple Java program designed to calculate electricity bills for customers based on the units consumed. This README provides an overview of the code and its functionality.

## Table of Contents

- [Introduction](#introduction)
- [Usage](#usage)
- [Code Explanation](#code-explanation)
- [License](#license)

## Introduction

The Electricity Billing System is a command-line program that allows users to enter customer information such as name and units consumed. It then calculates the electricity bill based on a predefined rate per unit. The program consists of three main components:

1. **Customer Class:** This class represents a customer and stores their name and units consumed.

2. **BillCalculator Class:** This class contains a static method to calculate the electricity bill based on the units consumed. It uses different rates per unit for different consumption ranges.

3. **ElectricityBillingSystem Class:** This is the main class where user interaction takes place. It prompts the user for customer details, calculates the bill, and displays the customer's name, units consumed, and bill amount.

## Usage

To use the Electricity Billing System, follow these steps:

1. Compile the Java code using a Java compiler.

   ```
   javac ElectricityBillingSystem.java
   ```

2. Run the program.

   ```
   java ElectricityBillingSystem
   ```

3. Follow the on-screen instructions to enter the customer's name and units consumed.

4. The program will calculate and display the bill amount.

## Code Explanation

Here's a brief explanation of the key components and logic in the code:

- The `Customer` class is used to create customer objects, storing their name and units consumed.

- The `BillCalculator` class contains a static method `calculateBill` that takes the units consumed as input and calculates the bill based on predefined rates per unit.

- The `ElectricityBillingSystem` class is the main class responsible for user interaction. It prompts the user to enter customer details, creates a `Customer` object, calculates the bill using the `BillCalculator`, and displays the results.

- The billing rates are predefined in the `calculateBill` method, with different rates for different consumption ranges.

- The program uses a `Scanner` to read user input from the command line.

## License

This code is provided under an open-source license. You are free to use, modify, and distribute it as needed, but please refer to the original license file (if provided) for specific terms and conditions.

---

Feel free to modify and enhance the code as needed for your specific requirements. If you have any questions or encounter issues, please refer to the code comments and Java documentation for further assistance.
