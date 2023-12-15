## Sumário
- [Bootstrap](#bootstrap)
    - [Por que usar Bootstrap?](#por-que-usar-bootstrap)
    - [Como usar o Bootstrap?](#como-usar-o-bootstrap)
        - [Diferença entre o Bootstrap normal e o minificado](#diferença-entre-o-bootstrap-normal-e-o-minificado)
    - [Breakpoints](#breakpoints)
    - [Formatação de texto](#formatação-de-texto)
        - [Cabeçalhos](#cabeçalhos)
        - [Texto de destaque](#texto-de-destaque)
        - [Texto em monotipo](#texto-em-monotipo)
        - [Classes de estilo](#classes-de-estilo)
        - [Texto de alinhamento](#texto-de-alinhamento)
        - [Texto de citação](#texto-de-citação)
        - [Truncar texto](#truncar-texto)
    - [Alinhamento](#alinhamento)
        - [Texto Justificado](#texto-justificado)
        - [Alinhamento Responsivo](#alinhamento-responsivo)
        - [Display](#display)
    - [Cores](#cores)

# Bootstrap
Bootstrap é um framework front-end que facilita a criação de sites responsivos e mobile-first. Ele é composto por um conjunto de classes CSS e, em alguns casos, JavaScript, que definem a aparência e o comportamento de diversos elementos HTML.

## Por que usar Bootstrap?
O Bootstrap é um dos frameworks front-end mais populares da web. Ele é fácil de usar e possui uma grande comunidade de desenvolvedores que contribuem para o seu crescimento. Além disso, ele é compatível com os principais navegadores e possui um sistema de grid responsivo que facilita a criação de layouts para desktops, tablets e smartphones.

- Melhora a velocidade de desenvolvimento
- Assegura a responsividade
- Prevente repetições entre projetos
- Adiciona consistencia
- Assegura compatibilitade entre navegadores
- grande comunidade
- constumizavel

## Como usar o Bootstrap?
Para usar o Bootstrap, você precisa adicionar o seu arquivo CSS e, em alguns casos, o seu arquivo JavaScript no seu documento HTML. Você pode fazer isso de duas maneiras:

- Baixando os arquivos CSS e JavaScript do Bootstrap e adicionando-os ao seu projeto
- Usando um CDN (Content Delivery Network) para adicionar os arquivos CSS e JavaScript do Bootstrap ao seu projeto

### Diferença entre o Bootstrap normal e o minificado
Diferença entre o bootstrap normal e o mim: O conteudo é o mesmo mas o mom não possuim espaços em branco( ). Por causa disso ele carrega mais rapido.

## Breakpoints
Breakpoints são os pontos de interrupção que definem o comportamento do layout em diferentes tamanhos de tela. O Bootstrap possui 5 breakpoints:

- Extra small (xs): < 576px
- Small (sm): >= 576px
- Medium (md): >= 768px
- Large (lg): >= 992px
- Extra large (xl): >= 1200px

Como o Bootstrap é mobile-first, o seu grid é baseado no breakpoint extra small. Isso significa que, se você não definir um breakpoint, o grid será aplicado para telas menores que 576px.

Para uma melhor noção do tamanho de cada breakpoint, Aqui um exemplo de dispositivo para cada breakpoint:

- Extra small (xs): smartphones
- Small (sm): tablets
- Medium (md): laptops
- Large (lg): desktops
- Extra large (xl): desktops grandes

## Formadação de texto

### Cabeçalhos
No bootstrap é possivel mudar uma tag para que ela se torne um cabeçalho. Para isso basta adicionar a classe .h1, .h2, .h3, .h4, .h5 ou .h6.

Ele tambem possui a classe .display-1, .display-2, .display-3, .display-4 que são cabeçalhos com tamanhos maiores.

### Texto de destaque
Para destacar um texto basta adicionar a classe .lead.

### Texto em monotipo
Um texto de monotipo é um texto que possui a mesma largura para todos os caracteres. Para isso basta adicionar a classe .text-monospace.

### Classes de estilo
O bootstrap possui classes para estilizar textos. São elas:

- fw-bold: deixa o texto em negrito
- fw-normal: deixa o texto normal
- fst-italic: deixa o texto em italico
- fst-normal: deixa o texto normal
- fw-semibold: deixa o texto semi-negrito
- fw-medium: deixa o texto com a fonte média
- fw-light: deixa o texto com a fonte leve
- fw-lighter: deixa o texto com a fonte mais leve
- fw-bolder: deixa o texto com a fonte mais negrito

- text-lowercase: deixa o texto em caixa baixa
- text-uppercase: deixa o texto em caixa alta
- text-capitalize: deixa a primeira letra de cada palavra em caixa alta

### Texto de alinhamento
Para alinhar um texto basta adicionar a classe .text-start, .text-center, .text-end.

- text-start: alinha o texto a esquerda
- text-center: alinha o texto ao centro
- text-end: alinha o texto a direita

### Texto de citação
Para criar um texto de citação basta adicionar a tag <blockquote> e classe .blockquote.

Se quiser adicionar um rodapé a citação basta adicionar a tag <footer> e classe .blockquote-footer.

### Truncar texto
Um texto truncado é um texto que possui um limite de caracteres. Para isso basta adicionar a classe .text-truncate.

## Alinhamento

### Texto Justificado
Um texto justificado é um texto que possui o mesmo tamanho de margem a esquerda e a direita. Para isso basta adicionar a classe .text-justify.

### Alinhamento Responsivo
Para alinhar um texto de forma responsiva basta adicionar a classe .text-{breakpoint}-{start|center|end}.

Exemplo:
```html
<p class="text-sm-start">Texto alinhado a esquerda em telas pequenas</p>
<p class="text-md-center">Texto alinhado ao centro em telas médias</p>
<p class="text-lg-end">Texto alinhado a direita em telas grandes</p>
```

### Display
O display é uma propriedade CSS que define como um elemento HTML deve ser exibido. O Bootstrap possui classes para alterar o display de um elemento HTML. São elas:

- d-{value}: define o display do elemento HTML
- d-{breakpoint}-{value}: define o display do elemento HTML para um breakpoint específico

Os valores que podem ser usados são:

- none: não exibe o elemento HTML
- inline: exibe o elemento HTML como um elemento inline
- inline-block: exibe o elemento HTML como um elemento inline-block
- block: exibe o elemento HTML como um elemento block
- table: exibe o elemento HTML como uma tabela
- table-cell: exibe o elemento HTML como uma célula de tabela
- table-row: exibe o elemento HTML como uma linha de tabela
- flex: exibe o elemento HTML como um flex container

Exemplo:
```html
<div class="d-none">Não exibe o elemento</div>
<div class="d-inline">Exibe o elemento como um elemento inline</div>
<div class="d-inline-block">Exibe o elemento como um elemento inline-block</div>
<div class="d-block">Exibe o elemento como um elemento block</div>
<div class="d-table">Exibe o elemento como uma tabela</div>
<div class="d-table-cell">Exibe o elemento como uma célula de tabela</div>
<div class="d-table-row">Exibe o elemento como uma linha de tabela</div>
<div class="d-flex">Exibe o elemento como um flex container</div>
```

## Cores
O Bootstrap possui classes para alterar a cor de um elemento HTML. São elas:

- text-{value}: define a cor do texto
- bg-{value}: define a cor do background

Os valores que podem ser usados são:

- primary: define a cor como primária
- secondary: define a cor como secundária
- success: define a cor como sucesso
- danger: define a cor como perigo
- warning: define a cor como aviso
- info: define a cor como informação
- light: define a cor como claro
- dark: define a cor como escuro
- white: define a cor como branco
- transparent: define a cor como transparente

Exemplo:
```html
<p class="text-primary">Texto com a cor primária</p>
<p class="bg-primary">Background com a cor primária</p>
```

