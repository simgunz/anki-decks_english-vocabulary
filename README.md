# Anki Vocabulary

Note: la nota è una collezione di fatti (proprietà). Esempio: un Paese da studiare, con tutte le sue info 
Campi: parti della nota (esempio bandiera, valuta, capitale) 
Tipo di nota: es geografia, vocabolario 
Carte: un modo specifico di presentare la nota, ci possono essere più carte per una nota 
Tipo di carta: struttura della carta specifica (es, vedo bandiera, devo ricordare il nome del paese). Ha un template front e un template back. Template sono HTML, fanno riferimento ai campi della nota. 
Tag: etichetta che si può dare ad ogni carta (es. livello A1, livello A2 ecc)

## Workflow

1. Git Synchronization
   ```
   git pull
   ```

2. Note Addition
   - Add notes

3. Anki Export
   - Export using crowdanki

4. Git Update
   ```
   git push
   ```

## How to insert new notes
+ Add a `draft` tag

## Tags

| Tag   | Meaning                                                      |
| ----- | ------------------------------------------------------------ |
| draft | The note is not ready to be studied. Some important fields are missing. |

