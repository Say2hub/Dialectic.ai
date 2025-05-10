Dialectic.AI 🤯🗣️
Welcome to Dialectic.AI, the ultimate AI-powered debate platform that transforms how you engage with ideas! Whether you’re sharpening your argumentation skills, preparing for a debate, or exploring the power of AI in dialogue, Dialectic.AI offers an immersive experience that’s both educational and exciting. Built with Gradio for a seamless interface and powered by the Groq API with the Llama-3.3-70B-Versatile model, this project lets you debate an AI opponent or watch two AI agents go head-to-head on any topic.
From classrooms to boardrooms, Dialectic.AI is your partner in mastering critical thinking and unlocking the potential of AI-driven discourse.
Why Dialectic.AI Rocks
Dialectic.AI isn’t just a tool—it’s a game-changer for how we learn, argue, and innovate. Here’s why it stands out:

Boosts Critical Thinking: Hone your ability to craft compelling arguments, anticipate counterpoints, and think logically by debating with a sophisticated AI.
Educational Powerhouse: Perfect for students, teachers, and debate clubs to practice structured argumentation and explore complex issues.
Professional Edge: Lawyers, politicians, and business leaders can refine persuasion, negotiation, and conflict resolution skills for real-world scenarios.
Pushes AI Boundaries: Showcases advanced natural language processing (NLP) and dialogue systems, demonstrating AI’s ability to engage in nuanced, multi-turn conversations.
Real-World Impact: From courtroom prep to policy analysis, Dialectic.AI has applications in education, law, politics, online platforms, and even personal decision-making.

Features

User vs. AI Debate:
Start a debate on any topic you choose.
Pick your stance (For or Against) and exchange arguments with the AI.
Conclude with a summary to wrap up your debate.


AI vs. AI Debate:
Enter a topic and watch two AI agents debate it with opening statements, rebuttals, and closings.
Arguments stream sequentially for a dynamic experience.
A neutral AI delivers a balanced final conclusion, summarizing both sides.


User-Friendly Interface:
Intuitive design makes it easy to jump into debates and explore AI-driven discussions.



Prerequisites

Python 3.7+
Groq API Key: Get yours by signing up at Groq.

Setup

Clone the Repository
git clone https://github.com/your-username/dialectic-ai.git
cd dialectic-ai


Set Up a Virtual Environment (Recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate


Install Dependencies
pip install -r requirements.txt


Set the Groq API Key
Set your Groq API key as an environment variable:
export GROQ_API_KEY="your-groq-api-key"  # On Windows: set GROQ_API_KEY=your-groq-api-key

Alternatively, modify the code to include your key directly (not recommended for security).


Usage

Run the Application
python dialectic_ai.py

This launches the Gradio interface in your browser.

Explore the Interface

User vs. AI Debate:
In the "Start Debate" tab, enter a topic (e.g., "Should AI be regulated?") and choose your stance.
Move to the "Debate" tab to submit arguments.
Conclude in the "End Debate" tab.


AI vs. AI Debate:
In the "AI vs. AI Debate" tab, input a topic and click "Start AI Debate".
Watch the debate unfold step-by-step, ending with a neutral conclusion.





Running in Google Colab
To run Dialectic.AI in Google Colab:

Upload dialectic_ai.py to your Colab environment.
Set your Groq API key in Colab Secrets:
Click the key icon in the sidebar.
Add a secret named GROQ_API_KEY with your key.


Update the API klucz retrieval in the code:from google.colab import userdata
groq_api_key = userdata.get('GROQ_API_KEY')


Run the cell to launch the interface.

Contributing
Got ideas to make Dialectic.AI even better? We’d love your input! Open an issue or submit a pull request to share your enhancements, from new features to UI improvements.
License
This project is licensed under the MIT License.
Acknowledgments

Powered by Groq and the Llama-3.3-70B-Versatile model for lightning-fast AI inference.
Built with Gradio for an intuitive and responsive interface.


Ready to debate like a pro? Clone Dialectic.AI and start exploring the art of argumentation today! 🚀
