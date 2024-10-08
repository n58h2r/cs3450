java c
Assignment #1
MECHENG 754: Management and Control of Electric Vehicle Batteries
Fall 2024
Assignment Due date: Thursday, Oct 10th, 2024, at 12:00 Midnight.
This Assignment will cover the following: literature review of battery modeling techniques, State of Charge-Open Circuit Voltage (SOC-OCV) derivation, and SOC-OCV curve fitting.
Problem 1 (15 pts):
Prepare a 4-page literature review (12-pt font, single spacing) on the following topics:
1. Modeling, SOH Estimation, and Aging/Degradation of Second-Life Batteries (2 pages)
o Review current modeling approaches and SOH estimation methods for second-life batteries.
o Address key aging mechanisms, data integration, and real-world application scenarios.
o Highlight emerging techniques and areas for future research.
2. Ultrafast Charging Modeling (2 pages)
o Summarize advancements in ultrafast charging models, focusing on impacts on battery performance and safety.
o Evaluate trade-offs between charging speed, thermal management, and longevity.
o Include recent case studies and optimization strategies.
Ensure each section critically reviews key research, identifies gaps, and suggests future directions.
Problem 2 (15 pts):
To obtain the SOC-OCV relationship, a static capacity test is conducted at a very low C-rate (C/15) to minimize battery dynamics. Starting from a fully discharged battery, the battery is charged until the maximum voltage is reached. Afterward, the battery is discharged at the same rate until the minimum voltage (cut-off) is attained. The battery charging and discharging curves are not identical due to hysteresis.
Using the experimental data files “Charge_SOCOCV.csv” and “DisChrg_SOCOCV.csv” along with the skeleton m-file “Assignment1_P2_Skeleton” provided to do the following:
1. (1 pts) Load the charging and discharging data files. Com代 写MECHENG 754: Management and Control of Electric Vehicle Batteries Fall 2024 Assignment #1
代做程序编程语言plete the skeleton file provided and submit it with your answer.
2. (2 pts) The data provided is sampled at 10 Hz (10 samples per second). To reduce the data size, resample the data provided at 1Hz. Complete the skeleton file provided and submit the completed m-file with your answer.
3. (2 pts) Plot charging and discharging voltage curves vs. time on the same figure. Print your name and student ID on top of the figure.
4. (2 pts) Plot charging and discharging voltage curves vs. SOC. Print your name and student ID on top of the figure.
5. (2 pts) Calculate the hysteresis curve. Complete the m-file provided.
6. (2 pts) Plot the hysteresis curve vs. SOC. Print your name and Student ID on top of the Figure.
7. (2 pts) Calculate the average of both charging and discharging voltage curves. Complete the skeleton file provided and submit the completed m-file with your answer.
8. (2 pts) Plot the SOC vs. averaged OCV. Print your name and student ID on top of the figure.
Problem 3 (15 pts):
Use the State of Charge (SOC) and Open Circuit Voltage (OCV) data provided in the excel file: “SOC_OCV.xlsx” and use the skeleton file provided, “Assignment1_P3_Skeleton” to do the following:
1. (2 pts) Load the data and submit your M-file that plots the SOC Vs. OCV curve, plot your name on top of the figure.
2. (3 pts) Consider the following polynomial for the OCV:
OCV(SOC) = p0 + p1 SOC + p2SOC2 + p3SOC3
Plot the identified polynomial coefficients.
3.   (3 pts) Plot the error curve between the identified polynomial and the actual SOC-OCV curves, print your name and student ID on top of the figure.
4.    (4 pts) Repeat the procedure for various orders (9, 10, and 12), plot all curves on one plot.
5.    (3 pts) Indicate the least order fit that should provide satisfactory results.



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
