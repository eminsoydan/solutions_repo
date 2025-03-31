# Problem 2
import matplotlib.pyplot as plt
import numpy as np

# Constants
g = 9.81  # Acceleration due to gravity (m/s^2)
dt = 0.01  # Time step (s)
total_time = 2  # Total simulation time (s)

# Initial conditions
y0 = 10  # Initial height (m)
v0 = 0   # Initial velocity (m/s)

time = np.arange(0, total_time, dt)
y_positions = []

# Simulation loop
y = y0
v = v0
for t in time:
    y_positions.append(y)
    v -= g * dt  # Update velocity
    y += v * dt  # Update position
    if y < 0:  # Stop when hitting the ground
        break

# Plot results
plt.plot(time[:len(y_positions)], y_positions)
plt.xlabel("Time (s)")
plt.ylabel("Height (m)")
plt.title("Object Falling Under Gravity")
plt.grid()
plt.show()
