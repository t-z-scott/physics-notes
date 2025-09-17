---
{"dg-publish":true,"permalink":"/3-senior-year/semester2/physics/ch-18-electric-forces-and-electric-fields/","tags":["physics"],"noteIcon":"","created":"2024-03-14T14:54:25.747-07:00","updated":"2025-09-17T01:29:39.084-07:00"}
---

# Electricity
The electrical nature of matter is inherent in atomic structure.

**Proton's charge**:    $+1e$ = $+1.602*10^{-19}\ C$ (Coulombs)
**Electron's charge**: $-1e$ = $-1.602*10^{-19}\ C$ 
**Neutron's charge**: none

Removing an electron from a neutral atom (where protons == electrons) yields a positively charged ion, called **electrification**. This results in a *transfer* of charge, not a *creation* of charge.
> Charge can neither be created or destroyed.
> - *Law of Conservation of Electrical Charge* 

---

# Charged Objects and the Electrical Force
> Objects with excess charge will exert forces on each other.
> - *Electrical Force* (like gravitational force)

Opposite charges ==attract==, like charges ==repel==. Attractive vs repulsive.

Newton's 2nd Law: $F=ma$ 
$\therefore$ Electric charges can accelerate forces.

---

# Conductors & Insulators
Conductors and insulators are determined by atomic structure. The valence (outermost) electrons are more weakly bound to the nucleus. They can "break free" and move through the material. These are called **conduction electrons**.

(negative charged obj: $-5 C$) --> ~conductor~ --> (positively charged obj: $+13C$)

Electrons will continue to flow until the charge on each object is ==equal==.
$-5C+13C=8C$, so each object must end up with a charge of $+4C$.

Generally, good thermal conductors are good electrical conductors.
*Conductors* - copper, silver, salt water, gold, iron
*Insulators* - rubber, glass, wood, plastic

---

# Charging an Object
- **_Two ways to charge_** -
	1. **Charging by contact**: touch a positively charged object with a negatively charged object, or vice versa
	2. **Charging by induction**: bring a negatively charged object close to a positively charged object, or vice versa.
		- (does not work for *insulators*, instead forms dipoles) - called **Polarization** 
			- **Dipoles**: two equal but opposite charges separated by some distance $r$.
		- produces *static cling* by forming a slight positive charge

---

# Coulomb's Law
**_Coulomb's Law_**: $F=k\dfrac{q_1*q_2}{r^2}$ (watch the magnitude! don't negate)
**Point charges**: charges that are much smaller than the distance separating them

What if there's *3 charges?* - Then the net force on one charge is the ==vector sum== of the other two forces.

---

# Electric Field
A charge creates an **electric field** that fills all space. Any other charge in that field will feel a force.
- Similarly, in a **gravitational field**, the earth fills all space, and the moon feels the effect of this field.
- *Stationary* charges create electric fields that fill all space. 
- Other (*non-stationary*) charges will feel forces in these electric fields.
$$ \vec{E}=\dfrac{\vec{F}}{q_0} $$
i.e. the electric field is *force* per unit *charge*: $\left[ \dfrac{N}{C} \right]$ 
If we place a charge $q$ in an electric field, it will feel a force given by $\vec{F}=q\vec{E}$. $E$ is created by other charges, <u>not</u> q.
## Electric Field of a Point Charge
**Electric field of a point charge**: $E=k\dfrac{Q}{r^2}$ 
>[!question] What is magnitude of the acceleration of a particle of mass $m$ and charge $+Q$ placed between the plates of a parallel plate capacitor of charge density $\delta$?
>$a=Q\delta/\epsilon_0m$ 

# Electric Field Lines
> Electric fields lines *always* start at and are directed away from positive charges and always end at and are directed toward negative charges.
>1. Lines start from positive charges and end on negative charges.
>2. The electric field vector at some point in space is always ==tangent== to the field line at that point.
>3. The *more lines* you have per unit volume (density), the *stronger* the field.
>4. The *number* of field lines is *proportional to the magnitude* of the charge.

---

## Parallel Plate Capacitor
Consider a metallic plate with a total charge $+q$ distributed uniformly over its surface. If the face of the plate has a surface area $A$, then $\sigma=\dfrac{q}{A}$ where $s$ is the *surface charge density*.

Now let's take two identical plates, one with total charge $+q$ and one with total charge $-q$. So the magnitude of $s$ is $q/A$ for each plate. In between the plates, there's a uniform electric field that points from the positive plate to the negative one. This is a **parallel plate capacitor**.

*Electric field between the plates*: $E=\dfrac{q}{\epsilon_0A}=\dfrac{\sigma}{\epsilon_0}$.
>[!note] The field doesn't depend on the distance from the charged plates. It's uniform, but only near the middle of the plates. This is a *fringe field*.

---

# Electric Field Inside a Conductor
Let's place a bunch of electrons at the center of a solid conducting sphere. *Repulsion spreads electrons out!* So, they move to the surface.
> At equilibrium under electrostatic conditions, any excess charge resides on the surface of the conductor.

The interior of the conductor still has electrons, but they are compensated exactly by the positive changes in the interior, so the interior is <u>electrically neutral</u>. Since the charges are static, the force on them is zero, therefore ==$E=0$==.

This is a static condition - once the surface charges are induced, they don't move.
> This electric field has to be perpendicular to the surface of a conductor.

---

# Electric Flux and Gauss' Law
**Flux**: measure of how much field passes perpendicularly through a surface

$$ \Phi_E=E_{\tau}A=(E\cos\phi)A $$
i.e. \[(electric field)(area)] = $\left[ \dfrac{N*m^2}{C} \right]$ 

We can now use the concept of electric flux and *Gauss' Law* to determine the [[3_senior_year!/semester2/physics/ch. 18 - electric forces and electric fields#Electric Field\|electric field]]. Let's start with a positive [[3_senior_year!/semester2/physics/ch. 18 - electric forces and electric fields#Electric Field of a Point Charge\|point charge]]: $E=k\dfrac{Q}{r^2}$.

To use Gauss' Law, you have to pick a surface. For example, for my point charge $+Q$, I'll enclose it in a spherical radius $r$. This is my surface.
- **Gaussian surface**: surface to which I will apply Gauss' Law
	- Ideally, it'll have high symmetry, like a sphere or cylinder, so it's easy to calculate the area of the surfaces.

>**Gauss' Law**: The electric flux passing through a Gaussian surface is equal to the charge enclosed by the surface divided by $\epsilon_0$.

$$ \Phi_E=\dfrac{Q_{\text{enc}}}{\epsilon_0} \rightarrow \boxed{\sum(E\cos\phi)\Delta A=\dfrac{Q_{\text{enc}}}{\epsilon_0}} $$
The summation here is to sum over the different areas you have in your Gaussian surface.
