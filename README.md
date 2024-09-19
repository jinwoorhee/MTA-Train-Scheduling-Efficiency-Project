# MTA-Train-Scheduling-Efficiency-Project
 A comprehensive MTA train scheduling and optimization solution to address crowding on key lines. The project includes database design, normalization, and query analysis for efficient scheduling and employee management.


Overview
This project, developed for the CIS 3400 course at Baruch College, focuses on solving the issue of excessive crowding on the MTA subway lines in Manhattan, particularly during peak hours. Our solution aims to optimize train schedules, improve service reliability, and streamline the management of train and employee schedules.

Problem Statement
The MTA faces significant overcrowding on specific subway lines, such as the 1, 2, 3, N, Q, and R, especially during rush hours. This leads to long delays, overcrowded platforms, and poor commuter experiences. The main objective of this project is to provide accurate train schedules, optimize train frequency, and better manage the flow of passengers.

Proposed Solution
Train Scheduling: Create accurate and transparent train schedules to help commuters better plan their trips and reduce waiting times during peak hours.
Passenger Control: Implement a system to regulate the number of passengers entering subway platforms, especially during busy periods.
Train Frequency: Analyze and adjust train frequency to distribute passenger loads evenly and minimize crowding. This includes adding more trains when necessary.
Employee Scheduling: Sync conductor and employee schedules with peak times to ensure smooth train operations and reduce delays.
Database Design
We designed a relational database to manage and track information related to trains, stations, routes, and employee schedules. The database includes the following tables:

Trains: Contains details like train ID, name, type, line, and capacity.
Stations: Stores information on station ID, name, division, borough, and line.
Routes: Defines routes with departure and termination stations, distance, and duration.
Train Schedule: Manages train schedules by linking train IDs, route IDs, and conductor IDs, along with departure and arrival times.
Employees: Maintains employee details, including personal information and contact details.
Employee Schedule: Tracks employee work shifts, including start and end times and assigned train schedules.
Conductor: Handles specific information about conductors, such as certification status.
Normalization
The database follows standard normalization practices to ensure efficiency and data integrity. Key steps include:

1NF: Eliminating repeating groups to ensure each table represents a valid relation.
2NF: Removing partial key dependencies to ensure each non-key attribute is fully functionally dependent on the primary key.
3NF: Eliminating transitive dependencies to maintain a clean relational structure.
Query Analysis
To optimize the train schedules, we analyzed route durations and capacities. We identified that lines 3, 4, and 5 experienced the most delays due to long routes and insufficient train capacity. Based on this, we recommended increasing the capacity or adding additional trains on these lines.

Sample queries were used to extract data on route distances, average durations, and train capacities, which informed our recommendations for improving schedule regularity and reducing delays.

ER Diagram
The entity-relationship (ER) diagram represents the database structure and relationships between different entities such as Trains, Routes, Stations, Employees, and Schedules. This helps visualize how the data is interconnected and aids in efficient database management.

Conclusion
Our solution provides a comprehensive approach to solving the problem of overcrowding on MTA subway lines. By optimizing train schedules and improving employee scheduling, we aim to enhance the commuting experience for MTA users.

Contributors
Crystal Leon: crystal.leon@baruchmail.cuny.edu
Tata Saoidoh: tata.dagnogo@baruchmail.cuny.edu
Yongqiang Zhou: yongqiang.zhou@baruchmail.cuny.edu
Jinwoo Rhee: jinwoo.rhee@baruchmail.cuny.edu
Mohammed Chenafi: mohammed.chenafi@baruchmail.cuny.edu
