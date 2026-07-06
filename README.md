# 132kV H Type Capacitor Bank Unbalanced Current Optimization

Static web tool for calculating and reducing unbalanced current in a 132kV H type capacitor bank.

## Configuration

- 96 capacitors total
- Four H bridge arms: C1 top left, C2 bottom left, C3 top right, C4 bottom right
- Capacitors are numbered 1-96: C1 is 1-24, C2 is 25-48, C3 is 49-72, and C4 is 73-96
- Each arm has 24 capacitors
- Each parallel group has 4 capacitors
- Each arm has 6 parallel groups in series
- Relay / CT branch is calculated using the approximate short-circuit model

## Use

Open `index.html` in a browser, enter the measured capacitance values, choose the number of swap pairs, and run `Optimize swaps`.
