

conda activate test2
conda deactivate
uv python list
uv python install cpython-3.11.13-windows-x86_64-none
uv python list
uv venv env --python cpython-3.10.18-windows-x86_64-none
D:\AI_Trip_Planner\env\Scripts\activate.bat
conda config --set auto_activate_base false
uv pip list
uv pip install langchain
uv pip list