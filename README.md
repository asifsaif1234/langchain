# LLM App

## How to run

1. Create the conda environment:
   ```bash
   conda create -n llmapp python=3.11 -y
   ```

2. Activate it:
   ```bash
   conda activate llmapp
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Register the env as a Jupyter kernel:
   ```bash
   python -m ipykernel install --user --name llmapp --display-name "Python (llmapp)"
   ```

5. Create a `.env` file in the project root:
   ```txt
   OPENAI_API_KEY=sk-proj-...
   GROQ_API_KEY=gsk_...
   ```

6. In VS Code / JupyterLab, select the kernel **Python (llmapp)**.
