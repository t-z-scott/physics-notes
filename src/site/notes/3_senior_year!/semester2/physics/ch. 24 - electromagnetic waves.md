---
{"dg-publish":true,"permalink":"/3-senior-year/semester2/physics/ch-24-electromagnetic-waves/","tags":["physics"]}
---

# Electromagnetic Waves
- *tl;dr* 
	1. Stationary charges create electric fields.
	2. Moving charges (constant velocity) create magnetic fields.
	3. Accelerating charges create electromagnetic waves.

Take a single positive charge and wiggle it up and down. The charge changes position as a function of time, thus, the [[3_senior_year!/semester2/physics/ch. 18 - electric forces and electric fields#Electric Field\|electric field]] it creates change in time.

But since the charge is moving, it constitutes a current. The current points *up* when the charge moves up, and the current points *down* when the charge moves down. This current, like all currents, creates a [[3_senior_year!/semester2/physics/ch. 21 - magnetic fields#Magnetic Fields\|magnetic field]]. By [[3_senior_year!/semester2/physics/ch. 21 - magnetic fields#direction of magnetic field lines around a wire (RHR-2)\|RHR-2]], we see that when the current points up, the magnetic field points into the screen, and when the current points down, the magnetic field points out of the screen. Therefore, this is a changing magnetic field and a changing electric field which are ==perpendicular== to each other. The fields move out away form the source (the accelerating charge).
## Propagation of EM Waves
An EM wave is a **transverse wave** (the wave motion is at right angles to the direction of propagation).

>The changing electric field induces a [[3_senior_year!/semester2/physics/ch. 21 - magnetic fields#Magnetic Fields\|magnetic field]] (which also changes), and this changing magnetic field induces an [[3_senior_year!/semester2/physics/ch. 18 - electric forces and electric fields#Electric Field\|electric field]], etc.

EM waves don't need a medium to travel through. They can propagate in a vacuum.

Maxwell's wave equation (**speed of an EM wave**): $\Delta*B=\mu_0J+\mu_0\epsilon_0\dfrac{dE}{dt}$. From partial differential equations, we identify the speed$^2$ of the wave as one over the coefficient on $dE/dt$. Thus we could write the wave equation as $\Delta*B=\mu_0J+\dfrac{1}{v^2}\dfrac{dE}{dt}$.

Therefore: 
$$ v^2=\dfrac1{\mu_0\epsilon_0}\rightarrow \boxed{v=\dfrac1{\sqrt{\mu_0\epsilon_0}}}\rightarrow v=\dfrac1{\sqrt{(4\pi*10^{-7})(8.85*10^{-12})}}\rightarrow v=\dfrac1{3.334*10^{-9}}\rightarrow v=2.999*10^8\ m/s $$
EM waves propagate at the ==speed of light==.

---

# Electromagnetic Spectrum
> Since [[#Electromagnetic Waves|EM waves]] move at the [[#Propagation of EM Waves|speed of light]], light itself must be an EM wave.

Like any wave, EM wave have a frequency, a period, and an amplitude. We know that $v=f\lambda$, and since $v=c$, we get $c=f\lambda$ for EM waves.
- $c=$ speed of light
- $f=$ frequency (Hz)
- $\lambda=$ wavelength (m)
Therefore $f=\dfrac{c}{\lambda}$. *Higher frequencies mean shorter wavelengths*.

---

# The Speed of Light
$$ \boxed{c=3.00*10^8} $$
- Moon to Earth -> 1.3s
- Sun to Earth -> 8 mins

1 **light year** (**ly**) = the distance light travels in 1 year $=9.5*10^{15}$ 

---

# Energy Carried by EM Waves
[[#Electromagnetic Waves]] carry energy just like any other wave. An EM wave consists of both an [[3_senior_year!/semester2/physics/ch. 18 - electric forces and electric fields#Electric Field\|electric]] and [[3_senior_year!/semester2/physics/ch. 21 - magnetic fields#Magnetic Fields\|magnetic field]], and [[3_senior_year!/semester2/physics/ch. 19 - potential energy#energy\|energy]] is contained in both fields.

A measure of the energy stored in an electric field is given by the **energy density**: $\text{Electrical Energy Density}=\dfrac{\text{Electrical Energy}}{\text{Volume}}=\dfrac{1}{2}\kappa\epsilon_0E^2$.

$\kappa$ is the dielectric constant, and it's 1 in a vacuum. So in a vacuum, $\boxed{ \text{Electrical Energy Density}=\frac{1}{2}\epsilon_0E^2 }$.

We find a similar expression for the energy density in the magnetic field: $\boxed{ \text{Magnetic Energy Density}=\dfrac1{2\mu_0}B^2 }$. The total energy density is the sum of these two, $u=\dfrac{1}{2}\epsilon_0E^2+\dfrac1{2\mu_0}B^2$.

But in an EM wave, the electric field and magnetic field carry the same energy. Thus $\dfrac{1}{2}\epsilon_0E^2+\dfrac1{2\mu_0}B^2$. We can rewrite the total energy density in terms of just $E$ or $B$: $\boxed{ u=\epsilon_0E^2=\dfrac1{\mu_0}B^2 }$.

**Total energy density in an EM wave**: $\boxed{E=cB}$.
$E \varpropto P$; proportionality constant is $c$ 
## energy density in rms
The magnitude of the electric and magnetic fields in an EM wave fluctuate in time. It is useful to consider an *average value* of the two fields. This is called the **rms** of **root-mean-square** value of the fields: $E_{rms}=\dfrac{E_0}{\sqrt{2}}$ // $B_{rms}=\dfrac{B_0}{\sqrt{2}}$. Here, ==$E_0$ and $B_0$ are the peak== values of the two fields.

Now can calculate an average density using the rms values:
$$ \boxed{\bar{u}=\dfrac12\epsilon_0E^2_{rms}+\dfrac1{2\mu_0}B^2_{rms}} $$

---

So as EM waves propagate through space, they carry energy along with them. The transport energy is related to the **intensity** of the wave. Intensity of a wave as the power per unit area: $S=\dfrac PA \rightarrow \dfrac w{tA} \rightarrow \dfrac E{tA}$ 

$\boxed{S=cu} \rightarrow S=\dfrac c{2\mu_0}B^2$ 
- $S=$ intensity
- $c=$ speed of light
- $u=$ energy density
In terms of rms values, $S\rightarrow \bar{S}$, the *average intensity*.

---

# The Doppler Effect
>[!quote]
>When the observer of a wave or source of the wave (or both) is moving, the observed wave frequency is different than that emitted by the source.

- [[#Electromagnetic Waves|EM waves]] also exhibit a Doppler effect, but
	1. They don't require a medium through which to propagate, and...
	2. Only the relative motion of the source to the observer is important, since the speed at which all EM waves move is the same, the speed of light.

If the EM wave, the source, and the observer all travel along the same line, then the **shift in frequency** is $\boxed{f_0=f_s\left( 1\pm\dfrac{v_{rel}}c \right)}$.
- $f_0=$ observed frequency
- $f_s=$ frequency emitted by the source
- $v_{rel}=$ relative velocity between observer and source
- ==for speeds $v_{rel}<c$==,
	- $+$ is used when the object and source move *toward* each other
	- $-$ is used when the object and source move *away* from each other

---

# Polarization
[[#Electromagnetic Waves]] are transverse waves and can be **polarized**.

The [[3_senior_year!/semester2/physics/ch. 18 - electric forces and electric fields#Electric Field\|electric field]] part of an EM wave oscillates up and down as the wave [[#Propagation of EM Waves|propagates]]. Thus the wave oscillates are perpendicular to the direction of travel and occur only in one direction. This wave is **linearly polarized**.
- (A vertical slit would allow the wave to pass through, since the slit is parallel to the oscillations. A horizontal slit would block the wave, since the slit in perpendicular to the oscillations.)
- Polarized light can be *produced* with an antenna. The up and down vibrations of the electrons in the antenna produce polarized waves whose direction is determined by the orientation of it.

Incandescent light is **unpolarized**, resulting from many atoms vibrating in all possible orientations.

---

## converting unpolarized to polarized light
**Polarizer** (aka **polaroid**): device that converts unpolarized light to polarized light by blocking all but one of the electric field orientations

**Transmission axis**: the one direction that a polarizer allows light to pass through it

>If the intensity of the unpolarized light is $S$ before it passes through the polarizer, then the intensity of the polarized light coming out will be $1/2\ S$.

---

## Malus' Law
Once light has been polarized, another polarizer called an **analyzer** to change the direction and intensity of the polarized light.

We know that intensity is $S=c\epsilon_0E^2$, $\therefore S \varpropto E^2$. Out of the analyzer, $S \varpropto E^2 \cos^2 \theta$, so both the intensity and polarization direction can be adjusted by changing the angle of the analyzer.

**Average intensity of light leaving the analyzer**: $\boxed{\bar S=\bar S_0 \cos^2 \theta}$ 
- $\bar S_0=$ average intensity of light entering the analyzer
- $\theta=$ angle between the electric field of the polarized light leaving the polarizer and the transmission axis of the analyzer