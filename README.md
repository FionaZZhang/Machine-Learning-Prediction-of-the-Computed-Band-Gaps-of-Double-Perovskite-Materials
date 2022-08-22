# Machine-Learning-Prediction-of-the-Computed-Band-Gaps-of-Double-Perovskite-Materials

This repository contains the machine learning data analysis coding for the research project. The code uses Python, and was developed using Jupyter Notebook. The paper is also attached. The paper is published here: https://chemrxiv.org/engage/chemrxiv/article-details/6284eddc6cae1c51680e49fa 

Configuration: 
'Atomistic Simulation PBL.ipynb' includes the machine learning model; 
'Atomistic Simulation PBL Optimization.ipynb' includes the optimization of the model; 
'Visualisation.ipynb' includes the charts and graphs in the paper; 
'Machine-Learning Prediction of the Computed Band Gaps of Double Perovskite Materials' is the paper preprint. 


Abstract: 
Conventional electronic structure methods based on density functional theory (DFT) suffer from not only high computational cost that scales cubically with the number of electrons, but also limited accuracy arising from the approximations of the exchange-correlation functional. In particular, the latter issue is particularly severe for insulators and semiconductors, whose band gaps are systematically underestimated by DFT. Surrogate methods based on machine learning has garnered much attention as a viable alternative to bypass these limitations, especially in prediction of solid-state band gaps. Here, we construct a random forest regression model for band gaps of double perovskite materials, using a dataset of 1306 band gaps computed with the GLLBSC (Gritsenko, van Leeuwen, van Lenthe, and Baerends solid correlation) functional. Among the 20 physical features employed, we find that the bulk modulus, superconductivity temperature, and cation electronegativity exhibit the highest importance scores, consistent with the physics of the underlying electronic structure. Using the top 10 features, a model accuracy of 85.6% with a root mean square error of 0.64 eV is obtained, comparable to a previous study employing kernel ridge regression. Our results attest to the potential of machine learning regressions for rapid screening of promising candidate functional materials.
