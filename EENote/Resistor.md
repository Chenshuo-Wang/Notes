### Ohm's Law
$$R=V/I$$
### Resistance of a Wire
$$R = \rho \frac{L}{A}$$
# Resistor and Circuit Formulas Cheat Sheet

## 1. Basic Definitions

### Ohm's Law

The fundamental relationship between voltage, current, and resistance.

$$V = I \cdot R$$
### Resistance of a Wire

Resistance depends on the material properties and geometry of the conductor.

$$R = \rho \frac{L}{A}$$

## 2. Conductance & Conductivity

### Conductance ($G$)

Conductance is the reciprocal of resistance, measuring how easily electricity flows.

$$G = \frac{1}{R} = \frac{I}{V}$$
### Conductivity ($\sigma$)

Conductivity is the reciprocal of resistivity.

$$\sigma = \frac{1}{\rho}$$

### Ohm's Law (Point Form)

Relating current density to electric field.

$$J = \sigma E = \frac{E}{\rho}$$
## 3. Resistor Combinations

### Series Circuits

In a series circuit, the total resistance is the sum of individual resistances.

$$R_{\text{eq}} = R_1 + R_2 + \dots + R_n = \sum_{i=1}^{n} R_i$$

- **Key Feature:** Current is the same through all components ($I = I_1 = I_2$).
    

### Parallel Circuits

In a parallel circuit, the reciprocal of the total resistance is the sum of the reciprocals of the individual resistances.

$$\frac{1}{R_{\text{eq}}} = \frac{1}{R_1} + \frac{1}{R_2} + \dots + \frac{1}{R_n} = \sum_{i=1}^{n} \frac{1}{R_i}$$

- **Key Feature:** Voltage is the same across all components ($V = V_1 = V_2$).
    

#### Special Case: Two Resistors in Parallel

$$R_{\text{eq}} = \frac{R_1 R_2}{R_1 + R_2}$$

#### Special Case: $n$ Identical Resistors

If $n$ resistors all have the same value $R$:

$$R_{\text{eq}} = \frac{R}{n}$$

## 4. Power & Energy

### Electric Power ($P$)

The rate at which electrical energy is converted into heat or other forms.

$$P = V \cdot I = I^2 \cdot R = \frac{V^2}{R}$$

- Unit: Watts [W]
    

## 5. Temperature Dependence

Resistance generally increases with temperature for conductors.

$$R = R_0 [1 + \alpha(T - T_0)]$$

- $R$: Resistance at temperature $T$
    
- $R_0$: Resistance at reference temperature $T_0$ (usually $20^\circ\text{C}$)
    
- $\alpha$: Temperature Coefficient of Resistance [$\text{K}^{-1}$ or $^\circ\text{C}^{-1}$]
    
- $T$: Current temperature
    
- $T_0$: Reference temperature
    

## 6. Divider Rules

### Voltage Divider Rule (Series)

Calculates the voltage $V_x$ across a specific resistor $R_x$ in a series circuit.

$$V_x = V_{\text{total}} \cdot \frac{R_x}{R_{\text{total}}}$$

For two resistors $R_1$ and $R_2$, the voltage across $R_2$ is:

$$V_2 = V_{\text{in}} \cdot \frac{R_2}{R_1 + R_2}$$

### Current Divider Rule (Parallel)

Calculates the current $I_x$ flowing through a specific resistor in a parallel circuit.

For two resistors $R_1$ and $R_2$ in parallel, the current through $R_1$ is:

$$I_1 = I_{\text{total}} \cdot \frac{R_2}{R_1 + R_2}$$

- **Note:** The numerator contains the _opposite_ resistor ($R_2$).