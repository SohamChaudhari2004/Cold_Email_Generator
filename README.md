# Cold Email Generator

This project is a Cold Email Generator that uses web scraping and language models to generate personalized cold emails based on job listings from various websites.


## Screenshots
![image](https://github.com/user-attachments/assets/c10cd89f-f5e9-4b89-84a4-363c5ee26cb8)
#### -----------------------------------------------------------------------------------------------------------------------------------------------------------
![image](https://github.com/user-attachments/assets/06c6fbf8-70b9-43fd-9bc9-3e2202d51f8c)


## Features

- Scrapes job details from a provided URL.
- Extracts job descriptions, skills, and other relevant information.
- Generates tailored cold emails using language models.
- Integrates portfolio links to showcase relevant projects.

## Prerequisites

- Python 3.8 or higher
- Git

## Installation

Follow these steps to set up the project on your local machine.

### 1. Clone the Repository

First, clone the repository to your local machine using:

```bash
git clone https://github.com/your-username/ColdEmailGenerator.git
cd ColdEmailGenerator
```

## Set Up a Virtual Environment (Recommended)

It is recommended to use a virtual environment to manage dependencies. To create and activate a virtual environment, run:

### On Windows:

bash:

```
python -m venv venv
.\venv\Scripts\activate
```

### On macOS and Linux:

bash:

```
python3 -m venv venv
source venv/bin/activate
```

### Install Dependencies

Install the required dependencies using the requirements.txt file:

Bash:

```
pip install -r requirements.txt
```

OR

Install globally on loacal system
Command Prompt:
```
pip install langchain langchain_community langchain_groq chromadb pandas python-dotenv unstructured selenium
```

<br>
<br>

````
This will install the following packages:

langchain==0.2.14
langchain-community==0.2.12
langchain-groq==0.1.9
unstructured==0.14.6
selenium==4.21.0
chromadb==0.5.0
streamlit==1.35.0
pandas==2.0.2
python-dotenv==1.0.0
````

### Set Up Environment Variables
Create a .env file in the root(app directiry) of the project to store environment-specific variables such as API keys. For example:

.env:
```
GROQ_API_KEY=your_api_key_here
```
### Run the Application
Start the Streamlit application by running:

bash
Copy code
```
streamlit run app/main.py
```
This command will launch the app, and it will be accessible at http://localhost:8501 in your web browser.

## Troubleshooting
Virtual Environment Not Set Up: If you don't want to use a virtual environment, you can install dependencies globally, but this is not recommended as it can lead to conflicts.
<br>
<br>
User Agent Warning: If you see a warning about the USER_AGENT environment variable not being set, you can ignore it or set it explicitly in your .env file.

