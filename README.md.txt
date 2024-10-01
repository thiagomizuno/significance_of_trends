# Evaluation of the Significance of Trends

This repository contains the files of an example of synthetic data and five real images presented in the article titled "Evaluation of the Significance of Spatial Trends for Geostatistical Simulation.", Alduini Mizuno, T., Deutsch, C.V.(2024)[1].

## Synthetic Data

<p align="center">
    <img src="fig01.png" alt="Figure 1" width="500"/>
</p>

Figure 1: The synthetic data $Z(u)$ in the file consists of 50% variance originating from the trend $m(u)$ and 50% from the simulation $R(u)$. File: [Synthetic_data.dat](Synthetic_data.dat).

For cases with contributions of variances with different weights, the equation used is:

$$
Z(u) = \sqrt{F} \cdot m(u) + \sqrt{(1 - F)} \cdot R(u) \cdot F + (1 - F) \cdot R(u)
$$


## Real Images

The following real images were provided by the [Centre for Computational Geostatistics (CCG)](https://www.ccgalberta.com/),  Mokdad, Binakaj e Boisvert (2022) [2].:

<p align="center">
    <img src="fig02.png" alt="Figure 2" width="500"/>
</p>

Figure 2: Image A31, file: [Exhaustive_A31.out](Exhaustive_A31.out).

---

<p align="center">
    <img src="fig03.png" alt="Figure 3" width="500"/>
</p>

Figure 3: Image D3, file: [Exhaustive_D3.out](Exhaustive_D3.out).


---

<p align="center">
    <img src="fig04.png" alt="Figure 4" width="500"/>
</p>

Figure 4: Image A18, file: [Exhaustive_A18.out](Exhaustive_A18.out).


---

<p align="center">
    <img src="fig05.png" alt="Figure 5" width="500"/>
</p>

Figure 5: Image A32, file: [Exhaustive_A32.out](Exhaustive_A32.out).


---

<p align="center">
    <img src="fig06.png" alt="Figure 6" width="500"/>
</p>

Figure 6: Image B16, file: [Exhaustive_B16.out](Exhaustive_B16.out).

## Contact

If you have any questions or suggestions, please contact Thiago A Mizuno at thiagomizuno@gmail.com.

## References
[1]: Alduini Mizuno, T., Deutsch, C.V. Evaluation of the significance of spatial trends for geostatistical simulation. Stoch Environ Res Risk Assess (2024). [https://doi.org/10.1007/s00477-024-02828-7](https://doi.org/10.1007/s00477-024-02828-7/)

[2]: Mokdad, K., Binakaj, D., & Boisvert, J. (2022). Data validation project: Validation of 114 spatial 2d datasets (non‐ synthetic data). CCG Paper 110, Centre for Computational Geostatistics, University of Alberta, Canada, 24.


