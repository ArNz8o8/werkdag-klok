# 🕒 Frontoffice Klok — HHS Bokeh Edition

Een interactief dashboard speciaal ontworpen voor de Frontoffice van FZ&IT aan De Haagse Hogeschool. Dit dashboard combineert real-time klokfunctionaliteiten met HHS-branding, humoristische werk-gerelateerde content en een dynamisch Bokeh-achtergrondeffect.

## ✨ Belangrijkste Functies

### 1. Dynamische Visuele Logica
* **Bokeh Achtergrond:** Genereert willekeurig zwevende cirkels in de officiële HHS-kleuren (Groen, Blauw, Grijs).
* **Smart Theme Switching:** * **Overdag:** Een lichte, energieke achtergrond met HHS-kleuren.
    * **Nacht/Gesloten:** Schakelt automatisch over naar een donker "after-hours" thema.
    * **16:29 Trigger:** Een speciale "special-glow" animatie om 16:29 om de bijna-einde-werktijd te vieren.

### 2. Tijd & Countdown Logica
* **Real-time Klok:** Nauwkeurige tijd- en datumweergave in het Nederlands.
* **Openingstijden Framework:** Het systeem is geprogrammeerd met de specifieke werktijden:
    * **Maandag t/m Donderdag:** 08:00 – 19:30 uur.
    * **Vrijdag:** 08:00 – 17:00 uur.
* **Weekend Countdown:** Berekent exact hoeveel dagen en uren het nog duurt tot het weekend (vrijdag 17:00). In het weekend telt hij af naar maandagochtend.

### 3. Content & Motivatie
* **Contextuele Berichten:** Toont elke 30 minuten een nieuwe quote of grapje over werken bij de Frontoffice (bijv. TOPdesk, Azure AD, Directory Manager).
* **Smart Ticker (Lichtkrant):** * Toont motiverende teksten tijdens werktijd.
    * Geeft een **live aftelling (HH:MM:SS)** in de ochtend tussen 07:45 en 08:00.
* **Weer-Integratie:** Haalt live de temperatuur en weerscondities op voor Den Haag via de Open-Meteo API.

## 🛠️ Technische Details

| Component | Technologie |
| :--- | :--- |
| **Frontend** | HTML5, CSS3 (Flexbox/Grid), JavaScript (ES6+) |
| **Fonts** | Open Sans via Google Fonts |
| **API** | Open-Meteo (Zonder API-key voor eenvoudige implementatie) |
| **Animaties** | CSS Keyframes (float, ticker, glow) |

## 🚀 Installatie

1. Kloon deze repository of download het `index.html` bestand.
2. Zorg dat het logo (`HHS_grijs_fc copy.png`) in dezelfde map staat.
3. Open `index.html` in een moderne browser (Chrome/Edge aanbevolen voor narrowcasting schermen).

## 📄 Licentie

Dit project is ontwikkeld voor intern gebruik bij De Haagse Hogeschool (FZ&IT). Vrij te gebruiken en aan te passen voor teamleden.

---
*Gemaakt met ☕ door ArNz8o8 en voor de Frontoffice.*
