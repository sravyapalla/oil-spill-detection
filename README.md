# Oil Spill Detection Project

This project is designed for detecting oil spills using deep learning techniques. It includes a dataset of images, a Jupyter notebook for model training and evaluation, and necessary dependencies.

## Project Structure

- **dataset/**: Contains the images used for training, validation, and testing the model.
  - **train/**: Training images for the oil spill detection model.
  - **val/**: Validation images for the oil spill detection model.
  - **test/**: Test images for the oil spill detection model.
  
- **models/**: Directory intended to store the trained model files.

- **spill_detection.ipynb**: Jupyter notebook containing the code for oil spill detection, including data preprocessing, model training, and evaluation.

- **requirements.txt**: Lists the Python dependencies required to run the project, including libraries such as PyTorch, torchvision, scikit-learn, and others.

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd spill_detection
   ```

2. **Install dependencies**:
   Make sure you have Python installed, then run:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter notebook**:
   Start Jupyter Notebook and open `spill_detection.ipynb` to begin training the model.

## Usage

Follow the instructions in the Jupyter notebook to preprocess the data, train the model, and evaluate its performance on the validation and test datasets.

## Contributing

Feel free to submit issues or pull requests if you have suggestions for improvements or additional features.