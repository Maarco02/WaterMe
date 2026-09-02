# Le mie piante 🌿

App per ricordarti quando innaffiare le tue piante. Funziona come PWA: si installa sul telefono come un'app vera, senza passare da App Store o Play Store.

## Come pubblicarla gratis con GitHub Pages

1. **Crea un repository**
   - Vai su [github.com](https://github.com) e crea un account se non ce l'hai già
   - Clicca "New repository", dagli un nome (es. `le-mie-piante`), lascialo **pubblico**, crealo

2. **Carica i file**
   - Nella pagina del repository, clicca "Add file" → "Upload files"
   - Trascina dentro tutti i file di questa cartella: `index.html`, `manifest.json`, `service-worker.js`, `icon-192.png`, `icon-512.png`, `icon-apple-touch.png`
   - Clicca "Commit changes"

3. **Attiva GitHub Pages**
   - Vai su "Settings" (impostazioni del repository) → "Pages" nel menu a sinistra
   - In "Branch" scegli `main` e cartella `/ (root)`, poi "Save"
   - Dopo un minuto o due, GitHub ti mostrerà un link tipo:
     `https://tuonome.github.io/le-mie-piante/`

4. **Installala sul telefono**
   - **iPhone**: apri il link con **Safari** → tocca "Condividi" → "Aggiungi alla schermata Home"
   - **Android**: apri il link con **Chrome** → apparirà "Installa app" (oppure menu ⋮ → "Aggiungi a schermata Home")

5. **Condividila con gli amici**
   - Basta mandare loro lo stesso link: ognuno la installa sul proprio telefono e ha i suoi dati separati

## Nota sulle notifiche

Le notifiche funzionano solo mentre apri l'app almeno una volta al giorno: ti segnalano subito cosa è in ritardo. Non possono "svegliarsi" da sole ad app completamente chiusa, perché questo richiederebbe un server di invio notifiche push, che va oltre una semplice pagina web gratuita.
