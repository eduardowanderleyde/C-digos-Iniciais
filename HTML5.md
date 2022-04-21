<!DOCTYPE html>
<html lang="pt-br">

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>Unicap Vídeos com HTML5</title>

</head>

<body style="background-color: yellow; font-family: Arial, Helvetica, sans-serif; font-size:20px;">
  
<h1 style="color:medium-blue; background-color: dodgerblue; font-size:1.5em;">Capítulo 1 </h1>
  
<h2 style="color:darkred; font-size:1.2em;">Capítulo 1.1</h2>
  
<p style="text-align:justify;"> Lasauhsasjidasjdia</p>
<h2 style="color:darkred; font-size:1.2em;">Capítulo 1.2</h2>

<p style="text-align:justify;"> Lasauhsasjidasjdia</p>
<h1 style="color:medium-blue; background-color: dodgerblue; font-size:1.5em;">Capítulo 2 </h1>
<h2 style="color:darkred; font-size:1.2em;">Capítulo 2.1</h2>
<p style="text-align:justify;"> Lasauhsasjidasjdia</p>

  
<hr> </h1><a href="pag2.html" rel="next" target="_self"> Clique para pag2</a>

  <p>Selecione qual capítulo você quer:</p>

<form action="/action_page.php">
  <label for="capitulos">Escolha o capitulo:</label>
  <select name="capitulos" id="capitulos">
    <optgroup label="Capitulos 1 ou 2">
      <option value="cap1">Capitulo 1</option>
      <option value="cap2">Capitulo 2</option>
    </optgroup>
    <optgroup label="Capitulo 3 ou 4">
      <option value="cap3">Capitulo 3</option>
      <option value="cap4">Capitulo 4</option>
    </optgroup>
  </select>
  <br><br>
  <input type="submit" value="Submit">
</form>
</body>

</html>
