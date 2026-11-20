# Diario di reparto: come metterlo su PC e telefono

## Cosa c'è nella cartella

- `index.html`: tutto il programma (aspetto, funzioni, esempi). È l'unico file da toccare per le modifiche.
- `manifest.webmanifest`: nome e icona dell'app.
- `sw.js`: permette di usarla anche senza internet.
- `icon-*.png`, `apple-touch-icon.png`: le icone.

## 1. Pubblicarla (una volta sola, circa 10 minuti)

Online va solo il programma: i dati dei pazienti restano sul tuo dispositivo e non vengono mai caricati.

1. Crea un account gratuito su https://github.com
2. In alto a destra premi **+**, poi **New repository**. Dagli un nome, per esempio `diario-reparto`, e lascialo **Public** (GitHub Pages gratuito richiede un repository pubblico; contiene solo il codice, niente dati). Premi **Create repository**.
3. Nella pagina del repository premi **uploading an existing file**, trascina **tutti i file** della cartella (non la cartella stessa) e premi **Commit changes**.
4. Vai in **Settings → Pages**. In "Branch" scegli `main` e la cartella `/ (root)`, poi premi **Save**.
5. Dopo 1–2 minuti l'indirizzo compare in alto nella stessa pagina, per esempio `https://tuonome.github.io/diario-reparto/`.

## 2. Installarla

- **PC (Chrome o Edge):** apri l'indirizzo e premi l'icona "Installa" nella barra dell'indirizzo (oppure menu ⋮ → *Installa Diario reparto*).
- **iPhone:** apri l'indirizzo con **Safari**, premi Condividi ⬆︎ → **Aggiungi a schermata Home**.
- **Android:** apri l'indirizzo con **Chrome**, menu ⋮ → **Installa app** (o *Aggiungi a schermata Home*).

## 3. Modificarla

1. Cambia `index.html`: chiedi a Claude di farlo (allega il file e descrivi cosa non va), oppure modificalo tu con un editor di testo.
2. Su GitHub, apri il repository, premi **Add file → Upload files**, carica il nuovo `index.html` (sostituisce il vecchio) e premi **Commit changes**.
3. Dopo un paio di minuti chiudi e riapri l'app sui dispositivi (con internet attivo): l'aggiornamento arriva da solo.

**I dati inseriti non si perdono con gli aggiornamenti**, purché resti uguale l'indirizzo. Per sicurezza, prima di modifiche grosse fai un backup.

## 4. Dati e backup

- Ogni dispositivo ha i suoi dati: PC e telefono **non si sincronizzano**.
- **Esporta / importa → Scarica file** salva un backup `.json`; con **Importa** (o scegliendo il file) lo ripristini o lo sposti su un altro dispositivo.
- Fai un backup ogni tanto: se cancelli i dati di navigazione del browser o disinstalli l'app, i dati spariscono.
- Usa solo iniziali o codici, mai nomi, date di nascita o altri dati identificativi. Prima di usarla con pazienti reali verifica cosa prevedono le policy del Gemelli.

## Prova senza pubblicare

Puoi aprire `index.html` con un doppio clic: funziona nel browser del PC, ma senza installazione né modalità offline.
