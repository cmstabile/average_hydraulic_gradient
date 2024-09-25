# average_hydraulic_gradient
 Average Hydraulic Gradient (AHG) Calculator
This Python program calculates the Average Hydraulic Gradient (AHG) from groundwater flow direction based on user inputs of groundwater elevations and distances between points.
Table of Contents
Description
Features
Requirements
Installation
Usage
Code Explanation
License
Description
The Average Hydraulic Gradient (AHG) is a measure used in hydrogeology to understand the underground water flow between multiple points (A, B, C). The program calculates the hydraulic gradients between these points, averages them, and outputs the result. It is a helpful tool for groundwater modeling and environmental studies.
Features
Easy-to-use command-line interface.
Input validation to ensure correct data types.
Accurate calculation of hydraulic gradients between specified points.
Display of individual gradients and the overall average.
Requirements
To run this program, you need the following:
Python 3.x: Make sure you have Python installed. You can download it from python.org.
Installation
Clone the repository (or create a repository for this):
bash
Copy code
git clone https://github.com/yourusername/ahg-calculator.git
cd ahg-calculator
Run the program: Simply execute the script from the terminal.
bash
Copy code
python AHG.py
Usage
After running the script, the program will prompt you for input values:
Groundwater elevation at Point A
Groundwater elevation at Point B
Groundwater elevation at Point C
Distance between Point A and Point B (in feet)
Distance between Point A and Point C (in feet)
Based on your input, the program will calculate and display:
Hydraulic Gradient between Point A and Point B.
Hydraulic Gradient between Point A and Point C.
The Average Hydraulic Gradient (AHG).
Example:
bash
Copy code
Average Hydraulic Gradient (AHG) Calculator
Enter the groundwater elevation at Point A: 100
Enter the groundwater elevation at Point B: 90
Enter the groundwater elevation at Point C: 85
Enter the distance between Point A and Point B (in feet): 50
Enter the distance between Point A and Point C (in feet): 75
Hydraulic Gradient between Point A and Point B: 0.2000
Hydraulic Gradient between Point A and Point C: 0.2000
Average Hydraulic Gradient (AHG): 0.2000
Code Explanation
1. hydraulic_gradient Function
This function calculates the hydraulic gradient between two points using the formula:
Gradient
=
Elevation at Point A
−
Elevation at Point B
Distance between them (in feet)
Gradient= 
Distance between them (in feet)
Elevation at Point A−Elevation at Point B
​
 
2. average_hydraulic_gradient Function
This function:
Prompts the user to enter groundwater elevations for Points A, B, and C.
Prompts for the distances between Points A & B, and A & C.
Calls the hydraulic_gradient function to calculate the gradients between these points.
Averages the two gradients to give the Average Hydraulic Gradient (AHG).
3. Input Validation
The program ensures that the user inputs numeric values. If the input is invalid (non-numeric), an error message is displayed, and the program exits.
4. Running the Program
You can run the program by executing the script in a terminal, and the results will be displayed in a clean, readable format.
License
This project is open-source and available under the MIT License.
Additional Notes:
Contributions: Claudio M Stabile
This structure provides clarity and ensures anyone visiting the repository can easily understand what the project is about, how to use it, and how the code works.
