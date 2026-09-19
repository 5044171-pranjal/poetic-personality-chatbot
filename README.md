echo "# 🌙 Poetic Personality Chatbot

A case project that transforms everyday user thoughts and feelings into lyrical poetry using an LLM via OpenRouter and advanced prompt engineering, complete with a real-time typing animation effect.

## 🚀 Features
* **Prompt Engineering:** Uses custom system instructions to shape the model into a warm, empathetic poetic companion.
* **Live Typing Animation:** Simulates a live poet composing verses line by line on your screen.
* **OpenRouter Integration:** Connects efficiently using the OpenAI Python SDK.

## 🛠️ Requirements
* Python 3.8+
* An OpenRouter API key

## ⚙️ Setup & Usage
1. Clone the repository:
   \`\`\`bash
   git clone https://github.com/5044171-pranjal/poetic-personality-chatbot.git
   cd poetic-personality-chatbot
   \`\`\`
2. Install the required dependencies inside your notebook or terminal:
   \`\`\`bash
   pip install openai --quiet
   \`\`\`
3. Set your OpenRouter API key as an environment variable:
   * **On Windows (Command Prompt):**
     \`\`\`cmd
     set OPENROUTER_API_KEY=your-api-key-here
     \`\`\`
   * **On Windows (PowerShell):**
     \`\`\`powershell
     \$env:OPENROUTER_API_KEY=\"your-api-key-here\"
     \`\`\`
   * **On Mac/Linux:**
     \`\`\`bash
     export OPENROUTER_API_KEY=\"your-api-key-here\"
     \`\`\`
4. Open the Jupyter Notebook and run the cells:
   \`\`\`bash
   jupyter notebook Poetic_Personality_Chatbot.ipynb
   \`\`\`

## 📝 Example Interaction
> **You:** I'm feeling happy today  
> **Poet:**  
> In fields of joy, your heart does dance,  
> With sunlight's glow, your soul's expanse.  
> Each breath a bloom, each step a song,  
> This lightness in you - stay this long." > README.md