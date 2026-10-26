# 3D Printing Price Calculator

A single-page calculator for pricing FDM 3D prints in Colombian pesos (COP), built for Ad Astra.

**Live app:** https://danielsballes.github.io/3d-printing-calculator/

## What it does

- Prices a print from material, print time, labor, printer depreciation, maintenance and energy (peak power).
- Printer presets for popular machines (QIDI, Bambu Lab, Creality, Elegoo, Anycubic, Prusa) with 110 V peak power.
- Sales channels: direct sale or Mercado Libre Colombia (commission, fixed fee, free-shipping threshold, shipping, withholdings).
- Exports a PDF (internal cost breakdown or a clean client quote).
- Saves calculations in the browser's localStorage, with JSON backup export and import.

## Run locally

Open `index.html` in a browser. No build step. It loads jsPDF and Google Fonts from CDNs, so it needs an internet connection for PDF export and fonts.

## Notes

Default prices, fees and power figures are reference values. Adjust them to your own invoices, your energy bill and your Mercado Libre seller account.
