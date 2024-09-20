# Currency Converter

This is a **Currency Converter** web application built using **HTML**, **CSS**, and **JavaScript**. It allows users to convert between different currencies by fetching real-time exchange rates from the [Currency API](https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies). The project showcases the use of **async/await functions**, **callbacks**, and dynamic DOM manipulation.

## Features

- **Real-time currency conversion** using the latest exchange rates.
- **Dynamic dropdown menus** to select currencies for conversion.
- Displays **country flags** based on selected currencies.
- Simple and clean user interface built using **HTML** and **CSS**.
- Implements **error handling** for invalid inputs and ensures valid results.

## Technologies Used

- **HTML**: For structuring the content of the webpage.
- **CSS**: For styling the user interface.
- **JavaScript**: To handle API requests, dynamic DOM manipulation, and asynchronous functions.
- **Currency API**: For fetching real-time exchange rates.

## How It Works

1. **Currency Selection**: 
   - Users can select the "From" and "To" currencies using dropdown menus. The application automatically sets "USD" as the default "From" currency and "INR" as the default "To" currency on page load.
   - Currency flags are dynamically updated based on the selected currencies.

2. **Amount Input**:
   - Users can enter the amount they wish to convert. If no amount is provided or if an invalid value is entered, the converter defaults to `1`.

3. **Conversion Process**:
   - Upon clicking the "Convert" button, an API request is made using the **Fawaz Ahmed Currency API** to get the latest exchange rate for the selected currencies.
   - The converted amount is then displayed on the screen.

## Installation and Usage

### Clone the repository:
```bash
git clone https://github.com/HarshitGoyal-0303/Currency-Convertor.git
