## 🌞📈 Weekly Temperature Visualization – Python with Matplotlib
### 🌟 Introduction
This Python script creates a visually appealing line chart that shows temperature changes throughout a week. It uses the Matplotlib library to make data presentation simple, elegant, and easy to interpret.
--
### 🧰 Tools Used

import matplotlib.pyplot as plt
🔹 matplotlib.pyplot is a powerful plotting library used for creating static, animated, and interactive visualizations in Python.

--
### 🧾 Code Breakdown

- temperatures = [20, 22, 19, 23, 21, 24, 20]
- days = ['Mon', 'Tue', 'Wed', 'Thu', 'Fri', 'Sat', 'Sun']
  
--
### 📌 Data:

temperatures: Temperature readings for each day of the week in °C.

days: Labels for the X-axis representing days of the week.

plt.plot(days, temperatures, marker='^')
--
### 🎨 Plotting:

Creates a line graph

Adds triangle markers (^) at each temperature point to highlight data clearly

plt.title('Weekly Temperature Readings')
plt.xlabel('Day')
plt.ylabel('Temperature (°C)')
--
### 📝 Labeling:

plt.title: Adds a meaningful graph title

plt.xlabel: Labels the X-axis as "Day"

plt.ylabel: Labels the Y-axis as "Temperature (°C)"

plt.grid(True)
plt.show()
--
### ✨ Final Touches:

plt.grid(True): Adds grid lines for better readability

plt.show(): Displays the final graph
--
### 📊 Expected Output
A clean, readable line graph showing how temperatures change from Monday to Sunday, with triangle markers on each point:

![image](https://github.com/user-attachments/assets/17c47274-af51-487e-9171-6432de6e6e2e)

