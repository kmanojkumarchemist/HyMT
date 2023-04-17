http://readme.md/
Bubble Detection and Electrochemical Analysis This program detects bubbles in a liquid and performs electrochemical analysis to calculate the rate of hydrogen gas production due to corrosion of a steel electrode.
Features 
Bubble detection algorithm accurately identifies bubbles of specified size Electrochemical analysis calculates rate of hydrogen gas production due to corrosion of a steel electrode Easy-to-use Python code with clear parameter definitions and explanations OpenCV and NumPy libraries used for image processing and calculations
Prerequisites
 Python 3.8.5 
OpenCV 4.5.1 
NumPy 1.20.1
How to Use 
Clone the repository to your local machine. 
Install the required libraries using pip: pip install opencv-python numpy.
 Open the Python script in your preferred Python editor. 
Modify the parameters and input values as necessary for your experiment. 
Run the script and wait for the results to be printed.

Input Values  
tube_height: Height of the tube in cm. tube_
diameter: Diameter of the tube in cm. 
liquid_viscosity: Viscosity of the liquid in Pa.s. 
frame_rate: Frame rate of the video capture in fps. 
time_interval: Duration of the experiment in seconds. 
corrosion_value: Corrosion rate in mm/year. 
bubble_count: Number of bubbles observed during the experiment. 
electrode_type: Type of electrode. Currently only supports steel, Aluminium, Platinum, Stainless steel and Stainless steel mesh . 
applied_current: Applied current in Ampere.
 electrode_area: Electrode surface area in m^2. 
liquid_volume: Volume of liquid in which electrode is submerged in liters. 
temperature: Temperature in Celsius. 
solution_concentration: Solution concentration in moles per liter. 
solution_medium: Solution medium, can be acidic, alkaline or neutral. 
After getting input the component captures the video feed from the webcam and passes each frame to the bubble detection component. 

Constants 
FARADAY_CONSTANT: Coulombs per mole of electrons. 
MOLAR_VOLUME: Liters per mole at STP. 
IDEAL_GAS_CONSTANT: L·atm/(mol·K).
License 
This program is licensed under the MIT License. See LICENSE.txt for more information.

Acknowledgements 
This program was created by K. Manojkumar Research scholar Department of chemistry   as a part of a Doctoral   project.
