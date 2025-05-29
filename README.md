## 📝 Códigos Principais

### `index.html` (Estrutura HTML)

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tecnologias no Agro: Do Campo à Cidade</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Tecnologias que Conectam o Campo e a Cidade</h1>
        <p>Descubra como a inovação no agronegócio chega até a sua mesa.</p>
    </header>

    <main class="gallery-container">
        <div class="gallery-item">
            <img src="" alt="Trator com tecnologia GPS">
            <div class="description">
                <h3>Agricultura de Precisão</h3>
                <p>Tratores equipados com GPS otimizam o plantio e a colheita...</p>
            </div>
        </div>
        </main>

    <footer>
        <p>&copy; 2024 Agrinho - Do Campo à Cidade.</p>
    </footer>
</body>
</html>
style.css (Estilização CSS)
CSS

/* Estilos Gerais */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #28a745; /* Verde Agrinho */
    color: white;
    padding: 20px 0;
    text-align: center;
}

/* Galeria de Imagens */
.gallery-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 25px;
    padding: 30px;
    max-width: 1200px;
    margin: 30px auto;
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
}

.gallery-item {
    background-color: #fff;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease-in-out;
}

.gallery-item img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.gallery-item .description {
    padding: 15px;
    text-align: center;
}

/* Responsividade Básica */
@media (max-width: 768px) {
    .gallery-container {
        grid-template-columns: 1fr;
    }
}.