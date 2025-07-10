# Attributi

Gli attributi sono informazioni aggiuntive che si mettono dentro un tag HTML per modificarne il comportamento o aggiungere dettagli.

📌 Gli attributi sono sempre scritti dentro il tag di apertura, nella forma:

```html
nomeAttributo="valore"
```

📘 Esempi comuni

🔹 1. href nell’<a> (collegamento)

```html
<a href="https://www.google.com">Vai su Google</a>
```

➡️ `href` indica dove porta il link

🔹 2. src e alt nell’<img>

```html
<img src="https://placehold.co/150x150" alt="Descrizione dell'immagine" />
```

`src`: percorso dell'immagine

`alt`: testo alternativo per l'accessibilità (letto da screen reader)

🔹 3. type e placeholder negli `<input>`

```html
<input type="text" placeholder="Inserisci il tuo nome" />
```

`type`: tipo di campo (es. testo, password, email…)

`placeholder`: testo che appare dentro il campo finché non scrivi

🔹 4. `class` e `id` per il CSS o JavaScript

```html
<p class="evidenziato">Questo paragrafo ha una classe.</p>
```

`class`: usata per applicare uno stile con il CSS

`id`: identificatore unico (utile per link interni o JS)

## Esercizio

📝 Crea una pagina HTML intitolata “Chi sono” in cui racconti qualcosa su di te. Usa i tag HTML per organizzare le informazioni nel modo più chiaro possibile.
Se vuoi una linea guida, puoi seguire questo schema:

```
- Titolo principale: Chi sono
- Aggiungi un’immagine che ti rappresenta (oppure, se non hai idee, usa un’immagine generica https://placehold.co/150x150)
- Elenca le tue passioni e per ognuna di esse aggiungi un link a wikipedia (ad esempio, se ti piace la musica, linka alla pagina di Wikipedia sulla musica).  
  - Plus: fai in modo che il link si apra in una nuova scheda del browser.
```   