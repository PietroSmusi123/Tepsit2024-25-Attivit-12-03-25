# Tepsit2024-25-Attivit-12-03-25

HelloWeb - Progetto Maven

  Descrizione del Progetto
Il progetto HelloWeb ha le seguenti funzionalità principali:

Pagina di Benvenuto (index.jsp):

Quando un utente visita la pagina principale (index.jsp), viene visualizzato il messaggio:
Benvenuto Utente Curioso, questo è la mia prima JSP. Oggi è il giorno <data>
Autore: <link>
Dove:
<data> è la data corrente (data di visita).
<link> è un collegamento a una pagina chiamata author.jsp che mostra i dettagli dell'autore.
Pagina dell'Autore (author.jsp):

La pagina author.jsp visualizza le informazioni dell'autore, incluse:
Nome
Cognome
Classe dell'autore
API REST:

È presente una API REST che risponde alla richiesta /api/test/eleonora con un messaggio predefinito.
Componenti Utilizzati
Maven:

Maven è stato utilizzato come sistema di gestione dei progetti. Tutte le dipendenze sono state gestite tramite il file pom.xml.
JSP (JavaServer Pages):

La pagina index.jsp è una JSP che genera il contenuto dinamico (data corrente e messaggio di benvenuto).
API REST:

L'API REST /api/test/eleonora è implementata come una servlet che gestisce le richieste GET.
