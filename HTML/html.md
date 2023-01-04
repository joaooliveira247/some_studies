# HTML

HTML (HyperText Markup Language) é uma linguagem de marcação utilizada para criar páginas da web. Ela fornece uma forma de descrever a estrutura de informações baseadas em texto em um documento, denotando certos textos como títulos, parágrafos, listas, links, citações e outros tipos de conteúdo.

O HTML é escrito sob a forma de elementos HTML, que consistem em tags incluídas em colchetes angulares (como <html>). As tags HTML são usadas para criar documentos HTML e são utilizadas para descrever o conteúdo da página da web.

## Tags

As tags HTML são elementos que formam os componentes de um documento HTML. Cada tag geralmente consiste em um termo entre < e >, e pode incluir atributos adicionais para fornecer mais informações sobre o elemento. Por exemplo:

```html
<tag attribute="value">Content</tag>
```

Algumas tags comuns incluem:

```html
- <p>: define um parágrafo
- <br>: adiciona uma quebra de linha
- <img>: insere uma imagem
- <div>: define uma divisão ou seção em um documento
- <a>: define um link para outro documento ou para uma localização em um mesmo documento
```

Há muitas outras tags disponíveis em HTML, cada uma com um propósito específico. Quando um navegador da web lê um documento HTML, ele interpreta as tags e as usa para exibir o conteúdo da página da web de maneira apropriada.

### *Exemplo*

Aqui está um exemplo de uma página HTML básica:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My Website</title>
  </head>
  <body>
    <h1>Welcome to my website!</h1>
    <p>Here you will find all sorts of interesting information about me and my hobbies.</p>
    <ul>
      <li>Hiking</li>
      <li>Cooking</li>
      <li>Reading</li>
    </ul>
    <p>Check out my <a href="/blog">blog</a> for more updates.</p>
  </body>
</html>
```

Este código cria uma página com um título "Welcome to my website!", um parágrafo de introdução e uma lista de itens. Ele também inclui um link para um blog. Quando essa página é carregada em um navegador da web, o conteúdo será exibido de acordo com as tags HTML.
