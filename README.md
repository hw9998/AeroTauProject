# Project Assignment: Aerodynamic Analysis of NACA 2412 Airfoil

## Introduction
This project aims to analyze the aerodynamic characteristics of the NACA 2412 airfoil. The analysis will be conducted using both computational tools (XFOIL/XFLR5) and theoretical approaches (thin airfoil theory), and will be compared with experimental results. Furthermore, the project involves implementing a panel method code, simulating boundary layer effects, studying and modeling flow separation, and examining unsteady aerodynamics.

## Objectives
1. Simulate the aerodynamic parameters of the NACA 2412 airfoil and 2 other NACA airfoils (0012, 2406 ) using XFOIL/XFLR5.
2. Compare the results with thin airfoil theory and experimental data.
3. Implement a panel method code to replicate the simulation results.
4. Investigate common methods to include drag into the panel method by modeling the boundary layer.
5. Study methods for flow separation and implement one of them.
6. Implement unsteady forcing on the airfoil and analyze its effects.

## Methodology

### 1. Simulation Using XFOIL/XFLR5
- **XFOIL/XFLR5 Setup**: Set up the simulation environment in XFOIL or XFLR5 for the NACA 2412 airfoil.
- **Parameter Analysis**: Run simulations to determine key aerodynamic parameters such as lift coefficient (\(C_L\)), drag coefficient (\(C_D\)), and moment coefficient (\(C_M\)) over a range of angles of attack.
- **Data Collection**: Collect and tabulate the results for comparison.

### 2. Comparison with Thin Airfoil Theory and Experimental Data
- **Thin Airfoil Theory**: Use thin airfoil theory to predict the lift coefficient of the NACA 2412 airfoil.
- **Experimental Data**: Gather experimental data from literature or databases for the NACA 2412 airfoil.
- **Comparison**: Compare the results from XFOIL/XFLR5 with those from thin airfoil theory and experimental data. Discuss the discrepancies and possible reasons for them.

### 3. Panel Method Implementation
- **Code Development**: Write a panel method code to simulate the flow over the NACA 2412 airfoil.
- **Validation**: Validate the code by comparing the results with those from XFOIL/XFLR5 and theoretical predictions.
- **Analysis**: Analyze the accuracy and limitations of the panel method code.

### 4. Boundary Layer and Drag Inclusion
- **Investigation**: Investigate common methods for including drag into the panel method by modeling the boundary layer.
- **Drela's Approach**: Refer to Mark Drela's paper on boundary layer modeling for including drag in aerodynamic simulations (Drela, M. "XFOIL: An Analysis and Design System for Low Reynolds Number Airfoils," MIT, 1989).
- **Implementation**: Implement a method based on Drela's approach to calculate the drag coefficient, you may choose to use the simplified method presented in class but you should explain throughly the limitations.
- **Comparison**: Compare the calculated drag coefficient with XFOIL results and discuss any discrepancies.

### 5. Flow Separation Modeling
- **Study Methods**: Review various methods for modeling flow separation.
- **Implementation**: Try to predict the seperation angle for NACA 2412 airfoil using your python code.
- **Analysis**: Analyze the effectiveness of the implemented method by comparing it with XFOIL predictions and experimental observations.

### 6. Unsteady Aerodynamics
- **Unsteady Forcing**: Implement unsteady forcing on the airfoil to simulate time-dependent effects.
- **Analysis**: Analyze the impact of unsteady forcing on aerodynamic parameters such as lift and drag coefficients.
- **Comparison**: Compare the results with steady-state predictions and discuss the differences.

## Tools and Software
- **XFOIL/XFLR5**: For initial simulation and data collection.
- **Python**: For implementing panel method code, boundary layer equations, and unsteady forcing.
- **Literature/Data Sources**: For gathering experimental data and theoretical predictions.

## Expected Outcomes
- A comprehensive set of aerodynamic parameters for the NACA 2412, 0012, 2406  airfoil obtained from XFOIL/XFLR5, thin airfoil theory, and experimental data.
- A validated panel method code capable of predicting aerodynamic characteristics with reasonable accuracy.
- Boundary layer implementation capable of reproducing drag coefficients comparable to those from XFOIL.
- An effective method for predicting flow separation.
- Analysis of unsteady aerodynamic effects on the NACA 2412 airfoil.

## Conclusion
This project will provide a thorough understanding of the aerodynamic behavior of the NACA 2412 airfoil through a combination of computational simulations, theoretical analysis, and code implementation. The insights gained will contribute to a deeper comprehension of airfoil aerodynamics and the effectiveness of various simulation and modeling approaches.

## References
- Anderson, J. D. (2010). Fundamentals of Aerodynamics. McGraw-Hill.
- Katz, J., & Plotkin, A. (2001). Low-Speed Aerodynamics. Cambridge University Press.
- Drela, M. (1989). "XFOIL: An Analysis and Design System for Low Reynolds Number Airfoils," MIT.
- Experimental data sources such as NASA technical reports and aerodynamic databases.
