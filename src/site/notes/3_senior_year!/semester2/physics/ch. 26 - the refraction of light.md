---
{"dg-publish":true,"permalink":"/3-senior-year/semester2/physics/ch-26-the-refraction-of-light/","tags":["physics"]}
---

# The Refraction of Light
Visible light and all [[3_senior_year!/semester2/physics/ch. 24 - electromagnetic waves#Electromagnetic Waves\|EM waves]] travel though a vacuum with speed $c$, but light can also travel though many different materials. The atoms in these materials absorb, re-emit, and scatter the light. Thus, the *speed of light slows down* as it travels though a material. (The actual speed of light depends on the material.)

**speed of light in a vacuum**: $c=\dfrac1{\sqrt{\mu_0\epsilon_0}}$ 
**speed of light in some material**: $v=\dfrac1{\sqrt{\mu\epsilon}}$ 
- $\mu\epsilon=$ material dependent

**index of refraction**: $\boxed{n=\dfrac cv}$ (describes the speed of light in a material; ==$n \ge 1$==)
{ #87dfd4}


---

# Snell's Law
When light in a vacuum enters a more dense material, like water, the light slows down and changes direction. This bending of light as it travels between two different materials is called **refraction**.
![water refraction.png](/img/user/0_attachments/water%20refraction.png)
As the incident wave strikes the water's surface, the lower part of the wave front hits first, slowing that side of the wave. The wave bunches up here, but not on the top side. There, it's still moving fast. This causes the wave to turn or bend.
>[!note] The refracted wave has a new wavelength. In this case, it's shorter.

As the light passes though different media, its frequency *stays the same*, but its wavelength changes.
$$ f=\dfrac v{\lambda} $$
Since $\lambda$ changes, the speed changes as well to keep $f$ constant.

---

## How does light get refracted?
- If the light is passing from a *less dense medium into a more dense medium*, it gets <u>bent towards the normal</u>.
- If the light is passing from a *more dense medium into a less dense medium*, it gets <u>bent away from the normal</u>.

The relationship between the incident and refracted angles is given by **Snell's Law of Refraction**.
$$ n_1\sin\theta_1=n_2\sin\theta_2 $$
- $n_1=$ index of refraction in medium 1
- $n_2=$ index of refraction in medium 2

---

## Apparent Depth
If you're standing on the shore of a lake and you want to kill a fish with a spear, the fish would appear closer to the surface than it actually is. Thus, in order to kill it, you should aim ==slightly below== the fish's apparent position.

**Apparent depth for observer directly above the object**: $\boxed{d'=d\left( \dfrac{n_2}{n_1} \right)}$ 
- $n_2=$ index of refraction for the refracted ray
- $n_1=$ index of refraction for the incident ray

---

# Total Internal Reflection
If a light ray strikes the surface of the water, part of the ray is refracted and part is reflected. The refracted ($\theta_R$) and reflected ($\theta_r$) angles will both change if the incident angle is changed (see [[#Snell's Law]]).

If a light ray emerges from a more dense medium into a less dense medium, like water to air, part of the ray is reflected and part is refracted.
>[!note] The refracted angle is greater than the incident angle since $n_{\text{air}}<n_{\text{water}}$.

If the incident angle is increased, so is the refracted angle. The refracted angle $=90\deg$ when $\theta_i=\theta_c$; here, $\theta_c$ is the **critical angle**. Therefore, when $\theta_i=\theta_c$, $\theta_{\text{refracted}}=90 \deg$. If $\theta_i>\theta_c$, then there's no refracted ray.

All incident light is completely reflected back into the medium. This is **total internal reflection**: $\boxed{\sin\theta_c=\dfrac{n_2}{n_1}}$.

---

# Polarization, Reflection, and Refraction of Light
Light that gets [[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#The Reflection of Light\|reflected]] at some angle off a non-metallic surface becomes partially polarized. There's a special incident angle such that the reflected [[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#Wave fronts and rays\|ray]] is *completely polarized* parallel to the surface. This is the **Brewster Angle ($\theta_B$)**.

At the Brewster angle, the reflected light is polarized parallel to the surface, and the angle between the reflected rays is 90 degrees (they're perpendicular).

**Brewster angle between two media**: $\boxed{\tan\theta_B=\dfrac{n_2}{n_1}}$ 
- $n_2=$ refracted ray
- $n_1=$ incident ray
Therefore at the Brewster angle, $\boxed{\theta_b+\theta_R=90\deg}$.

---

# Dispersion of Light
Light passing through a prism gets bent or [[#The Refraction of Light|refracted]]. However, how much it gets bent depends on the "color" of the light, i.e. its ==wavelength==.

*Violet* light has a higher refractive index than *red* light, so it gets bent more, in accord with [[#Snell's Law]]. Thus a prism can separate white light into all the visible colors.

**Dispersion**: the spreading out of light into its component colors; a refraction effect responsible for rainbows

---

# Lenses
A **lens** is an optical system that [[#The Refraction of Light|refracts]] (bends) light to form an image of the object. A lens consists of two or more surfaces, at least one of which is curved.

**Simple lens system**: optical system with just one lens
**Complex lens system**: optical system with more than one lens

If a lens has a spherical surface, then incoming parallel rays converge at a common point ($F$), the *focal point*.

Like for mirrors, we can identify a *focal length* for the lens.
**Focal length**: distance between the focal point (or one of the foci) to the center of the thin lens

If the parallel rays are bent away from the principal axis, they appear to diverge from a common point - **diverging** or **concave** lens.
If the parallel rays are bent toward the principal axis, they appear to converge on a common point - **converging** or **convex** lens.

---

# Formation of Images by Lenses
[[#Lenses]] are different than [[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#Images from Spherical Mirrors\|mirrors]] since the light rays pass through the lens. We'll use ray tracing again to determine the location, size, and orientation of images formed by lens. (We'll assume the lens is *thin* relative to its focal length, which ensures that both $d_i$ and $d_o$ can be measured from the center of the lens. Also, we'll assume that the object is located on the principle axis to the ==left== of the lens.)

We'll use three principle rays to locate the image:
1. [[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#^3aeacd\|Paraxial ray]] from the object that gets refracted as if it came from $F$ (red)
2. Travels through the center of the lens unaffected (green)
3. Travels towards the opposite $F$ and comes out parallel (blue)
## converging lens case 1: the object is located beyond 2F
![converging - object beyond 2F.png](/img/user/0_attachments/converging%20-%20object%20beyond%202F.png)
*Image properties* - real, inverted, and reduced
## converging lens case 2: the object is between F and 2F
![converging - object between F and 2F.png](/img/user/0_attachments/converging%20-%20object%20between%20F%20and%202F.png) 
1. [[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#^3aeacd\|Paraxial ray]] from the object that gets refracted as if it came from $F$ (red)
2. Travels through the center of the lens unaffected (green)
3. Travels towards the opposite $F$ and comes out parallel (blue)
*Image properties* - real, inverted, and enlarged
## converging lens case 3: the object is within F
![converging - object within F.png](/img/user/0_attachments/converging%20-%20object%20within%20F.png)
*Image properties* - virtual, upright, and enlarged
## diverging lens case
![diverging lens case img.png](/img/user/0_attachments/diverging%20lens%20case%20img.png)
*Image properties* - virtual, upright, and reduced

---

# The Thin Lens and Magnification Equation
We used the [[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#The Reflection of Light\|law of reflection]] to find a relationship between the focal length ($f$), the object distance ($d_0$), and the image distance ($d_i$) for mirrors. We can do the same thing for [[#Lenses]] using [[#Snell's Law]].

**Thin Lens Equation**: $\boxed{\dfrac 1f=\dfrac 1{d_o}+\dfrac 1{d_i}}$ 
**Magnification**: $\boxed{m=\dfrac{h_i}{h_o}=\dfrac{-d_i}{d_o}}$ 

## Sign Conventions for Lenses
This assumes the object is located to the left of the lens, and your eye is located to the right of the lens.
- focal length
	- $f$ is *positive* for converging lenses
	- $f$ is *negative* for diverging lenses
- object distance
	- $d_o$ is *positive* for objects left of the lens ([[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#^5a6df6\|real]])
	- $d_o$ is *negative* for objects right of the lens ([[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#virtual\|virtual]])
- image distance
	- $d_i$ is *positive* for images right of the lens (real)
	- $d_i$ is *negative* for images left of the lens (virtual)
- magnification
	- $m$ is *positive* for images upright with respect to the object
	- $m$ is *negative* for images inverted with respect to the object

---

# Lenses in Combination
Let's look at optical system with more than one lens - a compound [[#Lenses|lens]] system.
![combination lens system.png](/img/user/0_attachments/combination%20lens%20system.png)
The final image is virtual, inverted with respect to the original object, and it is greatly enlarged.

---

# The Refractive Power of a Lens
The refractive or bending power of a [[#Lenses|lens]] depends on $f$, the focal length.

**Refractive Power**: $\boxed{\dfrac 1{f[m]}}$ 
- units - *diopters* ($D=m^{-1}$)
