# UI for AI with Gradio!

This is a learning project that demonstrates how to create interactive UIs using Gradio for AI-related applications.

## What It Does

- Provides interactive user interfaces using the Gradio library
- Demonstrates integration with various AI service providers like OpenAI, Anthropic, and Google
- Showcases environment variable management with Python's `dotenv` package
- Runs entirely within a Jupyter Notebook environment for quick prototyping and testing

## Tech Stack

- **Languages**: ![Python](https://img.shields.io/badge/python-3.8%2B-blue) ![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)
- **Libraries**: Gradio, OpenAI, Python dotenv

## Prerequisites & Installation

Ensure you have Python 3.8 or newer installed on your system.

1. Clone the repository:

   ```bash
   git clone https://github.com/username/gradio-day.git
   cd ui_for_ai_with_gradio
   ```

2. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Set up your environment variables by creating a `.env` file in the project root directory with the following content:

    ```ini
    OPENAI_API_KEY=your_openai_api_key
    ANTHROPIC_API_KEY=your_anthropic_api_key
    GOOGLE_API_KEY=your_google_api_key
    ```

## Usage

1. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

2. Open the `ui_for_ai_with_gradio.ipynb` notebook and run all cells to start the Gradio application and interact with the AI services.

## What I Learned

- How to use Gradio to build quick and simple user interfaces for machine learning models.
- The process of managing API keys securely using environment variables and the dotenv library.
- How to integrate multiple AI service providers into a singular application for broader functionality.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.