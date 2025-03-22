## Getting Started

Welcome to the VS Code Java world. Here is a guideline to help you get started to write Java code in Visual Studio Code.

## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

> If you want to customize the folder structure, open `.vscode/settings.json` and update the related settings there.

## Dependency Management

The `JAVA PROJECTS` view allows you to manage your dependencies. More details can be found [here](https://github.com/microsoft/vscode-java-dependency#manage-dependencies).

# ATM (Sportello bancomat)
Realizzare un'applicazione che simuli uno sportello bancomat (ATM).
Le operazioni saranno rese possibili dopo l'inserimento di un codice conto (p.es.: 12345) e di un PIN (p.es.: 12345). Dopo aver inserito queste credenziali si avrà accesso alle seguenti operazioni:
-  prelievo (min 20/ max 500 Euro), il prelievo sarà possibile solo se la disponibilità sul conto è sufficiente
-  deposito (qualunque cifra)
-  bonifico: ovvero il trasferimento di un importo su un altro conto
-  ogni operazione prevede la "stampa" di una ricevuta con i dati relativi all'operazione effettuata
-  dopo ogni operazione dovrà essere aggiornato il saldo sul conto
-  utilizzare una classe ContoCorrente: ogni istanza della classe avrà un codice univoco , un PIN di sblocco delle operazioni e un saldo in Euro.
## Opzionale
  Consentire la gestione di più conti (inizialmente i dati relativi ai conti sono caricati da un file di testo)
