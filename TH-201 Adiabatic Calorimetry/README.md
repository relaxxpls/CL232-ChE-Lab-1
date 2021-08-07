# CL 232 - Lab 1

## Title

Determination of Partial molar enthalpies by Adiabatic Calorimetry

## Group

* Sub group code: **A2d**
* Members:
  * Laxman Desai
  * Akshata Jain
  * Kshitij Sovanee
  * Mahesh Prajapati
  * Kriti Chaturvedi
## Date of Experiment: 05-08-2021
 
## Date of Report Submission: 07-08-2021 

## Objectives

1. To determine the water equivalent of calorimeter and finding the specific heat capacity of solution.
    
2. To determine the Heat of mixing of solution and partial molar enthalpy of water and acetone at x=0.5 and partial enthalpy of mixing at infinite dilution.

## Notes on the Procedure

* Rinse the cylindrical container using the chemical to be poured in it. Reserve one container for each chemical.
* Check whether the stirrer works properly.
* Calculate the volume of each component required for each value of concentration.
* Pour the required volume of bulk solvent (component with higher mole fraction) into the adiabatic calorimeter and take the temperature reading (T0). 
* Pour the required volume of other component in the adiabatic calorimeter and start the power source and stopwatch. Note the voltage, current and temperature reading at this starting point (T1).
* Note the time taken for 20$^{\circ}$C rise in temperature by stopping stopwatch after 20$^{\circ}$C rise.
* Dispose off the solution in the waste solution container.
    
7.  Repeat the experiment for different set of values of mole fraction. 
    
# Results

## Raw Data
Least Counts:


| Column 1           | Column 2       |
| ------------------ | -------------- |
| Measuring Cylinder | 1 ml           |
| Pipette            | 0.02 ml        |
| Stopwatch          | 0.01s          |
| Voltmeter          | 0.1V           |
| Ammeter            | 0.1A           |
| Temperature sensor | 0.1$^{\circ}$C |


###### Table 4.1 Values of quantities used from literature
| Quantity                                | Value                                     |
| --------------------------------------- | ----------------------------------------- |
| Density of water                        | 997 kg/m$^3$                              |
| Density of acetone                      | 790 kg/m$^3$                              |
| Heat capacity of water at 20$^{\circ}$C | 1 cal/g$^{\circ}$C = 4.186 J/g$^{\circ}$C |

###### Table 4.2 Volume of water and acetone required for making solutions of corresponding concentration
| Sample ID | Mole Fraction of acetone (Xa) | Volume of Water required (Vw) | Volume of Acetone required (Va) |
| --------- | ----------------------------- | ----------------------------- | ------------------------------- |
| 1         | 0                             | 150                           | 0                               |
| 2         | 0.1                           | 102.94                        | 47.06                           |
| 3         | 0.3                           | 54.28                         | 95.72                           |
| 4         | 0.5                           | 29.4                          | 120.6                           |
| 5         | 0.7                           | 14.15                         | 135.85                          |
| 6         | 0.9                           | 3.95                          | 146.05                          |

##### Table 4.3 Measured quantities
| Sample ID | Mole Fraction of acetone | Total Mass | Total moles | Ti   | Tmi  | Tmf  | deltaTm | V    | i   | t for deltaTm = 2$^{\circ}$C |
| --------- | ------------------------ | ---------- | ----------- | ---- | ---- | ---- | ------- | ---- | --- | ---------------------------- |
| 1         | 0.1                      | 139.9292   | 6.335755    | 29.2 | 35.6 | 37.6 | 6.4     | 16.4 | 2.7 | 86.3                         |
| 2         | 0.3                      | 129.5159   | 4.31094     | 29.3 | 33.4 | 35.4 | 4.1     | 16.4 | 2.7 | 72.89                        |
| 3         | 0.5                      | 124.1916   | 3.26542     | 29.2 | 31.7 | 33.7 | 2.5     | 16.4 | 2.7 | 64.2                         |
| 4         | 0.7                      | 135.85     | 2.624577    | 29.3 | 30.3 | 32.3 | 1.0     | 16.4 | 2.7 | 56.73                        |
| 5         | 0.9                      | 146.05     | 2.195948    | 29.3 | 29.9 | 31.9 | 0.6     | 16.4 | 2.7 | 49.8                         |

