# Rwanda Grid Converter Mobile

Mobile-first single-file field tool for converting Rwanda grid references and WGS84 coordinates on a phone.

## Overview

This project is the mobile edition of the Rwanda Grid Converter. It is designed for touch screens and field use, with a compact layout, bottom navigation, live location support, map tools, pin history, route building, and quick report export.

## Main Mobile Features

- Convert `6-digit grid references` to `WGS84 geographic coordinates`
- Convert `WGS84 coordinates` back to `6-digit grid references`
- Work with `decimal` or `DMS` coordinate input
- Use a full-screen interactive `Leaflet` map
- Get your current phone location with `Me`
- Add pins directly from conversion results or by tapping the map
- Build simple routes from selected pins
- Generate a report and download a `CSV`
- Switch between supported map sheets inside the app

## Supported Sheets

- `GAKO`
- `GABIRO`
- `MIHINDI`
- `NYAGATARE`

`GAKO` uses its original GPS-calibrated base constants.

`GABIRO`, `MIHINDI`, and `NYAGATARE` use the configured sheet ranges and reference points currently stored in `index.html`.

## Project Files

- `index.html` - complete mobile app UI, styles, map tools, sheet setup, and conversion logic
- `image.png` - logo shown on the unlock screen

## How To Open On Mobile

1. Copy the project to your phone, or host `index.html` on a local/internal server.
2. Open `index.html` in a mobile browser such as Chrome or Safari.
3. Unlock the app.
4. Start working from the bottom navigation tabs.

Current unlock password in this build: `kwizera2026`

## How To Use

1. Choose the sheet you want to use.
2. Open `Grid -> Geo` to convert a `6-digit grid reference`.
3. Open `Geo -> Grid` to convert decimal or `DMS` coordinates.
4. Tap `Show on Map` to send the result to the map screen.
5. Use `Me` to center on your current location.
6. Tap the map to save named pins.
7. Select pins for a route if you want distance and movement estimates.
8. Use `Report` to open a printable/exportable summary and download `CSV`.

## Mobile Notes

- The layout is optimized for phones and touch interaction.
- Geolocation depends on browser permission being allowed on the phone.
- For the best experience, add the page to the home screen if your browser supports it.
- Some browsers may block the report popup until popups are allowed.

## Technical Notes

- No build step is required.
- No package installation is required.
- All logic is contained in `index.html`.
- Sheet calibration, anchors, and grid constants are stored directly in the `SHEETS` configuration in `index.html`.

## Support

This mobile app was created by `Kwizera`.

Help line: `0781845528`
