✍️ AI Blog Generator

An AI-powered blog generator built with Python, Streamlit, LangChain, and Groq.

This project creates a blog post through a three-step pipeline: it generates an outline, writes a draft, and polishes the final content.

✨ Features

* 📝 Generate a blog outline from a topic
* ✍️ Create a complete blog draft
* ✨ Polish the draft for better readability
* 🎨 Choose a writing tone: Direct, Normal, or Friendly
* ⚡ Powered by Groq’s language models
* 🖥️ Simple and interactive Streamlit interface

🛠️ Tech Stack

* Python
* Streamlit
* LangChain
* Groq
* python-dotenv

⚙️ Setup and Installation

1. Clone the repository

git clone https://github.com/DivyanshuJain2006/ai-blog-generator.git
cd ai-blog-generator

2. Install dependencies

pip install -r requirements.txt

3. Configure environment variables

Create a .env file in the project directory and add your credentials:

GROQ_API_KEY=your_groq_api_key
MODEL=your_groq_model_name

Replace the placeholder values with your actual API key and the model name supported by your Groq account.

Important: Never upload your .env file or expose your API key publicly.

4. Run the application

streamlit run app.py

The application will open in your browser.

🚀 How It Works

1. Outline: Generates an outline based on the topic and selected tone.
2. Draft: Writes the blog post using the generated outline.
3. Polish: Improves the draft and adds a title while preserving its meaning.

📁 Project Structure

ai-blog-generator/
├── app.py
├── requirements.txt
├── .gitignore
└── README.md

📌 Future Improvements

* Download generated blogs as Markdown files
* Add more writing tones and customization options
* Improve error handling and user feedback
* Add a blog history feature

