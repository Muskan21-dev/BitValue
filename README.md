# Bitcoin Price Calculator

This project is a simple web-based Bitcoin price calculator.  
It fetches the real-time Bitcoin price in USD and INR from the [CoinGecko API](https://www.coingecko.com/en/api) and allows users to calculate the value of a given amount of Bitcoin.  

It also includes **dark mode support**, **localStorage caching**, and **basic error handling** to improve user experience.

## Features

- Real-time Bitcoin prices in USD and INR
- Calculate the value based on user input
- Auto-refresh prices every 2 minutes
- Dark mode / light mode toggle
- Caching with localStorage (for offline fallback)
- Error handling for API failures
- Responsive and minimal UI

## Demo

> (Add your live link here if hosted, e.g., GitHub Pages, Vercel, Netlify)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/bitcoin-price-calculator.git
   ```
2. Open the `index.html` file in your browser.

> No backend or server setup is required. It's a fully client-side project!

## Usage

- Enter the amount of Bitcoin you own.
- Click **Calculate** to see the equivalent value in USD and INR.
- Click **Reset** to clear the input.
- Toggle between Dark Mode and Light Mode with the button.

The app automatically updates the prices every 2 minutes.

## Project Structure

```
bitcoin-price-calculator/
├── index.html
├── style.css
└── script.js
```

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- CoinGecko API

## Acknowledgements

- [CoinGecko API](https://www.coingecko.com/en/api) for providing free cryptocurrency price data.
- Made with ♥ by [Muskan](https://www.linkedin.com/in/your-linkedin-username/).

## License

This project is open source and available under the [MIT License](LICENSE).

