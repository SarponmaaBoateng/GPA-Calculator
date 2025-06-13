# GPA-Calculator
Description In this project, I built an interactive GPA calculator for a hypothetical educational institution. The GPA scale of 4 was used for this project.

Methodology

Three functions were created to grade a score, assign a grade point to a score, and calculator the GPA
Using a for loop, the code loops through the range of number of courses offered. In the loop, the name, score and credit hours for the course is collected from the user and appended to a 1ist.
The GPA is calculated by using the GPA function declared and appended to the list for displace
Display the output in a pandas dataframe
Challenges When using the float(input()) function to retrieve numerical information from the user, an error (ValueError) arises when a user inputs a string.

Solution To curb this, a while loop inconjuction the try and except functionalities were added to the code. Until a user inputs the right information, he will still stay in the while loop
