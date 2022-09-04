# Acessibilidade Web - Parte 1: Tornando seu Front-end Inclusivo

Curso da Alura sobre técnicas de acessibilidade no código HTML e CSS.

## Objetivo Final &#x1F3AF;

Criar um site acessível utilizando as tags e atributos corretos.

URL do curso -> [Acessibilidade Web - Parte 1: Tornando seu Front-end Inclusivo](https://cursos.alura.com.br/course/acessibilidade-web-front-end)

![Acessibilidade Web - Parte 1: Tornando seu Front-end Inclusivo](https://www.alura.com.br/assets/api/share/curso-acessibilidade-web-front-end.png)

## Links Úteis &#x1F517;
* [WebAIM](https://webaim.org/projects/screenreadersurvey7/) - Link estatístico sobre leitores de tela em cada navegador.
* [NVDA](https://www.nvaccess.org/) - Site oficial do software da NVDA, que é um dos leitores de tela mais utilizados.
* [Arquivos Base](https://github.com/designernatan/curso-acessibilidade-web-front-end-1/archive/14e5c4ffd5f7f6d767c8a88e88659f5cec5eb253.zip) - Arquivos base usados para o projeto.
* [Atalhos NVDA](https://webaim.org/resources/shortcuts/nvda) - Todos os atalhos do software do NVDA.

## Siglas &#x1F5FA;
* NVDA - **N**on**V**isual **D**esktop **A**ccess.

## Atalhos &#x2328;
* *h* - O leitor de tela vai ler os cabeçalhos da página.
    * *SHIFT* + *h* - Ler a hierarquia anterior do título atual.
* *k* - Ler link seguinte.
    * *SHIFT* + *k* - Ler o link anterior.
* *g* - Ler próxima imagem do site.
    * *SHIFT* + *g* - Ler a imagem anterior.
* *l* - Navega pelas listas no site.

## 01 - HTML e os Leitores de Tela &#x1F516;
* Tomar cuidado com a marcação de conteúdo quando estamos utilizando elementos HTML5. Vale mais por uma `<div>` do que usar um `<aside>` ou `<details>` erroneamente.
* O melhor caminho para deixar nosso projeto inclusivo não é apenas seguir regras e *guidelines*, mas testá-las por conta para começarmos a compreender os caminhos e dificuldades que muitas pessoas podem ter ao usar nosso produto e/ou serviço. Empatia.
* Evitar mais de um `<H1>` na página.

### 01 - Vários h1s na mesma Página
* Mudar a ordem de precedência dos títuls da página.
* Atalhos para navegar pela página do site usando o software do **NVDA**.

***

## 02 - Atributos lang e alt &#x1F516;
* `alt` nas imagens que possuem função de conteúdo.
* Escrever o `alt` de maneira descritiva, evitando redundâncias.
* Configurar o idioma principal do documento com o atributo `lang`.
* Colocar o elemento `<title>` em SVGs que forem inline (código direto no HTML).

### 01 - Cuidados com o Sotaque
* Definir o atributo `lang` para frases em outros idiomas.

### 02 - Textos Alternativos
* Colocar descrições nas imagens de forma direta.

### 03 - Alt e titles
* Diferença entre o `alt` e o `title`.
* Colocar descrições em **svg's**.

### 04 - Melhorando o alt
* Descrever melhor o valor do `alt`.
* Adicionar um `alt` sem valor para o leitor de leta ignorar.

***

## 03 - CSS Interfere no Leitor de Tela ou Não &#x1F516;
* Como o CSS impacta no leitor de tela.
* Propriedades CSS para esconder elementos visualmente da tela.

### 01 - Listas para Todos
* O CSS interfere no leitor de tela.

### 02 - Escondido Demais
* Esconder elementos visualmente do site sem interferir no leitor de tela.

***

## 04 - Um Pouco sobre roles e arias &#x1F516;
* Atribuir papeis específicos para um elemento no HTML.

### 01 - Pular Navegação
* Criar um link para o usuário ir para o conteúdo principal.
* Esconder visualmente o link para o conteúdo principal.

### 02 - facilitando para Outros Leitores
* Usar o atributo `role` para mudar o papel de um elemento HTML.

### 03 - Uma Ponta do WAI ARIA
* Fazer o leitor de tela não ter uma redundância ao ler o conteúdo que contem uma imagem.