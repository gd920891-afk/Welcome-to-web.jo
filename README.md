<!DOCTYPE html>
<html lang="pt">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
body {
    margin: 0;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background: white;
    font-family: Arial, sans-serif;
}

.container {
    display: flex;
    gap: 15px;
}

button {
    border: none;
    width: 150px;
    height: 55px;
    border-radius: 8px;
    color: white;
    font-size: 18px;
    font-weight: bold;
    cursor: pointer;
}

.abrir {
    background: black;
}

.baixar {
    background: green;
}
</style>
</head>

<body>

<div class="container">

<button class="abrir"
onclick="window.open('pdf-readme-pdf.pdf', '_blank')">
Abrir
</button>

<a href="pdf-readme-pdf.pdf" download>
<button class="baixar">
Baixar
</button>
</a>

</div>

</body>
</html>
