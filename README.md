# My Travel Buddy

My Travel Buddy is a web application designed to assist users with travel recommendations and information. The application uses templates for the front-end and includes images and styles to create an engaging user interface.

## Project Structure
my_travel_buddy/
├── templates/
│   ├── index.html
│   └── Simple.png


├── static/
│   ├── man.jpeg
│   ├── plane.jpg
│   └── styles.css

my_travel_buddy/
├── myapp.py
├── requirements.txt
└── .env


## Prerequisites

Ensure you have Python 3.7+ installed on your machine. You will also need to install the necessary libraries listed in the `requirements.txt` file.

## Installation

### Step 1: Set Up Environment Variables

Create a `.env` file in the root directory of the project and add the following environment variables:

```
# .env file containing all API keys
OPENAI_API_KEY=your_openai_api_key
ANTHROPIC_API_KEY=your_anthropic_api_key
TAVILY_API_KEY="your_tavily_api_key"
LANGCHAIN_API_KEY="your_langchain_api_key"
```

Replace `your_openai_api_key`, `your_anthropic_api_key`, `your_tavily_api_key`, and `your_langchain_api_key` with your actual credentials.

### Step 2: Install Dependencies

You can install the required dependencies using pip:


pip install -r requirements.txt


## Usage

### Step 3: Run the Application

Execute the main script to start the application:


python myapp.py


This will start the application, and you can access it in your web browser at `http://localhost:8501`.

## Project Files

### Templates

- `index.html`: The main HTML template for the application.
- `Simple.png`: An image used in the template.

### Static Files

- `styles.css`: The CSS file for styling the application.
- `man.jpeg`: An image used in the application.
- `plane.jpg`: Another image used in the application.

## Customization

You can modify the HTML, CSS, and images in the `templates` and `static` directories to customize the appearance of the application.

## Dependencies

Ensure the following dependencies are listed in your `requirements.txt`:

```plaintext
spotipy==2.24.0
openai==1.34.0
langchain_openai==0.1.8
langchain_community==0.2.4
langchain.memory==0.2.9
langchain.prompts==0.2.5
langchain.agents==0.2.5
langchain.schema==0.2.9
python-dotenv==1.0.1
```

## Acknowledgments


- [OpenAI](https://openai.com/) - AI models powering the chatbot.
---
