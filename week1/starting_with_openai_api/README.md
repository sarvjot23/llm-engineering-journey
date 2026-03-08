# Learning to Interact with Open AI API using Python

This project is an AI-focused exercise designed to consolidate learning progress in Jupyter Notebook and Python by integrating with OpenAI's GPT models.

## Key Features
- Loads environment variables using Python `dotenv` library.
- Connects to OpenAI's API using an API key.
- Demonstrates usage of OpenAI's `chat.completions` API.
- Contains error handling for API key validation.

## Tech Stack
- ![Jupyter Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange?logo=jupyter)
- ![Python](https://img.shields.io/badge/Python-3.8-blue?logo=python)

## Prerequisites & Installation
1. Make sure you have Python and Jupyter Notebook installed.
2. Clone this repository:
   ```bash
   git clone <repository-url>
   cd <repository-dir>
   ```
3. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Set up your `.env` file to store your OpenAI API key:
   ```
   OPENAI_API_KEY=your_openai_api_key_here
   ```

## Usage / How to Run
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook "learning_interaction_with_openai_api.ipynb"
   ```
2. Execute the cells in the notebook to test the integration with OpenAI's API.

## What I Learned
This project taught me how to:
- Use Python to manage and validate environment variables.
- Interact with OpenAI's API in a Jupyter Notebook environment.
- Handle common issues related to API key usage.

## License
This project is licensed under the MIT License.