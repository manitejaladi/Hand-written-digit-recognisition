# Handwritten Digit Recognition

This project focuses on the development and comparison of machine learning models for handwritten digit recognition, using the MNIST dataset. The goal is to create a robust tool for digit classification that can be applied in various industries such as document digitization, postal services, and banking.

## Project Structure

- `DA Project.ipynb`: Jupyter notebook containing the exploratory data analysis and initial model comparisons.
- `GUI.py`: Python script for the graphical user interface that enables users to interact with the models in real-time.
- `Model.py`: Contains the implementation of the machine learning models used for digit recognition.
- `Prediction.py`: Script for performing predictions using the trained models.
- `RandInitialize.py`: Helper script for random initialization of model parameters.

## Setup

1. **Clone the Repository**
git clone https://github.com/manitejaladi/hand-written-digit-recognition.git
cd handwritten-digit-recognition

2. **Install Dependencies**
pip install -r requirements.txt

3. **Run the Notebook**
jupyter notebook "DA Project.ipynb"


4. **Run the GUI Application**
python GUI.py


## Models Used

- **Linear Classifier**: Provides a basic but effective approach to recognize handwritten digits using linear transformations.
- **Keras Sequential API**: Implements a more complex neural network model to improve classification accuracy.
- **Multi-Layer Perceptron (MLP)**: A deep learning model that captures intricate patterns in the data, enhancing recognition capabilities.

## Results

The models were evaluated based on their accuracy and efficiency, with the Keras Sequential model achieving a high accuracy of approximately 96.94%, proving its efficacy in recognizing varied handwriting styles.

## Future Work

Further research could explore advanced neural architectures such as Convolutional Neural Networks (CNNs) and Recurrent Neural Networks (RNNs) to improve accuracy and processing times. Enhancements in user interface and model deployment strategies could also be considered to increase the usability of the application.

## Author
[Maniteja Ladi](https://github.com/manitejaladi)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
