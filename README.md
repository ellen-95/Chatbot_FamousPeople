# Chatbot: Talk with Albert Einstein

This project is an interactive chatbot that embodies the personality of Albert Einstein. Powered by [LangChain](https://python.langchain.com/) and [Gradio](https://www.gradio.app/), it allows users to chat with an AI that responds as Einstein, sharing personal anecdotes and scientific insights.

## Features

- Chat with an AI modeled after Albert Einstein
- Responses include personal experiences and reasoning
- Built with Python, LangChain, and Gradio
- Simple web interface

## Getting Started

1. **Clone the repository:**
   ```
   git clone https://github.com/ellen-95/Chatbot_FamousPeople.git
   cd Chatbot_FamousPeople
   ```
2. **Install dependencies:**
   ```
   pip install -r requirements.txt
   ```
3. **Set up your API key:**
  - Create a .env file in the project root.
  - Add your Gemini API key:
    ```
    GIMINI_API_KEY=your_google_gemini_api_key
    ```
4. **Run the app:**
   ```
   python main.py
   ```
## Deployment
This chatbot is deployed using Gradio. When you run the app, Gradio provides a public URL for sharing your chatbot.
**Note: The public Gradio URL is only available for one week.**

### Long-term Deployment Options
For persistent public access, consider these alternatives:
- Hugging Face Spaces
- Streamlit Cloud
- Heroku
- Vercel
- Docker containerization for flexible hosting

## Future Improvements
- Add support for more famous personalities
- Enhance conversation memory and context
- Integrate custom domain support
- Improve UI/UX with more avatars and themes
- Add multilingual support

