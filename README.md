# Basic NumPy and Graph Plotting with Matplotlib
This work aims to applying the concept of __NumPy array and Matplotlib__ for solving physics problems by Python 3 and Jupyter Notebook. There are some solutions for tasks in this Python code.

## P5.1 - Correct Einstein's mistakes
Special relativity is the area of physics deling with incredibly large velocities. In special relitivity, the momentum _p_ of an object with velocity _v_(in m/s), and mass _m_ (in kg) is given as.

$p=m.v.\gamma, \gamma=\frac{1}{\sqrt{1-\frac{v^{2}}{c^{2}}}}$

where c$\approx$ 300.000.000 m/s is the speed of light. The program below attempts to calculate the momentum of an object with speed equal to 1/3 the speed of light, and mass m = 0.14 kg. The program has many errors, and doesn't work. Copy and run the program. Correct the errors, and make it work like intended.

## P5.2 - Rydberg's constant
Rydberg's constant $R_{\infty}$ for a heavy atom is used in physics to calculate the wavelength to spectral lines. The constant has been found to have the following value:

$R_{\infty}=\frac{m_{e}e_{4}}{8\varepsilon_{0}{2}h^{3}c}$

where,
- $m_{e}=9.109 x 10^{-31}$ m is the mass of an electron
- $e=1.602 x 10^{-19}$ C is the charge of a proton (also called the elementary charge)
- $\varepsilon_{0}=8.854 x 10^{-12}C V^{-1} m^{-1}$ is the electrical constant
- h = 6.626 x $10^{-34}$ J s is Planck's constant
- c = 3 x $10^{8}$ m/s is the speed of light.

write the program which assigns the values of the physical constants to variables, and use the variables to calculate the value of Rydberg's constant.

## P5.3 - Measure time
A ball is dropped straight down from a cliff with height $\mathnormal{h}$. The position of the ball after a time $\mathnormal{t}$ can be expressed as:

$y(t)=v_{0}t - \frac{1}{2}at^{2} + h$

where a is the acceleration (in $m/s^{2})$ and $v_{0}$ is the initial velocity of the ball (Measured in m/s). We wish to find for how long time $t_{1}$ such that $y(t_{1})=h_{1}$. The position of the ball is measured per $\Delta{t}$ seconds.

Write a program which finds out how long time $t_{1}$ it takes before the ball reaches height $h_{1}$ by using a while loop.
$h=10 m, y_{1}=5 m, \Delta{t}=0.01, v_{0}=0 m/s$ and $a = 9.81 m/s^{s}$.

![Ball Fall Motion](https://github.com/dindagustiayu/Basic-NumPy-and-Matplotlib-for-solving-physics-problems./blob/main/Sample%20Plots/Ballmotion_colormap.svg)
## P5.4 - Free Fall Motion
A ball is dropped from rest at a height of h = 100 m. The time intervals is 0.1 s up to 5 s. The constant gravitational acceleration g = 9.81 $m/s^{2}$.(a) What time does the ball hit the ground, (b) what is the velocity of the ball and (c) plot the position of the ball vs time as it falls. 

- Free Fall Motion
  - Impact time (when y(t)=0)
  
     $t_{ground}=\sqrt{\frac{2h_{0}}{g}}$
    
  - Initial Velocity at the ground

     $v_{ground}=gt_{ground}$
 
  - Position
 
    $y(t)=h_{0}-\frac{g}{t^{2}}$

 ![Fall Motion](https://github.com/dindagustiayu/Basic-NumPy-and-Matplotlib-for-solving-physics-problems./blob/main/Sample%20Plots/Fallmotion_colormap.svg)

 ## P5.6 -Relativistic Momentum
In classical physics, we define the momentum $\mathnormal{p}$ of an object with mass $\mathnormal{m}$ and velocity $\mathnormal{v}$ as 

$p=m\times v$

A satellite with mass m = 1200 kg is trapped in the gravity of a black hole. It accelerates quickly from velocity $v=0$ to $v=0.9c$, where $\mathnormal{c}$ is the speed of light, $c\approx3x10^{8}$ m/s.

(a) write a program which prints a nicely formatted table to the terminal, containing the speed of the satellite in one column, and the momentum of the satellite in the other. Use time-intervals of $0.1c$ between $0c$ and $0.9c$.

__Hint__: Use scientific notation '%e' when printing the values, to avoid incredibly large floats. Alternatively, '%g', which picks the best notation for you. Try to limit the number of decimals to a reasonable number.

![Momentum](https://github.com/dindagustiayu/Basic-NumPy-and-Matplotlib-for-solving-physics-problems./blob/main/Sample%20Plots/Relativistic_colormap.svg)
