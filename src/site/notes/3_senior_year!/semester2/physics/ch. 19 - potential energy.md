---
{"dg-publish":true,"permalink":"/3-senior-year/semester2/physics/ch-19-potential-energy/","tags":["physics"]}
---

# conservative force
1. The work done on an object by a conservative force depends only on the object's initial and final position, and not the path taken.
2. The net work done by a conservative force in moving an object around a closed path is *zero*.

---

# Potential Energy
The [[3_senior_year!/semester2/physics/ch. 18 - electric forces and electric fields#Charged Objects and the Electrical Force\|electric force]], like gravity, is a [[#conservative force]].

Let's place a positive point charge $q$ in a uniform electric field and let it move from the positive plate to the negative plate. ==How much work== is done by the field in moving the charge?
\*Remember, $W=F*d$, where $F$ is the component of the constant force along the direction of the motion. Here, $F=qE$, so $W_{AB}=qE(y_f-y_o)=qE\Delta y=\Delta EPE$.
>The work done == change in electrostatic potential energy!

$\dfrac{W_{AB}}{q}=\boxed{\dfrac{\Delta EPE}{q}}$   The quantity on the right is the potential energy per unit charge. We call this the **electric potential**, $V$.
$$ \boxed{V=\dfrac{EPE}{q}} $$
units - $\left[\dfrac{\text{Energy}}{\text{Charge}}\right]= \left[\dfrac{J}{C}\right]=[V \text{ (volts)}]$ 
## work
1. Work is not a vector, but it can be either positive or negative:
	- *Positive* - Force is in the <u>same</u> direction as the motion.
	- *Negative* - Force is in the <u>opposite</u> direction as the motion.
2. If positive work is done on an object, the object *speeds up*.
3. If negative work is done on an object, the object *slows down*.

---

# Electric Potential Difference
We can determine the value of the potential at different points in space. For example, what is the difference in electrostatic potential between two points, A and B, in an [[3_senior_year!/semester2/physics/ch. 18 - electric forces and electric fields#Electric Field\|electric field]]?
![electric potential.png|250](/img/user/0_attachments/electric%20potential.png) 
$V_B-V_A=\dfrac{EPE_B}{q}-\dfrac{EPE_A}{q}=\dfrac{-W_{AB}}{q}$, so $\boxed{\Delta V=V_B-V_A=\dfrac{-W_{AB}}{q}}$.

Let's say the charge at point A is positive. If I release it, it'll move down towards B. Since the force is down and the motion is down, ==positive work is done== on the charge, so $W_{AB}$ is positive. This means $V_B-V_A$ is negative, or $V_A>V_B$. Point A is at a higher potential than point B.

- Positive charges, starting from rest, will move away from high potential regions and move toward low potential regions.
- Negative charges, starting from rest, will move away from low potential regions and move toward high potential regions.

---

## voltage
$1.5V=1.5\dfrac{J}{C} \rightarrow$ The battery supplies 1.5 Joules of energy for every Coulomb of charge.
## energy
If we accelerate an electron form rest through a potential difference of 1 Volt, then it would gain *1 electron volt* ($eV$) of **kinetic energy**. Energy is usually expressed in Joules: $\boxed{1eV=1.602*10^{-19}J}$ 
## energy conversion
Just like in a gravitational field, in an [[3_senior_year!/semester2/physics/ch. 18 - electric forces and electric fields#Electric Field\|electric field]], potential energy ($PE$) can be converted into kinetic energy ($KE$). For example, if we bring a positive charge close to a fixed, positive point charge, the repulsive force on it gets bigger and bigger. We have to do [[#work]] on the charge to move it closer, which increases its $PE$. When we release the charge, the stored electric potential energy ($EPE$) is converted into $KE$!
>[!note] The total mechanical energy of a system must be conserved.

$$ E_{\text{Tot}}=\frac{1}{2}mv^2+\frac{1}{2}I\omega^2+mgh+\frac{1}{2}kx^2+EPE $$
If the work done by non[[#conservative force]]s is *zero*, then $\boxed{E_{\text{Tot}_f}}=E_{\text{Tot}_o}$.
### types of kinetic energy
- $\frac{1}{2} mv^2$: linear or *translational* 
- $\frac{1}{2}I\omega^2$: rotational
- $mgh$: gravitational
- $\frac{1}{2}kx^2$: elastic
- $EPE$: electrostatic

---

# Electric Potential of a Point Charge
An electric [[#Potential Energy|potential]] exists around charges. What is the form of the potential for a point charge?

If we place a positive test charge near a positive fixed point charge, the [[3_senior_year!/semester2/physics/ch. 18 - electric forces and electric fields#Electric Field\|electric field]] created by the point charge does [[#work]] on the test charge and moves it to the *right*.

The work done on the field when moving the charge is $W_{AB}=k\dfrac{qQ}{r_A}-k\dfrac{qQ}{r_B}$.
Electric potential due to a point charge: $V=k\dfrac{Q}{r}$.

---

# Equipotential Surfaces
The [[#Electric Potential of a Point Charge]] is $V=k\dfrac{Q}{r}$. This means the potential is the same in every direction around the point charge at a distance $r$ away. This forms a spherical shell of radius $r$ around the charge.

Thus, the electric potential is the same everywhere on this spherical surface ($S_A$) - called an **equipotential surface**.
>[!note] The [[3_senior_year!/semester2/physics/ch. 18 - electric forces and electric fields#Electric Field Lines\|electric field lines]] are *perpendicular* to the equipotential surface.

In another equipotential surface which is further away but still around the point charge ($S_B$), there is a lower potential than there is in $S_A$. Thus, electric field lines point in the direction of decreasing potential (high --> low potential). Therefore, ==positive charges move in the same direction as the electric field points==, and negative charges move in the opposite direction of the field.
## work done on equipotential surfaces
The net electric force does *no* work as a charge moves on a equipotential surface. Why? $V_B-V_A=\dfrac{-W_{AB}}{q}$. But if we're on an equipotential surface, then $V_A=V_B$, and $W_{AB}=0$.

(In other words, in order for the charge to feel a force along an equipotential surface, there must be a component of the field along the surface, but $E$ is perpendicular to the surface everywhere.)

---

# Parallel Plate Capacitor
The positive plate is at a potential of $+9\ V$ and the negative plate is at $0\ V$. The [[#Equipotential Surfaces]] between the planes look like a parallel set of plates.

Let the plates be separated by a distance $\Delta s$. The [[3_senior_year!/semester2/physics/ch. 18 - electric forces and electric fields#Electric Field\|electric field]] is then $\dfrac{[\text{Change in voltage}]}{[\text{Change in distance}]}\rightarrow E=\dfrac{\Delta V}{\Delta s}$ (units: $\dfrac{V}{m}$). This is called the **electric field gradient**.

---

# Capacitor
We have two oppositely charged conducting plate separated by some small distance. We charge the plates by connecting them to a battery. The higher the voltage on our battery, the more charge we can put on each plate. Thus, $Q \varpropto V$.

$\boxed{Q=CV}$. $C$ is the **capacitance**.
$C=\dfrac{Q}{V} \rightarrow \dfrac{[\text{Charge}]}{[\text{Voltage}]}=\left[ \dfrac{C}{V} \right]=[\text{Farad}]=[F]$ 

\*A farad is a very large capacitance. We often use microfarads ($\mu f$: $1*10^{-6}\ F$) and picofarads ($pf$: $1*10^{-12}\ F$).

==The larger the capacitance, the more charge it will hold!== 
## Dielectrics
We can fill the space between the plates with some insulating material, say air, oil, paper, rubber, plastic, etc. This material is called a **dielectric**.

Since the dielectric is an insulator, the charges in it aren't free to move, but they can separate slightly within each atom. Each one of these atoms now produces a small internal [[3_senior_year!/semester2/physics/ch. 18 - electric forces and electric fields#Electric Field\|electric field]] which points in the *opposite direction* to the field between the plates.
>Thus, the net electric field between the plates is reduced by the dielectric.

The reduction of the field: $\boxed{\kappa=\dfrac{E_o}{E}}$.
$E_o=$ field without the dielectric
$E=$ field with the dielectric
$\kappa=$ dielectric constant (must be greater than 1, unitless)

| material | $\kappa$ |
| ---- | ---- |
| vacuum | 1 |
| air | 1.00054 |
| water | 80.4 |

==The larger $\kappa$ is, the more it reduces the field between the plates.== 

Let's say the plates have a surface area $A$ and are separated by a distance $d$.
$E=\dfrac{1}{\kappa}E_o=\dfrac{V}{d} \rightarrow E_o=\dfrac{\kappa V}{d}=\dfrac{\sigma}{\epsilon_o}=\dfrac{q}{\epsilon_o A} \rightarrow \boxed{q=\left( \dfrac{\epsilon_o A \kappa}{d}V \right)}$, but $q=CV$, so $\boxed{C=\dfrac{\epsilon_o A \kappa}{d}}$.

### Capacitors store charge - what about energy?
$$ EPE_{\text{Stored}}=\frac{1}{2}qV=\frac{1}{2}CV^2 $$
$\boxed{\dfrac{EPE}{\text{Vol}}=\text{Energy Density}=\frac{1}{2}\kappa \epsilon_o E^2}$ 
units: $\left[ \dfrac{\text{Energy}}{\text{Volume}} \right]=\left[ \dfrac{J}{m^3} \right]$ 

This expression holds true for any electric fields, not just for capacitors.