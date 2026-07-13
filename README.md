# 132kV H Type Capacitor Bank Unbalanced Current Optimization

Static web tool for calculating and reducing unbalanced current in a 132kV H type capacitor bank.

## Configuration

- 64 capacitors total
- Four H bridge arms: C1 front top, C2 front bottom, C3 rear top, C4 rear bottom
- Capacitors are numbered 1-64: C1 is 1-16, C2 is 17-32, C3 is 33-48, and C4 is 49-64
- Each arm has 16 capacitors
- Each parallel group has 4 capacitors
- Each arm has 4 parallel groups in series
- Relay / CT branch is calculated using the approximate short-circuit model

## Use

Open `index.html` in a browser, enter the measured capacitance values, choose the number of swap pairs, and run `Optimize swaps`.
