
# Tutorial: Criando uma Página HTML Com a lista de liguaguens mais utilizadas

Neste tutorial, vou mostrar a você como criar uma página HTML simples para exibir uma lista de liguaguens mais utilizadas. O código HTML que você forneceu é uma estrutura de exemplo que pode ser usada como ponto de partida.

## Pré-requisitos

Antes de começar, certifique-se de ter um editor de texto, como o Visual Studio Code, Sublime Text ou qualquer outro de sua escolha, instalado em seu computador.

### Passo 1: Estrutura Básica do HTML

O código começa com a estrutura básica do HTML, incluindo a declaração do tipo de documento, o elemento `<html>`, o elemento `<head>`, e o elemento `<body>`.

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <!-- Meta tags e título da página -->
    <title>Ranqueamento de Linguagens de Programação</title>
    <!-- Inclusão de estilos CSS no <head> -->
</head>
<body>
    <!-- Conteúdo da página vai aqui -->
</body>
</html>
```

### Passo 2: Adicionar Estilos CSS

Os estilos CSS são incluídos no arquivo `style.css` do documento. Esses estilos definem a formatação visual da página, como fonte, cores, largura da tabela, estilos das células e outras propriedades.

```css
    body {
        font-family: Arial, sans-serif;
        text-align: center;
    }

    h1 {
        color: #333;
    }

    table {
        width: 80%;
        margin: 0 auto;
        border-collapse: collapse;
        border: 1px solid #333;
    }

    th, td {
        padding: 10px;
        text-align: left;
    }

    th {
        background-color: #333;
        color: #fff;
    }

    tr:nth-child(even) {
        background-color: #f2f2f2;
    }

    tr:nth-child(odd) {
        background-color: #fff;
    }

    img {
        max-width: 100px;
    }

    iframe {
        width: 100%;
        height: 200px;
    }
```

### Passo 3: Conteúdo da Página

Dentro do `<body>`, é onde o conteúdo da página é adicionado. No exemplo, há um título `<h1>` e uma tabela que lista as linguagens de programação. Cada linha da tabela contém a posição, o logotipo da linguagem, uma descrição e um vídeo incorporado.

```html
<body>
    <h1>Linguagens de Programação Mais Usadas</h1>
    <table border="1">
        <tr>
            <th>Posição</th>
            <th>Logo da Linguagem</th>
            <th>Descrição</th>
            <th>Vídeo</th>
        </tr>
        <tr>
            <td>1</td>
            <td><img src="logo1.png" alt="Logo da Linguagem 1"></td>
            <td>Linguagem de Programação 1 é uma linguagem muito popular.</td>
            <td><iframe src="https://www.youtube.com/embed/VIDEO_ID_1" frameborder="0" allowfullscreen></iframe></td>
        </tr>
        <tr>
            <!-- Repita esta estrutura para cada linguagem -->
        </tr>
    </table>
</body>
```

### Passo 4: Personalização

Personalize o conteúdo da tabela, incluindo o nome das linguagens, descrições, URLs de imagem e IDs de vídeo. Você pode adicionar mais linhas à tabela para listar mais linguagens de programação.

### Passo 5: Visualize no Navegador

Salve o arquivo HTML com uma extensão .html e abra-o em um navegador para ver como a tabela de ranqueamento de linguagens de programação é exibida.

Este é um exemplo simples de como criar uma tabela HTML com estilos CSS incorporados para apresentar informações de ranqueamento. Você pode personalizar ainda mais o estilo e o conteúdo de acordo com suas necessidades.
