# Discovery of High Entropy Ceramics

## Description

This project aims to develop a deep learning model for predicting the composition of super-hard high entropy ceramics (HECs) based on their hardness properties. Traditional approaches rely on crystal structure information, but this project takes a composition-based approach, leveraging the broader availability and applicability of composition-based descriptors. By training the deep learning model using hardness values, the project enables high-throughput screening of HECs, offering valuable insights for the design and discovery of advanced functional materials.

The project begins with data preprocessing, where a dataset of HEC compositions and hardness values is analyzed. Relevant input features are identified through correlation analysis, and preprocessing techniques such as feature scaling are applied to ensure effective model training. The dataset is then split into training and testing sets for unbiased evaluation.

Three different regression models, including Linear Regression, Decision Tree Regressor, and Random Forest Regressor, are trained and evaluated to predict hardness. The Random Forest Regressor outperforms the other models, demonstrating its effectiveness in capturing the relationships within the data.

Additionally, a deep learning model using a Multilayer Perceptron architecture is developed and trained on the dataset. This model achieves satisfactory results, showcasing the potential of deep learning for hardness prediction.

Overall, this project offers a valuable tool for researchers and material scientists to predict the composition of super-hard HECs with superior hardness properties, accelerating the discovery of advanced functional materials in a high-throughput manner.

## Results

The regression models, including Linear Regression, Decision Tree Regressor, and Random Forest Regressor, were evaluated using the dataset. The Random Forest Regressor model outperformed the others, achieving an impressive R2 score of 0.82. This high score indicates that approximately 82% of the variance in hardness can be explained by the selected features. The model's ability to leverage the collective knowledge of multiple decision trees resulted in stronger predictive capabilities compared to Linear Regression and the Decision Tree model.

![image](https://github.com/barisayyildiz/discovery-of-hecs/assets/37713845/42160f1d-3540-4aec-8f22-0c35deca10e8)

Furthermore, a deep learning model using a Multilayer Perceptron architecture was developed and trained on the dataset. This model achieved remarkable results, with an R2 score exceeding 90%. The deep learning model's superior performance showcases its potential for accurately predicting the hardness of HEC compositions.

![image](https://github.com/barisayyildiz/discovery-of-hecs/assets/37713845/31c7298f-a519-4ffa-97a4-5c663baa0b44)

Visualization techniques, such as t-distributed Stochastic Neighbor Embedding (t-SNE) and correlation matrices, were employed to gain insights into the learned representations and interrelationships among the features. These visualizations revealed patterns, clusters, and interactions within the data, contributing to the interpretation of the models' predictions.

You can find all the detailed information in the .ipynb files


## Usage
To use this project, follow the steps below:

- Open the **discovery_of_hecs.ipynb** or **discovery_of_hecs_nn.ipynb** file using Jupyter Notebook
- Upload the **matdata.csv** file, which contains the materials data
- Run the notebook cells sequentially to execute the code and explore the discovery of high entropy ceramics (HECs) using machine learning models.
- Review the results, visualizations, and insights obtained from the analysis.
