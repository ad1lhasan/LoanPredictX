# LoanPredictX

LoanPredictX is a machine learning-based predictive model designed to classify loan defaults using boosting algorithms. The model leverages advanced techniques to enhance accuracy and interpretability, making it a robust solution for financial risk assessment.

## Features
- **Boosting Algorithms**: Utilizes XGBoost, LightGBM, and CatBoost for high-performance classification.
- **Explainability**: Incorporates SHAP and LIME for model interpretability.
- **Hidden Risk Factor Analysis**: Identifies key risk factors affecting loan default predictions.
- **Interactive Web Dashboard**: Visualizes predictions and insights in real-time.
- **AI-Powered Risk Alerts**: Provides risk assessment notifications based on model predictions.

## Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/ad1lhasan/LoanPredictX.git
cd LoanPredictX
pip install -r requirements.txt
```

## Usage
1. Prepare your dataset and place it in the `data/` directory.
2. Run the preprocessing script:
   ```bash
   python preprocess.py
   ```
3. Train the model using:
   ```bash
   python train.py
   ```
4. Evaluate the model:
   ```bash
   python evaluate.py
   ```
5. Launch the web dashboard:
   ```bash
   streamlit run dashboard.py
   ```

## Dataset
The model is trained on loan-related features, such as:
- Applicant income
- Loan amount
- Credit history
- Debt-to-income ratio
- Employment status

## Model Explainability
SHAP and LIME are used to analyze feature importance and individual predictions, providing transparency in decision-making.

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests to improve the project.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For questions or collaborations, reach out via email at `muhammedadilhasan@gmail.com` or connect on [ad1lhasan](https://www.linkedin.com/in/ad1lhasan/).

