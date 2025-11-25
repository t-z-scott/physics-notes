---
{"dg-publish":true,"permalink":"/3-senior-year/semester2/physics/ch-21-magnetic-fields/","tags":["physics"],"noteIcon":"","created":"2025-10-23T00:28:51.342-07:00","updated":"2025-09-20T17:48:58.000-07:00"}
---

# Magnetic Fields
Like charged object, magnetized objects can exert forces on each other - repulsive or attractive. A magnet has 2 poles: North and South.
>Like poles repel and opposite poles attract.

(Magnetic poles don't exist in a single pole - or a *magnetic monopole*.)

Electric charges produce electric fields and *magnets* produce magnetic fields.

A compass, like a positive test charge, can be used to determine what [[3_senior_year!/semester2/physics/ch. 18 - electric forces and electric fields#Electric Field Lines\|electric field line]]s look like around a magnet. The compass's North will always point toward a magnetic South. (Earth's magnetic south is next to its geographic North Pole, and its magnetic north is next to its geographic South Pole.)
## Properties of Magnetic Field Lines
1. The magnetic field lines will always point from a magnet's North pole to its South.
2. The magnetic field at any point in space is tangent to the field line at that point.
3. The rules of electric field lines still apply - closer lines means stronger field.
4. The field lines must form a closed loop (they don't start or stop in mid space).

---

# Magnetic Force
Charges feel forces in electric fields. Magnets feel forces in [[3_senior_year!/semester2/physics/ch. 21 - magnetic fields#Magnetic Fields\|magnetic fields]] under certain conditions:
1. The charge must be moving, i.e. it has a nonzero velocity.
2. The charge's velocity must have a component that is perpendicular to the magnetic field.

Thus, if a charge is moving in a magnetic field, but it moves along the same direction as the field (parallel to it), there is *no force*.

---

Force on a moving charge in a magnetic field: $\boxed{F=qvB\sin \theta}$ 
- $B=$ magnetic field
- $\theta=$ angle between $B$ and $v$ 
- units - $B=\left[ \dfrac{\text{Force}}{\text{Charge }* \text{ Velocity}} \right]=\left[ \dfrac{N*s}{C*m} \right]=[\text{Tesla}]=[T]$ 
We also use another unit of magnetic field, the *gauss*: $1 \text{ gauss }=1*10^{-4}\ T$. Earth's magnetic field is $\approx 0.5 \text{ gauss}$.
## direction of the force on a charged particle in a magnetic field (RHR-1)
![direction of magnetic force.png](/img/user/0_attachments/direction%20of%20magnetic%20force.png) 
**Right Hand Rule 1**: Point the fingers of your right hand in the direction of the magnetic field if the charge is ==positive==. If it's ==negative==, do the same, but reverse the direction of the force at the end.

---

# Motion of a charged particle in electric and magnetic fields
The force on a charged particle particle in an [[3_senior_year!/semester2/physics/ch. 18 - electric forces and electric fields#Electric Field\|electric field]] is directed along the field, either parallel or antiparallel - $F=qE$. The positively charged particle feels a force upward due to $E$.

The force on a charged particle in a [[3_senior_year!/semester2/physics/ch. 21 - magnetic fields#Magnetic Fields\|magnetic field]] is always perpendicular to the velocity and field - $F=qvB\sin \theta$.

By adjusting the magnitude of $E$ and $B$, I can find a combination where $F_M=F_E$, such that the net force on the charge is zero: the moves through the field with no deflection at all. This is a **velocity selector** - $\boxed{v=E/B}$.

---

## Work done by the fields
$W=F*d$, where $F$ is along the direction of motion and it's constant over the displacement.

*Electric case*: when the positive charge enters the field, the force is downward towards the negatively charged plate. The charge accelerates, and its velocity increases, so ==positive work== is done on the charge.

*Magnetic case*:
- The force is always at right angles to the velocity, so it's never along the direction of the motion (circular), so the magnetic force does ==no work== on the particle.
- The particle's speed is constant, but its direction changes. (Magnetic fields can not speed up or slow down charged particles, only change their direction.)
- Whenever we have circular motion, we can identify a *centripetal force*, which is the vector sum of the radial forces. Here, it's only due to the magnetic force.

radius: $\boxed{r=\dfrac{mv}{qB}}$ 
>The larger $B$ is, the tighter the circular path (smaller $r$).

---

# The Mass Spectrometer
Ionized particles are accelerated by a potential difference $V$. By conservation of energy, we know that this potential energy goes into the kinetic energy of the particle - $\Delta KE=\Delta EPE \rightarrow \frac{1}{2}mv^2=qV$. Solve this for speed:
$$ v=\sqrt{\dfrac{2qV}{m}} $$
This is the speed that the particle has when it enters the magnetic field. It then gets bent into a circular path whose radius is given by the [[3_senior_year!/semester2/physics/ch. 21 - magnetic fields#Work done by the fields\|previous equation]].

Therefore, the mass of the deflected ion is $\boxed{m=\left( \dfrac{qr^2}{2V} \right)B^2}$. By changing $B$, we can select a certain mass for a given radius.

---

# Force on a Current
Moving charges in a magnetic field experience a force. A current is just a collection of moving charges, so a current will also feel a force in a magnetic field. [[3_senior_year!/semester2/physics/ch. 21 - magnetic fields#direction of the force on a charged particle in a magnetic field (RHR-1)\|RHR-1]] is used to find the direction of the force on a charge moving in a magnetic field, or to find the direction of the force on a current carrying wire in a magnetic field.

Force on a current: $\boxed{F=ILB\sin\theta}$.
- $\theta=$ angle between the current and the magnetic field
- $I=$ current
- $L=$ length of the wire

The force is *maximum* when the field is perpendicular to the wire.

---

# Torque on a Wire Loop
Let's put a closed loop of wire carrying a current in a [[3_senior_year!/semester2/physics/ch. 21 - magnetic fields#Magnetic Fields\|magnetic field]]. We'll label each side of the loop 1 through 4. We can use $F=ILB\sin\theta$ ([[3_senior_year!/semester2/physics/ch. 21 - magnetic fields#Force on a Current\|force on a current]]) to calculate the force on each segment of the loop.
![wire loop.png|250](/img/user/0_attachments/wire%20loop.png)
Note: $F_2=F_4=0$, since $\theta=0$ for those segments.
By [[3_senior_year!/semester2/physics/ch. 21 - magnetic fields#direction of the force on a charged particle in a magnetic field (RHR-1)\|RHR-1]], $F_1$ points out of the screen and $F_3$ points into the screen. Thus, the loop wants to rotate.

Torque on a wire loop: $\tau_{\text{Net}}=NIAB\sin\phi$ 
- $N=$ the number of loops of wire
- $I=$ current
- $A=$ cross-sectional area of the loop
- $B=$ [[3_senior_year!/semester2/physics/ch. 21 - magnetic fields#Magnetic Fields\|magnetic field]] 
- $\phi=$ the angle between the magnetic field and the <u>normal</u> to the loop's surface

The net torque depends on the quantity $NIA$, which is the **magnetic moment** of the loop.
$\tau_{\text{Net}}=NIAB\sin\phi=\mu B\sin\phi$, where $\boxed{\mu=NIA}$ is the magnetic moment.
- units - $[\text{Current}*\text{Area}]=[A*m^2]$ 

## DC Electric Motors
![dc electric motor.png](/img/user/0_attachments/dc%20electric%20motor.png) 

---

# Magnetic Fields Produced by Currents
Moving charges experience a force in [[3_senior_year!/semester2/physics/ch. 21 - magnetic fields#Magnetic Fields\|magnetic fields]]. Currents also [[3_senior_year!/semester2/physics/ch. 21 - magnetic fields#Force on a Current\|feel a force]] in a magnetic field.
>Electric currents create magnetic fields.
>Or: moving charges create magnetic fields.

==Stationary charges== create [[3_senior_year!/semester2/physics/ch. 18 - electric forces and electric fields#Electric Field\|electric fields]]. Moving charges with a *constant $v$* create magnetic fields.

## magnetic field lines around a long, straight, current-carrying wire
The current produces concentric circular loops of magnetic field around the wire.
>[!note]
>The magnetic field vector at any point is always **tangent** to the field line.

### direction of magnetic field lines around a wire (RHR-2)
**Right Hand Rule 2**: Point the thumb of your right hand in the direction of the current, and your fingers curls around the wire showing the direction of the field lines.

Magnetic field created by a long straight wire: $\boxed{B=\dfrac{\mu_0I}{2\pi r}}$ 
- $\mu_0=$ permeability of free space: $\boxed{4\pi*10^{-7}\dfrac{T*m}{A}}$  

## direction of a magnetic field around a closed loop of current-carrying wire (RHR-3)
![magnetic field around a loop.png|200](/img/user/0_attachments/magnetic%20field%20around%20a%20loop.png) 

Magnetic field at the center of the loop: $\boxed{B=N\dfrac{\mu_0I}{2R}}$ 

**Right Hand Rule 3**: Curl your fingers of your right hand along the direction of the current, and your thumb point in the direction of the magnetic field.

---

## solenoid
**Solenoid**: current-carrying wire bent into a helix (*coil*)
- Use [[3_senior_year!/semester2/physics/ch. 21 - magnetic fields#direction of a magnetic field around a closed loop of current-carrying wire (RHR-3)\|RHR-3]] to find the direction of the [[3_senior_year!/semester2/physics/ch. 21 - magnetic fields#Magnetic Fields\|magnetic field]].

Magnetic field inside a solenoid: $\boxed{B=\mu_0In}$ 
- $n=N/L=$ number of turns per unit length (turn density)
>[!note]
>The field line from a solenoid look just like the field lines created by a bar magnet.
>![solenoid magnetic field.png|300](/img/user/0_attachments/solenoid%20magnetic%20field.png) 

Field lines emerge from a North pole and converge on a South pole. This is called an **electromagnet**. We can switch the direction of the field by switching the direction of the current.