# Neural-Network

A simple project made to understand the basics of deep neural networks.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cezary-rasinski/Neural-Network/blob/main/2x2_pixel_image_classifier.ipynb)

---
## Description
- **Dataset**: Generated random values within high&low range ([0.6 - 1.0]&[0.0 - 0.4]) to serve as clear distinctions for patterns  
- **PDF**: The pdf contains more of a theoretical and visual approach to the neural network, values used there are arbitrary.


## Description
- **Dataset**:  
  - Generated 2×2 images generated with clear “high” ([0.6–1.0]) and “low” ([0.0–0.4]) intensity ranges  
  - Two orientations per pattern class (solid, horizontal, vertical, diagonal) to account for patterns appearing both ways
  - Additive Gaussian noise (`noise_std=0.05`) for slight variation  

- **PDF (`Pixel_Neural_Network.pdf`)**:  
  - Theoretical & visual overview of the network  
  - Prototype inputs and example weight/bias tables  
  - Values in the PDF are illustrative and chosen arbitrarily  

- **Notebook (`2x2_pixel_image_classifier.ipynb`)**:  
  - Actual implementation 
  - Data generation code, model definition, training & evaluation  
