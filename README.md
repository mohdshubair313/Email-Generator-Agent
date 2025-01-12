# Email Generator Agent

## Overview

The Email Generator Agent is a project designed to automate the process of generating cold emails for job postings. By leveraging advanced AI models, it extracts job descriptions from URLs and creates compelling emails aimed at potential employers.

## Watch the Project Video

[![Youtube Video](https://img.youtube.com/vi/2Xo11kjJiZk/0.jpg)](https://www.youtube.com/watch?v=2Xo11kjJiZk)

## Technologies Used

- **Jupyter Notebook**: Used for creating and sharing documents that contain live code, equations, visualizations, and narrative text.
- **Python**: The primary programming language used for the project.
- **nest_asyncio**: A library to allow nested use of `asyncio.run`.
- **pydantic**: Data validation and settings management using Python type annotations.
- **pydantic_ai**: Integration of AI models with Pydantic for data validation.
- **rich**: A Python library for rich text and beautiful formatting in the terminal.
- **html2text**: Converts HTML to Markdown-formatted text.
- **python-dotenv**: Reads key-value pairs from a `.env` file and can set them as environment variables.
- **requests**: Simple HTTP library for Python.
- **BeautifulSoup**: A library for web scraping to pull data out of HTML and XML files.
- **Gradio**: A library for quickly creating user interfaces for machine learning models.

## Installation

To set up the project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/mohdshubair313/Email-Generator-Agent.git
    cd Email-Generator-Agent
    ```

2. Create a virtual environment and activate it:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Configure the environment variables:
    Copy the `.env.example` to a new file named `.env` and fill in your API key:
    ```bash
    cp .env.example .env
    ```

## Usage

To use the Email Generator Agent, follow these steps:

1. Open the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

2. Open `notebook/cold_email_generator.ipynb` and run all cells.

3. The notebook will prompt you to input the URL of a job posting. The agent will then scrape the job posting, extract relevant information, and generate a cold email.

## Project Structure

- `notebook/cold_email_generator.ipynb`: The main Jupyter Notebook for generating cold emails.
- `src/agent/agent.py`: Entrypoint for the email generator agents.
- `src/agent/cold_email_writer_agent/agent.py`: Code for the cold email writing agent.
- `requirements.txt`: List of required Python packages.

## Contributing

Contributions are welcome! Please create a pull request with a detailed description of the changes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

For any questions or inquiries, please contact [mohdshubair313](https://github.com/mohdshubair313).

---

Feel free to explore the repository and make the most of the Email Generator Agent!
