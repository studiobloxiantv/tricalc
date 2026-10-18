# Tricalc

An installable PWA starter for UK primary / Year 7 written arithmetic.

## Methods included
- Column addition
- Column subtraction with exchange notes
- Long multiplication and expanded / partial products (including 4-digit × 4-digit)
- Bus-stop division with remainders

## Run locally
PWA install and offline support require HTTPS or localhost. In this folder, run:

    python -m http.server 8000

Then visit http://localhost:8000.

## Icon note
The app favicon and PWA manifest point to the exact Google Play image URL supplied by you. For the most reliable install icon and offline use, download that image as a local PNG and update the manifest `icons[0].src` plus the HTML favicon href to its local filename. This environment could not fetch the remote image directly.
