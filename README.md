## Bulk renamer

### Piccolo script per rinominare fotografie

Creare la sottodirectory "origin" e caricare al suo interno tutte le foto.

Caricare nella directory principale un file "report.xlsx" contenente la prima colonna con l'elenco dei cognomi.

Installare l'unico modulo aggiuntivo necessario, es. con pipenv:
    
    pipenv install openpyxl

Lanciare lo script:

    python main.py

Ogni file corrispondente a un cognome più lungo di tre lettere verrà rinominato.
La tabella di conversione sarà scritta nel file "origin\log.txt".


