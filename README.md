########### English ###########

# 🏐 ZoneMap Suite

**ZoneMap Suite** is a professional video analysis overlay tool designed for Volleyball Scouts and Data Volley users. 

It creates a semi-transparent, perspective-corrected layer on top of your video player, allowing you to visualize tactical zones, net distribution, and service trajectories directly on the game feed.

![ZoneMap Main Screenshot](preview.png)
*(Place a screenshot of the app in action here)*

## ✨ Key Features

### 🎯 1. Perspective Correction
- **6-Point Calibration:** Easily align the grid to the court perspective using 6 draggable handles (Far Baseline, Net, Near Baseline).
- **Homography:** Uses advanced mathematics to ensure zones remain accurate even with angled camera views.

### 📐 2. Dual Operation Modes
- **Standard Mode:** Classic 3x3 Volleyball Zoning (Zones 1-9) with automatic mirroring.
- **Custom Mode:** A powerful 2D Vector Editor to draw specific tactical areas (conflict zones, defensive spots).

### 🏐 3. Advanced Tools
- **Net Grid:** Customizable horizontal divisions (e.g., 9 sectors) to analyze set distribution or attack paths.
- **Service Zones:** Automatic extension of court lines to visualize service corridors (5 zones).
- **Global Visibility:** "Panic button" to hide/show all overlays instantly.

### 🎨 4. Full Customization
- **Colors & Transparency:** Adjust opacity for lines, numbers, and background fills.
- **Click-Through:** The overlay is transparent to mouse clicks, allowing you to interact with DataVolley or the video player underneath.

---

## 📥 Installation

