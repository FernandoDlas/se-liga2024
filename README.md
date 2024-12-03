<!DOCRYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta nome="viewpot" content="width=device-width, initial-scale=1.0">
  <title>cálculo de média de notas</title>
  <link rel="stylesheet" href="styles.css">
</head>
<boby>
  <div class="container">
    <h1>calculadora de média de notas</h1>

    <form id="formulario">
      <label for="nota1" class="label">Nota do 1 trimestre:</label>
      <input type="number" id="nota1 class="input" required>
    
      <label for="nota2" class="label">nota do 2 trimestre:</label>
      <input type="number" id="nota2" class="input" required>

      <label for="nota3" class="label">nota do 3 Trimestre:</label>
      <input type="number" id="nota3" class="input" required>

      <button type="submit" id="calcular" class="botao">Calcular</button>
    </form>

    <div id="resultado" class="resultado">
     <!--Resultado será exibido aqui-->
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html>