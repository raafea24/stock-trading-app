# Stock Trading App

A responsive, single-page trading dashboard concept built with HTML, CSS, and JavaScript. It displays a sample Bitcoin balance, a chart, and recent transactions.

> **UI demo:** The figures are sample data. The BUY and SELL buttons are visual controls only; this project does not connect to an exchange, place orders, or manage a wallet.

## Features

- Balance summary with a sample BTC amount and percentage change.
- Candlestick and line chart rendered with CanvasJS. Click a chart legend item to show or hide its series.
- Sample received and sent transaction entries.
- Responsive layout using Bootstrap and Font Awesome icons.

## Run locally

No package installation or build step is required.

1. Clone the repository:
   ```sh
   git clone https://github.com/raafea24/stock-trading-app.git
   ```
2. Open `stock-trading-app/index.html` in a browser.

You can also serve the repository directory with any local static file server and open its local URL.

## Project structure

```text
index.html          Page markup and sample balance/transactions
css/custom.css      App-specific styles
css/                Bundled Bootstrap and Font Awesome styles
js/data-chart.js    Chart configuration and sample data
js/custom.js        App-specific JavaScript
js/                 Bundled jQuery and CanvasJS libraries
fonts/              Font Awesome font files
```

To change the displayed balance or transactions, edit `index.html`. To adjust the chart or its hard-coded 2016 data points, edit `js/data-chart.js`. The transaction examples in the page are dated 2022; neither set of values is live market data.

## Credits

Based on [project 38, Stock Trading App, in SudeepAcharjee/The-50-Front-end-Project](https://github.com/SudeepAcharjee/The-50-Front-end-Project/tree/main/38.Stock%20Trading%20App).
