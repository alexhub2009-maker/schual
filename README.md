# markdownexample

Ein fiktives Python-Projekt zur Demonstration eines **GitHub-Repositories** und der wichtigsten **Markdown-Befehle**.

---

## 📌 Projektbeschreibung

Dieses Repository dient als Beispielprojekt, um zu zeigen:

* wie ein GitHub-Repository erstellt wird
* wie eine `README.md` aufgebaut ist
* wie Markdown-Syntax funktioniert
* wie typische Git- und Python-Befehle verwendet werden

---

## ⚙️ Installation

```bash
# Repository klonen
git clone https://github.com/username/markdownexample.git

# In Projektordner wechseln
cd markdownexample

# Virtuelle Umgebung erstellen
python -m venv venv

# Virtuelle Umgebung aktivieren
# Windows
venv\Scripts\activate

# macOS / Linux
source venv/bin/activate

# Abhängigkeiten installieren
pip install -r requirements.txt
```

---

## ▶️ Projekt starten

```bash
python main.py
```

---

## 🧾 Markdown Cheat-Sheet

### Überschriften

```markdown
# H1
## H2
### H3
```

---

### Textformatierung

```markdown
**Fett**
*Kursiv*
~~Durchgestrichen~~
`Inline Code`
```

**Beispiele:**

* **Fett**
* *Kursiv*
* ~~Durchgestrichen~~
* `Inline Code`

---

### Listen

**Ungeordnete Liste**

```markdown
- Punkt 1
- Punkt 2
  - Unterpunkt
```

**Geordnete Liste**

```markdown
1. Erster Punkt
2. Zweiter Punkt
```

---

### Links & Bilder

```markdown
[GitHub](https://github.com)

![Bildbeschreibung](image.png)
```

---

### Codeblöcke

````markdown
```python
print("Hello World")
````

````

---

### Tabellen

```markdown
| Name | Rolle |
|------|-------|
| Max  | Dev   |
| Anna | PM    |
````

| Name | Rolle |
| ---- | ----- |
| Max  | Dev   |
| Anna | PM    |

---

### Zitate

```markdown
> Das ist ein Zitat.
```

> Das ist ein Zitat.

---

### Checklisten

```markdown
- [x] Aufgabe erledigt
- [ ] Aufgabe offen
```

* [x] Aufgabe erledigt
* [ ] Aufgabe offen

---

## 🌱 Git Cheat-Sheet

```bash
# Status anzeigen
git status

# Änderungen hinzufügen
git add .

# Commit erstellen
git commit -m "Initial commit"

# Branch erstellen
git branch feature

# Branch wechseln
git checkout feature

# Push zu GitHub
git push origin main
```

---

## 📁 Projektstruktur

```
markdownexample/
│
├── main.py
├── requirements.txt
├── README.md
└── venv/
```

---

## 👨‍💻 Autor

Beispielprojekt für Lernzwecke.
