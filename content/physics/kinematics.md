---
title: Vectors and Kinematics
date: 2024-08-19
---
> One must always start a study into the heavily crippled IB editions of the glorious subject of Physics with the initial understanding that the road ahead lead to pain immeasurable.
>
> -> Prime of the Faith


# Motion in 1D 
In this rendering of motion, you will *never* need to use vector quantities to describe movement due to the scalar nature of all quantities discussed.
## Reference Frames and Displacement
- Any measurement about motion is taken in terms of a *reference frame*.
> [!NOTE]
> **Example:** A train that moves with respect to the ground being held stationary, is not moving with respect to a stationary person inside that train. If a person were to walk, at let's say $5$ km/s toward the back of the train while it moves forward at $80$ km/h, the person is moving at $75$ km/h with respect to the stationary ground.
- In one dimension, only one axis, the $x$-axis of a coordinate plane is used.
- the *net* distance an object has traveled is known as *displacement*
- *total distance* is the overall distance traveled by the object/particle regardless of reference frame or initial/final positions
- change in positions is described using $\Delta x$

## Average Velocity
It is important to note that this equation was derived from the more complicated calculus variant of the velocity equation. There are 2 important terms here.

$$
\text{average speed}=\frac{\text{distance traveled}}{\text{time elapsed}}=\frac{\Delta x}{\Delta t}
$$
For any form of velocity, the speed is simply calculated by using the magnitude of the velocity vector $||\vec{v}||$, but since we exist in one dimension now, we will use $|v(t)|$
## Instantaneous Velocity
If the position equation is defined as $x(t)$, then:
$$
\text{instantaneous velocity} = \tfrac{\mathrm{d}x}{\mathrm{d}t} = v(t) = \lim_{\Delta t \to 0}{\tfrac{\Delta x}{\Delta t}}
$$

## Average Acceleration
The acceleration of an object is the rate at which the velocity of said object changes. **Average Acceleration** is defined as the change in velocity from 2 distinct points divided by the change in time between those 2 distinct points.
$$
\text{average acceleration} = \frac{\text{change of velocity}}{\text{time elapsed}}
$$
Or more mathematically:
$$
a=\frac{v_2-v_1}{t_2-t_1}=\tfrac{\Delta v}{\Delta t}
$$

## Instantaneous Acceleration 
If the velocity function is defined as $v(t)$ (this notation only applies to 1 dimension):
$$
a(t)=\tfrac{\mathrm{d}v}{\mathrm{d}t}=\lim_{\Delta t \to 0}{\tfrac{\Delta v}{\Delta t}}
$$
Please take calculus/study calculus if you want a neuron or two to function during the course of this, well, course.

## Motion at Constant Acceleration
During this section and any point you use these formulas, always take $t_0$ to be equivalent to $0=t_1$. This allows for the following line of reasoning:
$$
\bar{v}=\frac{x-x_0}{t-t_0}=\frac{x-x_0}{t}
$$
This clearly makes sense because $x_0$ is taken to be the initial position of the particle in 1D, and $t_0$ is taken to be simply $0$, when the clock starts. Therefore acceleration must be a constant like so:
$$
a=\frac{v-v_0}{t}
$$
Firstly, it is important to note that all variables without subscripts are taken to be definitions of that variable completely. In contrast, when you saw that $v$ had a little *bar* on top of it, $\bar{v}$ meant to be the ***average*** of $v$. Moving on, if you are required to find the velocity of an object after elapsed time $t$:
$$
v=v_0+at 
$$
> [!NOTE]
> **Example:** You are given that the acceleration of a motorcycle is constantly $4.0 \mathrm{m}/\mathrm{s}^2$. You need to find the speed of that motorcycle (note that we haven't given you any sense of position, $\therefore$ did not ask for velocity) after elapsed time $t=6.0\mathrm{s}$. The motorcycle starts from total rest, and when $t_1=t_0=0$. 

> [!faq]- Answer
> $4.0*6.0=24\mathrm{m}/\mathrm{s}$

Next, calculating the position:
$$
x=x_0+\bar{v}t 
$$
Because of the symmetric and uniform growth of the velocity over time:
$$
\bar{v}=(\frac{v_0+v}{2})t=x_0+t(\frac{v_0+v_0+at}{2})=x_0+t(\frac{2v_0+at}{2})
$$
This finally results in the formula for position in these scenarios:
$$
x=x_0+tv_0+\tfrac{1}{2}at^2
$$

## Objects in free fall
Just remember that $g=9.80\mathrm{m}/\mathrm{s}^2$


#physics