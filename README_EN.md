# LLM Deployment and Applications — Summer Training Materials

**[中文](./README.md) | English**

Course materials for the 2026 summer training program on large language models, including lecture slides, lab assignments, study notes, and a capstone report.

## Repository layout

~~~text
├── Textbook and slides/       # Five PDF slide decks
│   ├── AI and LLM fundamentals
│   ├── Linux operating-system fundamentals
│   ├── Local LLM deployment
│   ├── Calling LLM APIs
│   └── Container fundamentals
├── Lab assignments/           # Two assignments
├── Lab reports/               # One integrated LLM deployment report
├── Study notes/               # Notes on AI/LLMs and Linux
└── User guides/               # Detailed LM Studio guide
~~~

## Labs

1. **Quantized deployment with llama.cpp** — build from source, convert to GGUF, compare Q8_0/Q4_K_M/Q2_K, and run the server.
2. **Prompt engineering in Cherry Studio** — use LM Studio GPU acceleration, role prompts, few-shot examples, chain-of-thought, and output constraints.
3. **Streaming conversations with the Python API** — OpenAI-compatible APIs, multi-turn memory, and support for multiple backends.
4. **MCP and Skills** — the six MCP primitives and the @cherry/fetch and @cherry/memory integrations.
5. **Docker deployment** — Docker CE on Rocky Linux, an LLM inference container, and GPU access.

## Environment

- Windows 11 and a Rocky Linux virtual machine
- Python 3.x, openai, and python-docx
- llama.cpp, LM Studio, Cherry Studio, and Docker CE
- DeepSeek API
