# Forms

Un form (modulo) è una sezione di una pagina web che permette all’utente di inserire dei dati e inviarli.
Esempi comuni:

- Modulo di contatto
- Iscrizione a una newsletter
- Login
- Registrazione

## 🔧 Struttura base di un form

```html
<form action="pagina-di-destinazione" method="post">
  <!-- Campi input -->
</form>
```

- `<form>` è il contenitore del modulo
- `action` indica dove vengono inviati i dati
- `method="post"` o `"get"` specifica come vengono inviati

| Tag                                  | Cosa fa                                             |
| ------------------------------------ | --------------------------------------------------- |
| `<input>`                            | Campo di inserimento (testo, email, password, ecc.) |
| `<label>`                            | Etichetta per descrivere il campo                   |
| `<textarea>`                         | Area di testo multi-riga                            |
| `<select>` e `<option>`              | Menu a tendina                                      |
| `<button>` o `<input type="submit">` | Pulsante per inviare                                |

## Esercizio: Crea un modulo di contatto

Completa il seguente codice HTML per creare un modulo di contatto. Aggiungi i campi richiesti e assicurati di usare i tag appropriati.

Usa mdn per cercare i tag che ti servono e vedere come si usano: [MDN Web Docs](https://developer.mozilla.org/it/)

```html
<!DOCTYPE html>
<html lang="it">
  <head>
    <meta charset="UTF-8" />
    <title>Modulo di Contatto</title>
  </head>
  <body>
    <h1>Contattami</h1>

    <form method="post">
      <!-- Qui dovrebbe esserci un'etichetta per il campo "Nome" usando il tag <label> -->
      <!-- Qui dovrebbe esserci un campo di input per il testo del "Nome" usando il tag <input type="text"> -->
      <br /><br />

      <!-- Qui dovrebbe esserci un'etichetta per il campo "Email" usando il tag <label> -->
      <!-- Qui dovrebbe esserci un campo di input per l'email usando il tag <input type="email"> -->
      <br /><br />

      <!-- Qui dovrebbe esserci un'etichetta per il campo "Messaggio" usando il tag <label> -->
      <!-- Qui dovrebbe esserci un'area di testo multilinea per il "Messaggio" usando il tag <textarea> -->
      <br /><br />

      <!-- Qui dovrebbe esserci un'etichetta per il campo "Motivo del contatto" -->
      <!-- Qui dovrebbe esserci un menu a discesa per il "Motivo del contatto" usando il tag <select> -->
      <!-- All'interno del <select>, dovrebbero esserci le opzioni usando il tag <option> -->
      <!-- Esempio di opzione: <option value="info">Richiesta informazioni</option> -->
      <!-- Esempio di opzione: <option value="aiuto">Richiesta di supporto</option> -->
      <!-- Esempio di opzione: <option value="altro">Altro</option> -->
      <br /><br />

      <!-- Qui dovrebbe esserci un pulsante per inviare il modulo usando il tag <input type="submit"> -->
    </form>
  </body>
</html>
```
