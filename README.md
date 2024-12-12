# langflow-whl
langflow-whl

##install from .whl

Download files from: 
https://pypi.org/project/langflow-base/#files
https://pypi.org/project/langflow/

Create a virtual environment :
```bash
python -m venv .venv
.\.venv\Scripts\activate
```

Install langflow to virtual environment:
```bash
pip install langflow_base-0.1.1-py3-none-any.whl
pip install langflow-1.1.1-py3-none-any.whl  --use-deprecated=legacy-resolver
```

Run langflow from virtual environment:
```bash
langflow run
```