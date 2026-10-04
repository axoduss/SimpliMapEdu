# 🧠 Mappa Mentale

Un'applicazione web moderna e accessibile per creare e gestire mappe mentali in modo intuitivo.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## ✨ Caratteristiche Principali

- **🎨 Interfaccia Intuitiva**: Design pulito e moderno con nodi trascinabili
- **♿ Accessibilità**: Supporto completo per alto contrasto, font grandi e spaziatura ampia
- **📤 Multi-Export**: Esporta in PNG, SVG, PDF o Markdown
- **⌨️ Scorciatoie da Tastiera**: Lavora velocemente senza usare il mouse
- **🏷️ Marcatori**: Aggiungi icone per priorità e stato (⭐, ❗, ✅, 1️⃣, 2️⃣, 3️⃣)
- **📝 Note**: Aggiungi note dettagliate a ogni nodo
- **🔍 Ricerca**: Trova rapidamente i nodi nella tua mappa
- **💾 Salvataggio**: Salva e carica le tue mappe come file JSON

## 🚀 Utilizzo

### Creare una Mappa

1. Clicca su **"📄 Nuova"** per iniziare una nuova mappa
2. Il nodo radice è già selezionato - inizia a scrivere il tuo argomento principale
3. Usa **Tab** per aggiungere nodi figli
4. Usa **Invio** per aggiungere nodi fratelli

### Personalizzare i Nodi

- **Colori**: Seleziona uno dei 5 colori disponibili dalla toolbar
- **Marcatori**: Clicca su **"🏷️ Marcatori"** per aggiungere icone di priorità
- **Note**: Aggiungi note dettagliate a qualsiasi nodo

### Navigazione

- **Trascina** i nodi per riorganizzarli
- Usa i controlli **Zoom** (+, −, ⟲) in basso a destra
- Clicca su **"⌂"** per centrare la mappa

## ⌨️ Scorciatoie da Tastiera

| Tasto | Azione |
|-------|--------|
| `Tab` | Aggiungi nodo figlio |
| `Invio` | Aggiungi nodo fratello |
| `Canc` / `Backspace` | Elimina nodo selezionato |
| `Ctrl + N` | Nuova mappa |
| `Ctrl + S` | Salva mappa |
| `Ctrl + Z` | Annulla |
| `Frecce` | Sposta tra i nodi |
| `+` / `-` | Zoom avanti/indietro |
| `H` | Mostra/nascondi aiuto |

## 🎨 Colori Disponibili

- 🟢 Verde (`#4CAF50`)
- 🔵 Blu (`#2196F3`)
- 🟠 Arancione (`#FF9800`)
- 🩷 Rosa (`#E91E63`)
- 🟣 Viola (`#9C27B0`)

## 📤 Formati di Esportazione

- **PNG**: Immagine raster per presentazioni e documenti
- **SVG**: Grafica vettoriale per modifiche successive
- **PDF**: Documento pronto per la stampa
- **Markdown**: Testo strutturato per appunti

## ♿ Accessibilità

L'applicazione include diverse opzioni per migliorare l'accessibilità:

- **🔲 Alto Contrasto**: Attiva la modalità ad alto contrasto per una migliore visibilità
- **🔤 Font Grande**: Aumenta la dimensione del testo
- **↔️ Spaziatura Ampia**: Aumenta la spaziatura tra lettere e parole

## 🛠️ Tecnologie

- HTML5, CSS3, JavaScript (Vanilla)
- [jsPDF](https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js) per l'esportazione PDF
- Font: Verdana, Arial, Comic Neue (Google Fonts)

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
