---
{"dg-publish":true,"permalink":"/3-senior-year/semester2/physics/ch-29-particles-and-waves/","tags":["physics"],"noteIcon":"","created":"2024-04-08T11:39:05.391-07:00","updated":"2025-09-17T02:14:16.156-07:00"}
---

# blackbody
All objects are continuously absorbing and emitting radiation. When light (or any [[3_senior_year!/semester2/physics/ch. 24 - electromagnetic waves#Electromagnetic Waves\|EM]] radiation) falls on an opaque body, part of it is [[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#The Reflection of Light\|reflected]], and part of it is absorbed.
- *Light-colored* bodies *reflect* most of the radiation incident on them.
- *Dark-colored* bodies *absorb* most of the radiation incident on them.
>[!note] If an opaque body is in ==thermal equilibrium== with its surroundings, then it must be absorbing and emitting radiation at the same rate (equally).
>Otherwise it would either heat up or cool off, which would take it out of thermal equilibrium.

This radiation is called **thermal (heat) radiation**.
- For objects whose temperatures are $<\approx600\deg C$, this radiation isn't in the visible part of the EM spectrum, but in the *infrared*.
- A body begins to *glow dull red* at temperatures between $600$-$700\deg C$.
- A body at higher temperatures will *glow bright red*, or even *white hot*.

**Ideal blackbody** (aka **perfect blackbody**): body that absorbs and emits ==all the radiation== incident on it

A blackbody is composed of atoms. We can treat the atoms in the solid as being connected by invisible springs. Each atom will vibrate, or oscillate, in 3 dimensions. This is called the **simple harmonic approximation**.

The vibrating atoms absorbs and emit radiation. The equality relationship is $\boxed{I(\lambda)=\dfrac{4kT}{\lambda^2}}$. This is the **Rayleigh-Jeans Law**.
- $k=$ *Boltzmann constant* ($k=1.38*10^{-23}\ J/K$)
- $T=$ temperature
**Ultraviolet catastrophe**: the classical theory (above) fails miserably at low wavelengths.

The radiation intensity from an ideal blackbody varies from wavelength to wavelength. At higher temperatures, the intensity per unit wavelength is greater, and the maximum occurs at smaller wavelengths.
## planck's assumption
Planck assumed that the ==energy of the atomic oscillators was a discreet variable==. In other words, energy could only have certain discrete values, i.e. $E=0,\epsilon,2\epsilon,3\epsilon,\dots,n\epsilon$ (it is *quantized*). Also, this discrete value $\epsilon$ had to be proportional to frequency: $\epsilon\varpropto f$.
**Planck's assumption**: $\boxed{E=nhf,\ n=0,1,2,3,\dots}$ 
- This meant that an [[3_senior_year!/semester2/physics/ch. 24 - electromagnetic waves#Electromagnetic Waves\|EM wave]] must have an energy, $E=hf$. So energy comes in discrete packets of $hf$ called **quanta**, or **quantum of energy**.

Einstein worked off of this and found that the energy of light wasn't equally distributed through space. Instead, it consisted of discrete quanta of energy called **photons**.
**Energy of light (or a photon)**: $\boxed{E=hf=\dfrac{hc}{\lambda}}$ 

---

# The Photoelectric Effect
From [[#planck's assumption]], we find that we can calculate the frequency or wavelength of light from its energy. Also, the greater the intensity of light, the more photons it contains, but each photon's energy is still $E=hf$.

**Photoelectric Effect**: When light shines on a metal plate, some of the electrons in the metal get ejected from its surface and then are accelerated by a potential difference. This results in a current flow in the circuit as shown.
1. Only light with a frequency above some minimum value, $f_0$ (the **threshold frequency**), will result in electrons being ejected -- regardless of the light's intensity.
	- $f<f_0$, no ejected electrons
	- $f\le f_0$, electrons are ejected from the metal's surface
2. The maximum $KE$ of the ejected electrons remains constant, even if the intensity of the light in increased.

The photon energy is given by $\boxed{E=hf=\dfrac{hc}{\lambda}}$. The *more intense* the light is, the *more photons* it carries, but each photons still has an energy: $E=hf$.

---

Free electrons occupy the entire volume of the metal. However, electrons close to the metal's surface (surface electrons) are more weakly bound to the metal than the deep electrons. Therefore, it's the surface electrons that are ejected during the photoelectric effect.

But even though the surface electrons are more weakly bound, there is still a minimum "binding energy" you must overcome to get them out of the metal. This is called the Work Function ($W_0$) of the metal. It is an ==energy==, and it is typically on the order of a few eV.

During the effect, a photon of light ($f>f_0$) with energy $hf$ strikes the metal and electrons are ejected with energy KE.

By conservation of energy, the following relationship must be true:
$\text{The photon energy – The binding energy = KE of the ejected electrons}$
or $\boxed{hf-W_0=KE_{e-}}$ (Einstein equation for [[#The Photoelectric Effect]]). 

---

Light is composed of particles called So light is composed of particles called photons photons. Einstein showed that the total energy of an object is $E=\gamma\ mc^2$ where $\gamma=\dfrac1{\sqrt{1-\frac{v^2}{c^2}}}$. Notice that if $v=0$, then $\gamma=1$ and $E=mc^2$.

Rewrite the general energy equation: $\dfrac E{\gamma}=mc^2\rightarrow E\left( \sqrt{1-\frac{v^2}{c^2}} \right)=mc^2$ 

If we apply this to photons, $v=c$, so $E\left( \sqrt{1-\frac{v^2}{c^2}} \right)=mc^2\rightarrow0=mc^2$. Therefore, for the equation to be correct, $m$ must equal $0$ for the photon.

>[!quote] A photon is a massless particle that moves at the speed of light!

---

# The Momentum of a Photon and the Compton Effect
The photoelectric effect was the first evidence for this particle or photon description of light description of light. However, Einstein’s particle picture wasn’t truly appreciated until another set of experiments was performed around 20 years later.

Arthur Compton used the particle picture of light to explain his research, in which he was scattering light (X-ray photons) off of electrons at rest. This is known as **Compton Scattering** or the **Compton Effect**.

![compton effect.png](/img/user/0_attachments/compton%20effect.png)
By conversation of energy, $E_{\text{Incident photon}}=E_{\text{Scattered photon}}+KE_{\text{Recoiling electron}}$ or $hf=hf'+KE_{e-}$.

By conservation of linear momentum, $\overrightarrow{p}_{\text{Incident photon}}=\overrightarrow{p}_{\text{Scattered photon}}+\overrightarrow{p}_{\text{Recoiling electron}}$.

**Conservation of linear momentum**: $\boxed{\lambda'-\lambda=\dfrac h{mc}\left(1-cos\theta\right)}$ 

In words, this equation states that the difference in the wavelengths between the scattered photon and the incident photon is related to the scattering angle by the above relationship.

>[!note] $\cos\theta$ can vary between -1 and +1, so the shift in the photon’s wavelength will vary between 0 and $\dfrac{2h}{mc}$.

The largest shift occurs when $\theta=180\degree$. The incident photon comes in, and then after colliding with the electron, scatters straight back. The momentum of an individual photon in a light beam is small, but if there's a large number of them, their momentum can have an effect on macroscopic objects.

---

# Particle Waves - de Broglie
Working as a graduate student in 1923, de Broglie hypothesized that if light waves can have particle-like properties, then maybe particles (i.e. electrons) can have wave-like properties. This was a very radical assumption, since at this time, there was no evidence to support this hypothesis.

From Einstein’s relativity equations, it is found that the [[#The Momentum of a Photon and the Compton Effect|momentum of a photon]] is $p=\dfrac{hf}{c}=\dfrac h{\lambda}$. de Broglie rewrote this as $\boxed{\lambda=\dfrac hp}$ where $p$ is the relativistic momentum. This is known as the **de Broglie wavelength** of a particle. This allows us to calculate the wavelength for any object with nonzero momentum.
## particle-wave duality of light
Now let’s repeat [[3_senior_year!/semester2/physics/ch. 27 - interference and the wave nature of light#Young's Double Slit Experiment\|Young’s double-slit experiment]], but this time let's shoot electrons (particles) at the slits instead of light. We might expect the screen to have two bright fringes, one directly behind each slit. What we actually see is alternating dark and bright fringes. In other words, the electrons have ==acted like waves== and interfered with each other to produce the classic interference pattern!

Our notion of the electron as being a tiny discrete particle of matter does not account for the fact that the electron can behave as a wave in some circumstances. It exhibits a dual nature – behaving sometimes like a particle, and sometimes like a wave.

The previous scenario is also true for light. Sometimes it's wave-like and sometimes it's particle-like. This is referred to as the **particle-wave duality of light**. Wave properties are displayed by all particles, such as protons and neutrons too.

So all objects have a de Broglie wavelength – baseballs, cars, even you and me! But remember, in order for wave effects to be seen, such as interference and diffraction, the wavelength must be comparable to the size of the opening or obstacle.

---

# The Heisenberg Uncertainty Principle
We know that the bright fringes on the screen from the double-slit experiment with electrons were regions of high probability. An electron could go to any bright fringe. Let's consider single-slit diffraction with electrons, and concentrate on the ones that form the central bright fringe.

![heisenburg uncertainty graph.png](/img/user/0_attachments/heisenburg%20uncertainty%20graph.png)
The electrons enter the slit with momentum $p_x$. One they pass through, some on them must gain momentum in the $y$-direction. The maximum any electron could gain would be $\Delta p_y$. This represents the *uncertainty* in the momentum in the $y$-direction.

From single-slit diffraction with light and [[#Particle Waves - de Broglie|de Broglie]], $\Delta p_y=\dfrac hW$. This tells us that the smaller $W$ (width of the aperture), the more accurately we know the $y$-value of the electron as it passes through the slit. But the smaller $W$ is, the greater $\Delta p_y$ becomes. Thus $W=\Delta y$. Plugging into this equation, we find that $\boxed{\Delta y \Delta p_y \ge\dfrac {\bar h}2}$ ($\bar h=\dfrac h{2\pi}$). This is the **Heisenberg Uncertainty Principle (HUP) for Momentum and Position**.
>[!quote] It is impossible to specify precisely the position and momentum of a particle at the same time.

Another way to write the HUP is the following $\boxed{\Delta E\Delta t \ge \dfrac{\bar h}2}$. This is the **Heisenberg Uncertainty Principle for Energy and Time**.
>[!quote] The shorter the lifetime of a particle in a particular state, the greater the uncertainty in its energy.
