# portfolio01
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Survey Form</title>
  </head>
 <body>
  <h1 id="title">Survey Form</h1>
    <p id="description">Grazie per dedicare del tempo a fornire il tuo feedback. Le tue risposte ci aiuteranno a migliorare i nostri servizi.</p>
  
  <form id="survey-form">

      <label id="name-label" for="name">Nome</label>

     <input type="text" id="name" name="name" placeholder="Digita qui il tuo nome"    required>
     
      <label id="email-label" for="email">Email</label>
     
      <input type="email" id="email" name="email" placeholder="Ex.Mario.Rossi@gmail.com"required>

     
     
      <label id="number-label" for="number">Eta'(opzionale)</label>
  <input type="number" id="number" min="3" max="100"name="age"placeholder="Eta'">
  <label for="dropdown">Qual'e' la tua mansione?</label>
  <select id="dropdown" name="lavoro" required>
    <option value=""disabled selected hidden>Seleziona la tua mansione</option>
    <option value="Impiegato">Impiegato</option>
    <option value="Cuoco">Cuoco</option>
    <option value="Indipendente">Indipendente</option>
 
    </select>
    <p>
    <fieldset>
    <legend>Qual'e' il tuo livello di soddisfazione?</legend>
    <label>
      <input type="radio" name="soddisfazione" value="molto soddisfatto"required>Molto Soddisfatto</label>
     <label>
        <input type="radio" name="soddisfazione" value="soddisfatto">Soddisfatto</label>
      <label>
      <input type="radio" name="soddisfazione" value="Insoddisfatto">Insoddisfatto</label>

    </fieldset>
    </p>


    <p>
  <legend>Cosa hai apprezzato della tua esperienza?</leged><br>

    <label>
  <input type="checkbox" name="Ospitalita" value="Ospitalita">Ospitalita'</label>

  <label>
  <input type="checkbox" name="supporto allo studio" value="supporto allo studio">Supporto allo studio</label>

  <label>
  <input type="checkbox" name="materiale didattico" value="materiale didattico">Materiale Didattico</label>
 </p>
   <label for"commenti">Hai altri consigli o commenti?</label><br>
    <textarea name="commenti" id="commenti" placeholder="aggiungi i tuoi commenti">
 </textarea>
   
  <button type="submit" id="submit">Invia</button>
   </form>
  </body>
 
</html>
