<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>WEB.JO DIGITAL</title>

    <style>
        body {
            margin: 0;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: white;
            font-family: Arial, sans-serif;
        }

        .buttons {
            display: flex;
            gap: 20px;
        }

        .btn {
            width: 150px;
            padding: 18px 0;
            text-align: center;
            text-decoration: none;
            color: white;
            font-size: 18px;
            font-weight: bold;
            border-radius: 8px;
            cursor: pointer;
        }

        .abrir {
            background: #000000;
        }

        .baixar {
            background: #008000;
        }

        .btn:hover {
            opacity: 0.85;
        }
    </style>
</head>

<body>

    <div class="buttons">

        <!-- ABRIR PDF -->
        <a class="btn abrir"
           href="pdf-readme-pdf.pdf"
           target="_blank">
            Abrir
        </a>

        <!-- BAIXAR PDF -->
        <a class="btn baixar"
           href="pdf-readme-pdf.pdf"
           download>
            Baixar
        </a>

    </div>

</body>
</html>
