---
{"dg-publish":true,"permalink":"/3-senior-year/semester2/physics/ch-25-the-reflection-of-light/","tags":["physics"],"noteIcon":"","created":"2025-10-23T00:28:51.326-07:00","updated":"2025-09-20T18:22:43.000-07:00"}
---

# Wave fronts and rays
- **Condensation**: high density areas of air (aka **wave fronts**)
- **Rarefaction**: low density areas of air

Wave fronts propagate out away from the source, which we can draw in radial lines from the source that are perpendicular to the wave fronts. ![wave front.png|350](/img/user/0_attachments/wave%20front.png)
These lines are called **wave rays**, or just **rays**. Rays point in the direction of the wave velocity. (Think of the ray as a narrow beam of light showing the direction of the light’s path.)

>In plane waves, the rays are all parallel to each other.

---

# The Reflection of Light
Most objects will reflect at least a portion of the light that hits them. How the light is reflected depends largely on the condition of the object's surface.
- **Specular reflection** - If the surface is flat and smooth, then the reflected rays are all parallel.
- **Diffuse reflection** - If the surface is rough, then the reflected rays point in random directions.

>If the incident ray, the reflected ray, and the normal to the surface all reside in the same plane, then the *angle of incidence = angle of reflection*.
- **Law of Reflection** ($\theta_i=\theta_r$)
Note: the incident and reflected angles are both measured ==relative to the normal to the surface==.

---

# Plane Mirrors
A plane mirror's image has these properties:
1. The image is upright.
2. The image is the same size as the object.
3. The image is located as far behind the mirror as the object is located in front of it.
4. The image is reversed from left to right.

