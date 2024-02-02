# Calorie Counter

This is a simple web application that helps users track their daily calorie intake and expenditure.

## Features

- Users can set a daily calorie budget.
- Users can add entries for breakfast, lunch, dinner, snacks, and exercise.
- Each entry consists of a name and a calorie count.
- The application calculates the total calories consumed and burned, and compares it with the budget.
- The application displays a surplus or deficit of calories.
- Users can clear all entries and reset the budget.

## How It Works

The application uses JavaScript to manipulate the DOM and handle user interactions.

- `cleanInputString(str)`: This function removes plus signs, minus signs, and spaces from a string.
- `isInvalidInput(str)`: This function checks if a string matches the regular expression `\d+e\d+`, which represents a number in scientific notation.
- `addEntry()`: This function adds a new entry input field to the selected meal or exercise category.
- `calculateCalories(e)`: This function calculates the total calories consumed and burned, and compares it with the budget. It updates the output display with the results.
- `getCaloriesFromInputs(list)`: This function calculates the total calories from a list of input fields.
- `clearForm()`: This function clears all entry input fields and resets the budget.

## How to Use

1. Open the HTML file in a web browser.
2. Enter your daily calorie budget.
3. Select a meal or exercise category from the dropdown menu.
4. Click the "Add Entry" button to add a new entry input field to the selected category.
5. Enter the name and calorie count for each entry.
6. Click the "Calculate" button to calculate the total calories and compare it with the budget.
7. The results will be displayed in the output area.
8. Click the "Clear" button to clear all entries and reset the budget.

## Future Improvements

- Add a database to store user data.
- Add user authentication to allow multiple users to track their calories.
- Add a date picker to allow users to track their calories for specific dates.
- Add a chart to visualize the calorie data.