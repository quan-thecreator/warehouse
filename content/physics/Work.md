---
title: Work and Energy
date: 2024-10-06
---

# Work Done by Constant Force

In this current understanding of work in physics, only *transnational* motion is important. The work done to an object by constant force - both in magnitude and direction - is defined to be the product of the magnitude and direction of the displacement and the force parallel to the displacement. This only functions for the force component parallel to the displacement. Therefore:
$$
W=F_\parallel*d 
$$
If the object is moving horizontally, for example, work can be written as:
$$
W=Fd\cos\theta 
$$
Also, Work is a scalar quantity, no direction. magnitude, or any other attributes of a vector. When force and displacement are in the same direction, $\theta=0$, $\therefore \cos\theta=1$.


> [!NOTE] Example 1 
>   How much work did you do if you pushed a loaded grocery cart a distance of $50$ m by exerting a force of $30$ N on the cart?

> [!faq]- Answer 1 
> You did $30$ N $*$ $50$ m $=1500 \mathrm{N}*\mathrm{m}$ of work. 

A Newton meter also has an SI unit: the **joule**. It's also important to note that a force can be exerted on an object and do no work. That's because simply having a non-zero magnitude of force is not enough, one must also have a similarly qualified displacement. Additionally, remember this?
$$
v_2^2=v_1^2+2ad
$$
Using Newton's second law:

$$
W_{\mathrm{net}}=F_{\text{net}}d=mad=m(\frac{v_2^2-v_1^2}{2d})=m(\frac{v_2^2-v_1^2}{2})
$$ 
That could be distilled down to:
$$
W_{\text{net}}=\tfrac{1}{2}mv_2^2-\tfrac{1}{2}mv_1^2 
$$
Where transnational kinetic energy (KE):
$$
\textbf{KE}=\tfrac{1}{2}mv^2 
$$
Where: 
$$
W_{\text{net}}=\textbf{KE}_2-\textbf{KE}_2
$$

>   The net work done on an object is equal to the change in the object's kinetic energy.

## Potential Energy 

Using the above equations for work, displacement in the vertical axis is substituted for $\Delta h$, or the change in height. Work of vertical extension can also be denoted as:
$$
W_{\mathrm{ext}}=\textbf{PE}_1-\textbf{PE}_2=\Delta\textbf{PE}_G
$$
All of this is where potential gravitational energy is defined as:
$$
\textbf{PE}_G=mgy
$$
Where $y$ is the height of the object above some reference point, the table, ground, or something you get it. Work cannot be negative, so you might have to rearrange the equations to make it so that the difference in potential energy is multiplied by $-1$. Forexample, if the object was falling, the work done by gravity would have to be calculated using: 
$$
W_G=-mg(y_2-y_1)=-\Delta\textbf{PE}_G
$$

# Power 
Power is defined as the *rate at which work is done.* The alternate definition is the **rate at which energy is transformed.** 
$$
\bar{P}=\text{average power}=\frac{\text{work}}{\text{time}}=\frac{\text{energy transformed}}{\text{time}}=\frac{W}{t}=F\bar{v}
$$
Or in the better universe of calculus:
$$
P=\frac{\mathrm{d}W}{\mathrm{d}t}
$$
An important characteristic of all engines (machines that transform stored potential energy into kinetic energy) is their **efficiency** $e$. I must note that the use of $e$ is incredible insensitive and stupid, but I digress. 
$$
e=\frac{P_{\mathrm{out}}}{P_\mathrm{in}}
$$
# Work from Force and Displacement Vectors

Given:
- **Force vector**: \( \vec{F} = \langle F_x, F_y, F_z \rangle \)
- **Displacement vector**: \( \vec{d} = \langle d_x, d_y, d_z \rangle \)

The **work \(W\)** is the dot product (scalar product) of these two vectors:

\[
W = \vec{F} \cdot \vec{d} = F_x d_x + F_y d_y + F_z d_z
\]

## Key Properties of the Dot Product
1. **The result is a scalar**: Even though both force and displacement are vectors, the dot product outputs a single number (scalar) representing the total work.
2. **Geometric interpretation**: 
   \[
   W = |\vec{F}| \, |\vec{d}| \, \cos \theta
   \]
   where \( \theta \) is the angle between the force and displacement vectors. This shows that only the component of the force along the direction of displacement contributes to the work.

## Why Work is a Scalar and Not a Vector
- **Work measures energy transfer**—it doesn’t have direction but only magnitude (e.g., Joules). 
- If you tried to make it a vector, it would not have a meaningful physical interpretation since energy doesn’t have a direction in space—it just moves from one system to another.

## Example Calculation
If \( \vec{F} = \langle 5, 3, 0 \rangle \, \text{N} \) and \( \vec{d} = \langle 2, 4, 0 \rangle \, \text{m} \), the work done is:

\[
W = 5(2) + 3(4) + 0(0) = 10 + 12 = 22 \, \text{J}
\]

---

In summary, work is always a **scalar quantity**, even though it is derived from two vectors (force and displacement).
