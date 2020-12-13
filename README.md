# Project Work Ristorante

   1. Tecnologie utilizzate

	
    • Database MySql vers. 8.
    • WebServer Tomcat 9.
    • Java JDK 8.
    • Servlet/Jsp
    • Web Service RestFul

   2. Struttura del Progetto
              
          L’applicazione verrà realizzata secondo il Pattern MVC
   3. Descrizione entità
	
    Le entità saranno le seguenti:
    1. Utente
    2. Menù
    3. Prenotazione
	
3.1. Utente

    • Id
    • username
    • password
    • email
    • ruolo

	Gli utenti saranno distinti per Ruolo fra Admin e User

3.2. Menù

    • Id
    • titolo
    • descrizione 
    • tipo cucina
    • costo
    • immagine(Opzionale)

3.3. Prenotazione

    • Id
    • Id utente
    • Data e ora di prenotazione
    • Quantità

4. Presentazione Ristorante Take Away
        
        In questa sezione verrà descritta la componente di View relativa al sito di un ristorante take away.

4.1. Pagine Pubbliche
	
    • Landing Page/ Registrazione
    • Login
    • Logout
	
4.1.1 Landing Page/Login

  
    La Landing Page presenterà una form di Login ed un link alla pagina di Registrazione

	  Una volta Loggato con successo l’utente verrà reindirizzato alla Home
4.1.2 Registrazione

	La Pagina di registrazione permetterà agli utenti di registrarsi.
	
	Una volta completata con successo la registrazione l’utente verrà reindirizzato home.
		
	
4.2. Pagine Private

    • Home 
    • Listino Menù
    • Aggiungi Menù
    • Modifica Menù
    • Listino Prenotazioni
    • Gestione Utenti
    • Aggiungi Utente

4.1.1 Home

	Nella Home Page verranno presentate le prime 5 Categorie di cibo recuperate da una specifica API

		Documentazione:

		https://www.themealdb.com/api.php

		Api specifica:

	
    https://www.themealdb.com/api/json/v1/1/categories.php
	

	  Saranno presenti inoltre i link alle seguenti pagine:

	Utente:
	
	
    • Listino Menù
    • Listino Prenotazioni

	Admin:

    • Listino Menù
    • Gestione Utenti
4.1.2 Listino Menù

	Nella Pagina Listino Menù verrà visualizzata una tabella con tutte le info relative ai menù registrati nel sistema

	(Opzionale) Il listino menù potrà essere ordinato per costo, titolo e tipo cucina
	
	L’admin oltre a visualizzare le informazioni legate ai menù, potrà modificare o 	cancellare ogni singolo record tramite apposite CTA all’interno della tabella.

	L’utente visualizzerà in pagina anche il link al listino prenotazioni

	L’admin visualizzerà in Pagina il link alla pagina di Aggiunta menù
4.1.3 Aggiungi Menù
	
	Form aggiunta Menù
4.1.4 Modifica Menù
	
	Form Modifica Menù
4.1.Listino prenotazioni

	Tabella con la lista delle prenotazioni effettuate dall’utente

	(Opzionale) La tabella sarà ordinata per data ordine
4.1.6 Gestione Utenti

	La Pagina Gestione Utenti presenterà una tabella con la lista degli Utenti.
	
	Sarà inoltre presente la CTA Aggiungi Utente
4.1.7 Aggiungi Utente
	    
      Form Aggiunta Utente

4.1.8 Logout

  
    In ogni pagina privata dovrà inoltre essere presente un pulsante di Logout.
    Alla avvenuta Logout l’utente verrà reindirizzato alla Landing Page/Registrazione. 
