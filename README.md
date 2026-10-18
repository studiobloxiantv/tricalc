# Tricalc

A PWA calculator with a keypad, light/dark mode, and written-method working displayed above the calculator.

## Included
- Calculator-style numpad with arithmetic operators
- Column addition and subtraction layouts, including carry/exchange marks
- Long multiplication with partial-product rows
- Bus-stop division
- Light and dark mode
- PWA manifest and service worker

## Run
PWA install/offline support requires HTTPS or localhost. From this folder run `python -m http.server 8000` and open `http://localhost:8000`.

The favicon and manifest reference the icon URL supplied by the user. A remote icon may require internet access during installation.
