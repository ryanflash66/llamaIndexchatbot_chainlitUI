# llamaIndexchatbot_chainlitUI

A powerful document-based chatbot built with LlamaIndex and Chainlit that provides a conversational interface to your documents.

## Description

This project implements a chatbot that can ingest various document types (PDF, DOCX, PPT, images, etc.), index their content using LlamaIndex, and provide a user-friendly chat interface with Chainlit. Users can ask questions about their documents and receive relevant answers based on the document content.

## Features

- 📁 Multi-format document support (PDF, DOCX, PPTX, images, and more)
- 💬 Interactive chat interface powered by Chainlit
- 🔍 Semantic search and retrieval using LlamaIndex
- 🧠 Context-aware responses
- 📊 Document processing visualization
- 🚀 Easy to deploy and use

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/ryanflash66/llamaIndexchatbot_chainlitUI.git
   cd llamaIndexchatbot_chainlitUI
   ```

2. Install the required packages:

   ```
   pip install -r requirements.txt
   ```

3. Set up your environment variables (create a `.env` file):
   ```
   OPENAI_API_KEY=your_openai_api_key_here
   ```

## Usage

1. Place your documents in the `data/` directory.

2. Run the Chainlit app:

   ```
   chainlit run app.py
   ```

3. Open your browser and navigate to `http://localhost:8000` to interact with your documents through the chat interface.

## Project Structure

```
llamaIndexchatbot_chainlitUI/
├── app.py              # Main application file
├── utils/              # Utility functions
├── data/               # Directory for document storage
├── requirements.txt    # Project dependencies
└── README.md           # This file
```

## Dependencies

- llama-index - For document indexing and querying
- llama-hub - For data connectors
- unstructured - For parsing various document formats
- langchain - For language model integration
- chainlit - For the chat UI interface

## Configuration

You can customize the behavior of the chatbot by modifying the configuration parameters in the app. Key configurations include:

- Model selection (default: OpenAI)
- Chunk size for document processing
- Temperature and other generation parameters
- UI customization options

## Example Queries

- "Summarize the key points in the annual report."
- "What were the main conclusions of the research paper?"
- "Extract the financial data from Q3 earnings."
- "Compare the information between these two documents."

## License

MIT

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
