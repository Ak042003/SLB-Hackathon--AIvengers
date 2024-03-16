# SLB-Hackathon--AIvengers
**Language Translation Application using Streamlit**
This application is designed to translate text content from English to another language using the Hugging Face model for translation. The core functionality of this application is to process text input, parse it into structured data, translate it into the desired language, and then save the translated content as a JSON file.

**Usage:**

1) **Installation**:

Ensure you have Python installed on your system.
Install the required libraries using pip install -r requirements.txt.
Make sure you have access to the Hugging Face model API and obtain an authorization token.

2) **Input Text**:

Provide the text you want to translate in the designated area.

3) **Language Selection**:

Choose the target language you want to translate the text into.

4) **Translation Process**:

The application will process the input text, parsing it into structured data.
It will then translate the content into the selected language using the Hugging Face model.
The translated content will be structured in JSON format with keys for different sections of the original text.

5) **Output**:

The translated content will be displayed on the user interface.
Additionally, the translated data will be saved as a JSON file for further use.

**Requirements:**

Python 3.x
Streamlit
Requests
Hugging Face Model API access

**How to Run:**

Clone this repository to your local machine.
Install the required dependencies using pip install -r requirements.txt.
Obtain an authorization token for accessing the Hugging Face model API.
Run the Streamlit application using streamlit run app.py.
Input the text you want to translate and select the target language.
View the translated content on the application interface.
The translated data will also be saved as a JSON file in the specified location.
