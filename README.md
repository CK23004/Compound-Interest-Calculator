# Compound Interest Calculator

A single-page compound interest calculator that projects investment growth with optional recurring contributions. Built with HTML, Bootstrap, jQuery, and Chart.js (all loaded from CDNs).

## Project Screenshots

![Calculator screenshot 1](assets/Screenshot%20From%202026-01-23%2000-56-15.png)
![Calculator screenshot 2](assets/Screenshot%20From%202026-01-23%2000-57-37.png)
![Calculator screenshot 3](assets/Screenshot%20From%202026-01-23%2000-57-57.png)

## Getting Started
- Option 1: Open `index.html` directly in your browser.
- Option 2: Serve locally to avoid CDN or file-url issues:
  - From the project root, run `python3 -m http.server 8000`.
  - Visit http://localhost:8000 in your browser.

## Usage
1. Enter principal, annual interest rate, compounding period, and optional recurring contribution with its frequency.
2. Set the tenure using years and months.
3. Click **Calculate**.
4. Review the summary table (future value, interest earned, monthly rate, time to double) and the month-by-month chart/table.

## Inputs at a Glance
- Principal: starting amount.
- Interest Rate: annual percentage rate.
- Compounding Period: monthly, quarterly, half-yearly, or yearly.
- Contribution: recurring deposit; frequency can be monthly, quarterly, half-yearly, or annually.
- Tenure: years plus extra months.

## Tech Notes
- UI: Bootstrap 4.5.2, dark theme tweaks.
- Charts: Chart.js 3.7.0 line chart for future value and contributions.
- Behavior: jQuery for DOM handling and calculations.

## License
See [LICENSE](LICENSE) for details.
