Tree disease image classification
--

The core idea behind this project was to develop a comprehensive bot or application capable of classifying tree diseases. While this vision is still in progress, the challenge of collecting real-world data has paused its full implementation.

As a starting point, I utilized an apple tree disease image classification [dataset from Kaggle](https://www.kaggle.com/datasets/nirmalsankalana/apple-tree-leaf-disease-dataset). This allowed me to implement and test image classification algorithms—both from scratch and using a pre-built model (b0 from EfficientNet). The aim was to assess the achievable performance with readily available data from Kaggle and the internet, providing insights for future development with authentic, field-collected data. However, I found that the somewhat limited dataset wasn't of sufficient quality to achieve strong performance on external, real-world data. While the models performed well on the dataset itself, their accuracy significantly dropped when tested on small samples of images sourced directly from the internet. This result prompted me to consider building a specific image parser for that project.

Feel free to access the report using this [link](https://github.com/elch1k/tree_disease_image_classification/blob/main/tree_image_classification.ipynb).
