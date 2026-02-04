# 🎭 Emotion Analyzer – Streamlit App

Diese App macht hörbare Emotionen sichtbar: Sie bietet eine intuitive Analyse- und Visualisierungsumgebung für Sprachaufnahmen des RAVDESS-Datensatzes. Durch Audio-Exploration, akustische Feature-Analyse und ein Machine-Learning-Modul zur automatischen Emotionserkennung werden Emotionen in Sprache greifbar – für Forschung, Entwicklung und kreative Anwendungen.

---

## 🚀 Features

- **📊 Dashboard** – Überblick über Struktur und Verteilung des RAVDESS-Datensatzes
- **🎧 Audio Explorer** – Sprachaufnahmen abspielen, filtern und vergleichen
- **🔎 Feature Analysis** – Analyse akustischer Eigenschaften wie MFCCs, Tonhöhe, Energie
- **🎨 Visualizer** – Emotionale Merkmale grafisch erfahrbar machen
- **❤️ Emotion Analyzer (Demo)** – Automatische Emotionserkennung via Machine Learning

⚠️ **Hinweis:** Eine detaillierte Projektbeschreibung findet sich auch in der APP auf der Unterseite "Über das Projekt".

---

## 📦 Installation

### ⚙️ Abhängigkeiten installieren

pip install -r requirements.txt

⚠️ **Hinweis:** Nutze am besten eine virtuelle Umgebung (z. B. `venv` oder `conda`).

### ▶️ Anwendung starten

streamlit run main.py

📁 Stelle sicher, dass die Audiodaten (z. B. aus dem RAVDESS-Datensatz) im Ordner `data/ravdess/` liegen.

### 🗂️ Projektstruktur (Kurzfassung)

streamlit-app/
├── main.py                   	# Einstiegspunkt
├── pages/                   		# Unterseiten (Dashboard, Explorer etc.)
├── utils/                   		# Feature- und Visualisierungsfunktionen
├── data/                    		# RAVDESS-Daten (nicht im Repo)
├── requirements.txt
└── .streamlit/config.toml   	# Dark Theme + Farbdefinitionen

### ℹ️ Hinweise

* Entwickelt mit Python & Streamlit
* Analyse erfolgt u. a. über MFCCs, Zero-Crossing Rate, Spectral Features
* Emotionserkennung auf Basis trainierter Modelle (Demo-Zweck)

---

## 🧠 Vision

Die App verbindet Datenanalyse mit Empathie – als Beitrag für Forschung, kreative Arbeit und Mensch-Maschine-Kommunikation.

---

## 🤝 Mitwirken

Pull Requests und Issues sind willkommen.
