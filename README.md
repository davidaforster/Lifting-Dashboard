# Lifting-Dashboard
One Sentence Summary: Tableau dashboard analyzing my lifting progress from April-August 2025 - includes 1RM estimates, workout frequency, and bodyweight trends.

Overview:
The purpose of this dashboard is to analyze strength training trends for the middle third of the year. As a novice lifter, my goal is to identify where I am making the most progress and where I need to focus more effort.

About the Data:
The data was sourced from two Google Sheets I created, containing information from a lifting tracker I use on my phone. Since the tracker did not allow data export, I manually built the database with lookup tables and values such as lift_id, date, lift, weight, avg_reps, muscle_group, muscle_group2, volume, estimated_1rm_epley, and estimated_1rm_mayhew. The “1RM” (1-rep max) is the maximum weight that can be lifted one time - a key metric for tracking strength progression. To calculate it, I used the average of two formulas: the Epley formula, which is a linear estimation, and the Mayhew formula, which incorporates exponential decay.

Dashboard Features:
The dashboard includes several key views:

Estimated 1RM by muscle group, filterable to include any combination of groups.

Estimated 1RM by top ten lifts, allowing for tracking of progress for one lift at a time.

A bar chart showing weekly workout frequency and whether the target of four sessions per week was met.

A chart tracking body weight gain under caloric surplus and maintenance dieting.

Tools Used:
The project was built using Google Sheets for data collection and Tableau for visualization.

Key Insights:
An interesting pattern emerged in the “Arms” muscle group: while the average 1RM has decreased over time, the individual arm lifts in the top ten have actually increased significantly (see: triceps press and preacher curl in Estimated 1RM by top ten lifts). This drop in average is mainly because I’ve added more low-weight arm exercises - like seated bicep curls, hammer curls, and triceps extensions - in the last two months that bring the average down even though my key lifts are improving.

For shoulders, the average 1RM has mostly stayed flat, largely due to instability issues I’ve experienced this year. However, the overall KPI panel shows a steady increase in average 1RM, and the top ten lifts continue to trend upward consistently.

Next Steps:
I plan to keep focusing on heavy lifting for key exercises while putting more effort into strengthening and stabilizing my shoulders. I’m also considering developing a weighted average for muscle group 1RM values to better reflect progress, especially when incorporating more low-weight lifts into the routine.

Here is a preview of the dashboard:
![Dashboard screenshot](ExerciseDashv2Preview.jpg)
