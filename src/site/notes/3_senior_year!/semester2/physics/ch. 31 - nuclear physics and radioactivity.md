---
{"dg-publish":true,"permalink":"/3-senior-year/semester2/physics/ch-31-nuclear-physics-and-radioactivity/","tags":["physics"],"noteIcon":"","created":"2024-04-24T19:08:56.597-07:00","updated":"2025-09-17T02:19:33.772-07:00"}
---

# Nuclear Structure
We’ve been studying atomic structure – the [[3_senior_year!/semester2/physics/ch. 30 - the nature of the atom#Rutherford Scattering\|Rutherford model of the atom]], where electrons orbit around a nucleus. And now we know that it takes Quantum Mechanics to correctly describe the [[3_senior_year!/semester2/physics/ch. 30 - the nature of the atom#The Quantum-Mechanical Description of the Atom\|nature of these orbits]]. But what about the nucleus?

In 1932, scattering experiments by English physicist James Chadwick discovered another particle in the nucleus which had no charge → ==neutron==. So the nucleus is composed of positive protons and neutral neutrons. These are called ***nucleons***.

**Atomic number** ($Z$): distinguishes different elements in the periodic table; equals the number of protons they have in their nucleus

Each element also has an *atomic weight* or **atomic mass number** ($A$).

Let $N$ be the number of neutrons in the nucleus, then $\boxed{A=Z+N}$.

Shorthand notation for element representation: $^A_ZX$. For example, oxygen has 8 protons and $N=A-Z=16-8=8$ neutrons. So oxygen would be $^{16}_8O$.

The mass of the elements is usually given in **atomic mass units** ($u$). $\boxed{1u=1.6605*10^{-27}\text{ kg}}$.

**Isotopes**: nuclei that contain the same number of protons but a different number of neutrons
For example, boron exists in nature as two stable isotopes: $^{11}_5B$ and $^{10}_5B$.[^1] The atomic mass number ($A$) listed on the periodic table is the average atomic mass of the isotopes. For boron this is 10.811.

---

# Strong Nuclear Force and Stability
The protons and neutrons are clustered together in a blob that is approximately spherical. The radius of the nucleus is ~1 fm = $1*10^{-15}m$. Experiments show that: $\boxed{r\approx (1.2*10^{-15})A^{1/3}}$.

**Nucleon density**: number of protons and neutrons per unit volume; same for all atoms

So we have this spherical blob of positive protons and neutral neutrons. How does it stay together? For hydrogen, there’s no problem. It’s just one proton. But what about the the next simplest element, helium (He)?

There's 2 protons and 2 neutrons in helium, so there's 2 protons very close together. We know that like charges repel, and we can calculate the repulsive force between the two protons using [[3_senior_year!/semester2/physics/ch. 18 - electric forces and electric fields#Coulomb's Law\|Coulomb’s Law]]. Assuming the charges are separated by 1 fm, we get a force of 231 N. This results in an acceleration of the protons $=1.4*10^{29}\ m/s^2$. So why don’t the protons, and thus the nucleus, just fly apart? There must be an attractive force holding them together, and it’s not gravity, because the gravitational attraction between to subatomic particles is very small ($\approx 1.9*10^{-34}N$).

So, we need a new force. It’s the **strong nuclear force**. It's one of the fundamental forces, along with gravity and the electroweak force.
- *Characteristics of the strong nuclear force*:
	1. ***It's independent of charge***. Thus, the attractive force between 2 protons is the same as that between 2 neutrons or between a neutron and a proton.
	2. ***The range of the force is extremely short***. It is very strong for distances ~1 fm and essentially zero at farther distances.

Most nuclei listed in the periodic table are stable, but some are not.

>[!quote] The stability of a nucleus depends on the balancing between the electrostatic repulsion between protons and the strong nuclear attractive force between all nucleons.

Every proton in the nucleus feels Coulombic repulsion from every other proton, since the electrostatic force is long-ranged. But each proton and neutron only feels the strong nuclear force from its closest neighbors. To compensate for this, the more protons you add to the nucleus, an even greater number of neutrons must be number of neutrons must be added to try and balance the electrostatic force.

Eventually, as more and more protons are added, no number of extra neutrons can compensate for the large electrostatic repulsion, and the nucleus breaks apart. This occurs at $Z = 83$, which is bismuth (Bi). Any element with an atomic number $Z > 83$ will be unstable and break apart over time. It will rearrange itself into a stable nuclei. This process is called **[[#Radioactivity]]**.

---

# Nuclear Binding Energy
In order to separate two nucleons, we have to overcome the [[#Strong Nuclear Force and Stability|strong nuclear force]]. We refer to this as the **Nuclear Binding Energy**.

To analyze this problem quantitatively, we have to use Einstein’s famous $E=mc^2$. This equation gives us the *rest mass energy*. Thus, a change in mass of a system equals a change in rest mass energy: $\Delta E=\Delta mc^2$.

The binding energy of the nucleus appears as extra mass in the separated nucleons. In other words, the sum of the masses of the individual nucleons is greater than the mass of the stable nucleus by an amount Δm, where Δm = the mass defect of the nucleus.

The nuclear binding energy then is just this mass converted to energy:
$$ \text{Binding Energy}=(\text{mass defect})c^2=\Delta mc^2 $$

It's customary in these types of problems to use atomic mass units, $u$.

---

# Radioactivity
Any nucleus with more than 83 protons is unstable, or radioactive. These nuclei disintegrate over time, and during this process, 3 types of radiation may be produced. From ==lowest to highest energy==, these are[^2] 
1. $\alpha$ rays = $\alpha$ particles (helium nuclei)
2. $\beta$ rays = electrons
3. $\gamma$ rays (high-energy photons)
## $\alpha$ radiation
A nucleus that is emitting α particles is undergoing α decay. Each α particle is a He nucleus, so it is represented by $^4_2\text{He}$.

- **Transmutation**: a parent nucleus is converted into another element
	- Thus, for a transmutation to occur, the proton number ($Z$) of the parent *must* change.

In general, for $\alpha$ decay, we have:
$$
{ #A_ZP}
\rightarrow ^{A-4}_{Z-2}D+^4_2\text{He} $$
Notice that the number of nucleons is conserved.

We’ve learned in physics that quantities such as energy, mass, charge, linear and angular momentum, must be conserved. Like any physical process, radioactivity must also obey these laws. When a nucleus decays (say by alpha decay), the energy and momentum released during the decay process goes into the α particle and the *recoiling daughter nucleus*.

Notice that the linear momentum is conserved. Remember, explosions are like collisions in reverse!
## $\beta$ radiation
Beta rays are negatively charged particles, and experiments show them to be electrons. 

In general form, for $\beta$ decay, we have:
$$ \boxed{^A_ZP\rightarrow
{ #A_}
{Z+1}D+^0_{-1}\text e} $$
Notice that the charge is conserved.

So where does the electron come from? It’s not one of the atomic electrons orbiting the nucleus of the atom. It actually comes from inside the nucleus itself.

It turns out that neutrons themselves are unstable, and they will decay into a proton. When the neutron decays into a proton, it releases an electron ($β-$) and an antineutrino ($v^-_e$).
### $\beta^+$ decay
There's a 2nd type of $\beta$ decay called **$\beta^+$ decay**. Here the nucleus emits a positron.
**Positron**: electron's *antiparticle* (antimatter)
The positron has the same mass and spin of the electron, but opposite electric charge. The positron is created when a nuclear proton is transformed into a neutron.
$$
{ #A_ZP}
\rightarrow^A_{Z-1}D+^0_{+1}\text e $$
- $P=$ parent nucleus
- $D=$ daughter nucleus
- $\text e=\beta^+$ particle (electron)
### electron capture
There's a 3 type of β decay called **electron capture**: Here, the nucleus pulls in an orbital electron from the K-shell.
## $\gamma$ radiation
In gamma decay, a nucleus that is in an *excited state* decays to a lower energy state and emits a photon state and emits a photon. The nucleon energy, like the energy of the orbital electrons, exist only in discreet (quantized) levels. This decay is the nuclear analogue of the emission of light by atoms, i.e. electrons making transitions between two atomic energy levels.

> Orbital electron energy levels ~eV -> visible spectrum
> Nuclear energy levels ~MeV -> high energy photons ($\gamma$ rays)

$\gamma$ decay usually follows $\alpha-$ and $\beta-$ decay. In general, we have:

$$
{ #A_ZP}
^*\rightarrow
{ #A_ZP}
+^0_0\gamma $$

---

# The Neutrino
When a nucleus undergoes β decay, energy is released. However, the $KE$ of the radiated electron and recoiling nucleus cannot account for all of this energy. Some of the energy gets carried off by another particle, the **antineutrino**.

The decay of a neutron into a proton looks like this: $n\rightarrow p+e^-+\bar v^-_e$. (The “bar” over the ν indicates that it is the antiparticle.) Thus, the correct beta decay process of $^{234}\text{Th}$ should be $^{234}_{90}\text{Th}\rightarrow ^{234}_{91}\text{Pa}+^0_{-1}e+\bar v_e$. The **neutrino**[^3] has no charge and a very small mass, some 30,000 times less than the electron.

Neutrino production and β decay involve the **weak nuclear force**, which is a fundamental force much weaker than the strong nuclear force.

Together with gravity and the strong nuclear force, they make up the *3 fundamental forces*.

---

# Radioactivity 2
Assume I have a chunk of radioactive material that contains $N$ radioactive nuclei, or parent nuclei. Which one of these nuclei is going to decay, and when?

Since radioactivity is a quantum-mechanical process, we can’t know with certainty. We can only predict when a particular nucleus will decay Thus, radioactivity is a statistical process.

As time passes, some of the nuclei will decay, and $N$ will decrease. To help describe this process, we use the half-life.
**Half-life** ($T_{1/2}$): time it takes for ½ of the nuclei present to decay
- *units* - seconds (s) or years (yrs)

---

## activity
**Activity**: number of disintegrations per second, or the rate at which any particular radioactive sample decays

As each nuclei disintegrates, $N$ decreases. The more nuclei we start with, the more that will disintegrate in a given time period. The *activity equation* is:
$$ \dfrac{\Delta N}{\Delta t}\varpropto N \rightarrow \boxed{\dfrac{\Delta N}{\Delta t}=-\lambda N} $$
- $\lambda=$ **decay constant** (proportionality constant -- $s^{-1}$)
- The minus sign indicates that $N$ decreases as time passes decreases as time passes.
- *units* - $\dfrac{\Delta N}{\Delta t}=\left[ \dfrac{\text{Disintegrations}}{\text s} \right]=[\text{Bq}]$ (Becquerel)

Activity can also be measured in ==Curies==: $\boxed{1\text{Ci}=3.70*10^{10}\text{ Bq}}$ 

A graph of number of radioactive nuclei left vs. time shows an exponential decay: $\boxed{N=N_0e^{\lambda t}}$ 
- $N=$ number of nuclei left after time $t$ 
- $N_0=$ number of nuclei initially
- $e=2.178\dots$, the constant base for natural log ($\ln$)
At $t=0$, $N=N_0$.

We can relate the decay constant λ to the half-life since we know that when $t=T_{1/2}$, $N=\dfrac{N_0}2$. Thus,
$$ \dfrac{N_0}2=N_0e^{\lambda T_{1/2}}\rightarrow \dfrac12=e^{\lambda T_{1/2}} $$
Take the $\ln$ of both sides:
$$ \ln\left(\frac12\right)=\ln\left(e^{\lambda T_{1/2}}\right)\rightarrow \ln(1)-\ln(2)=-\lambda T_{1/2}\rightarrow\ln(2)=\lambda T_{1/2}\rightarrow\boxed{T_{1/2}=\frac{\ln2}{\lambda}=\frac{0.693}{\lambda}} $$

[^1]: Most boron atoms have 6 neutrons (81.1%), but some (18.9%) have only 5 neutrons.
[^2]: Continued in [[#Radioactivity 2]].
[^3]: "Neutrino" means little neutral one.