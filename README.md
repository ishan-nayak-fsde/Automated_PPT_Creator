# Automated_PPT_Creator
Give a subject and content (optional) it will give u a PPT in return


High level Model
----------------

Frontend (HTML/React/Streamlit)
        ↓
Agent Controller (Python)
        ↓
Local LLM (Ollama)
        ↓
PPT Generator (python-pptx)
        ↓
Download File



Steps
-----
1. Install : curl -fsSL https://ollama.com/install.sh | sh or https://ollama.com/
2. Pull Model : ollama pull llama3
3. Run Test : ollama run llama3
4. Install Dependencies : pip install python-pptx streamlit requests


