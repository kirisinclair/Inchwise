# Inchwise

A free browser game for learning imperial units in metric: inches, feet, yards, miles and square feet to centimeters or millimeters, and back.

- Five levels: Inchling (round multiples with a cheat line), Easy, Medium, Architect (fractions down to 1/16 in)
- Train in centimeters or millimeters
- Rounds of 10, scoring by accuracy, streaks, ruler feedback
- No accounts. History and best scores stay in the browser (localStorage)
- English and Russian interface
- A new background photo on every visit, no repeats until all have been shown

## Run

Open `index.html` in a browser, or serve the folder with any static host (GitHub Pages works as is).

## Add photos

Put a JPG into `bg/` named with the next number (`15.jpg`) and change `PHOTOS` in `index.html` to the new count.

## Conversion basis

1 in = 25.4 mm and 1 yd = 0.9144 m exactly (international yard and pound, 1959). Feet, miles and square feet are derived from these.
