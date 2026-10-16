# ✨ Royal Purple Dynamic Wedding Invitation Web App ✨

An interactive, royal purple-themed wedding invitation web application with dynamic animations, custom Bride/Groom display ordering, live Google Maps integration for both Marriage and Reception venues, background transition music, and instant QR Code sharing.

---

## 🌟 Key Features

* **🤵👰 Dynamic Groom / Bride Priority Selector:** 
  * Choose **Groom's Side** or **Bride's Side** as the first step.
  * Automatically reorders the couple's initials on the Royal Wax Seal (`G & B` vs `B & G`), the parents' blessings section, and the grand couple name reveal during the transition.
* **🎭 Royal Curtain & Wax Seal Transition:**
  * Opens with an interactive royal purple double curtain and a pulsing golden wax seal.
  * Tapping the seal unlocks browser audio, opens the curtains smoothly, and triggers a staggered card reveal with floating golden particles.
* **🎵 Custom Transition Music Support:**
  * Plays the background wedding song (`song.mp3` — *"Aaj Se Teri"*) automatically upon opening the invitation, complete with a floating play/pause toggle and a Web Audio API harp chime fallback.
* **💌 Curated & Custom Wedding Quotes:**
  * Includes pre-written royal wedding invitation quotes plus an option to write a custom blessing or quote.
* **📍 Marriage & Reception Venues with Live Google Maps:**
  * Separate sections for both the **Auspicious Marriage Ceremony** and the **Grand Reception Ceremony**.
  * Automatically generates embedded interactive Google Maps (`<iframe>`) and direct **"Open in Google Maps"** navigation buttons.
* **📱 Instant Scannable QR Code & Link Sharing:**
  * Encodes all wedding and reception data directly into URL query parameters (`?invite=1&side=...`).
  * Guests who scan the QR code bypass the creator form and immediately experience the royal curtain transition on their phones.

---

## 📂 Project Structure

```text
wedding-invite/
├── index.html          # Complete application (HTML5, CSS3, Vanilla JS)
├── song.mp3            # Transition audio ("Aaj Se Teri" MP3 renamed to song.mp3)
├── README.md           # Project documentation
└── requirements.txt    # Environment & dependency specifications
