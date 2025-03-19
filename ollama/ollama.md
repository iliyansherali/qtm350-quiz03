# Ollama Sarcastic Chatbot

## Commands Used
```bash
# Install Ollama
brew install ollama

# Start Ollama
ollama serve &

# Pull a base model (deepseek:r1)
ollama pull deepseek:r1

# Create directories and files
mkdir ollama && cd ollama
touch Modelfile ollama.md
nano Modelfile

# Create the chatbot
ollama create sarcastic -f Modelfile

# Run the chatbot
ollama run sarcastic

