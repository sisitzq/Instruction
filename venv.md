# virtualenvwrapper, 
```
by default stores environments in a central directory (commonly ~/.virtualenvs)
```

JupyterLab
```
register each virtual environment as a Jupyter kernel. Once you’ve created and activated your environment, install ipykernel:

  pip install ipykernel

Then register it with:

  python -m ipykernel install --user --name your_env_name --display-name "Python (your_env_name)"
```

 VS Code
 ```
select the interpreter for your project by opening the Command Palette (Ctrl+Shift+P) and running “Python: Select Interpreter.”
VS Code will scan for interpreters, including those in your centralized directory (e.g., ~/.virtualenvs).
```

python3 -m venv .venv
```
source .venv/bin/activate   # in ubunutu
. .venv/Scripts/Activate  # in PS shell
```

python is python3: 
```
sudo nano ~/.bashrc
add  alias python=python3

source ~/.bashrc
```

install pytorch
```
pip install --pre torch torchvision torchaudio --index-url https://download.pytorch.org/whl/nightly/cu128
```


