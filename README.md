# Dice Roll Display (Archived)

This project simulates a digital dice value checker using Logisim. It includes a simple 4-bit input and a logic-based comparator that detects whether the input value is **greater than 10**.

##  Features

- 4-bit input representing dice value (0–15)
- Logic gate-based comparator (`larger_10_comparator`)
- Output signal indicates whether input > 10
- Modular circuit design in Logisim Evolution

## How It Works

- A 4-bit binary input (e.g., from switches) simulates a dice roll.
- The value is passed to a subcircuit that uses AND, OR, and NOT gates to detect if it's greater than binary `1010` (decimal 10).
- The result is shown as a single-bit output (`is_large`), which can be used to trigger a display or flag.

## Running the Project

1. Open the `.circ` file using [Logisim Evolution](https://github.com/logisim-evolution/logisim-evolution/releases).
2. Simulate by toggling the input pins (dice value).
3. Observe the output — it lights up when the value is greater than 10.