1. Go to the [**Releases**](https://github.com/gabriop82/ZoneMap/releases) page.
2. Download the latest installer: `ZoneMap_Setup_v2.0.exe`.
3. Run the installer and follow the instructions.

---

## 🚀 How to Use

### First Run
Upon first launch, a Wizard will ask for your Team Name and preferences. This helps organize analytics and default settings.

### Controls & Calibration
1. **Launch the App:** You will see the Overlay and the Configuration Panel.
2. **Align the Court:** Drag the **6 Yellow Dots** on the overlay to match the court corners and the net line in your video.
3. **Toggle Edit Mode:**
   - **EDIT MODE:** You can move the dots and change configurations. The overlay intercepts clicks.
   - **OVERLAY MODE:** The yellow dots disappear. Clicks pass through to the video player below.

### Standard vs Custom
*   **Standard:** Use the dropdowns in the Control Panel to highlight specific zones (1-9) on the Near or Far court.
*   **Custom:** Switch to "Custom Mode". Use the **2D Editor** to draw rectangles. They will be projected in real-time onto the court. You can save and load different layouts (e.g., "Reception Layout", "Defense Layout").

---

## ⌨️ Shortcuts

| Key | Action |
| :--- | :--- |
| **F8** | Toggle Global Visibility (Show/Hide everything) |
| **F9** | Show/Minimize Configuration Panel |

---

## 🛠️ Technical Stack

Built with Python and modern libraries for high performance:
*   **GUI:** [PySide6](https://pypi.org/project/PySide6/) (Qt for Python)
*   **System Integration:** `pywin32` for advanced Windows API calls (Click-through, Always-on-top).
*   **Math:** `numpy` for homography and vector calculations.
*   **Telemetry:** Custom integration with Firebase Realtime Database.

---

## 👨‍💻 Author

Developed by **Gabrio Piozzi**.

*   [LinkedIn](https://www.linkedin.com/in/gabriopiozzi/)
*   [Instagram](https://www.instagram.com/piozzigabrio/)

---

### 📄 License
This project is proprietary. Unauthorized copying or distribution is strictly prohibited.

########### Italiano ###########

# 🏐 ZoneMap Suite

**ZoneMap Suite** è uno strumento professionale di overlay grafico per l'analisi video, progettato specificamente per Scoutman di Pallavolo e utilizzatori di Data Volley.

L'applicazione crea un livello semitrasparente, corretto prospetticamente, sopra il tuo video player o software di scout, permettendo di visualizzare zone tattiche, distribuzione a rete e traiettorie di battuta direttamente sul flusso di gioco.

![Anteprima ZoneMap](preview.png)
*(Sostituisci questo percorso con uno screenshot reale dell'app in azione)*

## ✨ Funzionalità Principali

### 🎯 1. Correzione Prospettica
- **Calibrazione a 6 Punti:** Allinea perfettamente la griglia alla prospettiva del campo trascinando 6 maniglie (Linea di Fondo Lontana, Rete, Linea di Fondo Vicina).
- **Omografia:** Utilizza calcoli matematici avanzati per garantire che le zone rimangano precise anche con inquadrature angolate o basse.

### 📐 2. Doppia Modalità Operativa
- **Modalità Standard:** La classica divisione del campo in 9 Zone (3x3) con specchiamento automatico tra campo vicino e lontano.
- **Modalità Custom:** Un potente **Editor Vettoriale 2D** per disegnare aree tattiche specifiche (es. zone di conflitto, buchi difensivi) che vengono proiettate in tempo reale sul video.

### 🏐 3. Strumenti Avanzati
- **Griglia Rete:** Divisione orizzontale personalizzabile (es. 9 settori) per analizzare la distribuzione del palleggiatore o le traiettorie d'attacco.
- **Zone di Battuta:** Estensione automatica delle linee laterali per visualizzare i corridoi di servizio (5 zone).
- **Visibilità Globale:** Un "Panic button" per mostrare/nascondere istantaneamente tutti gli overlay.

### 🎨 4. Personalizzazione Completa
- **Colori e Trasparenza:** Regola l'opacità di linee, numeri e riempimenti per adattarsi a qualsiasi video.
- **Click-Through:** In modalità "Overlay", la finestra diventa trasparente ai click del mouse, permettendoti di interagire liberamente con Data Volley o il player sottostante.

---

## 📥 Installazione

1. Vai alla pagina delle [**Releases**](https://github.com/gabriop82/ZoneMap/releases).
2. Scarica l'ultimo installer: `ZoneMap_Setup_v6.0.exe`.
3. Avvia l'installazione e segui le istruzioni a schermo.

---

## 🚀 Come si usa

### Primo Avvio
Alla prima apertura, un Wizard ti chiederà il nome della tua Squadra e alcune preferenze. Questi dati servono per organizzare le statistiche di utilizzo e impostare i default.

### Controlli e Calibrazione
1. **Avvia l'App:** Vedrai l'Overlay e il Pannello di Configurazione.
2. **Allinea il Campo:** Trascina i **6 Pallini Gialli** sull'overlay per farli coincidere con gli angoli del campo e la linea di rete nel video.
3. **Cambia Modalità (Tasto Edit):**
   - **MODALITÀ MODIFICA:** I pallini sono visibili e puoi spostarli. L'overlay intercetta i click.
   - **MODALITÀ OVERLAY:** I pallini spariscono per lasciare la visuale pulita. I click del mouse passano attraverso (Click-Through).

### Standard vs Custom
*   **Standard:** Usa i menu a tendina nel pannello per evidenziare zone specifiche (1-9) sul campo Vicino o Lontano.
*   **Custom:** Passa alla modalità "Custom". Usa l'**Editor 2D** per disegnare rettangoli o aree. Verranno proiettati sul campo rispettando la prospettiva. Puoi salvare e caricare diversi layout (es. "Schema Ricezione", "Schema Difesa").

---

## ⌨️ Scorciatoie da Tastiera

| Tasto | Azione |
| :--- | :--- |
| **F8** | Attiva/Disattiva Visibilità Globale (Nascondi tutto) |
| **F9** | Mostra/Minimizza il Pannello di Configurazione |

---

## 🛠️ Stack Tecnologico

Sviluppato in Python con librerie moderne per massime prestazioni:
*   **GUI:** [PySide6](https://pypi.org/project/PySide6/) (Qt for Python)
*   **Integrazione Sistema:** `pywin32` per la gestione avanzata delle finestre Windows (Click-through, Always-on-top).
*   **Matematica:** `numpy` per calcoli vettoriali e omografia.
*   **Telemetria:** Integrazione personalizzata con Firebase Realtime Database.

---

## 👨‍💻 Autore

Sviluppato da **Gabrio Piozzi**.

*   [LinkedIn](https://www.linkedin.com/in/gabriopiozzi/)
*   [Instagram](https://www.instagram.com/piozzigabrio/)

---

### 📄 Licenza
Questo progetto è proprietario. La copia o distribuzione non autorizzata è vietata.
