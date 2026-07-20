# Gaavn Fresh — MIS Dashboard

A single-file management dashboard for Gaavn Fresh dairy operations.
Shows daily P&L, cash flow, product-wise margins, monthly P&L and an
accountant-ready CSV export, aggregated live from the company's
operational Google Sheets via a Google Apps Script endpoint.

## Usage

1. Open the hosted page (GitHub Pages) on any phone or computer.
2. On first use, go to **Setup** and paste the MIS web-app URL
   (provided separately — it is never stored in this repository).
3. On a phone, use **Add to Home Screen** for an app-like experience
   (works on both iOS Safari and Android Chrome).

## Notes

- This repository contains only the dashboard front-end. It holds no
  spreadsheet IDs, no API keys and no business data.
- Data access is controlled entirely by the MIS web-app URL, which is
  entered at runtime and saved only in the device's local storage.

*Internal tool — not licensed for external use.*
