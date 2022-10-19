## Towards transferable data-driven models to predict urban pluvial flood water depth in Berlin, Germany

# Description

This reperository contains the code for the paper:

Data-driven models are rising as a surrogate to overcome the limitations of the expensively computational 2D hydrodynamic models. However, data-driven models' ability to generalise to unseen case studies and areas outside the training domain is considered their major challenge (Bentivoglio et al., 2022). While the hypothesis in the literature is that deep learning is superior to traditional machine learning algorithms, recent studies showed the contrast (Seleem et al., 2022; Grinsztajn et al., 2022). Data-driven models' performance depends on the availability and quality of data to train, validate and test the model but 2D hydrodynamic simulations are limited to small areas. Therefore, A transferable data-driven model would help to overcome the difficulties of upscaling 2D hydrodynamic models to city scale. Additionally, transfer learning techniques can boost the model performance outside the training domain.     

We evaluated the convolutional neural network and random forest's ability to predict flood water depth, generalise outside the training domain and improve their performance outside the training domain using transfer learning techniques.

The calculated predictive features and the water depth from the 2D hydrodynamic model are available on the following link: https://doi.org/10.5281/zenodo.7221058

# Convolutional neural network: U-Net architecture
We used the U-Net architeture.  
![U_net_architecture_2](U_net_architecture_2.png)

# Random forest
![random](random.png)


# References

Bentivoglio, R., Isufi, E., Jonkman, S. N., and Taormina, R.: Deep Learning Methods for Flood Mapping: A Review of Existing Applications
and Future Research Directions, Hydrology and Earth System Sciences Discussions, pp. 1–50, 2022.

Grinsztajn, L., Oyallon, E., and Varoquaux, G.: Why do tree-based models still outperform deep learning on tabular data?, arXiv preprint
arXiv:2207.08815, 2022

Seleem, O., Ayzel, G., de Souza, A. C. T., Bronstert, A., and Heistermann, M.: Towards urban flood susceptibility mapping using data-driven
models in Berlin, Germany, Geomatics, Natural Hazards and Risk, 13, 1640–1662, 2022.

Zhao, G., Pang, B., Xu, Z., Cui, L., Wang, J., Zuo, D., and Peng, D.: Improving urban flood susceptibility mapping using transfer learning,380
Journal of Hydrology, 602, 126 777, 2021.
