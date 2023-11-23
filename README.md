## Company and Position
Worked as a **Research and Development Intern** at **Buffalo Solar**, a solar panel manufacturing company based out of Buffalo NY, United States.

<img width="543" alt="image" src="https://github.com/sankalpsaoji98/Snow-Model-Project/assets/26198596/2f51bdca-c0ba-4bab-9393-0bf742d6836a">


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

<img width="920" alt="image" src="https://github.com/sankalpsaoji98/Snow-Model-Project/assets/26198596/db238c49-d45b-49b0-a0ca-8f41922247b8">

1) Data is obtained and processed for a year
2) Information available at an hourly level

## Model

1) We used the model proposed by Marion et al. (2013) for the National Renewable Energy Laboratory’s (NREL) System Advisor Model (SAM)
2) Calculates the percentage of a PV array that will be covered by snow given daily snow depth measurements as well as hourly system tilt, plane of array (POA) irradiance, and temperature values
3) The model considers snow sliding to be the dominant removal process and therefore does not account for snow melting or wind removal (except in the case of flat fixed-tilt systems)

<img width="955" alt="image" src="https://github.com/sankalpsaoji98/Snow-Model-Project/assets/26198596/7d5b5d13-378d-4f05-b7f4-23dc8effc61c">

1) At the beginning of each day, the model checks to see if a snowfall has occurred during the previous day.
2) If it has, the model assumes that the PV array being simulated will initially be covered by snow.
3) It proposes snow sliding will only occur as long as the following inequality is satisfied:

<img width="926" alt="image" src="https://github.com/sankalpsaoji98/Snow-Model-Project/assets/26198596/54f07e96-0233-48c8-a3c1-328f661e776e">

## Results

1) Three sites were tested – Buffalo NY, Wellsville NY, Worcester MA for the year 2020
2) Every site shows large losses in January, February, November and December
3) Below graph shows yearly variation (2020) of losses for Buffalo NY:

<img width="787" alt="image" src="https://github.com/sankalpsaoji98/Snow-Model-Project/assets/26198596/eb24287d-0a0d-4b8b-a995-8833078f8b5d">

<img width="882" alt="image" src="https://github.com/sankalpsaoji98/Snow-Model-Project/assets/26198596/c4ba9394-b41a-4946-91e2-66e22798bf72">

1) Three sites were tested – Buffalo NY, Wellsville NY, Worcester MA
2) Every site shows huge losses in January, February, November and December

<img width="918" alt="image" src="https://github.com/sankalpsaoji98/Snow-Model-Project/assets/26198596/025a9461-b311-4793-b4b4-667bfb4feb1d">

For 4 January 2020,
1) For a normal solar panel which produces no output with any kind of blockage, loss was seen to be = **62.32%**
2) For a panel with 3 rows which produces output whenever a row is free, loss was seen to be = **21.63%**

![image](https://github.com/sankalpsaoji98/Snow-Model-Project/assets/26198596/570a7612-18d6-4f0a-81e5-9f32d416fbff)

## Acknowledgements
The work was done for Buffalo Solar and is the property of the company.

