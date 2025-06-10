# 🧠 fhcw-aie

---

## 📦 1. Python 3.12 über Homebrew installieren

```bash
brew install python@3.12
```

---

## 🛠️ 2. Projekt- und venv-Struktur einrichten

```bash
mkdir mein-projekt
cd mein-projekt
python3.12 -m venv venv
source venv/bin/activate
```

---

## 📚 3. Pakete installieren

```bash
pip install --upgrade pip
pip install matplotlib
pip install numpy
pip install tensorflow
pip install tensorflow-datasets
pip install ipykernel
```

---

## 🧠 4. Jupyter-Kernel registrieren (für VS Code & Jupyter)

```bash
python -m ipykernel install --user --name=venv --display-name "Python (venv)"
```

---

## 🏁 5. Arbeiten mit der Umgebung

- **Aktivieren**:
  ```bash
  source venv/bin/activate
  ```

- **Deaktivieren**:
  ```bash
  deactivate
  ```