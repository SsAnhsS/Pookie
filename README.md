## 🤖 Projektbeschreibung

<img width="642" height="479" alt="Pookie_Hello_1" src="https://github.com/user-attachments/assets/7101c5f8-7cc8-4a1b-8499-9157ad3c3b30" />

Was wäre, wenn Technologie nicht nur auf Knopfdruck reagiert, sondern ihre **Umgebung wahrnimmt**?
Wenn sie Bewegungen erkennt, Routinen versteht und sich anpasst?

**Dieses Projekt geht genau diesen Schritt:**
Es schafft einen **interaktiven Begleiter**, der nicht nur auf klassische Eingaben reagiert, sondern sich **dynamisch verhält**.
Im Mittelpunkt steht **eine Kamera**, die Handlungen erfasst und eine intuitive Verbindung zwischen Mensch und Maschine herstellt.

Um Inhalte auf dem Display darstellen zu können, wurde **Python** mit der Spiele-Engine **PyGame** verwendet.
Mit PyGame lassen sich **2D-Charaktere** mithilfe von Sprites animieren – so kann **Pookie** durch verschiedene Szenen laufen.
Während der **physische Bau** des Geräts entwickelt wurde, entstand **parallel die Software**.

<img width="1920" height="1080" alt="Pookie_01" src="https://github.com/user-attachments/assets/73e8bb81-20a8-46ae-a499-f1d728f38ca3" />

<img width="1920" height="1080" alt="Pookie_02" src="https://github.com/user-attachments/assets/511ef760-cfb8-4a16-8bde-e80c4dbeb34f" />

<img width="1920" height="1080" alt="Pookie_03" src="https://github.com/user-attachments/assets/1dbd3495-589c-4839-827a-e384cdccf63b" />

### 🧠 Key-Features

* **Objekterkennung**
  KI-basierte Objekterkennung ermöglicht eine **passive Interaktion** zwischen Nutzer und Pookie.

* **Dynamischer Charakter**
  Pookie **beobachtet das Verhalten des Nutzers** – z. B. wie lange und wie oft jemand liest, Sport treibt oder am Handy ist –
  und **passt sich charakterlich an**.

* **Gyrosensor**
  Für eine **aktive Interaktion** ist ein Gyrosensor verbaut.
  So kann z. B. durch **Schütteln** mit Pookie interagiert werden.

---

### 🎯 Ziel

**Pookie** ist ein kleiner Computer mit **Display und Kamera**, der als interaktiver Begleiter auf das **Alltagsverhalten** des Nutzers reagiert.
Je nachdem, ob man lernt, arbeitet, entspannt oder am Handy ist, **verändert sich Pookies Verhalten und seine Umgebung**.

Das Ziel ist nicht nur Unterhaltung, sondern auch ein sanfter Hinweis darauf,
**wie das eigene Verhalten die Produktivität und Stimmung beeinflusst.**

---

## 💻 Meine Rolle im Projekt

Ich war an der **Softwareentwicklung und Produktumsetzung** beteiligt.
Darüber hinaus habe ich das **3D-Modell des Produkts** erstellt, das als Grundlage für das physische Design diente.

<img width="1920" height="1080" alt="Pookie_01" src="https://github.com/user-attachments/assets/14bb984c-6cc1-4054-84f3-28db530b2cdf" />

---

## 🧩 Technologien verwendet

| Bereich                | Technologie                 |
| ---------------------- | --------------------------- |
| **Programmiersprache** | Python                      |
| **Engine**             | PyGame                      |
| **Hardware**           | Kamera, Gyrosensor, Display |
| **3D-Modellierung**    | Blender                     |

---

## ⚙️ Projekt ausführen

### Virtuelle Umgebung erstellen und aktivieren

Beides:

```bash
python -m venv venv
```

**Mac:**

```bash
source venv/bin/activate
```

**Windows:**

```bash
venv\Scripts\activate
# oder
.\venv\Scripts\Activate.ps1
```

### Abhängigkeiten installieren

```bash
pip install -r requirements.txt
```

### Projekt starten

```bash
python main.py
```

Da nur das physische Gerät die **Kamera- und Sensorfunktionen** vollständig unterstützt,
kann man auf dem PC **Debug-Tasten** verwenden, um die Module zu testen:

---

## 🧩 Debug-Steuerung

| Taste                    | Funktion                                 |
| ------------------------ | ---------------------------------------- |
| **D**                    | Debug-Modus                              |
| **Klick auf Fenster**    | Fenster öffnen/schließen (tagesabhängig) |
| **↓ (Pfeil nach unten)** | Alles fällt herunter                     |
| **W**                    | Wechsel zwischen Tag/Nacht               |
| **S**                    | Sportmodus aktivieren                    |
| **O**                    | Charakter öffnet Fenster automatisch     |
| **T**                    | TikTok-Modus                             |
| **B**                    | Buch lesen                               |
| **H**                    | Hantelmodus                              |
| **R**                    | Reset                                    |

