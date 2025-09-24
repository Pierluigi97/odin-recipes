Incarico
Iterazione 1: struttura iniziale
All'interno della odin-recipesdirectory, creare un index.htmlfile.
Compilalo con il consueto codice HTML e aggiungi l' h1intestazione "Ricette Odin" al corpo.
Iterazione 2: pagina della ricetta
Crea una nuova directory all'interno della odin-recipesdirectory e chiamala recipes.
Crea un nuovo file HTML all'interno della recipesdirectory e assegnagli il nome della ricetta che conterrà. Ad esempio lasagna.html, puoi usare il nome del tuo piatto preferito o, se hai bisogno di ispirazione, puoi trovare una ricetta da usare su Allrecipes . Assicurati di includere il consueto codice HTML boilerplate. Questo codice boilerplate dovrebbe essere presente in ogni .htmlfile che crei.
Per ora, includi semplicemente un h1titolo con il nome della ricetta come contenuto.
Tornando al index.htmlfile, aggiungi un link alla pagina della ricetta che hai appena creato. Esempio: sotto l' <h1>Odin Recipes</h1>intestazione, scrivi il link in questo modo: <a href="recipes/recipename.html">Recipe Title</a>. Il testo del link dovrebbe essere ancora una volta il nome della ricetta.
Aggiungi un link alla pagina indice nella pagina delle tue ricette per una navigazione più semplice. Puoi posizionare questo link in cima o in fondo alla pagina delle tue ricette (ad esempio, lasagna.html). Ecco un esempio:

<a href="../index.html">Home</a>
Ciò consente agli utenti di tornare rapidamente alla home page dopo aver visualizzato la ricetta.

Iterazione 3: contenuto della pagina della ricetta
La tua nuova pagina di ricette dovrebbe contenere il seguente contenuto:

Un'immagine gratuita del piatto finito sotto l'intestazione h1 che hai aggiunto in precedenza.

Sotto l'immagine dovrebbe esserci un titolo "Descrizione" di dimensioni appropriate, seguito da uno o due paragrafi che descrivono la ricetta.

Sotto la descrizione, aggiungi la dicitura "Ingredienti" seguita da un elenco non ordinato degli ingredienti necessari per la ricetta.

Infine, sotto l'elenco degli ingredienti, aggiungi la dicitura "Passaggi" seguita da un elenco ordinato dei passaggi necessari per preparare il piatto.

Iterazione 4: aggiungere altre ricette
Aggiungi altre due ricette con strutture di pagina identiche alla pagina della ricetta che hai già creato.
Non dimenticare di linkare le nuove ricette nella pagina indice. Inoltre, potresti mettere tutti i link in un elenco non ordinato, in modo che non siano tutti sulla stessa riga.
Esempio:

 <ul>
    <li><a href="recipes/yourrecipe.html">Recipe Title 1</a></li>
    <li><a href="recipes/yourrecipe.html">Recipe Title 2</a></li>
    <li><a href="recipes/yourrecipe.html">Recipe Title 3</a></li>
  </ul>
I tuoi link non saranno appariscenti, ma per ora concentrati solo sulla loro realizzazione.
