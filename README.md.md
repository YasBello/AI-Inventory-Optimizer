# AI Inventory Optimizer 





For this project, we made a simple machine-learning system that predicts weekly sales using the Walmart Sales Forecasting dataset. It includes a trained XGBoost model and a small command-line prototype that lets the user enter store/department details and receive a predicted sales value!

---------------------------------------------------------------------------------------------------

#### Project Structure



**AI-Inventory-Optimizer** 

**Phase 1**

* Project\_Proposal.pdf



**Phase 2**

* Data\_Report.docx
* walmart\_preprocessed.csv
* feature\_dictionary.docx



**Phase 3**

* final\_xgboost\_model.pkl
* train\_and\_save\_model\_fixed.py
* Evaluation\_Report.pdf



**Phase 4**

* inventory\_mvp.py
* walmart\_preprocessed.csv



README.md

--------------------------------------------------------------

#### Installation



Make sure Python 3.10+ is installed:



pip install -r requirements.txt



**How to Run the Model**



To run the interactive prototype go to the Phase 4 folder.



Make sure the dataset (walmart\_preprocessed.csv) is in the same folder.



**Run:**



python inventory\_mvp.py


The script loads the trained model and asks for store/department inputs to generate a predicted weekly sales value.

------------------------------------------------------------------------------------------------------------

#### About the Model



Algorithm: XGBoost Regressor



Training file: walmart\_preprocessed.csv



Saved model: final\_xgboost\_model.pkl



The prototype loads the saved model and uses it for instant predictions.



**Dataset**



We used the publicly available Walmart Retail Sales dataset from Kaggle. The Phase 2 folder contains the cleaned and preprocessed version of the dataset used for training.



