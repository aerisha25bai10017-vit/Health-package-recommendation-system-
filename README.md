# Health-package-recommendation-system-
1. Overview of the Project
   
The Health Package Recommendation System is a Python-based program that recommends suitable medical check-up packages based on a person’s age and income group.
Different groups of society (Poor, Middle-Class, and Upper-Class) have different healthcare needs and financial capabilities. This project uses simple conditional logic to classify users into these groups and suggest the most beneficial and affordable health package for them.
The system ensures:
Easy classification
Accessible health guidance
Affordable package suggestions for all categories
This project can be used in healthcare kiosks, camps, or awareness programs.

2. Features

 a.User-Friendly Input
The application takes:
Name
Age
Annual Income
 b.Auto-Recommendation
Based on the inputs, the system recommends:
Poor People Health Package
Middle-Class Health Package
Premium/Lifestyle Package
Each category also changes based on age ≥ 60 (senior citizens).
c.Clear Display of Package Details
Each package contains:
Tests included
Screenings
Health services
Estimated cost range
d.Fully Automated Decision Logic
The health_package() function handles all conditional checks and returns the correct package.
e.Easily Extensible
More categories or medical tests can be added in future versions.

3. Technologies / Tools Used

Component        	                         Description

Python 3.x	                              Main programming language
Conditional Logic (if/elif)             	Used for decision-making
Functions                                	To keep code modular and clean
Console I/O	                              For reading user input and displaying output

4. Steps to Install & Run the Project

Step 1: Install Python
Download Python from:
https://www.python.org/downloads/
Install and ensure “Add to PATH” is checked.
Step 2: Save the Code
Create a file named:
health_package.py
Paste the complete code inside it.
Step 3: Run the Program
Open terminal / command prompt:
cd path/to/your/file
python health_package.py
Step 4: Input Details
You will be asked to enter:
Name
Age
Income
Step 5: View Recommended Package
The program prints the best health package for the user.

5. Instructions for Testing

When testing, check the program with different combinations:
✔ Case 1: Poor Citizen
Age < 60
Income: 20,000
→ Should show Poor Family Health Package
✔ Case 2: Poor Senior Citizen
Age ≥ 60
Income: 40,000
→ Should show Poor Senior Citizen Health Package
✔ Case 3: Middle-Class Family
Age < 60
Income: 2,00,000
→ Should show Middle-Class Family Package
✔ Case 4: Middle-Class Senior
Age ≥ 60
Income: 2,50,000
→ Should show Middle-Class Senior Health Package
✔ Case 5: Premium Lifestyle Package
Age < 60
Income: 4,00,000
→ Should show Premium Lifestyle Package
✔ Case 6: Premium Senior Package
Age ≥ 60
Income: 10,00,000
→ Should show Premium Senior Citizen Package
✔ Case 7: Invalid values
Test these inputs:
Age: negative
Income: negative
Strings instead of numbers
Expected:
Program may crash (since validation not added)
This can be added in future upgrades
