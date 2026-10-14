# MachineLearning_Q4
Actividad 1

Creamos el entorno virtual
python -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade huggingface_hub
python -m pip install --upgrade pip
hf auth whoami
pip install -r requirements.txt
pip install pyarrow openpyxl  # opcional: parquet y xlsx
python scripts/build_notebooks.py   # opcional: regenerar notebooks
jupyter lab

