# Aritra's Colab

A practical GenAI learning repository focused on two tracks:
- Core Gemini usage patterns and configuration
- A beginner-friendly, traditional Retrieval-Augmented Generation (RAG) workflow with LangChain and Chroma

This repository is designed as an educational codelab environment where each notebook can be run independently in Google Colab.

## Author

Aritra Banerjee
- GitHub: https://github.com/Aritra-221B

## Repository Contents

1. UnderstandingGenai.ipynb
- Introduces Gemini model setup and API key configuration in Colab
- Explains generation parameters such as temperature, top-p, top-k, and max output tokens
- Demonstrates practical API usage patterns:
	- Token counting
	- Embeddings
	- Chat sessions
	- Streaming responses
	- System instructions
	- Safety settings

2. SimpleTraditionalRAG.ipynb
- Walks through a complete traditional RAG pipeline for beginners
- Covers environment setup, dependency management, and module imports
- Builds a mini end-to-end flow:
	- Data preparation
	- Document chunking
	- Embedding generation
	- Chroma vector indexing
	- Prompt design
	- LCEL chain construction
	- Query execution with basic error handling

## Tech Stack

- Python
- Google Gemini API (google-generativeai, langchain-google-genai)
- LangChain and LCEL
- Chroma vector database
- PyPDF, python-dotenv, and supporting utilities
- Google Colab runtime

## Getting Started

1. Clone the repository:

	 git clone https://github.com/Aritra-221B/Aritras-Colab.git
	 cd Aritras-Colab

2. Open either notebook in Google Colab.

3. Configure your Google API key when prompted:
- In Colab secrets as GOOGLE_API_KEY, or
- Through secure runtime input cells (where applicable)

4. Run cells in sequence to reproduce the codelab outputs.

## Learning Outcomes

By working through these notebooks, you will be able to:
- Configure and safely use Gemini models for generation tasks
- Understand key generation controls and their trade-offs
- Build and run a classical RAG pipeline from raw text to answer generation
- Apply prompt engineering and safety controls in practical workflows

## Suggested Improvements

- Add requirements.txt with pinned versions for reproducibility
- Add sample outputs/screenshots for each notebook section

## Rights and Usage

Copyright (c) 2026 Aritra Banerjee.
All Rights Reserved.

No part of this repository, including notebook content, code, text, or derived materials, may be copied, redistributed, published, modified, or used for commercial or non-commercial purposes without prior written permission from the author.

See the full proprietary terms in the LICENSE file.