## how is an image formed in a plane mirror?
![plane mirror image formation.png](/img/user/0_attachments/plane%20mirror%20image%20formation.png) 
1. Use a ray that goes straight over and reflects straight back.
2. Now use a second ray which comes up from the object at some angle.
3. Extrapolate the second ray back behind the mirror. The two extrapolated rays intersect at the [[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#virtual\|virtual image]].
## virtual
- **Virtual image**: image formed by a plane mirror
- The light rays appear to come from the image, but they don't actually emanate from there

---

# Spherical Mirrors
So [[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#Plane Mirrors\|plane mirrors]] are flat, but what happens if the mirror is curved?

We can make two different types of spherical mirrors, depending on which side we put the reflective coating:
- If the inside is reflective, then we call this a **concave** mirror.
- If the outside is reflective, then we call this a **convex** mirror.
- $C=$ center of the mirror
{ #e0c8d1}

- $R=$ radius of curvature

**Principle axis**: a line that runs through the center of the mirror
**Paraxial rays**: parallel light [[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#Wave fronts and rays\|rays]] that are close to the principle axis
{ #3aeacd}

- Paraxial rays that strike a concave mirror are reflected *toward* the principle axis.
- Paraxial rays that strike a convex mirror are reflected *away from* the principle axis.
If an object is very far away, then all of the rays coming from it are parallel, i.e. they will be paraxial rays.

All paraxial rays get reflected through the same point, called the **focal point ($F$)**.
{ #f1cc0b}

- For the concave mirror, the parallel rays get reflected through the focal point, therefore the image is real (rays come from the image).
{ #5a6df6}

	- $\boxed{f=\frac 12R}$. Since $R$ is positive, $f$ will be positive for concave mirrors.
- For the convex mirror, the parallel rays get reflected away from the principle axis, but if you extrapolate them back, it looks like they emanate from the focal point. The image is [[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#virtual\|virtual]].
	- $\boxed{f=-\frac 12R}$. Since $R$ is negative, $f$ will be negative for convex mirrors.

As the rays get farther and farther away from principle axis, they no longer pass through the focal point. This is **spherical aberration**, and the image looks fuzzy. We can correct this by using a *parabolic mirror* instead of spherical one.

Let's look more closely at the surface of the mirror where a light ray strikes. When a paraxial ray comes in, it reflects off the surface and passes through $F$. Where it strikes the mirror's surface, [[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#The Reflection of Light\|the Law of Reflector]] is obeyed.

---
# Images from Spherical Mirrors
We'll now use *ray tracing* to determine the position, size, and orientation of images formed by [[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#Spherical Mirrors\|spherical mirrors]].
## concave mirrors case 1: a paraxial ray from the object passes through F upon reflection
Recall the [[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#^e0c8d1\|center of the mirrror]]. The object is located beyond $C$.
![concave - object located beyond C.png](/img/user/0_attachments/concave%20-%20object%20located%20beyond%20C.png)
The image is located at the intersection of the reflected rays. The image properties are:
1. The image is [[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#^5a6df6\|real]].
2. The image is *inverted* with respect to the object.
3. The image is *reduced* with respect to the object.
## concave mirrors case 2: a ray from the object passes through F and then hits the mirror
Recall the [[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#^f1cc0b\|focal point]] and [[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#^e0c8d1\|center of the mirror]]. The object is located between $C$ and $F$.
![concave - object located between C and F.png](/img/user/0_attachments/concave%20-%20object%20located%20between%20C%20and%20F.png)
Image properties:
1. The image is [[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#^5a6df6\|real]].
2. The image is *inverted* with respect to the object.
3. The image is *enlarged* with respect to the object.
## concave mirrors case 3: a ray from the object that passes through C and then hits the mirror
Recall the [[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#^f1cc0b\|focal point]]. The object is located inside of $F$.
![concave - object located before F.png](/img/user/0_attachments/concave%20-%20object%20located%20before%20F.png)
We see that the reflected rays don't intersect, so we must extrapolate the reflected waves back. Image properties:
1. The image is [[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#virtual\|virtual]].
2. The image is *upright* with respect to the object.
3. The image is *enlarged* with respect to the object.
## convex mirrors case
For convex mirrors, we will use 3 slightly different rays:
1. A [[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#^3aeacd\|paraxial ray]] from the object reflects as if origination from $F$.
2. A ray from the object that heads towards $F$ gets reflected parallel to the [[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#^3aeacd\|principle axis]].
3. A ray from the object that heads toward $C$ gets reflected back along the same path as if originating from $C$.
There's only one case to consider for convex mirrors, since there's only one location for the object.
![convex - object behind the mirror.png](/img/user/0_attachments/convex%20-%20object%20behind%20the%20mirror.png)
Image properties:
4. The image is [[3_senior_year!/semester2/physics/ch. 25 - the reflection of light#virtual\|virtual]].
5. The image is *upright* with respect to the object.
6. The image is *reduced* with respect to the object.

---

# Mirror and Magnification Equations
- $f=$ the focal length of the mirror
	- if ==positive==, the mirror is ==concave==
	- if ==negative==, the mirror is ==convex==
- $d_o=$ the object distance from the mirror
	- if *positive*, the *object is in front* of the mirror
	- if *negative*, the *object is behind* the mirror
- $d_i=$ the image distance from the mirror
	- if ==positive==, the image is in front of the mirror (*real*)
	- if ==negative==, the image is behind the mirror (*virtual*)
- $m=$ the mirror magnification
- $h_0=$ the object height
- $h_i=$ the image height

**the mirror equation**: $\boxed{\dfrac1{d_o}+\dfrac1{d_i}=\dfrac1f}$ 
- **the magnification equation**: $\boxed{m=\dfrac{\text{Image height}}{\text{Object height}}=\dfrac{h_i}{h_o}=-\dfrac{d_i}{d_o}}$ 
	- if *m > 1*, the image is *enlarged*.
	- if *m < 1*, the image is *reduced*.
	- if ==$m$ is positive==, the image is ==upright== with respect to the object.
	- If ==$m$ is negative==, the image is ==inverted==.
