# Avengers Chatbot with LLM Integration

## Overview
This project is a chatbot application that leverages the strengths of Large Language Models (LLM) to handle natural language queries specifically related to the Avengers. The chatbot is developed using Flowise and integrates the LLaMA3 LLM. The application allows users to interact with the chatbot through a user-friendly interface and provides accurate responses about the Avengers.

## Features
- **Domain**: The chatbot focuses on the Avengers, providing information and answering queries related to the Avengers universe.
- **LLM Integration**: Utilizes the LLaMA3 model integrated into Flowise for query processing.
- **Components Used**:
  - **Ollama Embeddings**: For embedding queries and context.
  - **ChatOllama**: The main chat interface for interaction.
  - **Conversational Retrieval QA Chain**: For retrieving relevant information.
  - **In-Memory Vector Store**: To store and retrieve embeddings.

## User Base
The application is designed for fans of the Avengers who want to learn more about the characters, storylines, and universe. It helps users by providing quick and accurate responses to their queries about the Avengers.

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm
- Flowise

### Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/manikanta-reddy-thikkavarapu-neu/chat-bot-with-llm-integration.git
    ```
2. Navigate to the project directory:
    ```sh
    cd chat-bot-with-llm-integration
    ```

### Running the Application
1. Start Flowise:
    ```sh
    npx flowise start
    ```
2. Open your browser and navigate to `http://localhost:3000` to access the chatbot interface.
3. Make sure your ollama app is running in `http://127.0.0.1:11434/`.
4. Now run **chatbot.html** using Live Server.

### Usage
- Type your query related to the Avengers into the input box.
- The chatbot will process your query and provide a relevant response based on the LLaMA3 model.

## Evaluation and Testing
The application has been tested with a variety of queries related to the Avengers to ensure its performance, accuracy, and usability. Below are some example queries:
- "Who are the original Avengers?"
- "Tell me about Iron Man's suit."
- "What is the storyline of Avengers: Endgame?"

## Video Demonstration
A detailed video walkthrough of the application demonstrating its features and usage can be found [here](https://www.youtube.com/your-video-link).

## Documentation
- **Flowise Documentation**: [Flowise Documentation](https://docs.flowiseai.com/)
- **LLama3 Documentation**: [LLama3 Documentation](https://ollama.com/library/llama3)
