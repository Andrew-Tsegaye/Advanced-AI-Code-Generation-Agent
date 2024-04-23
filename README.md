# Advanced AI Code Generation Agent

Welcome to the Code Generation Agent repository! This project aims to provide a versatile tool for generating code snippets based on user input and predefined templates. Whether you're a developer looking to streamline your workflow or a student seeking assistance with coding assignments, Code Generation Agent is here to help.

## Agent Functionalities
- Generate code based on user input and save it as a Python file.
- Provide explanations for the generated code.
- Retrieve relevant data from PDF files using Retrieval Augmented Generation (RAG) and provide appropriate responses based on that.

## Getting Started

To get started with Code Generation Agent, follow these steps:

1. **Clone the repository**: 
```bash
git clone https://github.com/Andrew-Tsegaye/Code-Gen-Agent.git
```

2. **Install Dependencies**:
   - To install the specified versions of the dependencies, ensure you have a Python version between `3.8` and `3.11` and run the following command:
```bash
pip install -r requirements.txt
```

## Next Steps:
- Activate the AI script from your terminal by running:
```bash
  ./ai/Scripts/activate
```
- Download the `mistral` LLM model from [Ollama Models](https://ollama.com/library). The `codellama` model will be automatically downloaded when you run the code.
- To run and Chat with [Mistral](https://ollama.com/library/mistral), execute the following command:
```bash
ollama run mistral
```

3. **Run the agent on your local machine**: 
```bash
python main.py
```

4. **Follow the prompts**: 
Once the AI is running on your local machine, follow the prompts to generate code snippets based on your requirements.

## Usage

Code Generation Agent is designed to be intuitive and easy to use. Simply launch the AI agent, choose your desired programming language as your custom data, select a template [I have provided my own template], and provide the necessary input when prompted. The agent will then generate the corresponding code snippet for you to use in your projects.

## Contributing

Contributions are welcome! If you have any ideas for new features, improvements, or bug fixes, feel free to submit a pull request. Please ensure that your code adheres to the existing style and conventions.

## Acknowledgements

Code Generation Agent wouldn't be possible without the contributions of the open-source community. I would like to thank all the developers who have helped make this project a reality.
- [LLAMA Index](https://www.llamaindex.ai/)
- [Ollama](https://github.com/ollama/ollama)
