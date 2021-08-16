## Datasets related to the paper "The dust emission potential of agricultural-like fires - theoretical estimates from two conceptually different dust emission parameterizations" of Wagner et al. (2021)

This repository contains the dataset that was used for the analysis and related plots of the paper of Wagner et al. (2021) entitled as "The dust emission potential of agricultural-like fires - theoretical estimates from two conceptually different dust emission parameterizations" and published in JGR. All data are given as netcdf-files.

The data are sorted after their usage to create the figures presented in the paper. The dataset used for Figure 2 and 3 contains the key wind field properties such as the friction velocity u* and the instantaneous momentum flux "tau" as well as the dust emission fluxes caused by saltation bombardment (SALT) and those by convective-turbulent motions (CTDE) for the 14 simulations used for Figure 3. The individual simulations are entitled as *Fire_00 - Fire_13*, whereby *Fire_01* serves as a reference case that is also used for the extented analysis shown in Figure 2, while all other simulations deviate from it concerning the averaged geostrophic wind velocity, fire intensity, or fire size as indicated in the list below. Additionally, a non-fire simulation (*Fire_00*) similar to *Fire_01* is included. 

Furthermore, the dependency of the dust emission fluxes of both dust emission schemes (SALT and CTDE) on changing soil-surface properties such as soil types (Figure 4), soil moisture contents (Figure 5), and different roughness lengths (Figure 6/7) are provided.

### List of the fire simulations

simulation name  | description
------------- | -------------
Fire_00 | NO-FIRE simulation, similar to Fire_01 but without any fire impacts
Fire_01 | reference simulation with a fire intensity F<sub>Fire</sub> of 150 kW/m<sup>2</sup>, a burning fire area A<sub>Fire</sub> of 7,000 m<sup>2</sup>, exposed to a mean ambient wind speed (geostrophic wind) of 3 m/s
Fire_02	|	as FIRE_01 but reduced geostrophic wind of 1 m/s
Fire_03	|	as FIRE_01 but reduced geostrophic wind of 2 m/s
Fire_04	|	as FIRE_01 but increased geostrophic wind of 4 m/s
Fire_05	|	as FIRE_01 but increased geostrophic wind of 5 m/s
Fire_06	|	as FIRE_01 but weaker fire intensity of 50 kW/m<sup>2</sup>
Fire_07	|	as FIRE_01 but weaker fire intensity of 75 kW/m<sup>2</sup>
Fire_08	|	as FIRE_01 but weaker fire intensity of 115 kW/m<sup>2</sup>
Fire_09	|	as FIRE_01 but stronger fire intensity of 270 kW/m<sup>2</sup>
Fire_10	|	as FIRE_01 but smaller burning area of 2,400 m<sup>2</sup>
Fire_11	|	as FIRE_01 but smaller burning area of 4,800 m<sup>2</sup>
Fire_12	|	as FIRE_01 but larger burning area of 11,700 m<sup>2</sup>
Fire_13	|	as FIRE_01 but larger burning area of 20,400 m<sup>2</sup>
