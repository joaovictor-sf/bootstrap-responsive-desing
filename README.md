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
    - [Elementos Flutuantes](#elementos-flutuantes)
    - [Posicionamento](#posicionamento)
    - [Margin e Padding](#margin-e-padding)
    - [Tamanho](#tamanho)
    - [Bordas](#bordas)
        - [Estilos de borda](#estilos-de-borda)
        - [Arredondamento de borda](#arredondamento-de-borda)

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

Também é possível alterar o tom(opacidade) da cor. Para isso basta adicionar o sufixo -{value} ao nome da cor. Os valores que podem ser usados são:

- 50: define o tom 50 da cor
- 100: define o tom 100 da cor
- 200: define o tom 200 da cor

Exemplo:
```html
<p class="text-primary-50">Texto com o tom 50 da cor primária</p>
<p class="bg-primary-100">Background com o tom 100 da cor primária</p>
```

## Elementos Flutuantes
O Bootstrap possui classes para alinhar elementos HTML. São elas:

- float-{value}: define o alinhamento do elemento HTML
- float-{breakpoint}-{value}: define o alinhamento do elemento HTML para um breakpoint específico

Os valores que podem ser usados são:

- start: alinha o elemento HTML a esquerda
- end: alinha o elemento HTML a direita
- none: não alinha o elemento HTML

O Bootstrap também possui classes para limpar o alinhamento de elementos HTML. São elas:

- clearfix: limpa o alinhamento de elementos HTML
- clearfix-{breakpoint}: limpa o alinhamento de elementos HTML para um breakpoint específico

Exemplo:
```html
<div class="clearfix">
    <div class="float-start">Alinha o elemento a esquerda</div>
    <div class="float-end">Alinha o elemento a direita</div>
    <div class="float-none">Não alinha o elemento</div>
</div>
```

## Posicionamento
O Bootstrap possui classes para posicionar elementos HTML. São elas:

- position-static: posiciona o elemento HTML de forma estática
- position-relative: posiciona o elemento HTML de forma relativa
- position-absolute: posiciona o elemento HTML de forma absoluta
- position-fixed: posiciona o elemento HTML de forma fixa
- position-sticky: posiciona o elemento HTML de forma sticky

O Bootstrap também possui classes para posicionar elementos HTML em relação a um breakpoint específico. São elas:

- position-{breakpoint}-static: posiciona o elemento HTML de forma estática para um breakpoint específico
- position-{breakpoint}-relative: posiciona o elemento HTML de forma relativa para um breakpoint específico
- position-{breakpoint}-absolute: posiciona o elemento HTML de forma absoluta para um breakpoint específico
- position-{breakpoint}-fixed: posiciona o elemento HTML de forma fixa para um breakpoint específico
- position-{breakpoint}-sticky: posiciona o elemento HTML de forma sticky para um breakpoint específico

Exemplo:
```html
<div class="position-static">Posiciona o elemento de forma estática</div>
<div class="position-relative">Posiciona o elemento de forma relativa</div>
<div class="position-absolute">Posiciona o elemento de forma absoluta</div>
<div class="position-fixed">Posiciona o elemento de forma fixa</div>
<div class="position-sticky">Posiciona o elemento de forma sticky</div>
```

## Margin e Padding
O Bootstrap possui classes para definir a margem e o padding de um elemento HTML. São elas:

- m-{value}: define a margem de um elemento HTML
- p-{value}: define o padding de um elemento HTML

Ultilizar apenas m ou p irá definir a margem ou o padding para todos os lados. Para definir a margem ou o padding para um lado específico, basta adicionar o sufixo -{side} ao nome da classe. Os lados que podem ser usados são:

- t: define a margem ou o padding para o topo
- b: define a margem ou o padding para a base
- s: define a margem ou o padding para os lados
- e: define a margem ou o padding para a esquerda
- x: define a margem ou o padding para os lados
- y: define a margem ou o padding para o topo e a base

Exemplo:
```html
<div class="mt-2">Define a margem como 0.5rem</div>
<div class="pb-3">Define o padding como 1rem</div>
<div class="px-4">Define a margem ou o padding como 1.5rem</div>
```

Os valores que podem ser usados são:

- 0: define a margem ou o padding como 0
- 1: define a margem ou o padding como 0.25rem
- 2: define a margem ou o padding como 0.5rem
- 3: define a margem ou o padding como 1rem
- 4: define a margem ou o padding como 1.5rem
- 5: define a margem ou o padding como 3rem
- auto: define a margem ou o padding como auto

Exemplo:
```html
<div class="m-0">Define a margem como 0</div>
<div class="p-1">Define o padding como 0.25rem</div>
```

O Bootstrap também possui classes para definir a margem e o padding de um elemento HTML em relação a um breakpoint específico. São elas:

- m-{breakpoint}-{value}: define a margem de um elemento HTML para um breakpoint específico
- p-{breakpoint}-{value}: define o padding de um elemento HTML para um breakpoint específico

Exemplo:
```html
<div class="m-sm-0">Define a margem como 0 para telas pequenas</div>
<div class="p-md-1">Define o padding como 0.25rem para telas médias</div>
```

## Tamanho
O Bootstrap possui classes para definir o tamanho de um elemento HTML. São elas:

- w-{value}: define a largura de um elemento HTML
- h-{value}: define a altura de um elemento HTML

Os valores que podem ser usados são:

- 25: define a largura ou a altura como 25%
- 50: define a largura ou a altura como 50%
- 75: define a largura ou a altura como 75%
- 100: define a largura ou a altura como 100%
- auto: define a largura ou a altura como auto

Exemplo:
```html
<div class="w-25">Define a largura como 25%</div>
<div class="h-50">Define a altura como 50%</div>
```

O Bootstrap também possui classes para definir o tamanho de um elemento HTML em relação a um breakpoint específico. São elas:

- w-{breakpoint}-{value}: define a largura de um elemento HTML para um breakpoint específico
- h-{breakpoint}-{value}: define a altura de um elemento HTML para um breakpoint específico

## Bordas
O Bootstrap possui classes para definir a borda de um elemento HTML. São elas:

- border: define a borda de um elemento HTML
- border-{side}: define a borda de um elemento HTML para um lado específico
- border-{side}-{breakpoint}: define a borda de um elemento HTML para um lado específico e um breakpoint específico

Os lados que podem ser usados são:

- top: define a borda para o topo
- bottom: define a borda para a base
- start: define a borda para a esquerda
- end: define a borda para a direita

Exemplo:
```html
<div class="border">Define a borda para todos os lados</div>
<div class="border-top">Define a borda para o topo</div>
<div class="border-bottom">Define a borda para a base</div>
<div class="border-start">Define a borda para a esquerda</div>
<div class="border-end">Define a borda para a direita</div>
```

O Bootstrap também possui classes para definir a cor da borda de um elemento HTML. São elas:

- border-{color}: define a cor da borda de um elemento HTML
- border-{color}-{side}: define a cor da borda de um elemento HTML para um lado específico
- border-{color}-{side}-{breakpoint}: define a cor da borda de um elemento HTML para um lado específico e um breakpoint específico

Os valores que podem ser usadadas são as classes de cores do Bootstrap.

Exemplo:
```html
<div class="border-primary">Define a cor da borda como primária</div>
<div class="border-top-secondary">Define a cor da borda para o topo como secundária</div>
```

O Bootstrap também possui classes para definir o estilo da borda de um elemento HTML. São elas:

- border-{style}: define o estilo da borda de um elemento HTML
- border-{style}-{side}: define o estilo da borda de um elemento HTML para um lado específico
- border-{style}-{side}-{breakpoint}: define o estilo da borda de um elemento HTML para um lado específico e um breakpoint específico

### Estilos de borda

Os valores que podem ser usados são:

- solid: define o estilo da borda como sólido
- dashed: define o estilo da borda como tracejado
- dotted: define o estilo da borda como pontilhado
- double: define o estilo da borda como duplo
- none: define o estilo da borda como nenhum

Exemplo:
```html
<div class="border-solid">Define o estilo da borda como sólido</div>
<div class="border-top-dashed">Define o estilo da borda para o topo como tracejado</div>
```

O Bootstrap também possui classes para definir a largura da borda de um elemento HTML. São elas:

- border-{width}: define a largura da borda de um elemento HTML
- border-{width}-{side}: define a largura da borda de um elemento HTML para um lado específico
- border-{width}-{side}-{breakpoint}: define a largura da borda de um elemento HTML para um lado específico e um breakpoint específico

Os valores que podem são as classes de tamanho do Bootstrap.

Exemplo:
```html
<div class="border-1">Define a largura da borda como 0.25rem</div>
<div class="border-top-2">Define a largura da borda para o topo como 0.5rem</div>
```

### Arredondamento de borda

No Bootstrap, também é possível definir o raio(arredondamento) da borda de um elemento HTML. Para isso, basta adicionar a classe .rounded. Os valores que podem ser usados são:

- rounded: define o raio da borda como 0.25rem
- rounded-{value}: define o raio da borda como um valor específico
- rounded-{side}-{value}: define o raio da borda para um lado específico como um valor específico
- rounded-{side}-{breakpoint}-{value}: define o raio da borda para um lado específico como um valor específico e um breakpoint específico

Os tipos de arrredondamento que podem ser usados são:

- top: define o raio da borda para o topo
- bottom: define o raio da borda para a base
- start: define o raio da borda para a esquerda
- end: define o raio da borda para a direita
- circle: define o raio da borda como um círculo
- pill: define o raio da borda como uma pílula

Exemplo:
```html
<div class="rounded">Define o raio da borda como 0.25rem</div>
<div class="rounded-1">Define o raio da borda como 0.5rem</div>
<div class="rounded-top-2">Define o raio da borda para o topo como 1rem</div>
```
