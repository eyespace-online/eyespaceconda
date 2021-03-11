## Conda Commands

Install Miniconda.
This command is OS specific. 
We install the MacOS version using Homebrew:

```
brew install --cask miniconda
```

Install dependencies:
```
conda env create -f environment.yaml
```

Activate environment:
```
conda activate eyespace-topo
```

Run tests:
```
py.test
```

Run viewer application:
```
python app.py
```

Deactivate when doen:
```
conda deactivate
```

