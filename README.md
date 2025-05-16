# 🤖 Agentic Workflows: Agents That Reason

![](./Assets/1.1%20AgWorkHeaderImage.png)

Welcome to **Agentic Workflows: A Builder’s Guide to LLM Agency**, a hands-on project demonstrating how to build progressively intelligent agents using OpenAI, CrewAI, and modern tool integrations.



## 🧠 What's Inside?

This repo explores **4 Levels of Agent Intelligence**:
1. ✅ Simple Agents
2. 🔧 Tool-Using Agents
3. 🧩 Multi-Step Agents
4. 🧠 Multi-Agent Workflows

Each Jupyter notebook demonstrates the architecture, behavior, and evolution of agent capabilities.

---

## 🛠️ Setup Instructions

### 1. 🔄 Clone the Repository
```bash
git clone https://github.com/your-org/agentic-workflows.git
cd agentic-workflows
```

### 2. 🐍 Create and Activate a Virtual Environment

Make sure you’re using Python 3.11+

#### Create virtual environment
```
python3.11 -m venv .agent_env
```

#### Activate it
#### On macOS/Linux:
```
source .agent_env/bin/activate
```
#### On Windows:
```
.agent_env\Scripts\activate
```

### 3. 📦 Install Requirements

```

pip install -r requirements.txt
```

⸻

### 🔐 Environment Variables

Create a .env file in the root directory with the following contents:

```
OPENAI_API_KEY=your-openai-key-here
ASTRA_TOKEN=your-astra-db-token
ASTRA_ENDPOINT=your-astra-db-endpoint
SERPER_API_KEY=your-serper-api-key
```

These are required for:
	•	OpenAI LLMs
	•	Astra DB (Vector retrieval)
	•	Serper.dev (Web search)

⸻

### 🧪 Running the Notebooks

Launch JupyterLab or VS Code with Python kernel support:

jupyter lab
or
code .

Then open any of the following notebooks:

1. Simple Agents.ipynb
2. Tool Calling.ipynb
3. MultiStep Agents.ipynb
4. Multi Agent.ipynb

Make sure your .env is loaded before execution (use python-dotenv or %load_ext dotenv in the notebook if needed).

---

### 📂 Folder Structure
```
.
├── Assets/                   # Visuals used in notebooks
├── 1. Simple Agents.ipynb
├── 2. Tool Calling.ipynb
├── 3. MultiStep Agents.ipynb
├── 4. Multi Agent.ipynb
├── .env                     # Environment secrets (excluded from Git)
├── requirements.txt
├── LICENSE
└── README.md
```

---

### ✅ Python Version

This project is tested with Python 3.11.2. Use pyenv or similar tools if needed to install the right version.

--- 

### 🧩 Dependencies

Major libraries used:
	•	crewai
	•	crewai-tools
	•	openai
	•	langchain
	•	python-dotenv
	•	serper-dev for search integration
	•	astra-db for vector store querying
	•	IPython for rich notebooks

--- 

### 🙋‍♂️ Questions?

Feel free to raise issues or ping abhinav.kimothi.ds@gmail.com if you’re stuck during setup or want to extend the framework!

---

### 🧠 License

MIT License — Use it, fork it, remix it!

---