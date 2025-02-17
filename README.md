# ADM1 Model

> Research CE 405: Project C / 18 : Investigating the potential of recovering bioenergy from a hybrid wastewater treatment technology


## Introduction

ADM1 (Anaerobic Digestion Model No. 1) is a structured model developed to describe anaerobic digestion processes. Created by the IWA Task Group for Mathematical Modelling of Anaerobic Digestion Processes, ADM1 is widely used for simulating and optimizing anaerobic digesters in both research and industrial applications.

This implementation of ADM1 is developed as a Google Colab Notebook (ADM1.ipynb), utilizing NumPy and Pandas, with SciPy’s ODE solvers to compute numerical solutions based on governing equations.

## Features

- Models biochemical processes involved in anaerobic digestion.
- Simulates substrate degradation and biogas production.
- Supports different anaerobic digester configurations.
- Implemented using ordinary differential equations (ODEs) for accurate process simulation.
- Ideal for research, education, and practical applications.

## Usage

Open the ADM1 Colab Notebook and run the cells sequentially to execute the model. Ensure that all dependencies are correctly installed in the Colab environment.

## Mathematical Foundations

This model is built using governing equations from ordinary differential equations (ODEs) to simulate the anaerobic digestion process. The numerical integration is performed using SciPy’s solve_ivp method.

### References for Mathematical Implementation:

- [Ordinary Differential Equations (Wikipedia)](https://en.wikipedia.org/wiki/Ordinary_differential_equation)
- [SciPy’s solve_ivp Documentation](https://docs.scipy.org/doc/scipy/reference/generated/scipy.integrate.solve_ivp.html)
- [Solving Differential Equations with SciPy](https://danielmuellerkomorowska.com/2021/02/16/differential-equations-with-scipy-odeint-or-solve_ivp/)

### Research and Documentation

The ADM1 model was originally developed based on research published by the IWA Task Group. For detailed theoretical background and implementation details, refer to:

- [Anaerobic Digestion Model No. 1 (ADM1) Research Paper](https://www.researchgate.net/publication/11198259_Anaerobic_digestion_model_No_1_ADM1)
- [ADM1 Book (Google Books)](https://g.co/kgs/3Lp1AKP)

## License

This project is licensed under the [MIT License](LICENSE) – see the LICENSE file for details.

## Acknowledgments

- IWA Task Group for Mathematical Modelling of Anaerobic Digestion Processes for developing the original ADM1 model.
- Researchers and authors whose work contributed to the theoretical foundations of this project.
