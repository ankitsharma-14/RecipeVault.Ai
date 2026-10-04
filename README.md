# 🍲 RecipeVault AI

**RecipeVault AI** is a 100% offline, privacy-first application built to preserve family history. It transcribes local audio recordings containing obscure regional dialects and family stories, extracts structured cooking instructions, and generates a formatted Markdown recipe book.

Built for the **Hacktoberfest Weekend Challenge: Build for a Friend**.

## Tech Stack
* **Frontend:** Streamlit
* **Audio Transcription:** Whisper (OpenAI open weights)
* **LLM:** Llama 3 (via Ollama)
* **Orchestration:** LangChain

## Why Local AI?
This project relies entirely on local, open-source AI to guarantee complete privacy for personal family stories. It works 100% offline, incurs zero API costs, and avoids the risk of cloud speech models misinterpreting highly specific regional dialects.

## Quick Start

### Prerequisites
1. Install [Ollama](https://ollama.ai/) and pull the Llama 3 model:
   ```bash
   ollama run llama3
