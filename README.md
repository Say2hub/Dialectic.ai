Dialectic.AI 🤯🗣️
Master the art of debate with AI-powered conversations.
Welcome to Dialectic.AI, an innovative AI-powered debate platform designed to sharpen your critical thinking and argumentation skills! Whether you're practicing for a debate, exploring complex topics, or simply curious about AI-driven dialogue, Dialectic.AI has you covered.
Built with Gradio for an interactive experience and powered by the Groq API using the llama-3.3-70B-Versatile model, this project lets you debate an AI opponent or watch two AI agents engage in a dynamic debate on any topic.
This project was developed to showcase the potential of AI in fostering structured reasoning and dialogue, making it a valuable tool for education, professional development, and AI research.

🌟 Features

User vs. AI Debate: Engage in a debate with an AI opponent by choosing your stance (For or Against) and exchanging arguments.
AI vs. AI Debate: Watch two AI agents debate a topic with opening statements, rebuttals, closings, and a neutral final conclusion.
Sequential Dialogue: Arguments stream one after another for a natural, real-time debate flow.
Interactive Interface: Built with Gradio for a seamless and intuitive user experience.
Educational Tool: Perfect for students, educators, and professionals to practice structured argumentation.


🛠️ Tech Stack

Groq API: Powers the llama-3.3-70B-Versatile model for generating thoughtful and logical arguments.
Gradio: Provides an interactive web interface for user engagement.
Python: The core programming language driving the project.


🚀 Getting Started
Prerequisites

Python 3.7+
pip for package management
A Groq API key (get yours here)

Installation

Clone the Repository
git clone https://github.com/your-username/dialectic-ai.git
cd dialectic-ai


Install Dependencies
pip install -r requirements.txt

Note: The full list of dependencies includes:

gradio==5.29.0
groq==0.24.0


Set Up Your Groq API KeySet your Groq API key as an environment variable:
export GROQ_API_KEY="your-api-key-here"  # On Windows: set GROQ_API_KEY=your-api-key-here

Alternatively, replace the placeholder in the code:
groq_api_key = "your-api-key-here"


Run the Application
python dialectic_ai.py

Open the Gradio URL (e.g., http://127.0.0.1:7860) in your browser to start debating!



📂 Project Structure
dialectic-ai/
├── dialectic_ai.py     # Main script for the debate platform
├── requirements.txt    # List of Python dependencies
├── README.md           # You’re reading it!
└── .gitignore          # Excludes unnecessary files from Git

Project Architecture Overview
graph TD
    A[User Input<br><i>Gradio Interface</i>] -->|Topic & Mode| B[Debate Logic<br><i>Python</i>]
    B -->|User vs. AI| C[User-AI Interaction<br><i>State Management</i>]
    B -->|AI vs. AI| D[AI-AI Debate<br><i>Sequential Streaming</i>]
    C -->|Prompt| E[Language Model<br><i>Grok Llama-3.3-70B</i>]
    D -->|Prompts| E
    E -->|Response| F[Debate Output<br><i>Gradio UI</i>]

    style A fill:#lightblue
    style B fill:#lightgreen
    style C fill:#lightyellow
    style D fill:#lightcoral
    style E fill:#lightpink
    style F fill:#lightblue


🎯 How It Works

User vs. AI Debate:
User selects a topic and stance, then engages in a debate with the AI.
The AI generates logical arguments based on the user’s stance and responses.
The debate concludes with a summary.


AI vs. AI Debate:
Two AI agents debate a topic with opening statements, rebuttals, and closings.
Arguments are displayed sequentially for a natural flow.
A neutral AI summarizes the debate and provides a balanced conclusion.


UI Interaction: Gradio delivers a real-time, interactive interface for both debate modes.


📸 Demo
Screenshots
Here’s what Dialectic.AI looks like in action (add your own screenshots to the assets/ directory):
The Gradio interface where users start and engage in debates.
An example of two AI agents debating a topic.
Video Demonstration
Watch Dialectic.AI in action (add your own video to the assets/ directory):
A short demo showing the debate platform in action.

⚙️ Customization

Prompt Tuning: Modify the prompts in dialectic_ai.py to adjust the AI’s debate style or tone.
Model Swap: Experiment with other LLMs supported by the Groq API.
Additional Features: Add more debate rounds, save transcripts, or integrate external data sources for evidence-based arguments.


🌍 Deployment
For a public-facing version:

Run locally with demo.launch(debug=True) for testing.
Deploy to Hugging Face Spaces for free hosting:gradio deploy

Follow the prompts to upload to your HF Space!


⚠️ Disclaimer
Dialectic.AI is designed for educational and entertainment purposes. The AI-generated arguments and conclusions are based on training data and may not reflect factual accuracy or professional opinions. Verify critical information independently.

🤝 Contributing
We’d love your help to make this project even better!  

Fork the repo.
Submit a pull request with your enhancements.
Open an issue for bugs or feature suggestions.


📜 License
This project is licensed under the MIT License—see the LICENSE file for details.

🙏 Acknowledgments

Groq: For providing high-performance AI inference with the Llama-3.3-70B-Versatile model.
Gradio: For making UI creation seamless and interactive.


“Debate smarter, think deeper, and let AI spark the conversation.”Ready to dive into the art of argumentation? Let’s get debating! 🚀
