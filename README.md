# Loan Calculator Web App

This web application calculates monthly loan payments, total payment, and total interest based on user inputs. It also provides a chart to visually display the principal and interest breakdown.

## Features

- Calculate loan payments, total payment, and total interest
- Switch between light and dark mode
- Interactive slider for selecting loan years
- Visual breakdown of loan details with a doughnut chart

## Technologies Used

- **HTML**: Structure and layout of the app
- **CSS**: Styling the page and supporting dark mode
- **JavaScript**: Calculations and interactive features
- **Chart.js**: Displaying a doughnut chart for loan details

## How to Use

1. Open the `index.html` file in a browser.
2. Enter the loan amount, interest rate, and loan duration in years.
3. Click the "Calculate" button to display the monthly payment, total payment, and total interest.
4. Use the slider to adjust the loan years.
5. Switch between dark and light mode using the toggle button.


### Dark Mode Switch
```javascript
document.getElementById('dark-mode-switch').addEventListener('change', function() {
  document.body.classList.toggle('dark-mode', this.checked);
});
