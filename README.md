# CycleGAN Monet Style Generator

## Description

This repository features a Keras implementation of CycleGAN tailored to generate images in the distinctive style of Claude Monet. CycleGAN, a robust image generation model, excels at learning correspondences between two dissimilar domains without the necessity of paired data.

The project draws inspiration from the artistic legacy of Claude Monet, a celebrated painter. For detailed insights into Claude Monet's works, please refer to the National Gallery of Art website: [Claude Monet](https://www.nga.gov/features/slideshows/claude-monet.html#slide_2).

The generator model architecture is influenced by the principles outlined in the Google for Developers article on Generative Adversarial Networks (GANs): [The Generator](https://developers.google.com/machine-learning/gan/generator?hl=es-419).

This implementation is guided by the Monet CycleGAN Tutorial created by amyjang, providing valuable insights into the practical aspects of CycleGAN: [Monet CycleGAN Tutorial](https://www.kaggle.com/code/amyjang/monet-cyclegan-tutorial).

## Usage

1. Download the Jupyter Notebook file `cyclegan-monet-style-generator.ipynb`.
2. Run the notebook in your Jupyter environment.

The notebook includes step-by-step instructions for loading the pre-trained model, performing transformations, and visualizing the results.

## Repository Structure

- **cyclegan-monet-style-generator.ipynb**: The main notebook containing the CycleGAN implementation and usage examples.
- **saved_models/**: A folder containing pre-trained models.

## Pre-trained Model

The pre-trained model is stored in the `saved_models/` folder. Load the model directly from the notebook to start generating Monet-style images.

## Data Source

The dataset originates from the Kaggle competition titled "I’m Something of a Painter Myself" by Amy Jang, Ana Sofia Uzsoy, and Phil Culliton (2020). For more information, refer to: [Kaggle Competition](https://www.kaggle.com/competitions/gan-getting-started).

## References

- Claude Monet. (2024). Retrieved March 10, 2024, from Nga.gov website: https://www.nga.gov/features/slideshows/claude-monet.html#slide_2
- The Generator. (2022). Retrieved March 10, 2024, from Google for Developers website: https://developers.google.com/machine-learning/gan/generator?hl=es-419
- amyjang. (2020, August 29). Monet CycleGAN Tutorial. Retrieved March 10, 2024, from Kaggle.com website: https://www.kaggle.com/code/amyjang/monet-cyclegan-tutorial

---

Feel free to reach out for any questions or concerns regarding this CycleGAN Monet Style Generator project report.
