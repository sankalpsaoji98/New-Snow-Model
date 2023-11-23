## Company and Position
Worked as a **Research and Development Intern** at **Buffalo Solar**, a solar panel manufacturing company based out of Buffalo NY, United States.

<img width="438" alt="image" src="https://github.com/sankalpsaoji98/Snow_Model_Project/assets/26198596/f7389cdc-26e1-4b13-ab55-f12ff4d1a704">

## Project
**Snow Model Project:**
Buffalo Solar has to promise a certain output to the customers when it sells solar panels. But, whenever snow falls on the panels, the energy output is reduced and it's hard to track it. So, the goal was to design a snow loss model to track the loss and give out correct estimates on the energy output.

## Table of Contents
- [Software](#software)
- [Data](#data)
- [Model](#model)
- [Results](#results)
- [Acknowledgments](#acknowledgments)

## Software
1) Heliscope
2) VSC Code
3) python3
4) MS Excel

## Data

<img width="920" alt="image" src="https://github.com/sankalpsaoji98/Snow_Model_Project/assets/26198596/0a2d2231-7e4e-4653-a274-2b1dfab2d430">

1) Data is obtained and processed for a year
2) Information available at an hourly level

## Model

1) We used the model proposed by Marion et al. (2013) for the National Renewable Energy Laboratory’s (NREL) System Advisor Model (SAM)
2) Calculates the percentage of a PV array that will be covered by snow given daily snow depth measurements as well as hourly system tilt, plane of array (POA) irradiance, and temperature values
3) The model considers snow sliding to be the dominant removal process and therefore does not account for snow melting or wind removal (except in the case of flat fixed-tilt systems)

<img width="955" alt="image" src="https://github.com/sankalpsaoji98/Snow_Model_Project/assets/26198596/c227f6db-4a6f-4331-b91d-dc338e0fc6e5">

1) At the beginning of each day, the model checks to see if a snowfall has occurred during the previous day.
2) If it has, the model assumes that the PV array being simulated will initially be covered by snow.
3) It proposes snow sliding will only occur as long as the following inequality is satisfied:

<img width="926" alt="image" src="https://github.com/sankalpsaoji98/Snow_Model_Project/assets/26198596/7e4a2767-e793-4bb7-8b9c-3b2626d296a9">

## Results

1) Three sites were tested – Buffalo NY, Wellsville NY, Worcester MA for the year 2020
2) Every site shows large losses in January, February, November and December
3) Below graph shows yearly variation (2020) of losses for Buffalo NY:

<img width="960" alt="image" src="https://github.com/sankalpsaoji98/Snow_Model_Project/assets/26198596/c5a8af26-00ba-4229-b1f2-0f307d51c5a5">

<img width="889" alt="image" src="https://github.com/sankalpsaoji98/Snow_Model_Project/assets/26198596/a943d501-22c0-480c-a268-09910941cac4">

1) Three sites were tested – Buffalo NY, Wellsville NY, Worcester MA
2) Every site shows huge losses in January, February, November and December

<img width="918" alt="image" src="https://github.com/sankalpsaoji98/Snow_Model_Project/assets/26198596/e51d194b-daa8-4bfb-affb-7b34b71d5782">

For 4 January 2020,
1) For a normal solar panel which produces no output with any kind of blockage, loss was seen to be = **62.32%**
2) For a panel with 3 rows which produces output whenever a row is free, loss was seen to be = **21.63%**

![image](https://github.com/sankalpsaoji98/Snow_Model_Project/assets/26198596/615ec560-246e-4b25-9fb9-dbc3d568cb6f)

## Acknowledgements
The work was done for Buffalo Solar and is the property of the company.

