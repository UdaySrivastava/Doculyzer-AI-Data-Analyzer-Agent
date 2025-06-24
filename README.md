# Doculyzer-AI-Data-Analyzer-Agent
Context-aware AI agent that analyzes documents (CSV, Excel, PDF, Word, images, TXT) and generates insights and visualizations via natural language queries.

- 🧠 Ask questions in natural language — get contextual insights from your documents
- 📁 Supports `.csv`, `.xlsx`, `.pdf`, `.docx`, `.txt`, `.png`, `.jpg`
- 🔍 OCR support for scanned documents and images
- 📊 Auto-generates visualizations with Python code
- 💬 Conversational interface through the terminal
- 🔐 Local execution of LLM-generated code in a sandboxed environment

## 💻 Instruction for Local Deployment

### 🔧 1. Clone the Repository
```bash
git clone https://github.com/your-username/Doculyzer-AI-Data-Analyzer-Agent.git
cd Doculyzer-AI-Data-Analyzer-Agent
```

### 🧪 2. Create Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate    # On Windows: venv\Scripts\activate
```

### 📦 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 🔑 4. Add Your TogetherAI API Key
Open the Jupyter Notebook file and set your API key:
```python
TOGETHER_API_KEY = "your-api-key-here"
```
You can obtain a free API key at: https://www.together.ai

### 📂 5. Upload Your File
In the notebook, set the file path:
```python
uploaded_file = "/path/to/your/file.pdf"  #.csv, .docx, .pdf etc.
```
## 💬 6. Start Asking Questions
Once the file is processed, type questions in the notebook or terminal:
```
Sample Questions:
What is the average age of customers?
Create a graph visualisation of country/ continent wise internet usage
Generate insights from this document.
```
