# JSON Formatter and Validator

This tool formats, minifies, and validates JSON in the browser. It uses the browser's own JSON parser, so what it accepts matches what your code will accept, and on an error it reports the parser's message, which usually names where the problem is.

**Live demo:** https://0xelitesystem.github.io/json-formatter-and-validator/

## What it does

Paste JSON and the tool validates it live. Format pretty-prints it at two or four spaces or a tab; minify strips all whitespace. It reports byte size and a key count, and copies the output. Invalid input shows the parser's error message rather than a vague failure.

Because validation uses the same parser the browser ships, it is an honest check: if it passes here, it parses in your JavaScript. Nothing is sent or saved.

## Aesthetic

A dot-matrix tractor-feed printout: sprocket-hole side strips, green-bar striping, and a dot-matrix status line that reads valid or invalid.

## Privacy

Everything runs in your browser. Nothing you type is sent anywhere, stored, or saved. Closing the tab clears it.

## Use it

Open `index.html` in any modern browser, or host it as a static page. No build step, no dependencies, no network calls.

## License

MIT. Copyright (c) 2026 0xelitesystem.
