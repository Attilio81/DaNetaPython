# DaNetaPython 🐍

Corso pratico Python per sviluppatori **C# / VB.NET** — con sito interattivo incluso.

---

## A cosa serve

Imparare Python **partendo da zero ma non da principiante**.  
Non perdi tempo su variabili e loop — sai già programmare.  
Il focus è su **cosa è diverso** da .NET e su come leggere, capire e validare codice Python generato dall'AI.

---

## Struttura

| Modulo | Argomento |
|--------|-----------|
| 00 | Setup ambiente — Python 3.11+, VS Code, estensioni, venv |
| 01 | Sintassi Python per chi viene da C# / VB.NET |
| | → Tipi e variabili, classi, dataclasses, pattern AI ricorrenti |
| | → **Tranelli frequenti**: `pathlib`, eccezioni, `__init__.py`, `requirements.txt` / `pyproject.toml`, `python-dotenv` |
| 02 | Leggere codice AI — duck typing, decoratori, generators, async/await |
| 03 | Analisi statica — AST, radon, bandit |
| 04 | Testing — pytest, mock, sandboxing |
| 05 | Automazione — pipeline completa di review automatica |
| EX | Esercizi su codice reale generato da ChatGPT / Claude / Copilot |
| 🤖 | Bonus — costruire un agente AI con AGNO framework |

---

## Sito interattivo

Apri `index.html` nel browser — niente server, niente install.

- Naviga i moduli dalla sidebar
- Spunta i singoli step di ogni modulo (progresso salvato in localStorage)
- Copia i code snippet con un click
- Scorciatoie tastiera: `0` home · `s` setup · `1–5` moduli · `e` esercizi · `b` bonus

---

## Tool necessari

```bash
# Moduli 00-05
pip install pytest pylint black radon bandit

# Modulo 01 — tranelli
pip install python-dotenv pydantic-settings

# Bonus AGNO
pip install agno duckduckgo-search

# API key (una delle due)
ANTHROPIC_API_KEY=sk-ant-...
OPENAI_API_KEY=sk-...
```

---

## Prerequisito unico

Saper programmare. Ce l'hai già.
