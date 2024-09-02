# Deep Learning for Quick, Draw! - Model Optimization and Visualization

## Description
This project focuses on optimizing deep learning models for image classification using the Quick, Draw! dataset. It involves experimenting with various model architectures and hyperparameters to enhance performance. TensorBoard is used for visualizing and monitoring the training process, providing insights into model behavior and performance.

## Key Features
- **Model Architectures:** Implements and evaluates GoogleNet and ResNet for image classification.
- **Hyperparameter Tuning:** Systematic exploration of different learning rates and activation functions to find the optimal configuration.
- **Visualization:** Utilizes TensorBoard for real-time monitoring of training metrics, including loss and accuracy, and to visualize model performance.
- **Dataset:** Quick, Draw! dataset, which consists of user-drawn images categorized into various classes.

## Technologies Used
- **Deep Learning Framework:** PyTorch
- **Visualization Tool:** TensorBoard
- **Dataset:** Quick, Draw!
- **Platform:** Google Colab for running experiments

## Results
- **Best Model:** GoogleNet with learning rate `0.1` and ReLU activation function.
- **Validation Accuracy:** `81.78%`
- **Test Accuracy:** `81.89%`
- Optimization of model configurations led to improved performance metrics and better insights into model behavior through TensorBoard visualizations.

## Usage

1. **Open Google Colab:**
   - You can run the notebook in Google Colab by opening the `.ipynb` file.

2. **Run the Training Notebook:**
   - Execute the cells in the notebook to train and evaluate the models. The training process will automatically log metrics for visualization in TensorBoard.

3. **Visualize Results:**
   - TensorBoard is integrated within the Colab notebook. Use the TensorBoard interface to monitor training progress and visualize results directly in Colab.

