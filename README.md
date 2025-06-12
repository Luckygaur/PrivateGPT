# PrivateGPT

PrivateGPT is a production-ready AI project that enables you to query your documents using the power of Large Language Models (LLMs), even without an Internet connection. Everything runs locally—ensuring complete data privacy.

This project offers an API with all the necessary building blocks to develop private, context-aware AI applications. It aligns with the [OpenAI API standard](https://openai.com/blog/openai-api) and supports both standard and streaming responses.

A simple [Gradio UI](https://www.gradio.app/) is also included for quick testing, along with utilities like bulk model download, document ingestion, and directory monitoring.

## 🎯 Why I Built This

Generative AI holds massive potential, but privacy concerns—especially in domains like healthcare, legal, or enterprise—block real-world adoption.

This inspired me to take the core ideas from earlier community prototypes and redesign them into something more modular, extensible, and ready for production environments.

If you're curious about the original educational version, you can still find it in the [primordial branch](https://github.com/zylon-ai/private-gpt/tree/primordial). But for best results, I recommend a clean install using this version.

## 🚀 Vision for PrivateGPT

The goal is to turn PrivateGPT into a flexible framework for working with generative models: from completions to document ingestion and retrieval-augmented generation (RAG) systems.

This version is designed to support developers building on top of AI primitives with clean interfaces and modular components.

Keep an eye on [releases](https://github.com/zylon-ai/private-gpt/releases) for updates and new features.

## 📚 Documentation

All setup instructions, usage guides, and configuration details are available here: [https://docs.privategpt.dev](https://docs.privategpt.dev)

This includes:
- Installation and environment setup
- Ingesting local documents
- Server deployment and API endpoints
- UI capabilities

## 🛠️ Contributing

Contributions are always welcome. Before opening a PR, please:
- Run `make check` to validate formatting and type hints
- Test using `make test`

Not sure where to start? Check out the public [Project Board](https://github.com/users/imartinez/projects/3) for open ideas.

## 🤝 Thanks to Open Tools That Made This Easier

- [Qdrant](https://qdrant.tech/) – Vector DB backend
- [Fern](https://buildwithfern.com/) – Docs & SDKs
- [LlamaIndex](https://www.llamaindex.ai/) – RAG abstractions
- [LangChain](https://github.com/hwchase17/langchain)
- [GPT4All](https://github.com/nomic-ai/gpt4all)
- [LlamaCpp](https://github.com/ggerganov/llama.cpp)
- [Chroma](https://www.trychroma.com/)
- [SentenceTransformers](https://www.sbert.net/)
