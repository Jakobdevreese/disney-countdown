# 🎢 Family Countdown – Disneyland Parijs

Een vrolijke, responsive **countdownklok** die aftelt naar ons vertrek naar **Disneyland Parijs**!  
👉 Vertrek op **31 oktober om 04:30 (Brussel-tijd)**  

Deze klok werkt op **elk toestel** (telefoon, tablet, computer of tv) en kan zelfs **gecast** worden via Chromecast of Android TV.  
Als het moment van vertrek aanbreekt, barst de pagina uit in **confetti 🎉**!

---

## 🌐 Live versie

👉 **https://jakobdevreese.github.io/disney-countdown/**

---

## 🛠️ Inhoud van deze repo

| Bestand | Beschrijving |
|----------|---------------|
| `index.html` | De hoofdpagina met de countdownlogica, knoppen en confetti-effect. |
| `style.css` | De vrolijke styling: pastelkleuren, ronde vormen, schaduwen, en responsive grid. |
| `manifest.json` | Maakt het mogelijk om de countdown te “installeren” als webapp op telefoon of tablet. |
| `icon-192.png`, `icon-512.png` | App-iconen voor de webapp (optioneel, mogen later vervangen worden). |
| `README.md` | Dit bestand, met uitleg en instructies. |

---

## 🚀 Hoe de countdown zelf aanpassen

Open `index.html` en wijzig deze regel:

```js
const target = new Date("2025-10-31T04:30:00+01:00");
```

### Tijd aanpassen

Gebruik ISO-formaat:

```
YYYY-MM-DDTHH:MM:SS+TZ
```

Bijvoorbeeld:

- `"2025-12-25T00:00:00+01:00"` → Kerstmis (middernacht)
- `"2026-07-15T09:00:00+02:00"` → zomervakantie

### Titel of emoji's

Aanpasbaar in de HTML:

```html
<h1>Vertrek naar Disneyland Parijs 🎢✨</h1>
```

---

## 💫 Gebruiksinstructies

### 📱 Op smartphone/tablet

1. Open de link.
2. Tik op **“Toevoegen aan startscherm”** (iOS of Android).  
   → De countdown opent daarna als **volledig scherm-app**.

### 🖥️ Op computer of laptop

- Open de link in je browser.  
- Klik op **Volledig scherm** (knop op de pagina of `F11`) voor een nette weergave.

### 📺 Casten naar tv

- Gebruik **Google Chrome** of **Microsoft Edge**.  
- Open het menu (⋮) → **Casten** → kies je **Chromecast/Android TV**.  
- De countdown verschijnt groot op je scherm!

*(Volledige Google Cast-integratie is niet nodig — tab-casting werkt universeel.)*

---

## ✨ Features

✅ Volledig **responsive** (werkt op groot en klein scherm)  
✅ **Confetti** wanneer de countdown nul bereikt  
✅ **Deelknop** om link eenvoudig te delen  
✅ **Volledig scherm-modus**  
✅ **PWA-ondersteuning** (installeerbaar als app)  
✅ Geen externe afhankelijkheden – werkt offline na laden  

---

## 🎨 Kleuren & thema aanpassen

Open `style.css` en wijzig de variabelen bovenaan:

```css
:root {
  --bg1:#ffecd2;
  --bg2:#fcb69f;
  --accent:#ffd166;
}
```

Je kunt ook een foto als achtergrond gebruiken:

```css
body {
  background: url('img/disney.jpg') center/cover fixed, #fcb69f;
}
```

---

## 💡 Tips

- Zet een tablet met de countdown in de woonkamer 🕓  
- Voeg een Bluetooth-speaker toe voor vrolijke Disney-muziek 🎶  
- Zet de klok op volledig scherm voor het ultieme “we vertrekken!”-moment 😄  

---

## 📄 Licentie

Vrij te gebruiken, delen en aanpassen voor persoonlijk gebruik.  
© 2025 – Met liefde gemaakt voor een magische familie-trip ✨