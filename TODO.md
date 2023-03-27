#  Add Ohm's Law calculator with unit conversions [#643][issue]
There are MANY [online calculators for Ohm's Law][calculator1]. The formulas are simple. The units are simple. But the UIs are clunky, and the UX is frustrating. Adding this calculator in FYN would create the first `oninput` (aka: no "click calculate", and certainly no "page reload") tool of its kind.

## Formulas
- `V = I x R`
- `I = V / R`
- `R = V / I`
- `P = V x I`
- `V = P / A`
- `A = P / V`

## Unit Modifiers
- `M`: Mega
  - `1`**M**<sub>*Unit*</sub> =`1,000,000` x `1`<sub>*Unit*</sub>
  - `1`**M**<sub>*Unit*</sub> =`1,000` x `1`**k**<sub>*Unit*</sub>
- `k`: kilo
  - `1`**k**<sub>*Unit*</sub> =`1,000` x `1`<sub>*Unit*</sub>
  - `1`**k**<sub>*Unit*</sub> =`0.001` x `1`**M**<sub>*Unit*</sub>
- `m`: milli
  - `1`**m**<sub>*Unit*</sub> =`0.001` x `1`<sub>*Unit*</sub>
  - `1`**m**<sub>*Unit*</sub> =`1,000` x `1`**µ**<sub>*Unit*</sub>
- `µ`: micro
  - `1`**µ**<sub>*Unit*</sub> =`0.000001` x `1`<sub>*Unit*</sub>
  - `1`**µ**<sub>*Unit*</sub> =`0.001` x `1`**m**<sub>*Unit*</sub>

## Units
- `V`: Voltage measured in Volts symbolized as V
  - `1`mV = `0.001`V
    - `1`V = `1000`mV
  - `1`µV = `0.000001`V
    - `1`µV = `1000`mV
    - `1`V = `1000000`µV
- `I`: Current measured in Amperes symbolized as A
  - `1`mA = `0.001`A
    - `1`A = `1000`mA
  - `1`µA = `0.000001`A
    - `1`µA = `1000`mA
    - `1`A = `1000000`µA
- `R`: Resistance measured in Ohms symbolized as Ω
  - `1`kΩ = `1000`Ω
    - `1`Ω = `0.001`kΩ
  - `1`MΩ = `1000000`Ω
    - `1`kΩ = `0.001`MΩ
    - `1`Ω = `0.000001`MΩ
- `P`: Power measured in Watts symbolized as W



## Visualized like so:
![The Ohm's Law Triangle][triangle]
![The Ohm's Law Wheel][wheel]
![The Power Formula Triangle][power]

[calculator1]: https://www.inchcalculator.com/ohms-law-calculator/
[triangle]: https://www.inchcalculator.com/wp-content/uploads/2022/09/ohms-law-triangle.png
[wheel]: https://www.inchcalculator.com/wp-content/uploads/2022/09/ohms-law-wheel.png
[power]: https://www.inchcalculator.com/wp-content/uploads/2022/09/power-formulas.png
[issue]: https://github.com/Srijita-Mandal/fix-your-nums/issues/643
