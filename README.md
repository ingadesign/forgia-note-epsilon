# Forgia Note Epsilon

Strumento per il vault Obsidian **Epsilon System**: incolli una pagina di regole D&D 5.5 (classe, sottoclasse, talento, background, incantesimo, specie) e la Forgia la trasforma in note `.md` nel formato del vault, con collegamenti `[[…]]` automatici e un JSON da importare nella scheda online.

## Come si usa
1. Apri `index.html` nel browser (doppio clic, non serve installare niente).
2. Incolla la pagina in **Incolla tutto** → **Crea le note**.
3. Controlla l'anteprima, poi **Scarica le note (.zip)**.
4. Trascina la cartella dello zip nel vault (es. `Bard/` dentro `Dm Rules/Classi`). Se esiste già: tieni premuto ⌥ Option e scegli **Unisci**, mai «Sostituisci».
5. Il file `… - regole per la scheda.json` si carica nella scheda con **Importa regole custom**.

## Note
- Tutto avviene nel browser: il testo incollato non viene inviato da nessuna parte.
- Bozze, lista e impostazioni dei collegamenti restano nel `localStorage` del browser.
- I testi delle regole non fanno parte di questo repository.
- Regole del progetto: `docs/` e `AGENTS.md` nel vault Epsilon_System.
