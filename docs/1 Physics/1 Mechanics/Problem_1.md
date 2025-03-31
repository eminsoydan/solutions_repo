# Problem 1
# **Investigating the Range as a Function of the Angle of Projection**

## **1. Theoretical Foundation**

Projectile motion refers to the motion of an object that is launched into the air, typically under the influence of gravity alone, following a curved trajectory. The two main components of the motion are horizontal motion (constant velocity) and vertical motion (accelerated due to gravity). 

### **1.1 Equations of Motion**

The projectile motion equations can be derived using Newton’s second law in both the horizontal and vertical directions. These equations assume that there is no air resistance and that the only force acting on the projectile after launch is gravity.

#### Horizontal Motion:
- The horizontal velocity remains constant throughout the flight because no forces act in the horizontal direction (assuming no air resistance).

The horizontal position as a function of time is:

$$
x(t) = v_0 \cos(\theta) t
$$

where:
- $x(t)$ is the horizontal displacement at time $t$,
- $v_0$ is the initial velocity,
- $\theta$ is the angle of projection,
- $t$ is the time elapsed since launch.

This equation indicates that the horizontal velocity is constant since no horizontal forces are acting on the projectile.

#### Vertical Motion:
- The vertical motion is influenced by gravity, which causes a downward acceleration $g$. The vertical velocity at any time $t$ is therefore decreasing due to gravity.

The vertical displacement as a function of time is given by:

$$
y(t) = v_0 \sin(\theta) t - \frac{1}{2} g t^2
$$

where:
- $y(t)$ is the vertical displacement at time $t$,
- $v_0 \sin(\theta)$ is the initial vertical velocity component,
- $g$ is the acceleration due to gravity ($9.81 \, \text{m/s}^2$).

### **1.2 Time of Flight**

The time of flight is the time at which the projectile returns to the ground, i.e., when $y(t) = 0$. This can be solved from the vertical motion equation:

$$
y(t) = v_0 \sin(\theta) t - \frac{1}{2} g t^2 = 0
$$

Factoring out $t$:

$$
t \left( v_0 \sin(\theta) - \frac{1}{2} g t \right) = 0
$$

This gives two solutions: $t = 0$ (which corresponds to the initial launch time) and:

$$
t_f = \frac{2 v_0 \sin(\theta)}{g}
$$

Thus, the time of flight is directly proportional to the initial velocity and the sine of the launch angle. The projectile stays in the air longer with higher initial velocity and larger launch angles.

### **1.3 Horizontal Range**

The range $R$ is the horizontal distance the projectile travels before landing. It can be found by substituting $t_f$ into the horizontal motion equation:

$$
R = x(t_f) = v_0 \cos(\theta) \cdot t_f
$$

Substitute the expression for $t_f$:

$$
R = v_0 \cos(\theta) \cdot \frac{2 v_0 \sin(\theta)}{g}
$$

Simplifying:

$$
R = \frac{v_0^2 \sin(2\theta)}{g}
$$

This is the equation for the range of a projectile launched from ground level. The range depends on the initial velocity squared, the gravitational constant, and the angle of projection.

## **2. Analysis of the Range as a Function of the Angle**

### **2.1 Dependence on Angle**

From the equation for the range:

$$
R = \frac{v_0^2 \sin(2\theta)}{g}
$$

The range is maximized when $\sin(2\theta)$ is maximized. Since the maximum value of $\sin(2\theta)$ is 1, the angle $\theta$ that maximizes the range is:

$$
\theta_{\text{max}} = 45^\circ
$$

Thus, the projectile travels the farthest when launched at a 45° angle.

### **2.2 Dependence on Other Parameters**

#### **Initial Velocity $v_0$**:
The range $R$ is directly proportional to the square of the initial velocity. Doubling the initial velocity quadruples the range:

$$
R \propto v_0^2
$$

#### **Gravity $g$**:
The range is inversely proportional to the acceleration due to gravity. If gravity were weaker (e.g., on the Moon), the range would be greater for the same initial velocity and launch angle.

$$
R \propto \frac{1}{g}
$$

