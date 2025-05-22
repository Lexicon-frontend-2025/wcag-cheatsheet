# WCAG Cheatsheet – Tillgänglig Webbutveckling

## 📘 Vad är WCAG?
WCAG (Web Content Accessibility Guidelines) är internationella riktlinjer för att göra webbinnehåll mer tillgängligt för personer med funktionsnedsättningar. Senaste versionen: **WCAG 2.1 / 2.2** (W3C).

## 🔑 Fyra grundprinciper (POUR)

| Princip | Förklaring |
|--------|------------|
| **P**erceivable (Märkbar) | Innehållet ska gå att uppfatta med sinnen (syn, hörsel etc). |
| **O**perable (Hanterbar) | Det ska gå att använda gränssnittet (tangentbord, ej tidspress). |
| **U**nderstandable (Förståelig) | Innehåll och gränssnitt ska vara begripliga. |
| **R**obust | Innehåll ska fungera i olika tekniker, hjälpmedel och webbläsare. |

---

## 🚦Nivåer
- **A** – Minimikrav
- **AA** – Rekommenderad standard
- **AAA** – Högsta möjliga tillgänglighet

---

## 📋 WCAG Checklist (för nivå AA – vanligast)

### 👁️ 1. Perceivable (Märkbar)

| Riktlinje | Exempel |
|-----------|---------|
| **Textalternativ** (1.1.1) | Alla bilder har `alt`-text. |
| **Undertexter** (1.2) | Video har textning eller transkription. |
| **Färger & kontrast** (1.4.3) | Text har minst 4.5:1 kontrast mot bakgrund. |
| **Zoombarhet** (1.4.4) | Inget innehåll bryts vid 200% zoom. |
| **Använd inte bara färg** (1.4.1) | T.ex. felmeddelanden har ikon + text, inte bara färg. |

### ⌨️ 2. Operable (Hanterbar)

| Riktlinje | Exempel |
|-----------|---------|
| **Tangentbordsnavigering** (2.1.1) | Allt går att navigera med tab-tangenten. |
| **Ingen tangentbordsfälla** (2.1.2) | Man kan tabba **både in och ut** ur interaktiva element. |
| **Tillräcklig tid** (2.2.1) | Ge möjlighet att förlänga tidsbegränsningar. |
| **Fokus syns tydligt** (2.4.7) | Länkar och knappar får visuell markering (t.ex. outline). |
| **Hoppa till innehåll** (2.4.1) | Lägg till en "Hoppa till innehåll"-länk i början. |

### 💬 3. Understandable (Förståelig)

| Riktlinje | Exempel |
|-----------|---------|
| **Språk anges** (3.1.1) | `<html lang="sv">` |
| **Formulär har etiketter** (3.3.2) | Alla `input`-fält har `<label for="...">`. |
| **Felmeddelanden är tydliga** (3.3.1) | Beskriv vad som är fel och hur man rättar det. |
| **Konsekvent navigation** (3.2.3) | Samma menystruktur på alla sidor. |

### 🔧 4. Robust

| Riktlinje | Exempel |
|-----------|---------|
| **Validerad HTML** (4.1.1) | Använd korrekt och semantisk HTML5. |
| **Tillgänglig ARIA** (4.1.2) | Använd `aria-*` bara där det behövs. |
| **Namn, roll, värde** | Element ska tydligt beskriva sin roll (särskilt med hjälpmedel). |

---

## 🧪 Testa din tillgänglighet

| Verktyg | Beskrivning |
|--------|-------------|
| [axe DevTools](https://www.deque.com/axe/devtools/) | Webbläsartillägg för att hitta WCAG-fel. |
| [WAVE](https://wave.webaim.org/) | Webbaserad testare för tillgänglighet. |
| [Lighthouse](https://developer.chrome.com/docs/lighthouse/) | Inbyggt i Chrome DevTools. |
| Skärmläsare | VoiceOver (Mac), NVDA (Windows), TalkBack (Android). |

---

## ✅ Snabbtips
- Använd **semantiska HTML-element**.
- Skriv **alt-texter** som beskriver funktion, inte bara utseende.
- Undvik "Klicka här" – använd beskrivande länkar.
- Testa med **tangentbordet endast**.
- Testa på **mobil + skärmläsare**.

---
