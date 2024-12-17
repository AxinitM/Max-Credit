# Microinvest Credit Calculator for one e-shop

This project is a modal window designed to calculate loan terms and payments for users of a photo goods store.
It includes an interactive table for selecting loan terms and dynamically updates monthly and total payment calculations.
In the full version, the product price (used for loan calculations) will be retrieved directly from the product card. 
In the current test mode, the product price is entered manually through a prompt window.
The modal also features a personal information form with validation and feedback mechanisms.

## Links
[Credit Calculator](https://axinitm.github.io/Max-Credit/))

## Features
- **Dynamic Loan Calculation**: Calculates monthly and total payments based on user input and predefined percentages for different loan terms.
- **Interactive Table**: Users can select loan terms directly from the table, which updates the calculations in real-time.
- **Form Validation**: Validates user input (name and phone number) to ensure correctness before submission.
- **Responsive Design**: Optimized for various screen sizes.
- **Thank You Message**: Displays a thank-you message upon successful form submission.

## Technologies Used
- **HTML**: Structure of the application.
- **CSS**: Styling and layout, including responsive design.
- **JavaScript**: Handles calculations, form validation, and dynamic interactions.

## Usage
1. **Input Item Price**: The application prompts the user to enter the item price (between 1000 and 100,000 lei).
2. **Select Loan Term**: Choose the desired loan term from the interactive table.
3. **Fill Out the Form**: Enter personal information including first name, last name, and phone number.
4. **Submit the Form**: After validation, the form submits and displays a thank-you message with details hidden.

## Validation Rules
- **First Name and Last Name**: Must contain only letters and at least two characters.
- **Phone Number**: Must start with `0` and contain exactly nine digits.

## File Structure
The entire project is contained in a single index.html file, which includes the HTML structure, inline CSS for styling, and inline JavaScript for interactivity.

## Future Enhancements
- Add server-side integration to process form submissions.
- Store and display loan calculation history.
- Add support for multiple currencies and localization.


