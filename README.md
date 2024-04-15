# SMS Spam Detection: Python Project

This project implements a machine learning model for classifying SMS messages as spam or legitimate (ham). It leverages the power of Streamlit to create a user-friendly web application for real-time spam detection and utilizes the Natural Language Toolkit (NLTK) for potential text pre-processing tasks.

![spam](https://github.com/KZV027/SMS-Spam-Detection-/assets/94216170/167bb131-d8f5-4340-9181-579c98def5d5)

## Project Structure:

```bash
  sms_spam_detection/
├── data/
│   ├── spam.txt  (or your spam SMS data file)
│   └── ham.txt   (or your ham SMS data file)
├── requirements.txt  (List of project dependencies)
├── model.py         (Code for training and saving the neural network model)
├── streamlit_app.py  (Code for building the Streamlit web application)
```
## Installation:

1. Clone this repository.

2. Create a virtual environment (recommended).

3. Navigate to the project directory.

4. Install dependencies:

```bash
  !pip install nltk
```
## Usage:

1. Train the model
2. Run the Streamlit app:
```bash
  streamlit run sms.py
```
3. Access the app in your web browser 

## Streamlit App:

* Enter an SMS message in the text box.
* Click the "Predict" button.
* The app displays the predicted classification (spam or ham) along with the model's confidence level.


## Additional Notes:

* Consider including pre-processing steps in model.py to clean and prepare SMS data (e.g., removing punctuation, stop words, converting to lowercase).
* Explore different neural network architectures for potentially higher accuracy (e.g., LSTMs).
* For a more robust solution, implement data pre-loading and caching mechanisms.

## Further Development:

* Enhance the Streamlit app with visualizations for model performance metrics.
* Integrate the app into a messaging platform for real-time spam filtering.

Feel free to customize and extend this project to suit your specific needs!
