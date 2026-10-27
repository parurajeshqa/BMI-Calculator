BMI Calculator in Java
📌 Project Description

The BMI (Body Mass Index) Calculator is a simple, console-based Java application that calculates a user's BMI based on their weight and height.

The program accepts weight in pounds and height in meters, converts the weight into kilograms, calculates the BMI, and displays a weight category based on the calculated result.

✨ Features
Accepts user weight in pounds.
Accepts user height in meters.
Converts weight from pounds to kilograms.
Calculates Body Mass Index (BMI).
Classifies BMI into four categories:
Underweight
Normal weight
Overweight
Obese
Displays the calculated BMI and corresponding category.
🛠️ Technologies Used
Programming Language: Java
Input Handling: Scanner class
Concepts: Variables, data types, arithmetic operations, conditional statements, and console input/output.
📂 Project Structure
text
BMI-Calculator/
└── src/
    └── day3/
        └── BMICalculator.java

🧮 BMI Formula

The program uses the following formula:

BMI = Weight (kg) / Height (m)²

Since the user enters weight in pounds, the program first converts it into kilograms.

Pounds to Kilograms Conversion:

java
weightInKgs = weightInPounds * 0.45359237;


BMI Calculation:

java
bmi = weightInKgs / (height * height);

📊 BMI Categories

The program uses the following BMI ranges to classify the result:

BMI Range	Category
Below 18.5	Underweight
18.5 to below 25	Normal weight
25 to below 30	Overweight
30 and above	Obese

Note: These are general adult BMI categories and are not a substitute for professional medical advice.

🚀 How to Run the Program
Prerequisites
Java Development Kit (JDK) installed on your computer.
A Java-supported IDE, such as Eclipse, IntelliJ IDEA, or VS Code, or a terminal.
Steps
Clone or download the repository.
Open the project in your preferred Java IDE.
Navigate to BMICalculator.java inside the day3 package.
Run the BMICalculator class.
Enter your weight in pounds when prompted.
Enter your height in meters.
View your calculated BMI and weight category.
Run Using the Terminal

From the directory containing the day3 folder, execute:

bash
javac day3/BMICalculator.java
java day3.BMICalculator

💻 Example Output
text
Enter you weight in pounds
150
Enter you height in meters
1.7
You BMI is 23.032...
You are normal


The displayed BMI value is calculated from the entered weight and height.

🎯 Learning Objectives

This project demonstrates the following Java programming concepts:

Using the Scanner class to accept user input.
Working with double variables for decimal values.
Performing unit conversions.
Applying mathematical formulas.
Using arithmetic operators.
Implementing conditional logic with if, else if, and else.
Displaying results using System.out.println().
🔮 Future Improvements
Validate that weight and height are positive numbers.
Prevent division by zero when the height is zero.
Format the BMI result to two decimal places.
Improve the user interface and input messages.
Add support for entering height in feet and inches.
Allow users to calculate BMI multiple times without restarting the program.
👨‍💻 Author

Created as a beginner-level Java project to practice user input, mathematical calculations, and conditional statements.

📄 License

This project is intended for educational and learning purposes.
