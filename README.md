
# Credit-Card-Fraud-Detection
 About The Code:

This is a machine learning project for credit card fraud detection. The project uses a logistic regression model to classify transactions as either legitimate or fraudulent based on their features.

The code begins with importing necessary libraries such as numpy, pandas, scikit-learn, and Streamlit. Then, the layout of the Streamlit application is set using the st.set_page_config() function. The load_data() function is defined to load data from a CSV file, which is uploaded by the user using the file_uploader() function. The train_model() function is defined to train a logistic regression model on the uploaded data. The function first separates the legitimate and fraudulent transactions, undersamples the legitimate transactions to balance the classes, and then splits the data into training and testing sets using the train_test_split() function. The logistic regression model is then trained on the training data and evaluated on the training and testing data using the accuracy_score() function.

The parse_transaction_string() function is defined to parse a comma-separated string of transaction features and convert it into a dictionary with feature names as keys and feature values as values.

Finally, the Streamlit application is created using the st.title() function to set the title, the file_uploader() function to allow the user to upload a CSV file, and the text_input() function to allow the user to input transaction features and get a prediction. The uploaded data is loaded using the load_data() function, and the model is trained and evaluated using the train_model() function. The training and testing accuracies are displayed using the st.write() function, and the user can input transaction features using the text_input() function.


![image](https://github.com/user-attachments/assets/84b60a55-3d3e-4003-9607-53e99dee0bb8)

