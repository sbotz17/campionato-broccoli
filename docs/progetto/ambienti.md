# Ambienti — Campionato Broccoli

- **Rami**: main (produzione); si lavora su rami `feature/`, `fix/`, `hotfix/` con pull request.
- **Test**: prova manuale nel browser; nessuna suite automatica.
- **Produzione**: GitHub Pages dal ramo `main`; nessun ambiente di test separato.
- **Dati**: Firebase Realtime Database, Auth e Storage (configurazione nel file `index.html` e nella console Firebase).
- **Backup**: export del Realtime Database dalla console Firebase (nessuno script nel repository).

Regole: nessuna modifica diretta alla produzione; PR e controlli prima del rilascio. Se un ambiente di test
separato non esiste, va creato solo con una decisione di Andrea (account e costi).
