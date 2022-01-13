# Propeller Design and Analysis
# Introduction
Hello There! 
I'm A Aerospace/Aeronautical Engineering Students currently diving too much time in MATLAB With further intrest in Java and Phyton.<br>
As this is just another upload from my assignment, Please do forgive me for doing something wrong.<br>
Further Feedback is welcomed as i dont get one from my proffesor.<br>

# Story Behind this Program
Started as a homework for design and analysis of propeller in excel.<br>
Later turns out to be a user based input calculation for propeller with multiple off design analysis for single propeller designed.<br>
and yes, i put too much work for this program that probably does not affect my grade so much.<br>

# What can this program do
- Calculating the chrord and twist angle distribution throughout the propeller blades with data of NACA 4412 as the airfoil of the propeller<br>
- With input at the command window such as :<br>
  - Input method (Power or Thrust)<br>
  - Propeller Diameter<br>
  - Number of Blades<br>
  - Number of element (spanwise) <br>
  - Root to tip ratio<br>
  - Axial Velocity<br>
  - Air density and dynamic viscosity<br>
  - Reynolds number assumption and angle of attack<br
  - Range of Velocity analyzed<br>
  - Range of RPM analyzed<br>
  - Range of pitch analyzed (not avaiable in current release)<br>
  - Reynolds & Power iterative error<br>
- With Output of : <br>
  - Propeller geometry (chord & twist distribution), Reynolds number distribution<br>
  - Thurst and power coefficient at respective analysis<br>
  - Effeciency at respective analysis<br>
<br>

# What this program does not do (yet)
- Calculating the temperature for one dimensional heat conduction with each end holds at a different temperature (Non - Homogeneous)<br>
- Determining The time with a maximum temperature as an input<br>
# What's The difference in difference version? <br>
Glad you ask because this code already have two version available (30 June 2021)<br>
- Version 1.0 <br>
  - Computation of The temperature using a single loop for the temperature by using Matlab Integral Fucntion<br>
  - Does not give the equation for Cn and U(x,t)<br>
  - Computation requires long time for 3000 data points at 100 order within +-5 minutes per temperature<br>
  - Computation is limited with one order input and three time elapsed input<br>
  - Plotting only based on a sigle order input<br>
- Version 2.0 <br>
  - Computation of Temperature are splitted into two loops with Cn and U(x,t) separated by using Matlab int function for Cn<br>
  - Displaying equation for Cn and U(x,t) in the command window<br>
  - Computational time is shortened as it does not requiring integration at each loop<br>
  - Computational is unlimited with as much as user input for order count and time elapsed (Though only debugged at max 3 each)<br>
  - Plotting Based on categorization of order and time elapsed<br>
# Disclaimer
- If you are using this code to do a calculation i did not held any responsiblility of any wrong data outputs that may affected you (altough Feedback is very much welcomed)<br>
- This is copyrighted by using MIT license with the details in the license file<br>
