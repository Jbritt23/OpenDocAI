# OpenDocAI

## Description
OpenDocAI is a sophisticated tool designed to process various document types, enabling users to extract text and engage with the content through AI-driven interactions. The application leverages OpenAI's GPT models to answer questions related to the document content, maintaining a conversation history that is prudently managed to optimize API token usage.

## Key Features
- **Document Processing**: Supports multiple file formats including PDF, DOCX, TXT, XLSX, and CSV.
- **Intelligent Question Answering**: Utilizes OpenAI's GPT-4 to provide answers based on the document's content.
- **Conversation History Management**: Maintains a history of interactions to provide context to the AI, improving the relevance of responses.
- **Efficient Token Management**: Implements conversation pruning strategies to reduce the token count required per API call, optimizing costs and improving efficiency.

## Installation

### Prerequisites
Ensure Python 3.8 or newer is installed along with the following packages:
- sqlite3
- PyPDF2
- python-docx
- pandas
- openai

Install the required packages using pip:
```bash
pip install PyPDF2 python-docx pandas openai
