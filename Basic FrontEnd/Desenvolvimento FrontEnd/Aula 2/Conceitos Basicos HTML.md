# Conceitos básicos do HTML

## O que é HTML

* Linguagem de Marcação de Hipertexto;

* Linguagem padrão criada para páginas da Web;

* Criada em 1991 pelo britânico Tim Berners-Lee e mantida pela W3C (World Wide Web Consortium);

* Decreve a estrutura básica do site;

* Consiste em uma série de elementos que informam ao navegador como exibir o conteúdo;

* O HTML através de seus elementos, define partes do conteúdo de uma página web indicando cada parte de sua estrutura como: "este é um título", "este é um parágrafo", " este é um link", etc. 

## Estutura básica de um código HTML

``` html

<!DOCTYPE html> <!-- Define que esse é um documento html  -->
<html lang="pt-br">  <!-- Define o idioma da página -->

<head> <!-- Dará informações para o navegador interpretar a página -->
    <meta charset="UTF-8">   <!-- Vai especificar a codificação de caracteres no documento, o "UTF-8" é o conjunto de carcteres universal -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">   <!-- Vai fornecer ao navegador instruções de como controlar e dimensionar, fazendo com que a página se adpte a tela de qualquer dispositivo -->
    <title>Document</title> <!-- Título da página -->
</head>

<body>  <!-- Onde fica todo o conteúdo visível da página  -->
    conteúdo
</body>

</html>
```
