# Fluffy Exe

Tool that creates quick prototypes for a user's request using ```huggingface/transformers```.

It first generates a plan with steps to create a prototype for the user's query, then executes that plan on a Modal VM, providing real-time output to user inputs.

## Features
- Creates a plan for prototype development
- Allows users to change the plan to tweek the prototype
- Execution of plans on Modal
- Real-time output display for user inputs

## Dependencies

### Fluffy
It is an answer-engine for public repos & open-source libraries. Fluffy excels in:
- Debugging specific and challenging bugs
- Exploring the latest in research-driven repos
- Bridging gaps in documentation
- [Fluffy](www.fluffystack.com)

### Exa
A search engine for AI that uses embeddings to find the best content on the web.
[Link](https://exa.ai/)

### Modal
Modal provides a seamless way to run code in the cloud without worrying about infrastructure.
[Link](https://modal.com/)

### Anthropic's Claude Sonnet
You are missing out if you haven't integrated it yet. [Try it out!](console.anthropic.com/)

## Project Structure

```
fluffyexeclaude/
|-- README.md
|-- fluffyexeclaude-backend/
|   `-- (Flask files)
`-- fluffyexeclaude-frontend/
    `-- (Next.js files)
```

## Getting Started

### Frontend Setup

To start the frontend:

```bash
cd fluffyexeclaude/fluffyexeclaude-frontend
npm run dev
```

### Backend Setup

To start the backend:

```bash
cd fluffyexeclaude/fluffyexeclaude-backend
source fluffyexeclaude-venv/bin/activate
python app.py
```

### Author - Avinaash Anand K
- [Twitter](https://x.com/avinaash_anand)
- [LinkedIn](https://www.linkedin.com/in/avinaashanand/)