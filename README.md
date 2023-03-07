# virtualCoffee
Virtual coffee SQL server

Es.1

- webapi (normale oppure minimal)

- elenco di utenti (tabella Users) - indirizzo email (key) | Nome | Cognome | isActive 

- api per la registrazione dell'utente (POST -> che riceve un utente) verifica se email esiste già
	-> esiste: ritorni BadRequest()
	-> non esiste: ritorni un Ok
	
- api ritorna tutti gli utenti attivi (isActive a true)
- api ritorna tutti gli utente anche quelli non attivi 

- api che permette di modificare il nome e cognome dell'utente

- api delete non cancella l'utente ma imposta il flag isActive a false
