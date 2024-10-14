# GAN for Fraud Detection - Jupyter Notebook

This repository contains a Jupyter notebook focused on using **Generative Adversarial Networks (GANs)** for fraud detection. The notebook walks through building and training GAN models to identify fraudulent activities, demonstrating how adversarial learning techniques can enhance the detection of anomalies in transactional data.

## Contents

- `gan_fraud.ipynb`: The primary notebook that guides you through the process of developing and evaluating a GAN model for fraud detection. This includes data preparation, model building, training, and evaluation of results.

## Key Concepts Covered

1. **Data Preprocessing**: 
   - Handling and preprocessing data relevant to fraud detection, ensuring the dataset is suitable for GAN training.
   
2. **Generative Adversarial Networks (GANs)**: 
   - Introduction to the architecture of GANs, consisting of a generator and a discriminator, and their roles in generating synthetic fraudulent samples and distinguishing between real and fake transactions.
   
3. **Model Training**: 
   - Training the GAN with the goal of improving the discriminator’s ability to detect fraudulent transactions.
   
4. **Evaluation Metrics**: 
   - Evaluation techniques to assess the effectiveness of the GAN in identifying fraudulent patterns.

## Getting Started

### Prerequisites

To run the notebook, you will need the following dependencies installed:

- Python 3.7+
- Jupyter Notebook or Jupyter Lab
- TensorFlow / PyTorch (for GAN implementation)
- NumPy
- Pandas
- Matplotlib / Seaborn (for data visualization)

You can install these dependencies using `pip`:

```bash
pip install numpy pandas matplotlib tensorflow
```

### Running the Notebook

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/Jencheng1/GAN4fraud.git
   cd GAN4fraud
   ```

2. Open the notebook:

   ```bash
   jupyter notebook gan_fraud.ipynb
   ```

3. Follow the steps in the notebook to preprocess the data, build the GAN model, and evaluate its performance.

## Credits

This notebook is based on learning materials provided by **Coursera** as part of the course **Data Balancing with Gen AI: Credit Card Fraud Detection**.

Special thanks to Coursera for providing the foundational knowledge and resources that inspired the creation of this project.

## Contributing

We welcome contributions to improve or expand this project. To contribute:

1. Fork this repository.
2. Create a new branch for your feature (`git checkout -b new-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin new-feature`).
5. Submit a Pull Request.

## License

This project is licensed under the MIT License. See the full license [here](https://www.mit.edu/~amini/LICENSE.md).
