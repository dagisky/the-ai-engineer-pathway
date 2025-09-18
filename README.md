# AI Engineer Pathway – IPython Notebook Examples

This repository provides a structured set of **IPython Notebooks** designed to guide through the **AI Engineer Pathway**.  

---

## 📦 Installation

### 1. Clone the repository
```bash
git clone https://github.com/dagisky/the-ai-engineer-pathway.git
cd ai-engineer-pathway
```

### 2. Create a virtual environment
```bash
python3 -m venv .venv
source .venv/bin/activate   # For Linux/Mac
.venv\Scripts\activate      # For Windows
```

### 3. Add enviromental variables
Create `.env` file in the root directory and add the following variables
```bash
AZURE_OPENAI_ENDPOINT = <Your OpenAI Endpoint>
AZURE_OPENAI_API_KEY = <Your Azure OpenAI Key>
OPEN_API_KEY = <Your OpenAI Key>   # For Openai account
SERPAPI_API_KEY = <Your Serpapi Key>
```

### 4. Install dependencies
```bash
pip install -r requirements.txt
```

### 5. Launch JupyterLab
```bash
jupyter lab
```

Open the notebooks inside the `notebooks/` folder to begin exploring.

---

## 📋 Requirements

The notebooks use modern AI and data science libraries:  

- **LangChain**: Workflow orchestration with LLMs  
- **MCP**: Multi-Channel Protocol integration for agentic AI  
- **Core Jupyter stack**: JupyterLab, Notebook, IPyKernel  
- **Vector Store**: ChromaDB  
- **Data & Visualization**: NumPy, Pandas, Seaborn, Matplotlib, Scikit-learn  
- **Interactive Widgets**: ipywidgets, ipympl  

Full list is in [`requirements.txt`](./requirements.txt).

 
##  Contribution

Pull requests are welcome!  
If you’d like to add new examples (e.g., Hugging Face integration, OpenAI fine-tuning, advanced governance patterns), please fork the repo and submit a PR.


