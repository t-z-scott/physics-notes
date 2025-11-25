---
{"dg-publish":true,"permalink":"/3-senior-year/semester2/physics/ch-30-the-nature-of-the-atom/","tags":["physics"],"noteIcon":"","created":"2025-10-23T00:28:51.241-07:00","updated":"2025-09-20T19:16:22.000-07:00"}
---

# Rutherford Scattering
There are two types of radiation in the atom, called $\alpha$ and $\beta$. **$\beta$-radiation** (or $\beta$-rays) are just electrons, but $\alpha$-particles are much heavier and positively charged.

The Rutherford experiment (shooting alpha particles at a gold film) proves the existence of an **atomic nucleus** (concentration of the positive charges in a very small region) by showing the deflection of the $\alpha$-particles.[^1] This led to the *nuclear (planetary) model* of the atom, which is still accepted today.

**Nuclear radii** $\approx1*10^{-15}$ 
**Electron orbit** $\approx1*10^{-10}$ 

---

# Line Spectra
All objects emit [[3_senior_year!/semester2/physics/ch. 24 - electromagnetic waves#Electromagnetic Waves\|EM]] radiation. Hot filaments in incandescent light bulbs emit a continuous range of wavelengths, some of which are in the visible [[3_senior_year!/semester2/physics/ch. 24 - electromagnetic waves#Electromagnetic Spectrum\|spectrum]]. This range of wavelengths results from the electrons being "excited" in the atoms that make up the solid.

In contrast, single atoms only emit radiation at certain wavelengths. Low-pressure gases, for example, only emit certain wavelengths of light when excited. We can use a [[3_senior_year!/semester2/physics/ch. 27 - interference and the wave nature of light#The Diffraction Grating\|diffraction grating]] to separate these wavelengths and produce a characteristic **line spectra** for those atoms.

![line spectra - hydrogen (balmer series).png](/img/user/0_attachments/line%20spectra%20-%20hydrogen%20(balmer%20series).png)
This is hydrogen's line spectra. It's the simplest element, so it has the simplest line spectra. It forms 3 groups of lines, called the ==*Lyman, Balmer, and Paschen series*==. <u>Only the Balmer series lies in the visible spectrum</u>.

**Lyman Series**: $\dfrac 1{\lambda}=R\left( \dfrac 1{1^2}-\dfrac 1{n^2} \right),\ n=2,3,4,\dots$ 
**Balmer Series**: $\dfrac1{\lambda}=R\left( \dfrac1{2^2}-\dfrac1{n^2} \right),\ n=2,3,4,\dots$ 
**Paschen Series**: $\dfrac1{\lambda}=R\left( \dfrac1{3^2}-\dfrac1{n^2} \right),\ n=2,3,4,\dots$ 
- $R=\text{Rydberg Constant}=1.097*10^7\ m^{-1}$ 

Since only the Balmer series is in the visible spectrum, the longest wavelength would occur for $n=3$, and the shortest would occur for $n=\infty$. For $n=3$, the Balmer series is ==656 nm== (red part of visible spectrum). For $n=\infty$, the Balmer series is ==365 nm== (ultraviolet part of visible spectrum).

![line spectra series.png](/img/user/0_attachments/line%20spectra%20series.png) 

---

# Bohr Model of the Atom
Like Einstein did with his [[3_senior_year!/semester2/physics/ch. 29 - particles and waves#The Photoelectric Effect\|photoelectric effect]], Bohr adopted [[3_senior_year!/semester2/physics/ch. 29 - particles and waves#planck's assumption\|Planck's idea]] of quantized energy levels, and assumed that the electrons in the hydrogen atom could only have certain values of energy (quantized). Each of these energy levels corresponds to a unique orbit that the electron moves in around the proton. The larger the orbit, the larger the energy.

Bohr's Assumptions:
1. Electrons travel in fixed orbits around the proton called **stationary orbits** or **states**, each being defined by a unique radius and energy. While in these orbits, the electrons *do not emit radiation*.
2. An electron in an atom emits radiation (emits *photons*) when and only when it moves from a higher energy level to a lower one (or, a ==larger orbit to a smaller one==). By conservation of energy, $\text{Photon Energy}=E_i-E_f \rightarrow \boxed{hf=E_i-E_f=\dfrac {hc}{\lambda}}$.
3. $\boxed{L_n=mv_nr_n=n\bar h\text{, }n=1,2,3,\dots}$ 

Solve the above for $v$ and plug in the force equation: $\boxed{r_n=\left( \dfrac{h^2}{4\pi mke^2} \right)\dfrac{n^2}Z=(5.29*10^{-11}m)\dfrac{n^2}{Z},\ n=1,2,3,\dots}$. This is the equation that gives us the different *quantized orbits*.

For the hydrogen atom, $Z=1$, and for the lowest quantized orbit ($n=1$) we find that $\boxed{r_1=5.29*10^{-11}m}$. This is the first **Bohr radius** for hydrogen. Remember, each $n$-level will correspond to a different Bohr radius.

Now that we have our expression for $r$, we can plug it into our equation for the total energy of the atom: $\boxed{E_n=-\left( \dfrac{2\pi mk^2e^4}{h^2} \right)\dfrac{Z^2}{n^2},\ n=1,2,3,\dots}$. This represents the ***quantized Bohr energy levels*** of the hydrogen atom. The stuff in parentheses is just a constant, so

$$ \boxed{E_n=-(2.18*10^{18}J)\dfrac{Z^2}{n^2}} $$
$$ \boxed{E_n=-(13.6\text{ eV})\dfrac{Z^2}{n^2}} $$

Again for hydrogen, $Z = 1$, and $n = 1$, so $\boxed{E_1=-13.6\text{ eV}}$. This is the energy of the electron in the first Bohr level. It's also called the **ground-state energy**.

![hydrogen atom states.png](/img/user/0_attachments/hydrogen%20atom%20states.png)
Notice, because of the $1/n^2$ dependence, the spacing between higher and higher energy levels decreases. So, if I add 13.6 eV to an electron in the ground state of a hydrogen atom, then it will have zero total energy and no longer be bound to the proton → *The electron is removed*. This process is called **ionization**.

![hydrogen atom states with series.png](/img/user/0_attachments/hydrogen%20atom%20states%20with%20series.png)
The *Lyman series* consists of transitions to the ground state ($n = 1$) starting with the first excited state ($n = 2$). The *Balmer series* consists of transitions to the first excited state ($n = 2$) starting with the 2nd excited state ($n = 3$). The wavelengths we observe from hydrogen are called **emission lines**.

Atoms can also absorb photons (**absorption lines**).

If a photon is incident on an atom and has an energy equal to the energy difference between two quantum energy levels of the atom, then the electron can get “bumped up” to that higher energy level, called an **excited state**.

Typically though, the lifetime of the electron in the excited state is finite and rather short. It quickly drops back down to a lower energy state and emits a photon whose energy is equal to the difference in the energies of the two levels.

---

# deBroglie's Explanation of Bohr's Angular Momentum Assumption
Based on Bohr’s work, deBroglie pictured the electron orbiting the proton as a particle-wave. For certain wavelengths, the electron will form ==standing waves== around the nucleus.

**Standing wave**: when the distance the wave travels is an integral number of its wavelength
![standing waves.png](/img/user/0_attachments/standing%20waves.png)
*[[3_senior_year!/semester2/physics/ch. 30 - the nature of the atom#Bohr Model of the Atom\|Bohr’s assumption]] of quantized angular momentum is exactly equivalent to a standing-wave condition for electron waves around the nucleus*.[^2] 

---

# The Quantum-Mechanical Description of the Atom
Considering the scope of the problem, Bohr’s achievements with such a simple model were remarkable. However, while the model worked well for simple hydrogen However, while the model worked well for simple hydrogen – one electron one electron orbiting one proton – it failed for more complicated atoms.

The electron states in the hydrogen atom were denoted by one unique number, $n$. It was later determined that for more complicated atoms (and hydrogen too), quantum mechanics would rely on 4 quantum numbers to describe the electron states in an atom.
1. **Principle Quantum number, $n$**: Similar to the Bohr model. It gives the [[3_senior_year!/semester2/physics/ch. 30 - the nature of the atom#Bohr Model of the Atom\|total energy of the atom]].
2. **Orbital Quantum number, $l$**: This number determines the angular momentum of the orbit. The values of $l$ depend on $n$: $l=0,1,2,\dots,(n-1)$. There are $n$ values of $l$. The magnitude of $L$ (the angular momentum) of the electron is then given by $\boxed{L=\sqrt{l(l+1)} \bar h}$.
3. **Magnetic Quantum number, $m$**: This becomes important when we place the atom in a magnetic field. The field alters the electron energy levels. This is known as the ==Zeeman Effect==.
	- If $B=0$, then $m_l$ plays no role. The value of $m_l$ depends on $l$ -- $m_l=-l,\ -l+1,\dots,-1,0,1,\dots,+l$, in integer steps.
	- There are ($2l+1$) total values of $m_l$.
	- If an atom is placed in a magnetic field pointing in the z-direction, then the component of the angular momentum which would arise along the z-direction due to the Zeeman effect is $\boxed{L_z=m_l\bar h}$.
4. **Spin Quantum number, $m$**: An electron has the intrinsic property of **spin**. The orbital and spin motions of the electron combine to produce magnetism in materials. The spin quantum number can only take two possible values, $\boxed{m_s=\pm\frac12}$.
	- **"spin-up" state** = $+1/2$ 
	- **"spin-down" state** = $-1/2$ 
	- Spin, like mass and charge, is an intrinsic property of all electrons. Each electron has the same spin.

Thus, there are 8 total states (in general, the total number of states is $(2n)^2$.

| $n$ | $l$ | $m_l$ | $m_s$ |
| --- | --- | ----- | ----- |
| 2   | 0   | 0     | +1/2  |
| 2   | 0   | 0     | -1/2  |
| 2   | 1   | -1    | +1/2  |
| 2   | 1   | -1    | -1/2  |
| 2   | 1   | 0     | +1/2  |
| 2   | 1   | 0     | -1/2  |
| 2   | 1   | 1     | +1/2  |
| 2   | 1   | 1     | -1/2  |

Quantum mechanics dictates that due to the [[3_senior_year!/semester2/physics/ch. 29 - particles and waves#The Heisenberg Uncertainty Principle\|HUP]], the position of the electron is uncertain. If we were to take many measurements of the electron's position, sometimes it would be very close to the nucleus, and sometimes it would be far away.

So the electron exists as a particle-wave in a probability cloud around the nucleus. If the electron is in the $n=1$ state, then after many measurements, the most probable distance for the electron would be at $r_1=5.29*10^{-11}\ \text m$. The higher-density cloud regions indicate areas of higher probability.

There are different probability clouds for different quantum states.

---

# The Pauli Exclusion Principle (PEP)
The [[3_senior_year!/semester2/physics/ch. 30 - the nature of the atom#Bohr Model of the Atom\|Bohr Model of the Atom]] was derived explicitly for one electron and one proton. Will the energy levels apply to atoms with more than one electron? No!

Once you add more than one electron to an atom, the electrons interact with each other due to [[3_senior_year!/semester2/physics/ch. 18 - electric forces and electric fields#Coulomb's Law\|Coulombic repulsion]]. This results in additional energy terms in $E_n$.

Quantum mechanics does describe the energy levels correctly in multi-electron atoms, and it uses the 4 quantum numbers: $n$, $l$, $m_l$, and $m_s$. The energy of the electrons depends on $n$ and $l$, and in general, the energy increases as $n$ and $l$ increase, but there are exceptions.

> Each value of $n$ corresponds to a single “shell ”.
> 1. K-shell for $n = 1$ 
> 2. L-shell for $n = 2$ 
> 3. M-shell for $n=3$ 

Each shell has ***subshells*** defined by the orbital quantum number, $l$. For example, the K-shell is the $n=1$, and it has one subshell, $l = 0$. The L-shell is the $n = 2$, and it has two subshells defined by $l = 0,1$.

When atoms are not subjected to violent collisions, high temperature, or high electric fields, then the electrons in the atoms tend to spend most of their time in the low energy levels of the atom. The lowest energy state is called the **ground state**.

However, when a multi-electron atom is in its ground state, not every electron can be in the $n = 1$ level. They must obey a rule known as the **Pauli Exclusion Principle** (**PEP**).
>[!quote] No two electrons in an atom can have the same set of values for their 4 quantum numbers.
>In other words, ==no two electrons can be in the same quantum state==.

Because of the PEP, there is a maximum number of electrons that can fit into each energy level and subshell.

---
## The PEP, cont.
Because of the PEP, there is a maximum number of electrons that can fit into each energy level and subshell.

*Example*: Take $n=1$. Then $l=0$, $m_l=0$, and $m_s=\pm1/2$. Thus, each $l=0$ subshell can hold a maximum of 2 electrons, one with spin-up and one with spin-down.

Now take $n=2$. Then $l=0,1$.
$$ l=0\rightarrow m_l=0,\ m_s=\pm\frac12 $$
$$ l=1\rightarrow m_l=-1,0,1 $$
- $m_l=-1,\ m_s=\pm\frac12$ 
- $m_l=0,\ m_s=\pm\frac12$ 
- $m_l=1,\ m_s=\pm\frac12$ 
Thus, we get 8 total states for $n=2$.

In general, the number of possible states for any given subshell $l$, is $2(2l+1)$. Representation of the $l$-subshell is customarily done by letter.

| $l$ | letter designation | max. number of $e^{-s}$: $2(2l+1)$ |     |
| --- | ------------------ | ---------------------------------- | --- |
| 0   | $\text s$          | 2                                  |     |
| 1   | $\text p$          | 6                                  |     |
| 2   | $\text d$          | 10                                 |     |
| 3   | $\text f$          | 14                                 |     |
| 4   | $\text g$          | 18                                 |     |
| 5   | $\text h$          | 22                                 |     |

In general, the maximum number of electrons in any shell ($n$) is $2n^2$.

Here's an example of the spectroscopic notation used to specify the electronic states in multi-electron atoms: $3p^4$.
- $n=3$ 
- $p$ -- $l=1$ 
- $4=$ number of $e^{-s}$ in the subshell

Specifying the $n$ and $l$ value for each electron in an atom in this way is called the **electronic configuration**.

---

*Example*: Write down the full electronic configuration for carbon.

Carbon's atomic number is 6, so it has 6 electrons to put into shells. The order that the shells fill up is given by the following construction:
![carbon electronic config.png](/img/user/0_attachments/carbon%20electronic%20config.png)
The order is shown by diagonal arrows starting in the upper right and pointing toward the lower left.

We start filling in these shells with carbon’s 6 electrons, keeping in mind that $s$'s hold 2 electrons, $p$'s hold 6, $d$'s hold 10, etc.

So for carbon, we find the electronic configuration to be $\boxed{1s^2\ 2s^s\ 2p^2}$.

---

# periodic table
Elements in the Periodic Table are arranged by their electronic configurations.

It’s the outermost electrons in each atom (valence electrons) that determines the element's physical physical properties.

The original periodic table was arranged by a Russian chemist, Dmitri Mendeleev, during the late 1800’s. He arranged elements with similar properties into columns properties into columns → they have the same number of valence electrons.

> [[3_senior_year!/semester2/physics/ch. 30 - the nature of the atom#The Quantum-Mechanical Description of the Atom\|Quantum mechanics]] and [[3_senior_year!/semester2/physics/ch. 30 - the nature of the atom#The Pauli Exclusion Principle (PEP)\|the PEP]] provide a natural explanation for why the elements are arranged as they are in the periodic table.

---

# X-Rays
Wilhelm Roentgen was a Dutch physicist working with cathode ray tubes Wilhelm Roentgen was a Dutch physicist working with cathode ray tubes back in the late 1800’s. In a cathode ray tube, electrons get accelerated through a large voltage and then collide with a metal target, such as Cu, Mo, or Pd.

When the electrons collided with the target, Roentgen noticed certain “rays” were produced. He found that they could travel through certain materials that were opaque to light. He thought they might be charged particles of some kind, but they didn't deflect in a magnetic field. Since he couldn’t figure out what they were, he called them called them “**X-Rays**”.

We now know that X-Rays are [[3_senior_year!/semester2/physics/ch. 24 - electromagnetic waves#Electromagnetic Waves\|EM]] radiation – light in the non-visible part of the [[3_senior_year!/semester2/physics/ch. 24 - electromagnetic waves#Electromagnetic Spectrum\|spectrum]]. Since they are EM radiation, they must be produced when charges are being accelerated. This occurs when the electrons slow down upon collision with the metal target.

If we measure the intensity of the X-Rays as a function of wavelength, we get the following characteristic plot:
![x-rays intensity graph.png](/img/user/0_attachments/x-rays%20intensity%20graph.png)
As the electrons slow down (decelerate) upon striking the metal target, the broad background part of the curve, called Bremsstrahlung[^3] radiation, is produced.

The large peaks in the intensity spectrum depend on the material of the target, and are called $K_{\alpha}$ and $K_{\beta}$. They're labeled "$K$" because they involve electrons in the $n=1$ ($K$-shell). As the electrons strike the atoms in the metal target, they slow down. But, if they have enough energy, they can knock an electron in the atom out of the $K$-shell. Then another electron in the atom sitting in a higher energy state falls down to replace it. When it makes this transition, a ==photon is emitted== with X-Ray energies.

The energy of the incident electrons must be large if they are to access the $K$-shell of the atoms in the metal. The energies of those levels is ~45,000 eV!
- The $K_{\alpha}$ line occurs when an $n=2$ electron falls back into the $K$-shell.
- The $K_{\beta}$ line occurs when an $n=3$ electron falls back into the $K$-shell.

[^1]: If the Plum-Pudding model was correct, they would travel straight through the film, and not deflect.
[^2]: For this condition, $2\pi r=n\lambda,\ n=1,2,3,\dots$ but $\lambda=\dfrac hp=\dfrac h{mv}$. Plug in: $2\pi r=\dfrac{nh}{mv}\rightarrow mvr=\dfrac{nh}{2\pi}\rightarrow L=n\bar h$. Which is just the Bohr assumption on angular momentum.
[^3]: Bremsstrahlung comes from the German word for “braking”.