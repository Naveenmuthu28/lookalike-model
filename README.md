# Lookalike Modeling with Logistic Regression and ML Algorithms

This project demonstrates a Lookalike Modeling approach using Logistic Regression and other machine learning algorithms to identify potential target groups based on similarity to a known seed group.

The core idea is to build a model that finds individuals in a "pool group" who resemble those in a "seed group" using historical features.


---

## Use Case Example

For this implementation, a diabetes dataset is used as an example domain:

- Seed group: Patients known to have diabetes
- Pool group: Individuals with unknown status
- Goal: Predict pool individuals likely to have diabetes (i.e., lookalikes of the seed group)

This approach is adaptable to other domains like marketing, fraud detection, customer segmentation, etc.

---

## Project Structure
```
lookalike-model/
├── Synthetic Dataset Generation Code/
│ └── synthetic email spam dataset.ipynb
├── diabetes_dataset.csv
├── diabetes_test_dataset.csv
├── predicted_diabetes_present_logistic.csv
├── look_alike_logistic.ipynb
├── look_alike_KNN.ipynb
├── look_alike_decisiontree.ipynb
├── requirements.txt
└── README.md
└── LICENSE
```
---

## Technologies Used

- Python
- Pandas & NumPy
- Scikit-learn
- Jupyter Notebook
- Logistic Regression, KNN, Decision Tree
- Synthetic Data Generation Techniques

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Naveenmuthu28/lookalike-model.git
   cd lookalike-model

2. Install dependencies:
   pip install -r requirements.txt

3. Open and run the notebooks in Jupyter:

    - look_alike_logistic.ipynb
    - look_alike_KNN.ipynb
    - look_alike_decisiontree.ipynb
    - (Optional) synthetic email spam dataset.ipynb to see synthetic data generation

---

## Files Description

- diabetes_dataset.csv: Source data with known diabetic cases
- diabetes_test_dataset.csv: Pool group with unknown cases
- predicted_diabetes_present_logistic.csv: Output of the logistic regression mode
- look_alike_logistic.ipynb: Lookalike modeling using Logistic Regression
- look_alike_KNN.ipynb: Lookalike modeling using KNN
- look_alike_decisiontree.ipynb: Lookalike modeling using Decision Tree
- synthetic email spam dataset.ipynb: Code for generating a synthetic dataset for email spam classification

---


## License
This project is licensed under the MIT License.
