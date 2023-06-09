# PDF Query Tool

## Description

This is a Python application using Streamlit that allows you to query a PDF file using natural language. It uses the OpenAI API to perform a similarity search in the text extracted from the uploaded PDF file. Given a user's query, it provides a response based on the contents of the PDF file.

## Installation

Before you start using this program, ensure that you have installed Python 3.x on your machine. If not, download and install Python from [here](https://www.python.org/downloads/).

After installing Python, clone this repository to your local machine by running the following command in your terminal:

```
git clone https://github.com/michelstoc/PDFQuery.git
```

Next, navigate to the repository's directory:

```
cd PDFQuery
```

Create a virtual environment to isolate your project's dependencies. Run the following command:

```
python3 -m venv venv
```

Activate the virtual environment:

- On Windows:
```
venv\Scripts\activate
```
- On Unix or MacOS:
```
source venv/bin/activate
```

Once your virtual environment is activated, install the required dependencies with the following command:

```
pip install -r requirements.txt
```

## Setup

Ensure that you have the OpenAI API key. This key should be stored as an environment variable. You can set it using the following command:

```
export OPENAI_API_KEY="your-api-key"
```

You also need to have a `.env` file in your project root directory with your OpenAI API key as follows:

```
OPENAI_API_KEY=your-api-key
```

The program uses the python-dotenv package to load this environment variable from the `.env` file.

## Usage

To start the Streamlit app, run the following command in your terminal:

```
streamlit run app.py
```

This will start a local development server and open a new browser window or tab with the Streamlit interface. Here, you can upload a PDF file and ask questions related to the content of the uploaded PDF file.

## Contribution

Contributions are welcome! Please feel free to make a pull request or open an issue on GitHub. If you notice a bug or have a feature request, please use the issues page to let us know.
