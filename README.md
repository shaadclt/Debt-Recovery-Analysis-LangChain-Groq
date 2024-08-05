# Debt Recovery Analysis with Langchain and Groq
This project leverages Langchain and Groq to analyze conversations between recovery agents and borrowers. The analysis includes summarization, key actions identification, sentiment analysis, named entity recognition (NER), and non-compliance checks.

## Overview
The project employs the Langchain and Groq models to:

1. Summarize conversations.
2. Identify key actions or next steps.
3. Perform sentiment analysis of both the recovery agent and the borrower.
4. Conduct named entity recognition.
5. Check for non-compliances based on predefined scenarios.

## Installation
To run this project, you'll need to install the required packages. The necessary packages are Langchain and Langchain-groq, which can be installed using pip.

## Environment Setup
API keys are necessary for accessing external services. You need to set up environment variables for Langchain and GROQ API keys. This allows the model to access and utilize the required external services.

## Model Initialization
Initialize the Groq model for processing the conversations. The model "llama3-8b-8192" is used for this purpose. This step sets up the model with the specified parameters and prepares it for the tasks.

## Instructions for the Model
Define the instructions for the model to perform the necessary tasks. These instructions guide the model to:

1. Summarize the conversation.
2. Identify key actions or next steps.
3. Perform sentiment analysis for both the recovery agent and the borrower.
4. Conduct named entity recognition.
5. Check for non-compliances based on predefined scenarios such as using threatening language, disclosing debt information to third parties, calling outside permissible hours, providing false or misleading information, and failing to validate the debt.

## Processing the Conversation
The conversation is processed by the model using the defined instructions. The model takes the conversation as input along with the instructions and performs the tasks specified.

## Output Parsing
The output from the model is parsed to get structured results. This involves interpreting the model's response and organizing it into a format that is easy to understand and use.

## Usage
To use this project:

1. Install the required packages.
2. Set up the environment variables with your API keys.
3. Initialize the Groq model.
4. Define the instructions for the model.
5. Process the conversation using the model.
6. Parse the output to get structured results.
   
Run the Colab notebook, provide the conversation as input, and let the model perform the analysis. Review the structured results to get insights into the conversation.

## License
This project is licensed under the MIT License.
