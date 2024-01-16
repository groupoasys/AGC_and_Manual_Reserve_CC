# Data of 118-node Power System 🌩️

## Goals 🚀

The aim of this repository is to provide the details of the power systems data set used in papers [[1]](https://arxiv.org/abs/2104.05746). This article have been developed by some members of the [OASYS group](https://sites.google.com/view/groupoasys/home) thanks to the funding of the project [Flexanalytics](https://groupoasysflexanalytics.readthedocs.io/en/latest/). We suggest you to visit the related links to know more our research 😉

## Contents 🌌

This repository includes data of the 300-bus and 118-bus systems, which are extracted from a [repository of power grids](https://github.com/power-grid-lib/pglib-opf); and data about the wind farms added to the system.

IEEE-118:
  * [Power System Data](https://github.com/groupoasys/AGC_and_Manual_Reserve_CC/blob/main/ieee118.txt)
  * [Wind Data](https://github.com/groupoasys/AGC_and_Manual_Reserve_CC/blob/main/Wind_Data_118.xlsx)

IEEE-300:
  * [Power System Data](https://github.com/groupoasys/AGC_and_Manual_Reserve_CC/blob/main/ieee_300.xlsx)
  * [Wind Data](https://github.com/groupoasys/AGC_and_Manual_Reserve_CC/blob/main/Wind_Data_300.xlsx)

To reproduce the results of such a paper, please contact Álvaro Porras (alvaroporras19@gmail.com) and get access to the scenarios (heavy files).

Note that:
  * IEEE-118: The modified parameters or new parameters about generators used in the paper are indicated in the case study section of the corresponding manuscript.
  * IEEE-300: Line capacities lower than 500 MW have been modified to 500 MW to guarantee the system´s feasibility.

## References 📚
[1] Á. Porras, L. Roald, J. M. Morales and S. Pineda, "Integrating Automatic and Manual Reserves in Optimal Power Flow via Chance Constraints," 2023.

## How to cite the repository and the paper? 📝

If you want to cite [this repository](https://github.com/groupoasys/AGC_and_Manual_Reserve_CC), please use the following bib entries:


* Repository:
```
@article{AGCmanual2023,
author = {OASYS},
journal = {GitHub repository (https://github.com/groupoasys/AGC{\_}and{\_}Manual{\_}Reserve{\_}CC)},
title = {{Data of 5-node and 2000-node Power Systems}},
url = {https://github.com/groupoasys/AGC{\_}and{\_}Manual{\_}Reserve{\_}CC},
year = {2023}
}
```

## Do you want to contribute? 👨🏾‍🔬
 
 Please, do it ☺ Any feedback is welcome 🤩 so feel free to ask or comment anything you want via a Pull Request in this repo.
 If you need extra help, you can ask Álvaro Porras (alvaroporras19@gmail.com).

 ## Contributors 👑
 
 * [OASYS group](http://oasys.uma.es) -  groupoasys@gmail.com
 
 ## Developed by 👨🏾‍💻
 * [Álvaro Porras](https://www.researchgate.net/profile/Alvaro-Porras-Cabrera) - alvaroporras19@gmail.com

 ## License 📝
 
    Copyright 2021 Optimization and Analytics for Sustainable energY Systems (OASYS)

    Licensed under the GNU General Public License, Version 3 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.gnu.org/licenses/gpl-3.0.en.html

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
