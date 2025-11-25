---
{"dg-publish":true,"permalink":"/3-senior-year/semester2/physics/ch-27-interference-and-the-wave-nature-of-light/","tags":["physics"],"noteIcon":"","created":"2025-10-23T00:28:51.250-07:00","updated":"2025-09-20T19:00:03.000-07:00"}
---

# The Principle of Linear Superposition
**Constructive interference** (**CI**): Take two waves of equal amplitude and wavelength and have them meet at a common point. If the waves are **in-phase**, then they meet crest-to-crest and trough-to-trough and their two amplitudes add to each other. The resulting wave would have an amplitude that is doubled.
{ #4bba24}


**Optical path difference** (**OPD**): the difference in distance that two waves travel
{ #ed9529}


For CI to occur, the waves have to meet crest-to-crest, so the waves must differ by an integer multiple of the wavelength $\lambda$: $\boxed{\text{OPD}=m\lambda,\ m=0,1,2,\dots}$ 

**Destructive interference** (**DI**): Take two waves of equal amplitude and wavelength and have them meet at a common point, but this time they're **out-of-phase**, meaning they meet crest-to-trough. The waves cancel each other out, and the resulting wave has zero amplitude (*is flat*).
{ #4a492b}


For DI to occur, the waves must meet crest-to-trough, so the waves must differ by any odd integer number of $\frac12 \lambda$: $\boxed{\text{OPD}=\left(m+\frac 12\right)\lambda,\ m=0,1,2,\dots}$ 

>[!note]
>All waves do this, including [[3_senior_year!/semester2/physics/ch. 24 - electromagnetic waves#Electromagnetic Waves\|EM waves]], and since light is an EM wave, light waves do this too.

For interference to continue at some point, the two sources of light producing the waves must be **coherent**, which means their phase relationship relative to each other remains constant in time.
{ #8b681b}

- If the waves were *in-phase*, they must stay in-phase until some interference.
- If the waves were *out-of-phase*, they must stay out-of-phase until some interference.

---

# Young's Double Slit Experiment
Look what happens when water strikes a barrier with two slits cut in it.
![water double slit experiment.png](/img/user/0_attachments/water%20double%20slit%20experiment.png)
Each slit acts like a [[3_senior_year!/semester2/physics/ch. 27 - interference and the wave nature of light#^8b681b\|coherent]] point source of waves. The bright regions are areas of [[3_senior_year!/semester2/physics/ch. 27 - interference and the wave nature of light#^4bba24\|CI]], and the dark regions are areas of [[3_senior_year!/semester2/physics/ch. 27 - interference and the wave nature of light#^4bba24\|DI]].

In the double slit experiment, each slit acts like a coherent light source. The two waves meet at point $P$ on a screen. $\Delta l$ is the [[3_senior_year!/semester2/physics/ch. 27 - interference and the wave nature of light#^ed9529\|OPD]] of the two light waves coming from $S_1$ and $S_2$. The waves interfere with each other.
- If $\Delta l=m\lambda$, there's ==CI, and we see a bright spot==.
- If $\Delta l=(m+\frac12)\lambda$, there's ==DI, and we see a dark spot==.

Thus we should see alternating bright and dark regions (called **fringes**) as we move along the screen and the above two conditions are satisfied.

Assume the screen is far away from the slits which are small (called the *Fraunhofer approximation*). Therefore the slits are very close together and $\theta$ is the same for each [[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#Wave fronts and rays\|ray]].

$\boxed{d\sin\theta=m\lambda}$ for constructive interference & $\boxed{d\sin\theta=\left(m+\frac12\right)\lambda}$ for destructive interference

>[!note]
> The **central bright fringe** at $\theta=0$ is the brightest fringe.
> Also, order means $m$.

This experiment gave very strong evidence that light is a wave. If it wasn't, we would only see two fringes instead of multiple.

---

# Thin Film Interference
Light waves can interfere in many situations. All we need is a difference in optical path length. If the [[3_senior_year!/semester2/physics/ch. 26 - the refraction of light#^87dfd4\|index of refraction]] of one surface is greater than the surface it's on top of, then part of a light [[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#Wave fronts and rays\|ray]] gets [[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#The Reflection of Light\|reflected]], and part gets [[3_senior_year!/semester2/physics/ch. 26 - the refraction of light#The Refraction of Light\|refracted]]. Then the refracted ray reflects back off the second surface and heads back into the air towards the eye. Thus, two rays reach our eyes, and ray 2 has traveled farther than ray 1. There is a difference in [[3_senior_year!/semester2/physics/ch. 27 - interference and the wave nature of light#^ed9529\|optical path length]].

If the first surface is then, and the ray strikes almost perpendicularly to the second, then the OPD is twice the first surface's thickness, or $\Delta l=2t$.
- If $2t=m\lambda$, there's [[3_senior_year!/semester2/physics/ch. 27 - interference and the wave nature of light#^4bba24\|CI]] and the ==first surface appears bright==.
- If $2t=(m+\frac12)\lambda$, there's [[3_senior_year!/semester2/physics/ch. 27 - interference and the wave nature of light#^4bba24\|DI]] and the ==first surface appears dark==.

**Wavelength of the light inside the first surface**: $\boxed{\lambda_{S_1}=\dfrac{\lambda_{vac}}{n_{S_1}}}$ 

When waves reflect from a boundary, it's possible for them to change their phase. For thin file, the following is used: $\boxed{\Delta l+(\text{any phase shifts})=\text{Interference condition}}$.
$$ 2t+(\text{phase shifts})=\begin{cases} m\lambda \\ (m+\frac12)\lambda\end{cases} $$

---

# Diffraction
**Diffraction**: bending of waves around obstacles or around the edges of openings (an [[3_senior_year!/semester2/physics/ch. 27 - interference and the wave nature of light#Thin Film Interference\|interference]] effect)

>[!quote]
>Every point on a [[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#Wave fronts and rays\|wave front]] acts as a tiny source of wavelets that move forward with the same speed as the wave. At a later time, the new wave front is the surface that is tangent to the wavelets.
>- *Huygens Principle* 
{ #37fe04}


$\boxed{\text{Diffraction} \approx \dfrac{\lambda}{W}}$. Thus, for more diffraction (or bending) of the waves, we want longer wavelengths and smaller openings.

---

## Single-slit Diffraction
Consider monochromatic light of wavelength $\lambda$ passing through a single, narrow slit of width $W$. As in the case for the [[3_senior_year!/semester2/physics/ch. 27 - interference and the wave nature of light#Young's Double Slit Experiment\|double slit]], here we have a central bright maximum. Why?

>[!answer]-
>[[3_senior_year!/semester2/physics/ch. 27 - interference and the wave nature of light#^37fe04\|Huygens]]: Wavelets arriving at the center of the screen are travelling parallel and essentially the same distance. Since the [[3_senior_year!/semester2/physics/ch. 27 - interference and the wave nature of light#^ed9529\|OPD]] is zero, they arrive in-phase and [[3_senior_year!/semester2/physics/ch. 27 - interference and the wave nature of light#^4bba24\|interfere constructively]].
>(The opposite is true for the dark fringes.)

$\boxed{\sin\theta=\dfrac{m\lambda}{W}}$. This is the condition for dark fringes for single-slit diffraction, with $m=1,2,3,\dots$ 

---

# Resolving Power
**Resolving Power**: the ability of an optical instrument to distinguish (or *resolve*) two closely-spaced objects

Look at the headlights of a car as it backs away from you. When it's close, it's easy to distinguish two separate headlights. As it gets farther away, you can't distinguish them clearly anymore. This inability to resolve two closely-spaced objects is due to [[3_senior_year!/semester2/physics/ch. 27 - interference and the wave nature of light#Diffraction\|diffraction]].

We have light passing through openings, i.e. any optical instrument, and it's diffraction through theses apertures that limits resolution. If the screen distance is much larger than the width of a circular aperture $D$, then $\sin\theta=\dfrac{1.22\lambda}D$.

---

## Rayleigh Criterion for Resolution
>[!quote] **Rayleigh Criterion for Resolution**: 2 closely-spaced objects are just resolved when the first dark fringe of one image falls on the central bright fringe of the other.

This judges whether or not two object are resolved.

If $\theta<\theta_{\text{min}}$, then we won't be able to resolve the two objects. Since $\theta_{\text{min}}$ is small, then $\sin\theta_{\text{min}}\approx\theta_{\text{min}}$. Thus $\boxed{\theta_{\text{min}}\approx1.22\dfrac{\lambda}D}$.

---

# The Diffraction Grating
**Diffraction grating**: made to repeat [[3_senior_year!/semester2/physics/ch. 27 - interference and the wave nature of light#Young's Double Slit Experiment\|Young's double slit experiment]] with many slits that are very close together

Each slit acts as a source of wavelets in accord with [[3_senior_year!/semester2/physics/ch. 27 - interference and the wave nature of light#Single-slit Diffraction\|Huygens]]. The figure shows how the first and second order *maxima* (bright fringes) develop.
![diffraction grating - maxima development.png|400](/img/user/0_attachments/diffraction%20grating%20-%20maxima%20development.png)

**Principal maxima of the diffraction grating**: $\boxed{\sin\theta=\dfrac{m\lambda}d}$, $m=0,\ 1,\ 2,\ 3,\ \dots$ 
- $d=$ slit separation distance, calculated by knowing the number of slits per cm
	- *(ex)* $d=\dfrac1{7500}\text{cm}=1.33*10^{-4}\text{cm}$ 

If we shined white light through a diffraction grating, we would get multiple colored bright fringes like the double slit. In a prism, the longer wavelengths are bent the most, whereas the diffraction grating bends the longer wavelengths the *most*.

---

# X-ray Diffraction
The Na (sodium) and Cl (chloride) ions form a 3-dimensional periodic array of atoms called a crystal. The distance between the atoms (**interatomic spacing**) is about $1\ A\ (1*10^{-10})$. Thus, this distance could act like the slit separation distance on a [[3_senior_year!/semester2/physics/ch. 27 - interference and the wave nature of light#The Diffraction Grating\|diffraction grating]] for waves with an appropriate wavelength.

Let's choose light whose wavelength is $~1*10^{-10}$ m. Light of this wavelength is in the ==X-ray== part of the EM spectrum. By shining X-rays on the crystal, we see [[3_senior_year!/semester2/physics/ch. 27 - interference and the wave nature of light#Diffraction\|diffraction]] effects. The diffraction pattern gives us information about the structure of the crystal and the distance between its atoms.

(X-ray diffraction is also vitally important to determining the structures of biological molecules, like proteins.)