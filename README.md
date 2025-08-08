# AlzNet Classifier

A deep learning model for Alzheimer's Disease classification using neuroimaging data.

## Project Overview
This project focuses on developing a deep learning model for the detection and analysis of Alzheimer's disease using neuroimaging data. The project includes Jupyter notebooks for model development and training, along with preprocessed neuroimaging datasets.

## Project Structure
- `NeuroScanNet.ipynb`: Main Jupyter notebook containing the deep learning model implementation and training pipeline
- `train-*.parquet`: Training dataset containing preprocessed neuroimaging features
- `test-*.parquet`: Test dataset for model evaluation

## Getting Started

### Prerequisites
- Python 3.8+
- Jupyter Notebook
- Required Python packages (install via `pip install -r requirements.txt`)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Rahulkichad/AlzNet-Classifier.git
   cd AlzNet-Classifier
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Open `NeuroScanNet.ipynb` to explore the model implementation and run the training pipeline.

## Dataset
The dataset consists of preprocessed neuroimaging data stored in parquet format:
- Training data: `train-*.parquet`
- Test data: `test-*.parquet`

## Model Architecture
The project implements a deep learning model for Alzheimer's disease detection, including:
- Data preprocessing and augmentation
- Convolutional Neural Network (CNN) architecture
- Training and evaluation pipelines
- Performance metrics and visualization

## Results
[Add your model's performance metrics and results here]

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
[Specify your license here, e.g., MIT License]

## Contact
Rahul Choudhary - rahulkichad@gmail.com
Project Link: [https://github.com/Rahulkichad/AlzNet-Classifier](https://github.com/Rahulkichad/AlzNet-Classifier)
