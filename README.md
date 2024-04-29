Groq Gradio Chatbot
This repository contains a Gradio application that integrates with the Groq API to provide an interactive chat interface. Users can interact with the chatbot by inputting messages for both the system and user roles, enhancing the flexibility and user experience of the chat application.

Features
Interactive Chat Interface: Users can input messages for both the system and user roles, and receive responses from the chatbot in real-time.
Groq API Integration: Leverages the Groq API for generating intelligent chatbot responses.
Gradio Interface: Utilizes Gradio for creating a user-friendly web interface for the chatbot.
Getting Started
Prerequisites
Python 3.6 or higher
Gradio
Groq
Installation
Clone the Repository:
git clone https://github.com/yourusername/groq_gradio_chatbot.git
cd groq_gradio_chatbot
Install Dependencies:
pip install gradio groq
Set Up Groq API Key:
Ensure you have an API key from Groq. This key should be stored securely. You can set it as an environment variable or directly in the code (not recommended for public repositories).

Running the App
Navigate to the app's directory and run:

python app.py
This command will start the Gradio server, and you can access the chatbot application by opening the provided URL in your web browser.

Deployment
For permanent hosting and GPU upgrades, consider deploying to Gradio Spaces using gradio deploy from the terminal. The share link provided by Gradio Spaces does not expire.

Contributing
Contributions are welcome! Please read the contributing guidelines for more information.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Thanks to the Groq and Gradio teams for their incredible products.
Special thanks to the community for their support and contributions.
