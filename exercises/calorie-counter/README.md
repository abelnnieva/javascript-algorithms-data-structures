# Calorie Counter

A simple web-based calorie tracker that helps users manage their daily calorie budget by logging meals, snacks, and exercise.

## Features

- **Add Entries**: Dynamically add input fields for meals, snacks, and exercise.
- **Calorie Budgeting**: Calculate calories consumed, burned, and remaining based on user inputs.
- **Error Handling**: Alerts users for invalid inputs (e.g., scientific notation or non-numeric entries).
- **Reset Functionality**: Clear all entries and reset the form with one click.

## How It Works

1. **Set Budget**: Enter your daily calorie budget in the input field.
2. **Add Entries**: Click the "Add Entry" button to log calories for breakfast, lunch, dinner, snacks, or exercise.
3. **Submit**: Press the "Calculate" button to view:
   - Remaining calories.
   - Total calories consumed.
   - Calories burned through exercise.
4. **Clear**: Use the "Clear" button to reset the form and start over.

## Technologies

- **HTML/CSS**: User interface.
- **JavaScript**: Dynamic form generation, calorie calculations, and validations.

## Notes

- Invalid inputs such as scientific notation (e.g., `1e10`) will trigger an error alert.
- Positive results indicate a calorie deficit, while negative results indicate a calorie surplus.

Stay on track with your calorie goals!
