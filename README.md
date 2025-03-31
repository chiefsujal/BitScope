# BitScope: Comprehensive Cryptocurrency Analytics Platform

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)  
[![Made with React](https://img.shields.io/badge/Made%20with-React-61DAFB.svg)](https://reactjs.org/)  
[![Powered by CoinGecko API](https://img.shields.io/badge/Powered%20by-CoinGecko%20API-FF9900.svg)](https://www.coingecko.com/en/api)

## Description

BitScope is a powerful and user-friendly web application designed to provide comprehensive cryptocurrency analytics. It empowers users with real-time tracking, in-depth trend analysis, and efficient portfolio management capabilities. Leveraging the CoinGecko API, BitScope delivers up-to-the-minute market data, allowing users to make informed decisions in the dynamic cryptocurrency market. With a focus on intuitive design, powerful functionality, and a responsive experience, BitScope caters to investors, traders, and enthusiasts alike.

## Features

* Real-time Cryptocurrency Tracking: Display live price movements, market capitalization, and trading volumes for a wide range of cryptocurrencies.
* Trend Analysis: Provide interactive charts and data visualizations to analyze market trends over various timeframes (7, 14, 30 days).
* Portfolio Management: Enable users to create a personalized watchlist of favorite cryptocurrencies for quick access and monitoring.
* Currency Conversion: Support multiple global currencies for seamless value conversion and tracking.
* Intuitive User Interface: Offer a clean, modern, and user-friendly interface for easy navigation and data interpretation.
* Comprehensive Data Insights: Display detailed information about each cryptocurrency, including market cap rank, sentiment analysis, and external links.
* fficient Data Filtering and Sorting: Allow users to filter and sort cryptocurrency data based on various criteria.
* Responsive Design: Ensure the application is accessible and functional across different devices and screen sizes.
* Interactive Charting: Utilize Recharts for dynamic and customizable data visualization.
* Customizable Time Ranges: Allow users to select different time ranges (7d, 14d, 30d) for chart data.
* Data Type Selection: Enable users to switch between price, market cap, and total volume data in charts.

## Technology Stack

* **Front-End:**
    * React.js
    * JavaScript (ES6+)
    * HTML5
    * CSS3
    * Tailwind CSS
    * Recharts
    * React Context API
* **Data Source:**
    * CoinGecko API
* **Testing:**
    * Jest
* **Build Tool/Package Manager:**
    * npm
* **Design:**
    * Figma
* **External Resources:**
    * Google Fonts
    * Iconify

## Project Structure

* **Root Directory (BitScope/):**
    * Contains the core project files and folders.
    * Includes configuration files, documentation, and source code.
* **node\_modules/:**
    * Stores all the project's installed dependencies from npm.
* **public/:**
    * Holds static assets like the `index.html` file (the entry point of the web application) and other static files (images, favicons, etc.).
* **src/:**
    * Contains the main source code of the React application.
    * **components/:**
        * Houses reusable React components like `Chart.js` (for Recharts), `CryptoDetails.js`, `Filters.js`, `Logo.js`, and `Navigation.js`.
    * **context/:**
        * Holds the react context files that manage the global states of the application. files like `CryptoContext.js`, `StorageContext.js`, `TrendingContext.js` are inside this folder.
    * **pages/:**
        * Contains React components that represent different pages or views of the application, such as `Crypto.js`, `Error.js`, `Home.js`, `Saved.js`, and `Trending.js`.
    * `App.js`: The root component of the React application.
    * `App.css`: Global styles for the App component.
    * `App.test.js`: Unit tests for the App component.
    * `index.js`: The entry point for the React application.
    * `index.css`: Global styles for the entire application.
    * `logo.svg`: The React logo SVG file.
    * `reportWebVitals.js`: File for tracking web vitals.
    * `setupTests.js`: Setup file for testing environment.
    * Other JavaScript and CSS files.
* `.gitignore`: Specifies files and directories to be ignored by Git.
* `CryptoBucks.fig`: The Figma design file for the project's UI.
* `documentation.txt`: The project's documentation file.
* `package.json`: Contains project metadata and dependencies.
* `package-lock.json`: Records the exact versions of installed dependencies.
* `postcss.config.js`: Configuration for PostCSS.
* `tailwind.config.js`: Configuration for Tailwind CSS.


## Installation

1.  Clone the repository:

    ```bash
    git clone [repository_url]
    ```

2.  Navigate to the project directory:

    ```bash
    cd BitScope
    ```

3.  Install dependencies:

    ```bash
    npm install
    ```

4.  Start the development server:

    ```bash
    npm start
    ```

5.  Open your browser at `http://localhost:3000`.

## Usage

* Use the search bar to find specific cryptocurrencies.
* Filter and sort data using the provided options.
* View detailed information about each cryptocurrency by clicking on its entry.
* Add cryptocurrencies to your watchlist for quick access.
* Customize charts by selecting different time ranges and data types.
* Change the displayed currency using the currency selector.

## Future Enhancements

* Implement user authentication and personalized dashboards.
* Add real-time price alerts and notifications.
* Integrate advanced charting capabilities and technical indicators.
* Expand the range of supported cryptocurrencies and data sources.
* Incorporate news and analysis sections for market context.
* Develop a mobile application version of BitScope.
* Implement more detailed filtering and sorting options.

## Contributing

Contributions are welcome! Please feel free to submit a pull request with any improvements or bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

* [CoinGecko API](https://www.coingecko.com/en/api) for providing cryptocurrency data.
* [React.js](https://reactjs.org/) for the front-end framework.
* [Tailwind CSS](https://tailwindcss.com/) for rapid UI development.
* [Recharts](https://recharts.org/en-US/) for data visualization.
* [Google Fonts](https://fonts.google.com/) for typography.
* [Iconify](https://iconify.design/) for icons.
* [Figma](https://www.figma.com/) for UI/UX design.
