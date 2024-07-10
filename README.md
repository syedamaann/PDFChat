# Revise lecture notes fast and simple!

https://github.com/syedamaann/PDFChat/assets/74735966/6cbba293-fbeb-40d7-b410-7ae68b69c9cd

As a student, I needed a way to quickly revisit my lecture notes, get specific explanations, and quiz myself to streamline my study workflow. While you can do this directly on ChatGPT, I thought it would be fun to build a lightweight application for this purpose. 

The app uses LangChain for orchestration, Streamlit for the UI, Ollama to run the LLM, and Neo4j to store vectors for efficient information retrieval. Docker is used for easy deployment and scalability.

<br />

## Setup Instructions

1. **Clone the repository:**
    ```bash
    git clone https://github.com/syedamaann/PDFChat.git
    cd PDFChat
    ```

2. **Build the Docker image:**
    ```bash
    docker build -t PDFChat .
    ```

3. **Run the application with Docker Compose:**
    ```bash
    docker-compose up
    ```

4. **Install Python dependencies (if not using Docker):**
    ```bash
    pip install -r requirements.txt
    ```

5. **Run the application (if not using Docker):**
    ```bash
    python app.py
    ```

That's it! You should now have the application up and running.

<br />

## Troubleshooting

- **API Key:** Ensure your OPENAI API Key is correctly set in .env if using OpenAI.
- **Dependencies:** Verify Python environment and network connectivity for installing dependencies.
- **Containerisation:** Check Docker installation and permissions for building and deploying images.
