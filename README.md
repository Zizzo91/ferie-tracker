# 🗓 Ferie Tracker

App web per la gestione di **ferie, permessi ed ex festività** sul calendario.

**[▶ Apri l'app](https://zizzo91.github.io/ferie-tracker/)**

---

## Funzionalità

- 📅 Calendario mensile e vista annuale
- 👥 Profili multipli
- 📊 Riepilogo mensile e barre di avanzamento
- ↩️ Undo dell'ultima azione
- 🌙 Dark mode
- 📤 Export / Import JSON
- ☁️ **Sincronizzazione cloud via GitHub Gist**
- 📱 **PWA** — installabile su iPhone, Android e Mac

---

## Come usare la Sincronizzazione Cloud (GitHub Gist)

1. Vai su [github.com/settings/tokens/new](https://github.com/settings/tokens/new?scopes=gist&description=FerieTracker)
2. Crea un **Personal Access Token** con scope `gist`
3. Nell'app, apri la card **"☁️ Sincronizzazione Cloud"**
4. Incolla il token nel campo **Token**
5. Clicca **"Salva su Gist"** → verrà creato automaticamente un Gist privato
6. Copia il **Gist ID** mostrato
7. Su un altro dispositivo: inserisci stesso token + Gist ID → clicca **"Carica da Gist"**

> ⚠️ Il token è salvato **solo in memoria** nella sessione corrente, mai su disco.

---

## Come installare come app (PWA)

### iPhone / iPad
1. Apri **Safari** → vai sull'app
2. Tocca l'icona **Condividi** → **Aggiungi a schermata Home**

### Mac (Chrome / Edge)
1. Apri l'app nel browser
2. Clicca l'icona di installazione nella barra degli indirizzi

### Android
1. Apri **Chrome** → vai sull'app
2. Tocca i tre puntini → **Aggiungi a schermata Home**

---

## Stack tecnico

- HTML/CSS/JS vanilla — zero dipendenze backend
- [Lucide Icons](https://lucide.dev/) per le icone SVG
- Google Fonts (Inter)
- GitHub Gist API per il sync cloud
- Service Worker per la cache offline
- GitHub Pages per il deploy
