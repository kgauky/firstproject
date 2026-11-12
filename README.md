# firstproject

Base de projet Python configurée avec pytest.

## Préparer l'environnement

```bash
python -m venv .venv
source .venv/bin/activate  # Windows : .venv\Scripts\activate
python -m pip install -e ".[dev]"
```

## Lancer les tests

```bash
pytest
```

Le code du package se trouve dans `src/firstproject/` et les tests dans `tests/`.
