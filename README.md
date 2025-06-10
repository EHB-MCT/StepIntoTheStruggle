# Step Into the Struggle 🎮🧠  
**Interactieve video experience in het vel van van een jongere uit een sociale woonwijk waar je keuzes ga moeten maken na elke scene aan de hand van een handgebaar.**


---

## 📍 Inhoud

- [Beschrijving](#beschrijving)
- [Doelstelling](#doelstelling)
- [Technologieën](#technologieën)
- [Interactieve Gebaren](#interactieve-gebaren)
- [Projectstructuur](#projectstructuur)
- [Installatie](#installatie)
- [Credits](#credits)

---

## 📖 Beschrijving

**Step Into the Struggle** is een immersieve video-ervaring waarin de gebruiker morele keuzes maakt via handgebaren. Je speelt het verhaal door fysieke poses vast te houden. Elke keuze leidt tot een nieuwe wending en reflectie.

De installatie werd ontwikkeld als bachelorproef en onderzoekt hoe motion tracking, storytelling en game design kunnen samenkomen in een sociaal-kritisch werk.

---

## 🎯 Doelstelling

> **Hoe kan een interactieve installatie jongeren uit sociale woonwijken bewust maken van de impact van hun keuzes op hun persoonlijke ontwikkeling en toekomst?**

## 🧰 Technologieën

- [TouchDesigner](https://derivative.ca/)
- MediaPipe (Hand & Face tracking via CamSchnappr)
- Python (TouchDesigner DAT scripting)
- Adobe Premiere Pro (video editing)
---

## ✋ Interactieve Gebaren

| Gesture          | Functie                            |
|------------------|-------------------------------------|
| Thumbs Up      | Start spel / de waarheid zeggen |
| Thumbs down      | Stop spel / Liegen |
| Victory Sign   | Kalm blijven                            |
| Twee Vuisten   | Illegale taak accepteren                            |
| Pointing Up    | Meelachen                            |
| Middle Finger  | Rebellie              |
| Open Palm(s)   | Vrede / Weigeren                    |

Iedere gesture wordt pas actief binnen zijn eigen scène.

---

## 📁 Projectstructuur

/TouchDesigner_Project
├── project.toe # Hoofdprojectbestand
├── assets/ # Alle video/audio bestanden
├── gestures/ # Gesture detectie via select CHOPs
├── scripts/ # Python logic per gesture
├── output/ # Rendered scenes & transitions
└── docs/ # Documentatie, storyboards, screenshots

yaml
Copier
Modifier

---

## 🛠️ Installatie

1. Download dit project of clone via:
   ```bash
   git clone https://github.com/EHB-MCT/StepIntoTheSrtuggle.git
Open project.toe in TouchDesigner (2023.1+)

Zorg dat je webcam geactiveerd is

Start het project via gesture 👍 (thumbs up)

Volg de instructies op het scherm

👤 Credits
Gemaakt door: Naïl L'Maimouni
Onder begeleiding van: Stefan Tilburgs
Hogeschool: Erasmushogeschool Brussel | Multimedia & Creative Technologies
Jaar: 2024 – 2025

