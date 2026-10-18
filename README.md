# 🧠 SimpliMap Edu

Un'applicazione web moderna e accessibile per creare e gestire mappe mentali in modo intuitivo, progettata per essere inclusiva per tutti gli utenti, inclusi quelli con DSA, dislessia, ADHD e altre esigenze specifiche.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## ✨ Caratteristiche Principali

- **🎨 Interfaccia Intuitiva**: Design pulito e moderno con nodi trascinabili e toolbar organizzata per gruppi funzionali
- **♿ Accessibilità Completa**: Supporto per alto contrasto, font speciali (OpenDyslexic, Lexend), griglia di allineamento, tema low-sensory e modalità focus
- **📤 Multi-Export**: Esporta in PNG, SVG, PDF o Markdown
- **⌨️ Scorciatoie da Tastiera**: Lavora velocemente senza usare il mouse
- **🏷️ Marcatori**: Aggiungi 14 icone diverse per priorità, stato e note (⭐, ❗, ✅, ❌, ⏳, 🔄, 1️⃣, 2️⃣, 3️⃣, 📌, 💡, ❓, 📅, 🔖)
- **📝 Note**: Aggiungi note dettagliate a ogni nodo
- **🔍 Ricerca**: Trova rapidamente i nodi nella tua mappa con evidenziazione
- **💾 Salvataggio**: Salva e carica le tue mappe come file JSON (.simplimap o .json)
- **📎 Raggruppa**: Raggruppa nodi selezionati con una graffa
- **🔊 Leggi ad Alta Voce**: Funzione di sintesi vocale per i nodi selezionati
- **✏️ Formattazione Testo**: Grassetto, corsivo, sottolineato direttamente nei nodi

## 🚀 Utilizzo

### Creare una Mappa

1. Clicca su **"📄 Nuova"** per iniziare una nuova mappa
2. Il nodo radice è già selezionato - inizia a scrivere il tuo argomento principale
3. Usa **Tab** per aggiungere nodi figli
4. Usa **Invio** per aggiungere nodi fratelli

### Personalizzare i Nodi

- **Colori**: Seleziona uno dei 5 colori disponibili dalla toolbar (Verde, Blu, Arancione, Rosa, Viola)
- **Marcatori**: Clicca su **"🏷️ Marcatori"** per aggiungere icone di priorità, stato o note
- **Note**: Aggiungi note dettagliate a qualsiasi nodo
- **Formattazione**: Applica grassetto (Ctrl+B), corsivo (Ctrl+I) o sottolineato (Ctrl+U)
- **Font**: Scegli tra Lexend (consigliato), OpenDyslexic (per dislessia) o Verdana

### Gestire i Nodi

- **Aggiungi Figlio**: Clicca su **"➕ Figlio"** o premi **Tab**
- **Aggiungi Fratello**: Clicca su **"➕ Fratello"** o premi **Invio**
- **Elimina**: Clicca su **"🗑️ Elimina"** o premi **Canc/Backspace**
- **Raggruppa**: Seleziona più nodi e clicca su **"📎 Raggruppa"** (Ctrl+G)
- **Trascina**: Sposta i nodi per riorganizzare la mappa

### Navigazione

- **Trascina** i nodi per riorganizzarli
- Usa i controlli **Zoom** (+, −, ⟲) in basso a destra
- Clicca su **"⌂"** per centrare la mappa
- Usa **Spazio + trascina** per la panoramica
- Usa le **Frecce** per spostarti tra i nodi

## ⌨️ Scorciatoie da Tastiera

| Tasto | Azione |
|-------|--------|
| `Tab` | Aggiungi nodo figlio |
| `Invio` | Aggiungi nodo fratello |
| `Canc` / `Backspace` | Elimina nodo selezionato |
| `Ctrl + N` | Nuova mappa |
| `Ctrl + S` | Salva mappa |
| `Ctrl + O` | Apri mappa |
| `Ctrl + Shift + S` | Salva su file |
| `Ctrl + Z` | Annulla |
| `Ctrl + Y` | Ripristina |
| `Ctrl + E` | Esporta |
| `Ctrl + F` | Cerca |
| `Ctrl + B` | Grassetto |
| `Ctrl + I` | Corsivo |
| `Ctrl + U` | Sottolineato |
| `Ctrl + G` | Raggruppa nodi |
| `Frecce` | Sposta tra i nodi |
| `+` / `-` | Zoom avanti/indietro |
| `0` | Reset zoom |
| `H` | Mostra/nascondi aiuto |
| `G` | Mostra/nascondi griglia |
| `F` | Attiva/disattiva focus mode |
| `L` | Attiva/disattiva low-sensory |

## 🎨 Colori Disponibili

