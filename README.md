# Kristyasworn — Registro di Costruzione

Dashboard statica (HTML/CSS/JS puro, nessuna build necessaria) per il deckbuilding Edison Format.

## Deploy su Vercel

1. Push di questo repo su GitHub (vedi sotto).
2. Su vercel.com → **Add New → Project** → importa il repository.
3. Framework Preset: **Other** (è HTML statico, nessuna build da eseguire).
4. Build Command: vuoto. Output Directory: `.` (root).
5. Deploy.

Nota: questa versione salva i dati in `localStorage`, quindi la persistenza è **locale al browser** in cui la usi — se apri il sito da un altro dispositivo o browser, parti dalla lista di riferimento predefinita, non vedrai le modifiche fatte altrove. Non c'è nessun backend/database condiviso dietro.