#### **Launch Height $h$**:
If the projectile is launched from a height $h$ above the ground, the time of flight will be longer. This modifies the range equation, and the range increases as the height increases. The general range equation for a projectile launched from height $h$ is:

$$
R = \frac{v_0 \cos(\theta)}{g} \left( v_0 \sin(\theta) + \sqrt{(v_0 \sin(\theta))^2 + 2gh} \right)
$$

### **2.3 Maximum Range**
From the previous analysis, the maximum range occurs at an angle of $\theta = 45^\circ$, but the exact relationship can be altered by the presence of air resistance, launch height, and varying gravitational fields.

## **3. Practical Applications**

### **3.1 Sports and Ballistics**
- In sports such as basketball, golf, or soccer, players aim to optimize their launch angle to maximize the distance the ball travels.
- Ballistics uses similar principles to calculate the trajectory of missiles and artillery shells.
  
### **3.2 Engineering and Spaceflight**
- Engineers use projectile motion to design launch systems, such as in the case of launching rockets into orbit or artillery shells for military applications.
- In space missions, the motion of projectiles and spacecraft is affected by the curvature of the Earth and varying gravitational forces at different altitudes.

### **3.3 Air Resistance and Real-World Corrections**
- In real life, air resistance plays a significant role in projectile motion. The drag force acting on the projectile slows it down, altering its trajectory and range.
- The Magnus effect, which results from the rotation of the projectile, creates lift and further modifies the trajectory.

## **4. Isaac Newton’s Contributions to Projectile Motion**

Isaac Newton's work laid the foundation for understanding projectile motion in a more rigorous and mathematical manner. In his *Philosophiæ Naturalis Principia Mathematica* (1687), Newton formulated the laws of motion, which govern the motion of all objects, including projectiles.

### **4.1 Newton’s Laws of Motion**

- **First Law (Inertia)**: A body remains at rest, or in uniform motion, unless acted upon by an external force. This law is essential for understanding why a projectile continues to move horizontally at constant velocity once it is launched, as there is no horizontal force acting on it in ideal conditions (assuming no air resistance).
  
- **Second Law (F = ma)**: The acceleration of an object is proportional to the net force acting on it and inversely proportional to its mass. For a projectile, the vertical motion is governed by the gravitational force, which causes a downward acceleration of $g$. The horizontal motion is unaffected by force (ignoring air resistance), and hence, the velocity remains constant.

- **Third Law (Action and Reaction)**: For every action, there is an equal and opposite reaction. This law is crucial in understanding the launch mechanism of a projectile, such as the force exerted by a cannon on the projectile and the recoil experienced by the cannon itself.

### **4.2 Newton’s Gravitation and Projectile Motion**

Newton’s law of universal gravitation explains why projectiles follow a curved trajectory under the influence of gravity. Newton proposed that every mass attracts every other mass with a force that is proportional to the product of their masses and inversely proportional to the square of the distance between their centers. The gravitational force is the key factor that influences the vertical motion of projectiles.

### **4.3 Impact on Modern Physics**

Newton’s laws provided the foundation for classical mechanics, which describes the motion of projectiles in a wide range of scenarios. These ideas were later expanded upon by other scientists, leading to more advanced models that take into account factors like air resistance and relativistic speeds.

## **5. Implementation in Python**
![image](https://github.com/user-attachments/assets/ffb30d9e-6e25-41a7-abcb-af44c8aee4f9)

Below is a Python script to visualize the range as a function of launch angle:

```python
import numpy as np
import matplotlib.pyplot as plt

def range_equation(v0, theta, g=9.81):
    return (v0**2 * np.sin(2 * np.radians(theta))) / g

angles = np.linspace(0, 90, 100)
v0 = 20  # Initial velocity in m/s
ranges = range_equation(v0, angles)

plt.figure(figsize=(8,6))
plt.plot(angles, ranges, label=f'Initial Velocity = {v0} m/s')
plt.axvline(45, color='r', linestyle='--', label='Optimal Angle')
plt.xlabel("Launch Angle (degrees)")
plt.ylabel("Range (m)")
plt.title("Projectile Range vs. Launch Angle")
plt.legend()
plt.grid()
plt.show()