- 🟢 Verde (`#4CAF50`)
- 🔵 Blu (`#2196F3`)
- 🟠 Arancione (`#FF9800`)
- 🩷 Rosa (`#E91E63`)
- 🟣 Viola (`#9C27B0`)

## 🏷️ Marcatori Disponibili

| Icona | Significato |
|-------|-------------|
| ⭐ | Importante / Priorità alta |
| ❗ | Attenzione / Urgente |
| ✅ | Completato |
| ❌ | Non completato / Annullato |
| ⏳ | In attesa / In corso |
| 🔄 | Da revisionare |
| 1️⃣ | Priorità 1 |
| 2️⃣ | Priorità 2 |
| 3️⃣ | Priorità 3 |
| 📌 | Fisso / Importante |
| 💡 | Idea |
| ❓ | Domanda |
| 📅 | Scadenza / Data |
| 🔖 | Segnalibro |

## 📤 Formati di Esportazione

- **PNG**: Immagine raster per presentazioni e documenti
- **SVG**: Grafica vettoriale per modifiche successive
- **PDF**: Documento pronto per la stampa
- **Markdown**: Testo strutturato per appunti e note

## ♿ Accessibilità

L'applicazione include diverse opzioni per migliorare l'accessibilità e supportare utenti con esigenze specifiche:

### Opzioni di Visualizzazione

- **🔲 Alto Contrasto**: Attiva la modalità ad alto contrasto per una migliore visibilità
- **⊞ Griglia**: Mostra una griglia di allineamento per aiutare nella disposizione dei nodi (utile per disgrafia/discalculia)
- **🌿 Low-Sensory**: Tema a basso impatto sensoriale per utenti con autismo o sensibilità visiva
- **🎯 Focus Mode**: Nasconde i nodi non correlati per migliorare la concentrazione (utile per ADHD)

### Font Speciali

- **Lexend**: Font moderno e leggibile (consigliato)
- **OpenDyslexic**: Font specifico per dislessia
- **Verdana**: Font classico ad alta leggibilità

### Altre Funzioni

- **🔤 Font Grande**: Aumenta la dimensione del testo
- **↔️ Spaziatura Ampia**: Aumenta la spaziatura tra lettere e parole
- **🔊 Leggi ad Alta Voce**: Sintesi vocale per i nodi selezionati
- **Supporto Screen Reader**: Completa implementazione ARIA per l'accessibilità
- **Riduzione Movimento**: Rispetta le preferenze di riduzione del movimento del sistema

## 🛠️ Tecnologie

- HTML5, CSS3, JavaScript (Vanilla)
- [html2canvas](https://html2canvas.hertzen.com/) per l'esportazione PNG
- [jsPDF](https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js) per l'esportazione PDF
- Font: Lexend (Google Fonts), OpenDyslexic, Verdana, Arial
- Web Speech API per la sintesi vocale

## 📁 Struttura del Progetto

```
├── index.html          # File principale dell'applicazione
├── README.md           # Questo file
└── ...
```

## 💾 Formato di Salvataggio

Le mappe vengono salvate come file JSON con estensione `.simplimap` o `.json`, contenenti:
- Struttura dei nodi (gerarchia)
- Testo di ogni nodo
- Colori e marcatori
- Note associate
- Posizioni dei nodi
- Impostazioni di visualizzazione

## 📋 Toolbar Organizzata

La toolbar è organizzata in gruppi funzionali per facilitare l'accesso alle funzioni:

1. **File**: Nuova, Apri, Salva
2. **Nodi**: Aggiungi figlio, Aggiungi fratello, Elimina, Marcatori, Raggruppa
3. **Colori**: 5 colori per personalizzare i rami
4. **Vista**: Contrasto, Griglia, Low-sensory, Focus, Leggi
5. **Formattazione testo**: Font grande, Spaziatura, Grassetto, Corsivo, Sottolineato, Selezione font
6. **Altro**: Esporta (PNG, SVG, PDF, Markdown), Cerca

## 🤝 Contribuire

1. Fork del repository
2. Crea un branch per la tua feature (`git checkout -b feature/NuovaFeature`)
3. Commit delle modifiche (`git commit -m 'Aggiunta nuova feature'`)
4. Push sul branch (`git push origin feature/NuovaFeature`)
5. Apri una Pull Request

## 📄 Licenza

Questo progetto è distribuito sotto licenza MIT. Vedi il file [LICENSE](LICENSE) per i dettagli.

## 📞 Supporto

Per problemi, suggerimenti o domande, apri una issue nel repository.

---

**Creato con ❤️ per rendere la creazione di mappe mentali semplice e accessibile a tutti.**

*SimpliMap Edu è progettato per essere inclusivo e supportare studenti e professionisti con diverse esigenze di apprendimento.*
