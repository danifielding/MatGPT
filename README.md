# matgpt

This project integrates OpenAI's ChatGPT API with MATLAB. It provides a seamless way to send prompts to the any OpenAI LLM model and retrieve AI-generated responses in real-time. This integration can be used for automated MATLAB scripting, data analysis, or educational purposes.

# Features
* HTTP communication:
  * Utilizes MATLAB's webwrite function to send POST requests to the OpenAI API
* Customizable API calls:
  * Easily modify the prompts and other parameters to tailor the interaction with ChatGPT
* Response handling
  * Parses and displays the response from ChatGPT directly in the MATLAB console

# Prerequisites
* MATLAB:
  * Ensure MATLAB is installed on your system
* OpenAI API key:
  * Obtain an API key from OpenAI

# File Structure
* chatgpt.m:
  * The main function that makes HTTP calls to the OpenAI API
* run_chatgpt.m:
  * A script that demonstrates how to use the chatgpt.m function with a sample prompt
* README.md:
  * This document

# Setup and Installation
1.) Clone the Repository:
* git clone git@github.com:your-username/matgpt.git
* cd MATLAB-ChatGPT-Integration

2.) Add Your OpenAI API Key:
* Open run_chatgpt.m.
* Replace 'your-api-key' with your actual OpenAI API key.

3.) Run the Example:
* In MATLAB, navigate to the project directory and run:
  * run_chatgpt

# Usage of "chatgpt.m"
This function sends a prompt to the OpenAI ChatGPT API and returns the model's response.

# Usage of run_chatgpt.m"
This script demonstrates how to use the chatgpt.m function with a sample prompt.

# Contributions 
Contributions are welcome! Please submit a pull request with a clear description of the changes. Ensure that your code follows MATLAB coding standards and is thoroughly tested.

# License
This project is licensed under the Creative Commons License. See the LICENSE file for more details.
