# Ohm's Law Calculator

This is a simple Python program that calculates Voltage (**V**) using Ohm’s Law.

## Formula

V = I * R

Where:
- **V** = Voltage (in volts)
- **I** = Current (in amperes)
- **R** = Resistance (in ohms)

## Python Code
```python
# Author: Ntaganira Habimana Happy (GitHub: Habimana06)
# Ohm's Law Calculator: V = I * R

# Get user input for current (I) and resistance (R)
I = float(input("Enter current (in amperes): "))
R = float(input("Enter resistance (in ohms): "))

# Calculate voltage
V = I * R

# Display the result
print(f"Voltage (V) = {V} volts")
