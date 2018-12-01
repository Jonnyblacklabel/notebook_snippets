# notebook_snippets
Eine Sammlung meiner Jupyter Notebook Snippets. Python-Packages die ich teste, oder Workflows die ich verwende. 
Das Repository ist über 'pipenv' aufgebaut. Es kann geklont und per `pipenv install` in ein virtuelles Python Environment installieren werden.

## Klonen des Repos
Das Repository kann einfach heruntergeladen werden. Natürlich ebenfalls per Git-Befehl oder in der GUI eurer Wahl.
```bash
# Repository Klonen
git clone https://github.com/Jonnyblacklabel/notebook_snippets.git
```

## Installation des Klons
Der Befehl erstellt ein neues virtuelles Environment und installiert dort alle in der Pipfile angegebenen Packages.
```python
pipenv install pipenv
```

## Jupyterlab ausführen
Jupyterlab wird direkt im Environment gestartet. Dafür muss im Ordner ein Terminal (oder Powershell) ausgeführt werden. Darin folgenden Befehl ausführen:
```python
# Jupyterlab starten
pipenv run jupyter lab
```
**Achtung**: Wenn Jupyter bereits genutzt wird und der Pfad für die Notebooks geändert wurde, kann es sein das dieser Pfad für die Notebooks verwendet wird. 


## Weiteres
### Pipenv installieren
Falls noch nicht vorhanden, muss 'pipenv' installiert werden. https://pipenv.readthedocs.io/en/latest/
```python
# Installation von pipenv 
# (https://pipenv.readthedocs.io/en/latest/install/#installing-pipenv)
pip install --user pipenv
```

### Andere Python Version
Aktuell genutzte Python Version: Python 3.6 (wie in der Pipfile definiert). 
Ist eine andere Version installiert, muss diese angegeben werden.
```python
# Beispiel für Python 3.7
pipenv install --python "C:\Users\Johannes\AppData\Local\Programs\Python\Python37-32\python.exe"
```