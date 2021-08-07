# CL 232 - Lab 1

## Title

Determination of partial molar enthalpies by Adiabatic Calorimetry

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

1. To determine heat of mixing of binary mixture using an adiabatic caloriemeter
2. To determine the water equivalent of calorimeter and finding the specific heat capacity of solution.
3. To determine the partial molar enthalpy of water and acetone at x=0.5 and partial enthalpy of mixing at infinite dilution.

## Notes on the Procedure

1. Rinse the cylindrical container using the chemical to be poured in it. Reserve one container for each chemical.
2. Check whether the stirrer works properly.
3. Calculate the volume of each component required for each value of concentration.
4. Determine the water equivalent of the flask by taking 150ml of distilled water
5. Pour the required volume of bulk solvent (component with higher mole fraction) into the adiabatic calorimeter and take the steady temperature reading (T0).
6. Pour the required volume of other component in the adiabatic calorimeter and start the power source and stopwatch. Note the voltage, current and temperature reading at this starting point (T1).
7. Note the time taken for 20$^{\circ}$C rise in temperature by stopping stopwatch after 20$^{\circ}$C rise.
8. Dispose off the solution in the waste solution container.
9. Repeat the experiment for different set of values of mole fraction.

## Set-up

1. Adiabatic Flask
2. Heating element having a heating coil and a temperature sensor
3. Temperature Display connected to the temperature sensor
4. Magnetic stirrer and bead for homogenisation of the solution
5. Timer - To keep track of time
6. Voltage and Current regulator
7. Acetone
8. Measuring flask

## Results

### Raw Data

###### Table 1

Counts:

| Instrument         | Least Count    |
| ------------------ | -------------- |
| Measuring Cylinder | 1 ml           |
| Pipette            | 0.02 ml        |
| Stopwatch          | 0.167s         |
| Voltmeter          | 0.01V          |
| Ammeter            | 0.01A          |
| Temperature sensor | 0.1$^{\circ}$C |
| Weighing Scale     | 0.1g           |

###### Table 2: Values of quantities used from literature

| Quantity                                | Value                                     |
| --------------------------------------- | ----------------------------------------- |
| Density of water                        | 997 kg/m$^3$                              |
| Density of acetone                      | 790 kg/m$^3$                              |
| Heat capacity of water at 20$^{\circ}$C | 1 cal/g$^{\circ}$C = 4.186 J/g$^{\circ}$C |

###### Table 3: Volume of water and acetone required for making solutions of corresponding concentration

| Sample ID | Mole Fraction of acetone (Xa) | Volume of Water required (Vw) | Volume of Acetone required (Va) |
| --------- | ----------------------------- | ----------------------------- | ------------------------------- |
| 1         | 0                             | 150                           | 0                               |
| 2         | 0.1                           | 102.94                        | 47.06                           |
| 3         | 0.3                           | 54.28                         | 95.72                           |
| 4         | 0.5                           | 29.4                          | 120.6                           |
| 5         | 0.7                           | 14.15                         | 135.85                          |
| 6         | 0.9                           | 3.95                          | 146.05                          |

###### Table 4: Measured quantities

| Sample ID | Mole Fraction of acetone Xa | Total Mass m (g) | Total moles n (mol) | Ti($^{\circ}$C) | Tmi ($^{\circ}$C) | Tmf ($^{\circ}$C) | deltaTm ($^{\circ}$C) | Voltage V (volt) | Current i (A) | t for deltaTm = 2$^{\circ}$C (second) |
| --------- | --------------------------- | ---------------- | ------------------- | --------------- | ----------------- | ----------------- | --------------------- | ---------------- | ------------- | ------------------------------------- |
| 1         | 0.1                         | 139.9292         | 6.335755            | 29.2            | 35.6              | 37.6              | 6.4                   | 16.4             | 2.7           | 86.3                                  |
| 2         | 0.3                         | 129.5159         | 4.31094             | 29.3            | 33.4              | 35.4              | 4.1                   | 16.4             | 2.7           | 72.89                                 |
| 3         | 0.5                         | 124.1916         | 3.26542             | 29.2            | 31.7              | 33.7              | 2.5                   | 16.4             | 2.7           | 64.2                                  |
| 4         | 0.7                         | 135.85           | 2.624577            | 29.3            | 30.3              | 32.3              | 1.0                   | 16.4             | 2.7           | 56.73                                 |
| 5         | 0.9                         | 146.05           | 2.195948            | 29.3            | 29.9              | 31.9              | 0.6                   | 16.4             | 2.7           | 49.8                                  |

## Calculations

### Determining water equivalent (K) of the calorimeter

The relevant equation is:

\begin{equation}
    \begin{split}
        Q(input) &= m_wC_p\Delta T+K\Delta T\\
        IVt&=\rho_wV_wC_p\Delta T+K\Delta T
    \end{split}
\end{equation}

where w represents 'water'. Substituting vales, $K=1275.22g=1.275$kg.

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

Plugging in the values ($x=0.1$ for first sample) led to $V_1=47.06$mL. Similarly for other samples.

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

At $x_1=x_2=0.5, \frac{d\Delta H_m}{dx_1}=2294.17$J/mol and thus:

\begin{equation}
    \begin{split}
        H_{1p}&=-1088.21+(0.5)(2294.17)=58.875J/mol\\
        H_{2p}&=-1088.21-(0.5)(2294.17)=-2235.29J/mol
    \end{split}
\end{equation}

### Infinite dilution partial molar enthalpies

