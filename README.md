# Sales Summary Single-Page Application

This is a simple client-side web application that fetches sales data from an attached CSV file, calculates the total sales, and displays the result dynamically. It demonstrates the integration of Bootstrap 5.3.3 for styling, includes a fallback style, and performs several validation checks.

## Features

- Fetches embedded CSV data simulating an attachment.
- Parses CSV and sums the 'sales' column.
- Sets the document title with a base64-decoded seed string.
- Includes a currency selector allowing users to choose among USD, EUR, GBP, and TH.
- Converts the total sales based on selected currency rates defined in `rates.json`.
- Mirrors the active currency in the `#total-currency` element.
- Displays the total sales inside styled Bootstrap alerts.
- Ensures Bootstrap CSS is loaded.
- Performs validation on document title, CSS loading, and total calculation.

## Usage

Open the `index.html` file in a browser. The app runs entirely on the client-side with JavaScript.

## Notes

- In this example, the CSV data is embedded within the script to simulate an attachment. In a real scenario, replace the fetch source accordingly.
- The currency rates are fetched from an internal JSON string for simplicity.
- The total sales are converted based on the selected currency and displayed with two decimal places.
- Validation logs are printed to console for verification.

### License

This project is licensed under the MIT License.