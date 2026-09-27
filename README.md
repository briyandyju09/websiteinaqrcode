# Briyan's Caesar Salad

> A single-page Caesar cipher tool, designed to live inside a QR code.

## Stack

- Plain HTML + CSS + vanilla JavaScript — a single file, no build step, no dependencies.

## Description

A tiny web page that encrypts and decrypts text with a Caesar cipher. Because the whole tool
fits in one self-contained HTML file, it can be encoded directly into a QR code — scan the code
and the tool opens in the browser, no hosting required.

## Features

- Encrypt and decrypt with a configurable shift (1–25).
- **Case-preserving** — uppercase and lowercase letters keep their case; non-letters pass
  through unchanged.
- Runs entirely client-side with zero dependencies.
- Small enough to embed in a single QR code.

## How to Build / Run

No build step — open `main.html` in any browser:

```bash
# optional: serve locally
python -m http.server 8000
# then open http://localhost:8000/main.html
```

To turn it into a QR code, paste the contents of `main.html` into a site-in-a-QR tool such as
[sandwich.a-burger.xyz](https://sandwich.a-burger.xyz).

## Credits

QR-code embedding via [sandwich.a-burger.xyz](https://sandwich.a-burger.xyz).