By letting the mole fractions tend to limits 1 and 0:

\begin{equation}
    \begin{split}
        H_{1\infty}(x_1\to0)&=\Delta H_m+(1)\frac{d\Delta H_m}{dx_1}=-31521.02J/mol\\
        H_{2\infty}(x_1\to1)&=\Delta H_m-(1)\frac{d\Delta H_m}{dx_1}=-4913.55J/mol
    \end{split}
\end{equation}

###### Table 5: Derived Quantities

| Molarity$(x_a)$ | Heat Capacity Cp(J/gK) | Error in Cp (J/gK) | Heat of Mixing Qm(J) | Enthalpy of Mixing $\Delta H_m$(J/mol) | Error in $\Delta H_m$(J/mol) |
| --------------- | ---------------------- | ------------------ | -------------------- | -------------------------------------- | ---------------------------- |
| 0.1             | -                      | -                  | -                    | -                                      | -                            |
| 0.3             | -                      | -                  | -                    | -                                      | -                            |
| 0.5             | -                      | -                  | -                    | -                                      | -                            |
| 0.7             | -                      | -                  | -                    | -                                      | -                            |
| 0.9             | -                      | -                  | -                    | -                                      | -                            |

### Error Analysis

The error propagation is:

\begin{equation}
    \begin{split}
        \frac{\Delta k}{k}&=\frac{\Delta I}{I}+\frac{\Delta V}{V}+\frac{\Delta t}{t}+\frac{\Delta (\Delta T)}{\Delta T}+\frac{\Delta m}{m}\\
        \frac{\Delta Cp}{Cp}&=\frac{\Delta k}{k}+\frac{\Delta I}{I}+\frac{\Delta V}{V}+\frac{\Delta t}{t}+\frac{\Delta (\Delta T)}{\Delta T}+\frac{\Delta m}{m} \\
        \frac{\Delta (\Delta H_m)}{\Delta H_m}&=\frac{\Delta k}{k}+\frac{\Delta Cp}{Cp}+\frac{\Delta(\Delta T)}{\Delta T}+\frac{\Delta m}{m}
    \end{split}
\end{equation}

Plugging in values and least count led to an error of 8.41% for the first sample.

## Discussion

### Known Behaviour Model

### Observations

### Questions

Perform the experiment to test the following hypotheses:

1. The calorimeter functions adiabatically
2. A temperature increase of 2$^{\circ}$C is sufficient to estimate “K” with < 5% uncertainty (Uncertainty decreases if dynamic std-dev is used instead of least count)
3. For a given 2-component system mixing can only be an exothermic or endothermic process
4. Find the heat capacity of the pure component along with its uncertainty. Compare with literature value and comment
5. Find the partial molar enthalpy of mixing at $x_1=x_2=0.5$ and at infinite dilution.

### Hypotheses

**Error is estimation of K:**
Based on the data provided for calculating water equivalent and errors, the error in estimation was calculated as follows:

\begin{equation}
    \begin{split}
        \frac{\Delta k}{k}&=\frac{\Delta I}{I}+\frac{\Delta V}{V}+\frac{\Delta t}{t}+\frac{\Delta (\Delta T)}{\Delta T}+\frac{\Delta m}{m}\\
        \frac{\Delta k}{k}&=\left[\frac{0.01}{2.7}+\frac{0.01}{16.3}+\frac{0.167}{86.4}+\frac{0.1}{2}+\frac{0.1}{150\times0.997}\right]\times100\%=5.69\%\\
    \end{split}
\end{equation}

Thus, the hypothesis that a temperature rise of 2$^{\circ}$C is enough to estimate K with $<5\%$ accuracy is **incorrect**.

**Heat of mixing**:
Heat of mixing (delta Hm) is defined as the change in enthalpy observed when two liquids are mixed, being the sum of the changes in enthalpy which occur during the mixing process. It primarily depends upon the interactions of the molecules of the substances involved and the ratio they are mixed in.
Mixing enthalpy is zero if the mixture is ideal (if there are no interactions between the molecules). However, interactions between the two components can cause endothermic effects or exothermic effects depending on the relative attractions of molecules. In this case (water-acetone mixture), hydrogen bonding increases with increase in the concentration of acetone up to a certain concentration/mole fraction of acetone. However, as acetone molecules come to the surface, the hydrophobic acetone group forms clusters and hence reduces its contact with water. Therefore, we observe the temperature of bulk to be greater than the reference temperature (at low temperatures) due to high hydrogen bonding between acetone and water molecules compared to hydrogen bonding between water- water molecules and acetone-acetone molecules, resulting in the release of heat.

**Heat Capacity of Acetone:**
The heat capacity of a substance is defined as the quantity of heat required to raise its temperature by 1$^{\circ}$C (equivalent to 1 K). It is observed that with increase in mole fraction of acetone, the time taken to achieve a set temperature rise of 2$^{\circ}$C decreases - this indicates that the heat capacity of the mixture decreases with the increase in mole fraction of acetone. Heat capacity of the mixture can be considered a weighted average of heat capacities of the components (with the number of moles being the respective weights for total heat capacity and mole fractions being the weights for the molar heat capacity) and heat capacity decreases with increase in the weightage for acetone. Therefore, the heat capacity of acetone is less than the heat capacity of water. This is in fact true, since literature suggests heat capacity of acetone=$1.29$ J/g$.$K which is definitely less than water.
*We have not calculated the specific heat of acetone since the data provided did not include values for 1M solution.*
