# Answer-Selection-Models-SiameseNN-Transformers
Implementations of Siamese Neural Networks and Transformer models for answering medical questions. This project predicts the relevance of answers to questions using deep learning techniques, with tasks covering contrastive loss, multi-head attention, and NLP preprocessing.
## Objectives
- Develop a **Siamese Neural Network** using contrastive loss to classify paired data.
- Build a **Transformer-based model** to determine the relevance of question-answer pairs.

## Dataset
The data is provided in the following CSV files:
- `train.csv`: Training data containing questions, answers, and relevance labels.
- `val.csv`: Validation data for model tuning.
- `test.csv`: Test data for final evaluation.

### Data Format
Each file contains the following columns:
- `qtext`: The question text.
- `atext`: The answer text.
- `label`: Binary label (1 for relevant, 0 for irrelevant).

## Requirements
- Python 3.8+
- Jupyter Notebook
- TensorFlow/Keras
- Pandas
- NumPy

Install the required packages using:
```bash
pip install -r requirements.txt
```

## Repository Structure
```
.
├── SiameseNN_Transformers.2.ipynb          # Main Jupyter Notebook containing code and outputs
├── data/               # Folder containing `train.csv`, `val.csv`, `test.csv`
├── README.md           # Project documentation (this file)
└── requirements.txt    # List of required Python packages
```

## Usage
### Run the Notebook
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook A3.2.ipynb
   ```
2. Follow the instructions in the notebook to execute the code for both tasks.

### Tasks Overview
#### Task 1: Simple Siamese Neural Network
- Implements a Siamese network with:
  - Two hidden layers.
  - ReLU activation.
  - Euclidean-distance-based contrastive loss.
- Outputs prediction accuracy and failure cases.

#### Task 2: Transformer Model
- Implements a Transformer-based model with:
  - Tokenization and padding.
  - Transformer encoder with multi-head attention.
  - Binary classification output.
- Reports test accuracy and analyzes failure cases.



## Contribution
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add feature-name'`).
4. Push to your branch (`git push origin feature-name`).
5. Open a pull request.

## License