## Calculations 

### Determining water equivalent (K) of the calorimeter:

The relevant equation is:

\begin{equation}
    \begin{split}
        Q(input) &= m_wC_p\Delta T+K\Delta T\\
        IVt&=\rho_wV_wC_p\Delta T+K\Delta T
    \end{split}
\end{equation}

where w represents 'water'. Substituting vales, K=.

### Volume of water and acetone required for Sample 1

Let $n_1$\& $n_2$ represent the number of moles of acetone and water respectively. For the first sample:

\begin{equation}
    \frac{n_1}{n_1+n_2}=x(=0.1/0.3/0.5/0.7/0.9)
    \implies (1-x)n_1=xn_2
\end{equation}

If m and M represent mass and molar mass respectively:

\begin{equation}
    \begin{split}
        \frac{(1-x)m_1}{M_1}&=\frac{xm_2}{M_2}\\
        \frac{(1-x)\rho_1V_1}{M_1}&=\frac{x\rho_2V_2}{M_2}
    \end{split}
\end{equation}

Further, since $V_1+V_2=150mL$, we have:

\begin{equation}
    \begin{split}
        \frac{(1-x)\rho_1V_1}{M_1}&=\frac{x\rho_2(150-V_1)}{M_2}
\end{split}
\end{equation}

Plugging in the values ($x=0.1$ for first sample) leads to $V_1=47.06$mL. Similarly for other samples.

### Mixing enthalpy for Sample 1

The relevant equation is:

\begin{equation}
    Q = (mCp+K)\Delta T\implies mCp+K=Q/2=IVt/2
\end{equation}

Next, we also have:

\begin{equation}
    \begin{split}
    Q_m=-(mCp+K)\Delta T_m&=-IVt\Delta T_m/2\\
    \therefore \Delta H_m=\frac{-IVt\Delta T_m}{2(n_1+n_2)}
    \end{split}
\end{equation}
For sample 1, the value obtained was $\Delta H_m=-1923.98$J/mol

### Partial molar enthalpies at $x_1=x_2=0.5$

The requisite expressions:
\begin{equation}
    \begin{split}
    H_{1p}&=\Delta H_m+x_2\frac{d\Delta H_m}{dx_1}\\
    H_{2p}&=\Delta H_m-x_1\frac{d\Delta H_m}{dx_1}
    \end{split}
\end{equation}
At $x_1=x_2=0.5$, $\frac{$

### Infinite dilution partial molar enthalpies

### Error Analysis

The error propagation is:
\begin{equation}
    \begin{split}
        \frac{\Delta k}{k}&=\frac{\Delta I}{I}+\frac{\Delta V}{V}+\frac{\Delta t}{t}+\frac{\Delta (\Delta T)}{\Delta T}+\frac{\Delta m}{m}\\
        \frac{\Delta Cp}{Cp}&=\frac{\Delta k}{k}+\frac{\Delta I}{I}+\frac{\Delta V}{V}+\frac{\Delta t}{t}+\frac{\Delta (\Delta T)}{\Delta T}+\frac{\Delta m}{m} \\
        \frac{\Delta (\Delta H_m)}{\Delta H_m}&=\frac{\Delta k}{k}+\frac{\Delta Cp}{Cp}+\frac{\Delta(\Delta T)}{\Delta T}+\frac{\Delta m}{m}
    \end{split}
\end{equation}

## Discussion

### Known Behaviour Model

### Observations

### Questions

Perform the experiment to test the following hypotheses:

1. The calorimeter functions adiabatically
2. A temperature increase of 2$^{\circ}$C is sufficient to estimate “K” with < 5% uncertainty (Uncertainty decreases if dynamic std-dev is used instead of least count)
