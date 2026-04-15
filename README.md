# ENERGY-EFFICIENCY-AND-WASTE-
This project focuses on analyzing machine-level energy efficiency across different plants and time periods using SQL. The objective is to identify inefficient machines by comparing their average energy consumption per unit with plant-level statistical benchmarks.

The solution involves calculating AvgEnergyPerUnit for each machine on a monthly basis and comparing it with the plant-month average and standard deviation. Machines exceeding the threshold (average + 1 standard deviation) are flagged as "Inefficient", while others are marked as "Efficient".

Key concepts used in this project include data aggregation, grouping, joins, subqueries, and statistical analysis using SQL functions. The final output is stored in a structured table (EnergyEfficiencyFlags) that can be used for reporting and decision-making.
