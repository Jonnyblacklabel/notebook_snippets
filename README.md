# notebook_snippets
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Jonnyblacklabel/notebook_snippets/master)
Eine Sammlung einiger Jupyter Notebook Snippets.
Notebooks einfach herunterladen und im eigenen Environment probieren, oder Repository klonen und das virtuelle Environment aus der `.yml` Datei erstellen.

## Klonen des Repos
Das Repository kann einfach heruntergeladen werden. Natürlich ebenfalls per Git-Befehl oder in der GUI eurer Wahl.
```bash
# Repository Klonen
git clone https://github.com/Jonnyblacklabel/notebook_snippets.git
```

## Environment erstellen
Der Befehl erstellt ein neues virtuelles Environment und installiert dort alle in der Pipfile angegebenen Packages.
```python
conda env create -f notebook_snippets_env.yml
```