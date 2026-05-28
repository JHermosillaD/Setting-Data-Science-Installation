# Setting Up the Data Science Environment
> A personal Jupyter Lab installation in Ubuntu

Install in command line:
```bash
sudo apt-get install dvipng texlive-latex-extra texlive-fonts-recommended cm-super texlive-fonts-extra
```

Create environment:
```bash
python3 -m venv ~/.venvs/datascience
```

Add to .bashrc:
```bash
alias dsenv="source ~/.venvs/datascience/bin/activate"
```

Install packages:
```bash
pip install -r datascience-requirements.txt
```
