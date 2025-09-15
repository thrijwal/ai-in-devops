🐳 Dockerfile Generator
A GenAI powered tool that generates optimized Dockerfiles based on programming language input. This project uses Ollama with the Llama3 model to create Dockerfiles following best practices.

💡 How It Works
    1. The script takes a programming language as input (e.g., Python, Node.js, Java)
    2. Connects to the Ollama API running locally
    3. Generates an optimized Dockerfile with best practices for the specified language
    4. Returns the Dockerfile content with explanatory comments

🚀 Project Setup
    1. Download and Install Ollama
       curl -fsSL https://ollama.com/install.sh | sh
    2. Start Ollama Service
       ollama serve
    3. Pull Llama3 Model
       ollama pull llama3.2:1b

📝 Example Usage
    PS D:\DevOps\devops-with-genai\llm-projects\local-llms-ollama\dockerfile-generator> py .\generate_dockerfile.py
         Enter the programming language: groovy
         Generated Dockerfile:
         <think>
            Alright, so I'm trying to create a Dockerfile for Groovy. Let me think about how to approach this step by step.

Result
   Here’s an ideal Dockerfile for Groovy, incorporating best practices and clear steps:

   ```dockerfile
   # Dockerfile for Groovy

   # Base Python version
   FROM py3

   # Install dependencies
   RUN pip3 install -r requirements.txt

   # Build system configurations
   ALpine
   poetry --install poetry linter typescript
   poetry --system-set --build TypeScript-exc "typescript-exc/lyndon"
   poetry --system-set build build --project g

   # Create working directory
   mkdir -p app

   # Install development tools
   RUN pip3 install -r requirements.txt


   # Add Groovy CLI tool (for Windows)
   RUN g install --path "C:\Program Files" --build 1
   RUN g install --path "C:\Program Files" --build 1


   # Set up the container with the application
   RUN g-run --app root --web /app/app.html
   RUN g-run --app root --web /app/app.html   