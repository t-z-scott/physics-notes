---
{"dg-publish":true,"permalink":"/3-senior-year/semester2/physics/ch-20-electric-circuits/","tags":["physics"],"noteIcon":"","created":"2025-10-23T00:28:51.355-07:00","updated":"2025-09-20T17:43:04.000-07:00"}
---

# Electromotive Force
Electrical energy is transferred from a power source, such as a battery, to a device, such as a light bulb. Inside a battery, a chemical reaction separates positive and negative charges, creating a [[3_senior_year!/semester2/physics/ch. 19 - potential energy#Electric Potential Difference\|potential difference]]. This potential difference is equivalent to the battery's voltage, or $emf\ (\epsilon)$ (**electromotive force**, which is a potential, not a force).

Because of the $emf$ on the battery, an [[3_senior_year!/semester2/physics/ch. 18 - electric forces and electric fields#Electric Field\|electric field]] is produced within and parallel to the wires. This creates a force on the charges in the wire and moves them around the circuit. This *flow of charge* in a conductor is called the **electrical current** ($I$).

Electrical current: $\boxed{I=\dfrac{\Delta q}{\Delta t}}$ 
- units - $\left[ \dfrac{\text{Charge}}{\text{time}} \right]=\left[ \dfrac{C}{s} \right]=[\text{Ampere}]=[A]$ 

If the current only moves in ==one direction==, like with batteries, it's called **direct current** ($DC$).
If the current moves in ==both directions==, like in a house, it's called **alternating current** ($AC$).

Electric current is due to the flow of moving electrons, but we will use the *positive conventional current* in circuit diagrams. $I$ shows the direction of "positive" charge flow from high to low potential.

---

# Ohm's Law
The battery pushing the current acts like a water pump pushing the water through a pipe. The voltage of the battery is like pump pressure - the larger the voltage, the greater the current. $V \varpropto I$.

Ohm's Law: $\boxed{V=IR}$ 
- $R=$ electrical resistance
- units - $R=\left[ \dfrac{\text{Volts}}{\text{Amp}} \right]=\left[ \dfrac{V}{A} \right]=[\text{Ohm}]=[\ohm]$ 

**Resistor**: component of an electrical circuit that offers resistance to the flow of electric current.

---

# Resistivity
The electrical [[3_senior_year!/semester2/physics/ch. 20 - electric circuits#Ohm's Law\|resistance]] of a conductor depends on its shape. Longer wires have more resistance; fatter wires have less. Thus, $R \varpropto \frac{L}{A}$.

Resistivity: $\boxed{R=\rho \dfrac{L}{A}}$ 
- $\rho=$ **electrical resistivity** (proportionality constant)
- units - $\rho=R\dfrac{A}{L} \left[ \dfrac{\ohm*m^2}{m} \right] \rightarrow [\ohm*m]$ 

Resistivity is an intrinsic property of materials, like density. Every piece of copper has the *same resistivity*, but the resistance of any one piece depends on its size and shape.
## Temperature Dependence of Resistivity
The resistance of most materials changes with temperature. For good conductors (metals), the resistance *decreases* with decreasing temperature. For poor conductors (insulators), the resistance *increases* with decreasing temperature.

Resistance: $\boxed{R=R_0[1+\alpha(T-T_0)]}$ 
- $R=$ resistance at temperature $T$ 
- $R_0=$ resistance at temperature $T_0$ 
- $\alpha=$ temperature coefficient of resistivity ($\alpha>0$ for metals // $\alpha<0$ for insulators)

---

# Electrical Power
Power: $P=IV=I^2R=\dfrac{V^2}{R}$.
## Electrical Energy
Work and energy have the same units (Joules). So, $\boxed{\text{Energy}=\text{Power}*\text{Time}}$. Electrical companies measure your monthly energy in this way, using *kilowatt\*hours* ($kWh$).

$$ \boxed{1\ kWh=3.6*10^6\ J} $$

## Power Transmission
Electrical power is transmitted at high voltages instead of high currents, because *thermal losses* (losing electrical power by converting it to heat) is proportional to $I^2$ for a given voltage and proportional to $V$.

$\boxed{P \varpropto I^2}$     //    $\boxed{P \varpropto V}$ 

---

# Alternating Current
Circuits where the current periodically switches direction use **alternating current** (**AC**). The most common type of AC current is one that varies sinusoidally with time.

Voltage in an AC circuit as a function of time: $\boxed{V=V_0\sin 2\pi ft=V-0 \sin \omega t}$.
- $V_0=$ peak (max) voltage
- $f=$ frequency (Hz)

Since the voltage in an AC circuit oscillates in time, so does the current.
$I=\dfrac{V_0}{R}\sin2\pi ft=I_0 \sin2\pi ft$, where $I_0=V_0/R$.
## Power in an AC Circuit
Just like in a DC circuit, the power is $P=IV$, but since both the current and the voltage fluctuate in time, so does the power.
$P=IV=(I_0\sin2\pi ft)(V_0\sin2\pi ft)=I_0V_0\sin^22\pi ft$.

Since the power fluctuates in time, we often just reference the *average power* in the circuit.
$\bar{P}=\frac{1}{2}I_0V_0$.
We can rewrite the equation for this as:
$$ \bar{P}=\left(\dfrac{I_0}{\sqrt{2}}\right) \left(\dfrac{V_0}{\sqrt{2}}\right)=I_{\text{ms}}V_{\text{ms}} $$
Unless otherwise stated, the voltage in AC circuits will represent the rms voltage, and the power will represent the average power.
$$ \bar{P}=I_{\text{rms}}V_{\text{rms}}=I_{\text{rms}}^2R=\dfrac{V_{\text{rms}}^2}{R} $$

---

# Series Circuits
A **series circuit** is when the ==same current== runs through two components connected in series. The *voltage drop* ([[3_senior_year!/semester2/physics/ch. 19 - potential energy#Electric Potential Difference\|potential difference]]) across resistors is different.

Net resistance (equivalent resistance): $\boxed{R_{\text{eq}}=R_1+R_2+\dots+R_n}$ 

---

# Parallel Circuits
A **parallel circuit** is when the ==current is split== across different wires. For this type of circuit, the *voltage drop* ([[3_senior_year!/semester2/physics/ch. 19 - potential energy#Electric Potential Difference\|potential difference]]) is the same.

Net resistance (equivalent resistance): $\boxed{ \dfrac{1}{R_{\text{eq}}}=\dfrac{1}{R_1}+\dfrac{1}{R_2}+\dots+\dfrac{1}{R_n} }$ 

---

# Series and Parallel Circuits
If resistors are hooked up both in [[#Series Circuits|series]] and in [[#Parallel Circuits|parallel]] in the same circuit, you must combine resistors to find $R_{\text{eq}}$.

---

# Internal Resistance
Batteries and generators have some resistance as well. This is called **internal resistance** ($r$). In batteries it's due to the chemicals, and in generators it's due to the wire resistance. The voltage across the battery (terminal voltage, $V_T$) is less than the full voltage $V$, since some is lost across $r$.

Terminal voltage: $\boxed{V_T=V-V_r}$ 
## Kirchhoff's Rules
In many circuits, applying the [[#Series Circuits|series]] or [[#Parallel Circuits|parallel]] methods is not sufficient to analyze them. There are two other rules we can use called **Kirchhoff's Rules**.
### 1. Junction Rule
Current into a junction has to equal current out, based on conservation of charge.
### 2. Loop Rule
Around any closed circuit loop, the sum of the [[3_senior_year!/semester2/physics/ch. 19 - potential energy#Electric Potential Difference\|potential difference]] has to equal the sum of the potential rises. (This is based on conservation of energy.)

---

# Measuring Voltages and Currents
Currents and voltages can be measured with devices called **ammeters** and **voltmeters**, respectively. Both these devices rely on the DC *galvanometer*. 
## ammeter resistance
(A circuit must be "broken" to use an ammeter - it needs to be inserted inside the circuit.)

Inside an ammeter, a small resistor ($r_s$) is wired in parallel with the galvanometer. Almost all of the current passes through the shunt resistor, so the ammeter has very little effect on the circuit, i.e. ==nearly zero resistance==.
## Voltmeter
**Voltmeter**: measures the [[3_senior_year!/semester2/physics/ch. 19 - potential energy#Electric Potential Difference\|potential difference]] between two points in the circuit, i.e. across a resistor. It doesn't have to be inserted in the circuit. A voltmeter has a *high resistance*, so ==very little current== actually flows through the voltmeter.

---

# Capacitors in Series and Parallel
Capacitors connected in [[#Parallel Circuits|parallel]]: $\boxed{ C_{\text{eq}}=C_1+C_2+\dots+C_n }$ 
Capacitors connected in [[#Series Circuits|series]]: $\boxed{ \dfrac{1}{C_{\text{eq}}}=\dfrac{1}{C_1}+\dfrac{1}{C_2}+\dots+\dfrac{1}{C_n} }$ 

---

# RC Circuits
**RC Circuit**: a resistor is in [[3_senior_year!/semester2/physics/ch. 20 - electric circuits#Series Circuits\|series]] with a [[3_senior_year!/semester2/physics/ch. 20 - electric circuits#Capacitors in Series and Parallel\|capacitor]]. When the switch closes, charge builds up gradually on the capacitor plates as the current flows and approaches an equilibrium value ($Q_0$). If the capacitor is initially uncharged at $t=0$, then the charge on the capacitor at some later time $t$ is $\boxed{Q=Q_0\left[1-e^{-t/RC}\right]}$.

If $t=0$, then $Q=Q_0\left[1-e^{0/RC}\right]=Q_0[1-1]=0$. We can get the voltage across the capacitor at any time by dividing by the charge by the capacitance, since $V=Q/C$: $\boxed{V=V_0\left[1-e^{-t/RC}\right]}$.
## RC
units - $[\text{Resistance}*\text{Capacitance}]=[\ohm*F]=\left[ \left(\dfrac{V*s}{Q}\right) \left(\dfrac{Q}{V}\right) \right]=[s]$ 
$RC$ has the units of time, and the product is known as the **time constant** of the circuit. $\boxed{\tau=RC}$ 

Charging equation: $\boxed{Q=Q_0\left[1-e^{-t/\tau}\right]}$ 
## Discharging a Capacitor in an RC Circuit
A capacitor is charged all the way to $Q_0$ and then **discharged** through the resistor. When we close the switch, a current flows through the resistor and charge dissipates from the capacitor plates.

Discharging equation: $\boxed{Q=Q_0e^{-t/\tau}}$. At $t=0$, $Q=Q_0e^{0/\tau}=Q_0$.
