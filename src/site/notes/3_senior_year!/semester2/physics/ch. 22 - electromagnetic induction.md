---
{"dg-publish":true,"permalink":"/3-senior-year/semester2/physics/ch-22-electromagnetic-induction/","tags":["physics"]}
---

# Induced emf
Electric currents (moving charges) create [[3_senior_year!/semester2/physics/ch. 21 - magnetic fields#Magnetic Fields\|magnetic fields]]. Magnetic fields can create currents, but it has to be a *changing* magnetic field.
>[!note] A current would also be produced if you held the magnet stationary and moved the coil.

**Induced current**: current that is produced in the coil
The coil then acts like a battery, or a source of $\text{emf}$. This emf is an **induced emf**.
- The current and emf (voltage) are induced, because they are due to the charging magnetic field.

Another way to induce an emf and produce a current in the coil is to enlarge or shrink the *area of the coil*. As long as the area of the loop keeps changing, an induced current will flow. Since you're moving the conductor which contains charges, you're moving the charges in a magnetic field. Thus they ==feel a force==.

**Electromagnetic induction**: producing induced emfs with a charging magnetic field

---

# Motional emf
If we include a conducting rod at right angles to a uniform [[3_senior_year!/semester2/physics/ch. 21 - magnetic fields#Magnetic Fields\|magnetic field]], the electrons in the rod feel a force when the rod moves, because they are charges moving in a magnetic field (see [[3_senior_year!/semester2/physics/ch. 21 - magnetic fields#Magnetic Force\|magnetic force]]).

By [[3_senior_year!/semester2/physics/ch. 21 - magnetic fields#direction of the force on a charged particle in a magnetic field (RHR-1)\|RHR-1]], the electrons move to the bottom of the rod, and positive charges move to the top. Therefore, the rod acts as a source of emf, like a battery. The induced emf is **motional emf** (motion of charges through a magnetic field).

An electric field is setup within the rod, and the separation of charges along the rod continues until the attractive electrical force between the charges equals the magnetic force ($F_E=F_M$).

The motional emf is maintained as long as the bar keeps moving. If $v=0$, then $F_M=qvB\sin\theta=0$ and $F_E$ will reunite the $+$ and $-$ charges, thereby eliminating the emf.

emf: $\boxed{\epsilon=vBL}$ -- true when $v$, $B$, and $L$ are mutually perpendicular
- $\epsilon=$ induced emf (voltage)
- $v=$ speed of the bar
- $B=$ magnetic field
- $L=$ length of the bar in the field

---

## motional emf with a complete circuit
When we slide the bar to the right at speed $v$, an [[#Induced emf]] is set up across the bar, and an induced current will flow. The bar acts like a battery, so the current will flow counter-clockwise.

Now the current in the moving bar feels a force from the magnetic field. By [[3_senior_year!/semester2/physics/ch. 21 - magnetic fields#direction of the force on a charged particle in a magnetic field (RHR-1)\|RHR-1]], this force is directed to the left. The force *opposes* the direction of motion of the rod. The rod will stop unless a larger force keeps pulling it to the right. As the rod slides, the light bulb uses energy, which comes from the force.

We must have conversation of energy, so the work done on the rod in sliding it to the right is equal to the energy consumed by the light bulb.
> When a motional emf leads to an induced current, a magnetic force will act to oppose the motion in accord with the Principle of Conservation of Energy.

This is the foundation for Lenz's Law.

---

# Magnetic Flux
Remember [[3_senior_year!/semester2/physics/ch. 18 - electric forces and electric fields#Electric Flux and Gauss' Law\|electric flux]]?

Magnetic flux: $\boxed{\Phi_m=BA\cos \phi}$ 
- $B=$ magnetic field
- $A=$ surface
units - $(\text{Magnetic Field})*(\text{Area})=[T*m^2]=[\text{Weber}]=[\text{Wb}]$ 

The magnetic flux will be maximum when the field is perpendicular to the surface.

Note that $\Phi_M \varpropto B$. So, if $B$ increases then the magnetic flux $\Phi_M$ also increases. Remember that the magnitude of $B$ is represented by the density of field lines. The more field lines you have per unit area, the stronger the field.
>Therefore, the more field lines you have per unit area, the bigger the flux.

$\Phi_M \varpropto B \varpropto (\text{the \# of field lines thru a surface})$ 

---

## sliding conducting bars and magnetic flux
Let the bar start at $t=0$. Now let the bar move to its position when $t=t_0$. The bar moves a distance $x_0$ and sweeps out an area $A_0$. Now let the bar slide for a longer time to $t_f$. It moves to position $x_f$ and sweeps out an area $A_f$.

We know the emf across the bar is $\epsilon=vBL=\dfrac{\Delta x}{\Delta t}BL=\dfrac{\Delta(xL)}{\Delta t}B=\dfrac{\Delta(A)}{\Delta t}B=\dfrac{\Delta(B*A)}{\Delta t}=\dfrac{\Delta(\Phi_M)}{\Delta t}$ 
$\boxed{\epsilon=\dfrac{\Delta(\Phi_M)}{\Delta t}}$  Therefore, the induced emf is equal to the change in the magnetic flux divided by the change in time.

This is usually written as $\epsilon=\dfrac{-\Delta \Phi_M}{\Delta t}$. It's negative because the induced current flows in a direction such that the [[3_senior_year!/semester2/physics/ch. 21 - magnetic fields#Magnetic Fields\|magnetic field]] it creates *opposes* the change in the magnetic flux.

---

# Faraday's Law of Electromagnetic Induction
Often times the magnetic flux will pass through a coil with multiple turns.
$$ \boxed{\epsilon=-N\dfrac{\Delta \Phi_M}{\Delta t}} $$
- **Faraday's Law** (units are in volts)
- $N=$ turns in the coil

So an emf is [[#Induced emf|induced]] whenever $\Phi_M$ changes in time. Since $\Phi_M=BA\cos \phi$, we could write Faraday's Law as $\boxed{\epsilon=\dfrac{-\Delta (BA\cos \phi)}{\Delta t}}$.
>Therefore, if $B$, $A$, or $\phi$ change in time, then an emf is induced.

---

# Lenz's Law
Remember [[#Faraday's Law of Electromagnetic Induction]].

A changing [[3_senior_year!/semester2/physics/ch. 21 - magnetic fields#Magnetic Fields\|magnetic field]] can produce a current. To get the *direction*, we must consider two magnetic fields:
1. the original one that produced the induced current
2. the field created by the induced current itself

>[!quote] **Lenz's Law**: The induced emf resulting from a change in [[#Magnetic Flux]] leads to an induced current, which produces a magnetic field to oppose the change in flux.

- If the original field is *increasing*, then the induced field must point in the *opposite* direction.
- If the original field is *decreasing*, then the induced field must point in the *same* direction.

---

# Generators
Running a current through a loop of wire in a [[3_senior_year!/semester2/physics/ch. 21 - magnetic fields#Magnetic Fields\|magnetic field]] causes it to rotate. The reverse is also true - rotating a conducting loop in a magnetic field produces a current.

The [[#Motional emf]] was derived from $v$ being perpendicular to $B$, but as the loop rotates, the angle between $v$ and $B$ changes. Thus, the true motional emf is a function of angle: $\boxed{\epsilon=vBL\sin\theta}$.

Since the loop's motion is rotational, it's convenient to express $v$ and $\theta$ in terms of angular variables: $v=r\omega$ and $\theta=\omega t$.

If we let $A$ be the area of the loop and $N$ the number of turns in the loop, then we find the following expression for the emf produced by the loop:
$$ \boxed{\epsilon=NAB\omega \sin\omega t} $$
It's useful to rewrite it as $\epsilon=\epsilon_0\sin\omega t$, where $\epsilon_0=\epsilon_{\text{Max}}=NAB\omega$.

Remember that $\omega$ has the units of \[rad/s], and $\omega=2\pi f$, where $f$ is in \[Hz]. The emf produced by the coil is a sinusoidal function, and therefore changes sign as a function of time.
![coil emf.png](/img/user/0_attachments/coil%20emf.png) 
>[!note]
>The emf oscillates between its positive and negative maximum value.

Since the emf changes sign as a function of time, so does the current. This is an example of an [[3_senior_year!/semester2/physics/ch. 20 - electric circuits#Alternating Current\|AC]] **generator**.

---

# Mutual Induction
Let's place two coils side by side. Let's connect one to an AC [[#Generators|generator]] (*primary coil*) and the other to a voltmeter (*secondary coil*). ![mutual induction.png|500](/img/user/0_attachments/mutual%20induction.png) The primary coil creates a [[3_senior_year!/semester2/physics/ch. 21 - magnetic fields#Magnetic Fields\|magnetic field]], and some of those field lines pass through the secondary coil. This produces a change in [[#Magnetic Flux|magnetic flux]] in the secondary coil, leading to an [[#Induced emf]]. This is called **mutual inductance**.

Recall [[#Faraday's Law of Electromagnetic Induction]]. The net flux through the secondary coil is $N_s\Phi_s \varpropto I_P,\ \therefore$  the flux through the secondary coil is proportional to the current in the primary coil.
$$ N_s\Phi_s=MI_P\rightarrow \boxed{M=\dfrac{N_s\Phi_s}{I_P}} $$
$M=$ mutual inductance. Substitute this into Faraday's Law: $\epsilon_s=-N\dfrac{\Delta \Phi_s}{\Delta t}=-\dfrac{\Delta (N_s\Phi_s)}{\Delta t}=-\dfrac{\Delta (MI_P)}{\Delta t}=-M\dfrac{\Delta I_P}{\Delta t}\rightarrow \epsilon_s=-M\dfrac{\Delta I_P}{\Delta t}$. This proves that induced emf in the secondary coil depends on changing current in the primary coil.
- units - $\left[ \dfrac{V*s}{A} \right]\rightarrow [\text{Henry}]\rightarrow [H]$

---

# Self Inductance
Consider one coil connected to an AC [[#Generators|generator]]. The AC current produces a changing [[3_senior_year!/semester2/physics/ch. 21 - magnetic fields#Magnetic Fields\|magnetic field]], which produces a change in [[#Magnetic Flux]] within the coil, which leads to an [[#Induced emf]] in the coil. This process is called **self induction**.

$\Phi=$ flux though one loop of the coil // $N\Phi=$ net flux
$\Phi \varpropto B \varpropto I$, so $N\Phi \varpropto I$. Making it an equality, $N\Phi=LI$.
$$ \boxed{L=\dfrac{N\Phi}{I}} $$
Using [[#Faraday's Law of Electromagnetic Induction]] like we did for [[#Mutual Induction]], we find that $\boxed{\epsilon=-L\dfrac{\Delta I}{\Delta t}}$.

---

# Transformers
We can use one coil to [[#Induced emf|induce an emf]] (voltage) in another coil by [[#Mutual Induction]].
![transformer.png](/img/user/0_attachments/transformer.png) 
The induced emf in the secondary coil is proportional to the turns ratio: $\boxed{\dfrac{N_s}{N_p}}$. Thus, the more turns you have in the secondary coil, the higher the induced emf.
- $N_s=$ num of turns in secondary coil
- $N_p=$ num of turns in primary coil
The iron core ensures the flux through each coil is the same, and we get $\boxed{\dfrac{V_s}{V_p}=\dfrac{N_s}{N_p}}$. This is the **transformer equation**.
## transformer types
A transformer can either increase or decrease the primary voltage ($V_P$).
- If $N_s>N_p$, then the transformer is a ==step-up transformer==.
- If $N_s<N_p$, then the transformer is a ==step-down transformer==.
## current in a transformer
What happens when the voltage increases, but you need to have **_conservation of energy_**?
> Energy delivered to the primary coil = energy delivered to the secondary coil

$\text{Energy}=\text{Power}*\text{time}$, so the power is each coil must be equal. $I_pV_p=I_sV_s\rightarrow I_s=I_p\dfrac{V_p}{V_s}$, therefore if you have a step-up transformer, then $V_s>V_p$ and the current in the secondary coil ($I_s$) goes down. (This assumes no loss due to heat in the transformer, which for good ones, is about 1%.)