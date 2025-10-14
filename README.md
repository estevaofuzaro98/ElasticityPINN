## ElasticityPINN

<img src="imgs/GraphicalAbstractFig.png" width="80%">

This repository serves as a comprehensive tutorial on introducing PINNs to solve elasticity problems. It demonstrates how PINNs can predict stress distribution solely based on the physical laws of elasticity theory.

### Table of Contents
- [Overview](#overview)
- [Usage](#usage)
- [Documentation](#documentation)
- [Authors](#authors)
- [Citing ElasticityPINN](#citing-elasticitypinn)
- [License](#license)
- [Institutional support](#institutional-support)
- [Funding](#funding)
- [Contact](#contact)

### Overview
**ElasticityPINN** is a computational framework developed to solve two-dimensional elasticity problems using **Physics-Informed Neural Networks (PINNs)**. Instead of relying on conventional meshing techniques from the Finite Element Method (FEM), this approach embeds the governing equations and boundary conditions directly into the neural network’s loss function. The repository contains a reproducible notebook that demonstrate this methodology through a classical benchmark case — **triangular plate under a vertical distributed load**, where the PINN accurately predicts the stress field without using any analytical or FEM data for training. This case serves as an introductory example of how PINNs can generate physics-consistent stress distributions in solid mechanics problems.  


### Usage
To get started with **ElasticityPINN**, follow these steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/estevaofuzaro98/ElasticityPINN.git
   ```
2. Navigate to the package directory:
   ```bash
   cd ElasticityPINN
   ```

### Documentation
The main routine was coded in `Python Notebook` and provides a step-by-step implementation of the PINN formulation, including the definition of the governing equations, boundary conditions, and loss function components. Each section is thoroughly commented to ensure reproducibility and facilitate adaptation to new elasticity problems.

### Authors
- Estevão Fuzaro de Almeida (FEIS/UNESP)
- Samuel da Silva (FEIS/UNESP)

### Citing ElasticityPINN
If you use **ElasticityPINN** in your research, please cite the following publication:
- E. F. Almeida and S. da Silva, *Some Regards on using Physics-Informed Neural Networks for Solving Two-Dimensional Elasticity Problems*, **Journal of the Brazilian Society of Mechanical Sciences and Engineering**, 2025 [DOI: 10.1007/s40430-025-06047-1](https://link.springer.com/article/10.1007/s40430-025-06047-1)

<!--
```
@article{Almeida2025,
   author       = {E. F. Almeida and S. Silva},
   title        = {Some Regards on using Physics-Informed Neural Networks for Solving Two-Dimensional Elasticity Problems},
   year         = {2025},
   journal      = {Journal of the Brazilian Society of Mechanical Sciences and Engineering},
   volume.      = {XX},
   pages        = {XXXXX},
   note         = {10.000/doi2bedefined},
}
```
-->

### License

**ElasticityPINN** is distributed under the MIT license, allowing unrestricted academic and commercial use with proper attribution. See the LICENSE file for details. All new contributions must be made under the MIT license.

<img src="logo/mit_license_red.png" width="15%"> 

### Institutional support

This research was conducted within the Department of Mechanical Engineering, School of Engineering of Ilha Solteira (FEIS/UNESP).

<img src="logo/logo_feis.png" width="15%"> &nbsp; &nbsp; <img src="logo/logolab.png" width="20%">

### Funding

The development of **ElasticityPINN** was supported by research agencies through the following grants:

- São Paulo Research Foundation (FAPESP), grant number 2022/16156-9
- National Council for Scientific and Technological Development (CNPq/Brazil), grant number 309467/2023-3
- National Institute of Science and Technology, Smart Structures in Engineering (INCT-EIE)
   - Funded by the Brazilian agencies:
      -  CNPq, grant number 406148/2022-8
      -  Coordination for the Improvement of Higher Education Personnel (CAPES)
      -  Minas Gerais State Research Support Foundation (FAPEMIG)

<img src="logo/sponsors.png" width="60%">

### Contact

For questions, collaborations, or further information, please contact:

- **Estevão Fuzaro de Almeida** — [estevao.fuzaro@unesp.br](mailto:estevao.fuzaro@unesp.br)  
- **Prof. Samuel da Silva** — [samuel.silva13@unesp.br](mailto:samuel.silva13@unesp.br)
