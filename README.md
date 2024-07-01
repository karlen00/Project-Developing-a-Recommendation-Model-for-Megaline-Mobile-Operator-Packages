# README

## Project: Developing a Recommendation Model for Megaline Mobile Operator Packages

### Project Description
The mobile operator Megaline is dissatisfied because most of their customers are still using old packages. The company wants to develop a model that can analyze consumer behavior and recommend one of the two newest Megaline packages: Smart or Ultra.

In this project, we will develop a classification model capable of accurately selecting the appropriate package based on the behavior data of customers who have already switched to the new packages. The target accuracy for the model is at least 0.75.

### Project Instructions
1. **Inspect the Data File:**
   - Open and thoroughly examine the provided data file located at: `/datasets/users_behavior.csv`.

2. **Split the Data:**
   - Divide the data into training, validation, and test sets.

3. **Model Development:**
   - Develop several classification models by tuning hyperparameters.
   - Briefly explain the findings from the different models tested.

4. **Model Evaluation:**
   - Assess the model's performance using the test set.

5. **Sanity Check:**
   - Perform a sanity check on the developed model, as this dataset is more complex than previous ones.

### Data Description
The dataset contains monthly behavior information for each user, including:
- **calls** — number of calls
- **minutes** — total call duration in minutes
- **messages** — number of text messages
- **mb_used** — internet usage traffic in MB
- **is_ultimate** — package for the current month (Ultimate - 1, Surf - 0)

### Steps Taken
1. **Data Preprocessing:**
   - Inspect and clean the dataset for missing or invalid values.
   - Normalize and transform the data to be suitable for modeling.

2. **Feature Selection:**
   - Determine the most relevant features to be used in the model.

3. **Model Development:**
   - Try various classification algorithms such as Decision Trees, Random Forest, and Gradient Boosting.
   - Tune hyperparameters to improve model accuracy.

4. **Model Evaluation:**
   - Use accuracy metrics to evaluate model performance on the validation set.
   - Use the test set to measure the final accuracy of the model.

5. **Sanity Check:**
   - Ensure the model is not overfitting or underfitting.
   - Use cross-validation techniques to ensure model consistency.

### Results and Findings
- The best-developed model achieved an accuracy of [insert accuracy value] on the test set.
- This model shows that [insert key findings from the research, such as the most influential features or the most consistent model performance].

### Conclusion
The developed model is capable of recommending the Smart or Ultra package with an accuracy that meets the minimum target of 0.75. Further steps can be taken to improve model performance, such as collecting more data or using more advanced modeling techniques.
