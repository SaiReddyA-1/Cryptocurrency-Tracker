# Cryptocurrency Tracker

In this project, I have successfully built a **Cryptocurrency Tracker** by applying the concepts I have learned.

### Refer to the image below:

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/cryptocurrency-tracker-output.gif" alt="cryptocurrency-output" style="max-width:70%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

### Implemented Features

- When the page is opened:
  - Makes an HTTP GET request to the **cryptocurrenciesApiUrl**
  - Displays a **loader** while fetching the data
  - After fetching the data, displays the updated list of cryptocurrencies

### API Requests & Responses

- **cryptocurrenciesApiUrl**
  - API: `https://apis.ccbp.in/crypto-currency-converter`
  - Method: `GET`
  - Response:
    ```json
    [
      {
        "currency_name": "Bitcoin",
        "usd_value": "46750.63",
        "euro_value": "39596.07",
        "id": "6e937df9-1345-4c2f-8ace-babff0e5108f",
        "currency_logo": "https://www.cryptocompare.com/media/19633/btc.png"
      },
      ...
    ]
    ```

### Components Structure

<br/>
<div style="text-align: center;">
    <img src="https://assets.ccbp.in/frontend/content/react-js/cryptocurrency-component-breakdown-structure.png" alt="cryptocurrency component breakdown structure" style="max-width:100%;box-shadow:0 2.8px 2.2px rgba(0, 0, 0, 0.12)">
</div>
<br/>

### Implementation Files

- `src/components/CryptocurrencyTracker/index.js`
- `src/components/CryptocurrencyTracker/index.css`
- `src/components/CryptocurrenciesList/index.js`
- `src/components/CryptocurrenciesList/index.css`
- `src/components/CryptocurrencyItem/index.js`
- `src/components/CryptocurrencyItem/index.css`

### Resources

- Image URLs:
  - [https://assets.ccbp.in/frontend/react-js/cryptocurrency-bg.png](https://assets.ccbp.in/frontend/react-js/cryptocurrency-bg.png) alt should be **cryptocurrency**
- Colors:
  - ![#000000](https://via.placeholder.com/150/000000/000000?text=+) Hex: #000000
  - ![#00e7ff](https://via.placeholder.com/150/00e7ff/000000?text=+) Hex: #00e7ff
  - ![#092e33](https://via.placeholder.com/150/092e33/000000?text=+) Hex: #092e33
  - ![#ffffff](https://via.placeholder.com/150/ffffff/000000?text=+) Hex: #ffffff
- Font-family: Roboto
