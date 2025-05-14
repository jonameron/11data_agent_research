# 🤖 Drei Wege, einen KI-Agenten zur Social-Media-Automatisierung zu erstellen (Schülerpraktikum)

Dieses Projekt zeigt drei unterschiedliche Ansätze, um Social-Media-Inhalte mit Hilfe von Künstlicher Intelligenz zu automatisieren – für Entwickler, Low-Code-Nutzer und No-Code-Einsteiger.  
Die jeweiligen **Codebeispiele befinden sich im Ordner [`/code`](./code)**.

---

## 🧠 1. Vollständiger Code (Programmierung)

**Ideal für Entwickler:innen**, die volle Kontrolle und Anpassbarkeit benötigen.

- **Sprachen:** Python, Node.js  
- **Bibliotheken/Tools:**  
  `openai`, `langchain`, `serpapi`, `beautifulsoup4`, `schedule`, `tweepy`, `linkedin-api`

### 📈 Ablauf:

1. **Themenvorschläge generieren**  
   → `openai.ChatCompletion`
2. **Aktuelle Informationen suchen**  
   → `serpapi` oder `BeautifulSoup4`
3. **Post texten im gewünschten Stil**  
   → GPT Prompt Engineering
4. **Automatisch posten**  
   → APIs von Twitter, LinkedIn, etc.

👉 Siehe Beispiele im Ordner [`/code/full-code`](./code/full-code)

---

## 🔧 2. Low-Code mit Automatisierungsplattformen

**Geeignet für technisch affine Nutzer:innen**, die visuelle Tools bevorzugen.

- **Plattformen:** Zapier, Make.com, Pipedream, n8n

### 🧩 Bausteine:

- **OpenAI-Modul:** Generiert Themen
- **Websuche-Modul:** Bing oder integrierte APIs
- **GPT-Textmodul:** Formatiert Inhalte im Zielstil
- **Publikationsmodul:** Buffer, Telegram, Instagram etc.

> **Ablauf:** Bausteine logisch verknüpfen, Prompts anpassen

👉 Siehe Beispiele im Ordner [`/code/low-code`](./code/low-code)

---

## 🟢 3. No-Code Tools für Einsteiger:innen

**Für alle**, die ohne Programmierkenntnisse starten möchten.

- **Tools & Plattformen:**  
  ChatGPT (eigene GPTs), Zapier-Vorlagen, Canva AI, Copy.ai, Notion AI

### 📌 Beispiel:

1. Thema manuell eingeben  
2. KI generiert Text automatisch  
3. Per Drag-and-Drop oder Integration posten

👉 Siehe Beispiele im Ordner [`/code/no-code`](./code/no-code)

---

## 📂 Verzeichnisstruktur

```plaintext
/code
├── full-code      → Python- oder Node.js-Beispiele
├── low-code       → Make.com, Zapier, n8n-Flows
└── no-code        → Screenshots, Konfigurationen & Beispiele
