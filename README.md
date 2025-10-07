# Sales Summary Web Application

## Summary:
This static web application fetches a `data.csv` file to calculate the total sum of sales and display it on a single page. The title of the page is set to "Sales Summary 24f100364@ds.study.iitm.ac.in-2025-10-07-11". The total sales amount is shown prominently inside `#total-sales`. Bootstrap 5 is loaded from jsdelivr for styling purposes.

## Setup:
To deploy this application on GitHub Pages, follow these steps:
1. Fork this repository to your GitHub account.
2. Upload your `data.csv` file to the repository.
3. Go to the repository's Settings.
4. Scroll down to the GitHub Pages section.
5. Choose the main branch as the source.
6. Your web application will be published at: `https://your-username.github.io/your-repository-name`.

## Usage:
- Access the page by opening the provided GitHub Pages link.
- There are no query parameters or configuration options.
- Key Features:
  - Fetches `data.csv` file automatically.
  - Calculates the total sum of sales.
  - Sets the title dynamically.
  - Displays the total sales amount prominently.

## Code Explanation:
This web application uses HTML, CSS, and JavaScript to fetch and process the `data.csv` file. Key libraries used include Bootstrap 5 for styling from jsdelivr CDN. The logic involves parsing the CSV file, summing up the sales column values, and updating the DOM to display the total sales amount.

## License:
This project is licensed under the MIT License.