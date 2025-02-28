# Hybrid Metaheuristic Vehicle Routing Problem for Security Dispatch Operations
This repository contains the dataset associated with the paper: Hybrid Metaheuristic Vehicle Routing Problem for Security Dispatch Operations


Overview: 
This paper investigates the optimization of the Vehicle Routing Problem for Security Dispatch (VRPSD), which focuses on security and patrolling applications. VRPSD involves challenging constraints, including precise timing and strict time windows.


We propose and evaluate three metaheuristic-based algorithms:


ALNS-TA: Single-phase Adaptive Large Neighborhood Search (ALNS) with Threshold Accepting (TA).

Multiphase ALNS-TA: Multiphase ALNS combined with TA.

Hybrid Multiphase ALNS-TS-TA: Multiphase ALNS with Tabu Search (TS) and TA.


Experimental results on a dataset with 251 customer requests demonstrate that the Hybrid Multiphase ALNS-TS-TA algorithm achieves the best performance, balancing exploration and exploitation effectively.


Dataset: 
This repository includes four CSV files used in the experiments:

Service_Window.csv – Defines the time windows for each service request.

Vehicle.csv – Contains vehicle specifications, including capacity constraints.

Matrix_Schedules_In_Second.csv – Provides the time-based distance matrix for the problem instance.

Service_Time_Demands.csv – Lists the service time required for each customer request.

Contact: 
For any questions regarding the dataset or implementation details, please contact: gary_wang@sfu.ca 

