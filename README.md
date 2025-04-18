<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>MG Personalización</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #2c3e50;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .productos {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
    }
    .producto {
      background: white;
      border: 1px solid #ccc;
      border-radius: 10px;
      width: 300px;
      margin: 10px;
      padding: 15px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .producto img {
      max-width: 100%;
      border-radius: 10px;
    }
    form {
      margin-top: 10px;
    }
    label, input, textarea {
      display: block;
      width: 100%;
      margin-bottom: 10px;
    }
    button {
      background-color: #2980b9;
      color: white;
      padding: 10px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #3498db;
    }
  </style>
</head>
<body>

  <header>
    <h1>MG Personalización</h1>
    <p>Productos únicos, hechos a tu medida</p>
  </header>

  <section class="productos">

    <div class="producto">
      <img src="camiseta.jpg" alt="Camiseta personalizada">
      <h2>Camiseta personalizada</h2>
      <form>
        <label for="nombre1">Nombre o texto</label>
        <input type="text" id="nombre1" placeholder="Tu texto aquí">

        <label for="imagen1">Subir imagen (opcional)</label>
        <input type="file" id="imagen1">

        <button type="submit">Personalizar</button>
      </form>
    </div>

    <div class="producto">
      <img src="taza.jpg" alt="Taza personalizada">
      <h2>Taza personalizada</h2>
      <form>
        <label for="nombre2">Nombre o texto</label>
        <input type="text" id="nombre2" placeholder="Tu texto aquí">

        <label for="imagen2">Subir imagen (opcional)</label>
        <input type="file" id="imagen2">

        <button type="submit">Personalizar</button>
      </form>
    </div>

  </section>

</body>
</html>
