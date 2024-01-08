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
    - [Botões](#botões)
        - [Cores disponiveis](#cores-disponiveis)
        - [Tamanhos disponiveis](#tamanhos-disponiveis)
        - [Estados disponiveis](#estados-disponiveis)
        - [Grupos de botões](#grupos-de-botões)
            - [Botões com dropdown](#botões-com-dropdown)
            - [Botões com radio ou checkbox](#botões-com-radio-ou-checkbox)
    - [Navegação](#navegação)
        - [Alinhamento](#alinhamento-1)
        - [Orientação](#orientação)
        - [Variante](#variante)
        - [Fill e Justify](#fill-e-justify)
    - [Barra de navegação](#barra-de-navegação)
        - [Conteudo](#conteudo)
        - [Posicionamento](#posicionamento-1)
        - [Scrolling](#scrolling)
        - [Toggler](#toggler)
        - [Dropdown](#dropdown)
        - [Formulário](#formulário)
        - [Textos](#textos)
        - [Offcanvas](#offcanvas)
    - [Formulários](#formulários)
        - [Formulários básicos](#formulários-básicos)
        - [Select](#select)
        - [Range](#range)
        - [Tamanho](#tamanho-1)
        - [Checkboxes e radios](#checkboxes-e-radios)
        - [Switches](#switches)
        - [Grupo de inputs](#grupo-de-inputs)
    - [Alertas](#alertas)
        - [Fechar](#fechar)
        - [Links](#links)
    - [Barra de progresso](#barra-de-progresso)
        - [Tamanho](#tamanho-2)
        - [Cor](#cor)
        - [Label](#label)
        - [Múltiplas barras](#múltiplas-barras)
    - [Tabelas](#tabelas)
        - [Cores de fundo](#cores-de-fundo)
        - [Table group dividers](#table-group-dividers)
        - [Tabelas responsivas](#tabelas-responsivas)
    - [Paginação](#paginação)
        - [Tamanho](#tamanho-3)
        - [Com icons](#com-icons)
        - [Alinhamento](#alinhamento-2)
    - [Cartões](#cartões)
        - [Título e texto](#título-e-texto)
        - [Links](#links-1)
        - [Imagem](#imagem)
            - [Imagem com overlay](#imagem-com-overlay)
        - [Cartões de cabeçalho e rodapé](#cartões-de-cabeçalho-e-rodapé)
        - [Grupos de cartões](#grupos-de-cartões)
    - [Icones](#icones)
    - [Layouts](#layouts)
        - [Container](#container)
        - [Grid](#grid)
            - [Tamanho](#tamanho-4)
            - [Alinhamentos](#alinhamento-3)
                - [Vertical](#vertical)
                - [Horizontal](#horizontal)
            - [Ordem](#ordem)
            - [Offset](#offset)
            - [Colunas em uma linha](#colunas-em-uma-linha)
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

## Botões
O Bootstrap possui classes para estilizar botões. São elas:

- btn: define o estilo do botão
- btn-{color}: define a cor do botão
- btn-{size}: define o tamanho do botão
- btn-{outline}: define o botão como outline(transparente com borda)
- btn-{block}: define o botão como block

### Cores disponiveis
Pode ultilizar as classes do bootstrap para definir a cor e o tamanho do botão.

Exemplo:
```html
<button class="btn btn-primary">Botão primário</button>
<button class="btn btn-secondary">Botão secundário</button>
<button class="btn btn-success">Botão de sucesso</button>
<button class="btn btn-danger">Botão de perigo</button>
<button class="btn btn-warning">Botão de aviso</button>
<button class="btn btn-info">Botão de informação</button>
<button class="btn btn-light">Botão claro</button>
<button class="btn btn-dark">Botão escuro</button>
<button class="btn btn-white">Botão branco</button>
<button class="btn btn-transparent">Botão transparente</button>
```

### Tamanhos disponiveis
Exemplo:
```html
<button class="btn btn-sm">Botão pequeno</button>
<button class="btn btn-md">Botão médio</button>
<button class="btn btn-lg">Botão grande</button>
```

### Estados disponiveis
É possivel definir o botão como active, disabled ou focus. Para isso basta adicionar a classe .active, .disabled ou .focus.
Active: deixa o botão com a cor primaria. Pode ser ultilizado para indicar qual aba está selecionada.
Disabled: deixa o botão desabilitado. Pode ser ultilizado para indicar que o botão não pode ser clicado.
Focus: deixa o botão com uma borda azul. Pode ser ultilizado para indicar que o botão está selecionado.

Exemplo:
```html
<button class="btn btn-primary active">Botão primário</button>
<button class="btn btn-primary disabled">Botão primário</button>
<button class="btn btn-primary focus">Botão primário</button>
```

Tambem é possivel ultilizar o data-bs-toggle="button" para criar um botão que alterna entre ativo e inativo.

### Grupos de botões
Ultizando a classe .btn-group é possivel agrupar botões.

Exemplo:
```html
<div class="btn-group">
    <button class="btn btn-primary">Botão primário</button>
    <button class="btn btn-primary">Botão primário</button>
    <button class="btn btn-primary">Botão primário</button>
</div>
```

Tambem é possivel agrupar botões verticalmente. Para isso basta adicionar a classe .btn-group-vertical.

Exemplo:
```html
<div class="btn-group-vertical">
    <button class="btn btn-primary">Botão primário</button>
    <button class="btn btn-primary">Botão primário</button>
    <button class="btn btn-primary">Botão primário</button>
</div>
```

Outra forma de agrupar botões é utilizando a classe .btn-toolbar. Ela agrupa os botões horizontalmente e adiciona uma margem entre eles.

Exemplo:
```html
<div class="btn-toolbar">
    <div class="btn-group me-2">
        <button class="btn btn-primary">Botão primário</button>
        <button class="btn btn-primary">Botão primário</button>
        <button class="btn btn-primary">Botão primário</button>
    </div>
    <div class="btn-group me-2">
        <button class="btn btn-primary">Botão primário</button>
        <button class="btn btn-primary">Botão primário</button>
        <button class="btn btn-primary">Botão primário</button>
    </div>
    <div class="btn-group">
        <button class="btn btn-primary">Botão primário</button>
        <button class="btn btn-primary">Botão primário</button>
        <button class="btn btn-primary">Botão primário</button>
    </div>
</div>
```

#### Botões com dropdown
Tambem é possivel criar um grupo de botões com dropdown. Para isso basta adicionar a classe .btn-group e a classe .dropdown-toggle.

Exemplo:
```html
<div class="btn-group">
    <button class="btn btn-primary">Botão primário</button>
    <button class="btn btn-primary">Botão primário</button>
    <button class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown"></button>
    <ul class="dropdown-menu">
        <li><a href="#" class="dropdown-item">Item 1</a></li>
        <li><a href="#" class="dropdown-item">Item 2</a></li>
        <li><a href="#" class="dropdown-item">Item 3</a></li>
    </ul>
</div>
``` 

#### Botões com radio ou checkbox
Tambem é possivel criar grupos de botões com radio ou checkbox. Para isso basta adicionar a classe .btn-group e a classe .btn-check.

Exemplo:
```html
<div class="btn-group">
    <input type="radio" name="btn-radio" id="btn-radio-1" class="btn-check">
    <label for="btn-radio-1" class="btn btn-primary">Botão primário</label>
    <input type="radio" name="btn-radio" id="btn-radio-2" class="btn-check">
    <label for="btn-radio-2" class="btn btn-primary">Botão primário</label>
    <input type="radio" name="btn-radio" id="btn-radio-3" class="btn-check">
    <label for="btn-radio-3" class="btn btn-primary">Botão primário</label>
</div>
```

## Navegação
O Bootstrap possui classes para estilizar a navegação. São elas:

- nav: define o estilo da navegação
- nav-{type}: define o tipo da navegação
- nav-{type}-{color}: define a cor da navegação
- nav-{type}-{size}: define o tamanho da navegação
- nav-{type}-{fill}: define a navegação como fill(ocupando todo o espaço disponível)
- nav-{type}-{justify}: define a navegação como justify(distribuindo os itens igualmente)
- nav-{type}-{orientation}: define a orientação da navegação
- nav-{type}-{variant}: define a variante da navegação

Os tipos que podem ser usados são:

- nav: define o tipo da navegação como tabs
- nav-pills: define o tipo da navegação como pills
- nav-tabs: define o tipo da navegação como tabs
- nav-underlines: define o tipo da navegação como underlines

Exemplo:
```html
<ul class="nav nav-pills">
    <li class="nav-item"><a href="#" class="nav-link">Link 1</a></li>
    <li class="nav-item"><a href="#" class="nav-link">Link 2</a></li>
    <li class="nav-item"><a href="#" class="nav-link">Link 3</a></li>
</ul>
```

As cores que podem ser usadas são as classes de cores do Bootstrap.

### Alinhamento
Para alinhar a navegação, basta adicionar a classe .justify-content-{value}. Os valores que podem ser usados são:

- start: alinha a navegação a esquerda
- center: alinha a navegação ao centro
- end: alinha a navegação a direita
- around: distribui os itens igualmente com espaços iguais entre eles
- between: distribui os itens igualmente com espaços maiores entre eles
- evenly: distribui os itens igualmente com espaços iguais entre eles

Exemplo:
```html
<ul class="nav nav-pills justify-content-start">
    <li class="nav-item"><a href="#" class="nav-link">Link 1</a></li>
    <li class="nav-item"><a href="#" class="nav-link">Link 2</a></li>
    <li class="nav-item"><a href="#" class="nav-link">Link 3</a></li>
</ul>
```

### Orientação
Para definir a orientação da navegação, basta adicionar a classe .flex-{value}. Os valores que podem ser usados são:

- row: define a orientação da navegação como horizontal
- column: define a orientação da navegação como vertical

Exemplo:
```html
<ul class="nav nav-pills flex-row">
    <li class="nav-item"><a href="#" class="nav-link">Link 1</a></li>
    <li class="nav-item"><a href="#" class="nav-link">Link 2</a></li>
    <li class="nav-item"><a href="#" class="nav-link">Link 3</a></li>
</ul>
```

### Variante
Para definir a variante da navegação, basta adicionar a classe .nav-{variant}. Os valores que podem ser usados são:

- nav-{variant}: define a variante da navegação como default
- nav-{variant}-light: define a variante da navegação como light
- nav-{variant}-dark: define a variante da navegação como dark

Exemplo:
```html
<ul class="nav nav-pills nav-light">
    <li class="nav-item"><a href="#" class="nav-link">Link 1</a></li>
    <li class="nav-item"><a href="#" class="nav-link">Link 2</a></li>
    <li class="nav-item"><a href="#" class="nav-link">Link 3</a></li>
</ul>
```

As variantes servem para definir a cor do texto e do background da navegação.

### Fill e Justify
Para definir a navegação como fill ou justify, basta adicionar a classe .nav-{fill} ou .nav-{justify}.

Exemplo:
```html
<ul class="nav nav-tabs nav-fill">
    <li class="nav-item"><a href="#" class="nav-link">Link 1</a></li>
    <li class="nav-item"><a href="#" class="nav-link">Link 2</a></li>
    <li class="nav-item"><a href="#" class="nav-link">Link 3</a></li>
</ul>
```

Fill faz com que os itens da navegação ocupem todo o espaço disponível. Justify faz com que os itens da navegação sejam distribuídos igualmente.

## Barra de navegação
Para criar uma barra de navegação, basta adicionar a classe .navbar. Para definir a cor da barra de navegação, basta adicionar a classe .navbar-{color}. As cores que podem ser usadas são as classes de cores do Bootstrap.

Exemplo:
```html
<nav class="navbar navbar-primary"></nav>
```

### Conteudo
Navbar podem conter links, textos e formulários. Algumas classes podem ser usadas para estilizar esses elementos. São elas:

- navbar-brand: define o estilo do link da marca
- navbar-text: define o estilo do texto
- navbar-toggler: define o estilo do botão de toggle
- collapse.navbar-collapse: define o estilo do conteúdo que será escondido
- navbar-scroll: define o estilo da barra de rolagem

Exemplo:
```html
<nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Navbar</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Link</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Dropdown
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" aria-disabled="true">Disabled</a>
        </li>
      </ul>
      <form class="d-flex" role="search">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">Search</button>
      </form>
    </div>
  </div>
</nav>
```

### Posicionamento
Navbar podem ser posicionadas de 3 formas: fixed-top, fixed-bottom e sticky-top. Para isso, basta adicionar a classe .fixed-top, .fixed-bottom ou .sticky-top.

Exemplo:
```html
<nav class="navbar navbar-primary fixed-top"></nav>
```

### Scrolling
Navbar podem ser fixadas ou escondidas quando o usuário rolar a página. Para isso, basta adicionar a classe .navbar-scroll. Para definir o comportamento da barra de rolagem, basta adicionar a classe .navbar-scroll-{value}. Os valores que podem ser usados são:

- auto: define o comportamento da barra de rolagem como auto
- touch: define o comportamento da barra de rolagem como touch(oculta quando o usuário rolar a página)
- scroll: define o comportamento da barra de rolagem como scroll

Exemplo:
```html
<nav class="navbar navbar-primary navbar-scroll navbar-scroll-touch"></nav>
```

### Toggler
Navbar podem ser colapsadas em telas pequenas. Para isso, basta adicionar a classe .navbar-toggler. Para definir o comportamento do toggler, basta adicionar a classe .navbar-toggler-{value}. Os valores que podem ser usados são:

- expand: define o comportamento do toggler como expand
- collapse: define o comportamento do toggler como collapse

Exemplo:
```html
<nav class="navbar navbar-primary navbar-toggler navbar-toggler-expand"></nav>
```

Icones podem ser adicionados ao toggler. Para isso, basta adicionar a classe .navbar-toggler-icon.

Exemplo:
```html
<nav class="navbar navbar-primary navbar-toggler navbar-toggler-expand">
    <button class="navbar-toggler">
        <span class="navbar-toggler-icon"></span>
    </button>
</nav>
```

### Dropdown
Navbar podem conter dropdowns. Para isso, basta adicionar a classe .dropdown-menu ao elemento que será o dropdown. Para definir o comportamento do dropdown, basta adicionar a classe .dropdown-menu-{value}. Os valores que podem ser usados são:

- start: define o comportamento do dropdown como start
- end: define o comportamento do dropdown como end

Exemplo:
```html
<nav class="navbar navbar-primary">
    <div class="dropdown-menu dropdown-menu-start">
        <a href="#" class="dropdown-item">Item 1</a>
        <a href="#" class="dropdown-item">Item 2</a>
        <a href="#" class="dropdown-item">Item 3</a>
    </div>
</nav>
```

### Formulários
Navbar podem conter formulários. Para isso, basta adicionar a classe .navbar-form ao elemento que será o formulário.

Exemplo:
```html
<nav class="navbar navbar-primary">
    <form class="navbar-form">
        <input type="text" class="form-control">
        <button class="btn btn-primary">Enviar</button>
    </form>
</nav>
```

### Textos
Navbar podem conter textos. Para isso, basta adicionar a classe .navbar-text ao elemento que será o texto.

Exemplo:
```html
<nav class="navbar navbar-primary">
    <span class="navbar-text">Texto</span>
</nav>
```

### Offcanvas
Um offcanvas é um menu que aparece quando o usuário clica em um botão. Esse menu pode ser posicionado a esquerda ou a direita da página. Para criar um offcanvas, basta adicionar a classe .offcanvas. Para definir o posicionamento do offcanvas, basta adicionar a classe .offcanvas-{side}. Os lados que podem ser usados são:

- start: define o posicionamento do offcanvas a esquerda
- end: define o posicionamento do offcanvas a direita

Exemplo:
```html
<nav class="navbar navbar-primary">
    <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasNavbar" aria-controls="offcanvasNavbar" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="offcanvas offcanvas-start">
        <div class="offcanvas-header">
            <h5 class="offcanvas-title">Offcanvas</h5>
            <button class="btn-close" data-bs-dismiss="offcanvas" aria-label="Close"></button>
        </div>
        <div class="offcanvas-body">
            <ul class="navbar-nav">
                <li class="nav-item"><a href="#" class="nav-link">Link 1</a></li>
                <li class="nav-item"><a href="#" class="nav-link">Link 2</a></li>
                <li class="nav-item"><a href="#" class="nav-link">Link 3</a></li>
            </ul>
        </div>
    </div>
</nav>
```

Quando o usuário clicar no botão, o offcanvas será exibido. Para definir o comportamento do offcanvas, basta adicionar a classe .offcanvas-{value}. Os valores que podem ser usados são:

- show: define o comportamento do offcanvas como show
- hide: define o comportamento do offcanvas como hide

Quando se usa o offcanvas, é necessário adicionar o atributo data-bs-toggle="offcanvas" e o atributo data-bs-target="#{id}" ao botão que irá abrir o offcanvas. O atributo data-bs-target="#{id}" deve ter o mesmo valor do atributo id do offcanvas.

Se usado em uma navbar dark, você pode precisar adicionar a classes como: text-bg-dark, dropdown-menu-dark e bg-dark.

## Formulários

### Formulários básicos
As duas classes mais básicas para estilizar formulários são .form-control e .form-label. A classe .form-control estiliza os inputs e a classe .form-label estiliza as labels.

A classe .form-control tambem pode ser usada para estilizar selects, textareas e inputs com o atributo type="file".

Exemplo:
```html
<form>
    <div class="mb-3">
        <label for="input-1" class="form-label">Input 1</label>
        <input type="text" id="input-1" class="form-control">
    </div>
    <div class="mb-3">
        <label for="input-2" class="form-label">Input 2</label>
        <input type="text" id="input-2" class="form-control">
    </div>
    <div class="mb-3">
        <label for="input-3" class="form-label">Input 3</label>
        <input type="text" id="input-3" class="form-control">
    </div>
</form>
```

É possivel colocar o label flutuando sobre o input.

Exemplo:
```html
<form>
    <div class="form-floating mb-3">
        <input type="email" class="form-control" id="floatingInput" placeholder="name@example.com">
        <label for="floatingInput">Email address</label>
    </div>
</form>
```

Se voce quiser adicionar um texto de ajuda, basta adicionar a classe .form-text ao elemento que será o texto de ajuda.

Exemplo:
```html
<form>
    <div class="mb-3">
        <label for="input-1" class="form-label">Input 1</label>
        <input type="text" id="input-1" class="form-control">
        <span class="form-text">Texto de ajuda</span>
    </div>
</form>
```

### Select
Para estilizar um select, basta adicionar a classe .form-select.

Exemplo:
```html
<form>
    <label for="subject" class="form-label">Subject</label>
    <select name="subject" id="subject" class="form-select">
        <option value="pricing">Pricing</option>
        <option value="technical" selected>Technical</option>
        <option value="other">Other</option>
    </select>
</form>
```

Usando multiple, o select se torna um select de múltipla escolha e com o size você pode definir quantas opções serão exibidas ao mesmo tempo.


### Range
Para estilizar um range, basta adicionar a classe .form-range.

Exemplo:
```html
<form>
    <label for="range" class="form-label">Range</label>
    <input type="range" id="range" class="form-range">
</form>
```

### Tamanho
Para definir o tamanho de um input, basta adicionar a classe .form-control-{size}. Os tamanhos que podem ser usados são:

- sm: define o tamanho do input como small
- md: define o tamanho do input como medium
- lg: define o tamanho do input como large

Exemplo:
```html
<form>
    <input class="form-control form-control-lg" type="text" placeholder=".form-control-lg">
    <input class="form-control" type="text" placeholder="Default input">
    <input class="form-control form-control-sm" type="text" placeholder=".form-control-sm">
</form>
```

### Checkboxes e Radios
Se ultiliza de 3 classes para estilizar checkboxes e radios. São elas:

- .form-check: estiliza o container do checkbox ou radio
- .form-check-input: estiliza o input do checkbox ou radio
- .form-check-label: estiliza o label do checkbox ou radio

Exemplo:
```html
<div class="form-check">
    <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault">
    <label class="form-check-label" for="flexCheckDefault">
        Default checkbox
    </label>
</div>
```

Se desejar deixar o checkbox ou radio inline, basta adicionar a classe d-flex.

Exemplo:
```html
<h3 class="m-3">Inline</h3>
<div class="d-flex">
    <div class="form-check">
        <input class="form-check-input" type="checkbox" id="inlineCheckbox1" value="option1">
        <label class="form-check-label" for="inlineCheckbox1">1</label>
    </div>
    <div class="form-check ms-3">
        <input class="form-check-input" type="checkbox" id="inlineCheckbox2" value="option2">
        <label class="form-check-label" for="inlineCheckbox2">2</label>
    </div>
    <div class="form-check ms-3">
        <input class="form-check-input" type="checkbox" id="inlineCheckbox3" value="option3" disabled>
        <label class="form-check-label" for="inlineCheckbox3">3 (disabled)</label>
    </div>
</div>
```

Se quiser que eles fiquem reversos, basta adicionar a classe .form-check-reverse.

Exemplo:
```html
<div class="form-check form-switch form-check-reverse">
    <input class="form-check-input" type="checkbox" id="flexSwitchCheckReverse">
    <label class="form-check-label" for="flexSwitchCheckReverse">Reverse switch checkbox input</label>
</div>
```

### Switches
Para estilizar um switch, é necessário adicionar a classe .form-switch.

Exemplo:
```html
<div class="form-check form-switch">
  <input class="form-check-input" type="checkbox" role="switch" id="flexSwitchCheckDefault">
  <label class="form-check-label" for="flexSwitchCheckDefault">Default switch checkbox input</label>
</div>
```

### Grupo de inputs
Para agrupar inputs, basta adicionar a classe .input-group ao elemento que será o grupo. Para definir o tamanho do grupo, basta adicionar a classe .input-group-{size}. Os tamanhos que podem ser usados são:

- sm: define o tamanho do grupo como small
- lg: define o tamanho do grupo como large

Exemplo:
```html
<div class="input-group input-group-sm mb-3">
    <span class="input-group-text" id="inputGroup-sizing-sm">Small</span>
    <input type="text" class="form-control" aria-label="Sizing example input" aria-describedby="inputGroup-sizing-sm">
</div>
```

O input-group tambem pode conter um input-group-text. Que serve para adicionar um texto ao grupo.

## Alertas
Para criar um alerta, basta adicionar a classe .alert ao elemento que será o alerta. Para definir a cor do alerta, basta adicionar a classe .alert-{color}. As cores que podem ser usadas são as classes de cores do Bootstrap.

Exemplo:
```html
<div class="alert alert-primary">Alerta primário</div>
```

### Fechar
Para adicionar um botão de fechar ao alerta, basta adicionar o atributo data-bs-dismiss="alert" ao botão.

Exemplo:
```html
<div class="alert alert-primary alert-dismissible fade show">
    Alerta primário
    <button class="btn-close" data-bs-dismiss="alert"></button>
</div>
```

### Links
Para adicionar um link ao alerta, basta adicionar a classe .alert-link ao elemento que será o link.

Exemplo:
```html
<div class="alert alert-primary">
    Alerta primário
    <a href="#" class="alert-link">Link</a>
</div>
```

## Barra de progresso
Para criar uma barra de progresso, basta adicionar a classe .progress ao elemento que será a barra de progresso. Para definir o estilo da barra de progresso, basta adicionar a classe .progress-{style}. Os estilos que podem ser usados são:

- progress: define o estilo da barra de progresso como normal
- progress-striped: define o estilo da barra de progresso como striped
- progress-animated: define o estilo da barra de progresso como animated

Exemplo:
```html
<div class="progress">
    <div class="progress-bar" style="width: 25%"></div>
</div>
```

### Tamanho
Para definir o tamanho da barra de progresso, basta adicionar a classe .progress-{size}. Os tamanhos que podem ser usados são:

- sm: define o tamanho da barra de progresso como small
- lg: define o tamanho da barra de progresso como large

Exemplo:
```html
<div class="progress progress-sm">
    <div class="progress-bar" style="width: 25%"></div>
</div>
```

Você tambem pode definir o tamanho da barra de progresso modificando as propriedades width e height.

Exemplo:
```html
<div class="progress" style="height: 1px;">
    <div class="progress-bar" style="width: 25%"></div>
</div>
```

### Cor
Para definir a cor da barra de progresso, basta adicionar uma das classes de cores do Bootstrap.

Exemplo:
```html
<div class="progress">
    <div class="progress-bar bg-primary" style="width: 25%"></div>
</div>
```

### Label
Para adicionar um label a barra de progresso, basta adicionar a classe .progress-bar-label ao elemento que será o label.

Exemplo:
```html
<div class="progress">
    <div class="progress-bar" style="width: 25%">
        <span class="progress-bar-label">25%</span>
    </div>
</div>
```

### Múltiplas barras
Para criar múltiplas barras de progresso, basta adicionar multiplos elementos com a classe .progress-bar.

Exemplo:
```html
<div class="progress">
    <div class="progress-bar" style="width: 15%"></div>
    <div class="progress-bar bg-success" style="width: 30%"></div>
    <div class="progress-bar bg-info" style="width: 20%"></div>
</div>
```

## Tabelas
Para criar uma tabela, basta adicionar a classe .table ao elemento que será a tabela. Para definir o estilo da tabela, basta adicionar a classe .table-{style}. Os estilos que podem ser usados são:

- table: define o estilo da tabela como normal
- table-striped: faz com que as linhas da tabela sejam listradas
- table-striped-columns: faz com que as colunas da tabela sejam listradas
- table-bordered: faz com que a tabela tenha bordas
- table-borderless: faz com que a tabela não tenha bordas
- table-hover: faz com que as linhas da tabela mudem de cor quando o usuário passar o mouse sobre elas
- table-dark: define o estilo da tabela como dark
- table-sm: define o estilo da tabela como small

Exemplo:
```html
<table class="table table-striped table-bordered table-hover table-dark table-sm">
    <thead>
        <tr>
            <th>Nome</th>
            <th>Idade</th>
            <th>Sexo</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>João</td>
            <td>20</td>
            <td>Masculino</td>
        </tr>
        <tr>
            <td>Maria</td>
            <td>18</td>
            <td>Feminino</td>
        </tr>
        <tr>
            <td>José</td>
            <td>25</td>
            <td>Masculino</td>
        </tr>
    </tbody>
</table>
```

### Cores de fundo
Para definir a cor de fundo de uma linha, basta adicionar a classe .table-{color} ao elemento que será a linha. As cores que podem ser usadas são as classes de cores do Bootstrap.

Exemplo:
```html
<table class="table">
    <thead>
        <tr>
            <th>Nome</th>
            <th>Idade</th>
            <th>Sexo</th>
        </tr>
    </thead>
    <tbody>
        <tr class="table-primary">
            <td>João</td>
            <td>20</td>
            <td>Masculino</td>
        </tr>
        <tr class="table-secondary">
            <td>Maria</td>
            <td>18</td>
            <td>Feminino</td>
        </tr>
        <tr class="table-success">
            <td>José</td>
            <td>25</td>
            <td>Masculino</td>
        </tr>
    </tbody>
</table>
```

Se a tabela tiver bordas, a cor da borda será a mesma da cor de fundo. Para mudar a cor da borda, basta adicionar a classe .border-{color} ao elemento que será a linha.

### Table group dividers
Adicione uma borda mais espessa e mais escura entre os grupos de tabelas - &lt;thead>, &lt;tbody> e &lt;tfoot> - com .table-group-divider. Personalize a cor alterando o border-top-color.

Exemplo:
```html
<table class="table">
    <thead>
        <tr>
            <th>Nome</th>
            <th>Idade</th>
            <th>Sexo</th>
        </tr>
    </thead>
    <tbody class="table-group-divider">
        <tr>
            <td>João</td>
            <td>20</td>
            <td>Masculino</td>
        </tr>
        <tr>
            <td>Maria</td>
            <td>18</td>
            <td>Feminino</td>
        </tr>
        <tr>
            <td>José</td>
            <td>25</td>
            <td>Masculino</td>
        </tr>
    </tbody>
</table>
```

### Tabelas responsivas
Para criar uma tabela responsiva, basta adicionar a classe .table-responsive ao elemento que será a tabela.

Exemplo:
```html
<div class="table-responsive">
    <table class="table">
        <thead>
            <tr>
                <th>Nome</th>
                <th>Idade</th>
                <th>Sexo</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>João</td>
                <td>20</td>
                <td>Masculino</td>
            </tr>
            <tr>
                <td>Maria</td>
                <td>18</td>
                <td>Feminino</td>
            </tr>
            <tr>
                <td>José</td>
                <td>25</td>
                <td>Masculino</td>
            </tr>
        </tbody>
    </table>
</div>
```

Você tambem pode adicionar a classe .table-responsive-{breakpoint} para definir o comportamento da tabela em telas pequenas. Os breakpoints que podem ser usados são:

- sm: define o comportamento da tabela em telas pequenas como scroll
- md: define o comportamento da tabela em telas médias como scroll
- lg: define o comportamento da tabela em telas grandes como scroll
- xl: define o comportamento da tabela em telas extra grandes como scroll
- xxl: define o comportamento da tabela em telas extra extra grandes como scroll

## Paginação
Para criar uma paginação, basta adicionar a classe .pagination ao elemento que será a paginação.

Exemplo:
```html
<ul class="pagination">
    <li class="page-item"><a href="#" class="page-link">1</a></li>
    <li class="page-item"><a href="#" class="page-link">2</a></li>
    <li class="page-item"><a href="#" class="page-link">3</a></li>
</ul>
```

### Tamanho
Para definir o tamanho da paginação, basta adicionar a classe .pagination-{size}. Os tamanhos que podem ser usados são:

- sm: define o tamanho da paginação como small
- lg: define o tamanho da paginação como large

Exemplo:
```html
<ul class="pagination pagination-sm">
    <li class="page-item"><a href="#" class="page-link">1</a></li>
    <li class="page-item"><a href="#" class="page-link">2</a></li>
    <li class="page-item"><a href="#" class="page-link">3</a></li>
</ul>
```

### Com icons
Para adicionar icons a paginação, basta adicionar &-laquo; ou &-raquo; dentro do elemento que será o link.

Exemplo:
```html
<ul class="pagination">
    <li class="page-item"><a href="#" class="page-link">&laquo;</a></li>
    <li class="page-item"><a href="#" class="page-link">1</a></li>
    <li class="page-item"><a href="#" class="page-link">2</a></li>
    <li class="page-item"><a href="#" class="page-link">3</a></li>
    <li class="page-item"><a href="#" class="page-link">&raquo;</a></li>
</ul>
```

### Alinhamento
Para alinhar a paginação, basta adicionar a classe .justify-content-{value}. Os valores que podem ser usados são:

- start: alinha a paginação a esquerda
- center: alinha a paginação ao centro
- end: alinha a paginação a direita
- around: distribui os itens igualmente com espaços iguais entre eles
- between: distribui os itens igualmente com espaços maiores entre eles
- evenly: distribui os itens igualmente com espaços iguais entre eles

Exemplo:
```html
<ul class="pagination justify-content-center">
    <li class="page-item"><a href="#" class="page-link">&laquo;</a></li>
    <li class="page-item"><a href="#" class="page-link">1</a></li>
    <li class="page-item"><a href="#" class="page-link">2</a></li>
    <li class="page-item"><a href="#" class="page-link">3</a></li>
    <li class="page-item"><a href="#" class="page-link">&raquo;</a></li>
</ul>
```

## Cartões
Um cartão é um container flexível que pode conter quase qualquer conteúdo. Para criar um cartão, basta adicionar a classe .card ao elemento que será o cartão.

Exemplo:
```html
<div class="card">
    <div class="card-body">
        <h5 class="card-title">Título</h5>
        <p class="card-text">Texto</p>
    </div>
</div>
```

### Título e texto
Para adicionar um título ao cartão, basta adicionar a classe .card-title ao elemento que será o título. Para adicionar um texto ao cartão, basta adicionar a classe .card-text ao elemento que será o texto.

Exemplo:
```html
<div class="card">
    <div class="card-body">
        <h5 class="card-title">Título</h5>
        <p class="card-text">Texto</p>
    </div>
</div>
```

Se quiser acrescentar um subtítulo, basta adicionar a classe .card-subtitle ao elemento que será o subtítulo.

### Links
Para adicionar um link ao cartão, basta adicionar a classe .card-link ao elemento que será o link.

Exemplo:
```html
<div class="card">
    <div class="card-body">
        <h5 class="card-title">Título</h5>
        <p class="card-text">Texto</p>
        <a href="#" class="card-link">Link</a>
    </div>
</div>
```

### Imagem
Para adicionar uma imagem ao cartão, basta adicionar a classe .card-img-{position} ao elemento que será a imagem. As posições que podem ser usadas são:

- top: define a posição da imagem como top
- bottom: define a posição da imagem como bottom
- start: define que a imagem ficará a esquerda
- end: define que a imagem ficará a direita

Exemplo:
```html
<div class="card">
    <img src="https://picsum.photos/200/300" class="card-img-top" alt="...">
    <div class="card-body">
        <h5 class="card-title">Título</h5>
        <p class="card-text">Texto</p>
    </div>
</div>
```

#### Imagem com overlay
Para adicionar um overlay a imagem, basta adicionar a classe .card-img-overlay ao elemento que será o overlay.

Exemplo:
```html
<div class="card">
    <img src="https://picsum.photos/200/300" class="card-img-top" alt="...">
    <div class="card-img-overlay">
        <h5 class="card-title">Título</h5>
        <p class="card-text">Texto</p>
    </div>
</div>
```

### Cartões de cabeçalho e rodapé
Para criar um cartão de cabeçalho, basta adicionar a classe .card-header ao elemento que será o cabeçalho. Para criar um cartão de rodapé, basta adicionar a classe .card-footer ao elemento que será o rodapé.

Exemplo:
```html
<div class="card">
    <div class="card-header">
        Cabeçalho
    </div>
    <div class="card-body">
        <h5 class="card-title">Título</h5>
        <p class="card-text">Texto</p>
    </div>
    <div class="card-footer">
        Rodapé
    </div>
</div>
```

### Grupos de cartões
Para agrupar cartões, basta adicionar a classe .card-group ao elemento que será o grupo.

Exemplo:
```html
<div class="card-group">
  <div class="card">
    <img src="..." class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">Card title</h5>
      <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
    </div>
    <div class="card-footer">
      <small class="text-body-secondary">Last updated 3 mins ago</small>
    </div>
  </div>
  <div class="card">
    <img src="..." class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">Card title</h5>
      <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
    </div>
    <div class="card-footer">
      <small class="text-body-secondary">Last updated 3 mins ago</small>
    </div>
  </div>
  <div class="card">
    <img src="..." class="card-img-top" alt="...">
    <div class="card-body">
      <h5 class="card-title">Card title</h5>
      <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
    </div>
    <div class="card-footer">
      <small class="text-body-secondary">Last updated 3 mins ago</small>
    </div>
  </div>
</div>
```

## Icones
O Bootstrap possui uma biblioteca de icones chamada Bootstrap Icons. Existem 2 formas de usar os icones do Bootstrap Icons. A primeira é usando o Bootstrap Icons como uma fonte. Para isso, basta adicionar o seguinte link no head do seu documento HTML:

```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap-icons/1.5.0/font/bootstrap-icons.min.css">
```

A segunda forma é usando o Bootstrap Icons como um SVG. Para isso, basta adicionar o seguinte link no head do seu documento HTML:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.2/font/bootstrap-icons.min.css">
```

Para escolher um icone, basta acessar o site do Bootstrap Icons e escolher o icone que você deseja usar. Depois, basta copiar o código do icone e colar no seu documento HTML.

Exemplo:
```html
<i class="bi bi-alarm"></i>
```

## Layouts
O Bootstrap possui 2 layouts: flex e grid. O layout flex é usado para criar layouts simples e o layout grid é usado para criar layouts mais complexos.

### Container
Um container é um elemento que contém os elementos da página. Para criar um container, basta adicionar a classe .container ao elemento que será o container.

Exemplo:
```html
<div class="container">
    <h1>Container</h1>
</div>
```

Um container pode ser implementado de 3 formas: container, container-fluid e container-{breakpoint}.

- container: define o container que se ajusta a largura de telas pequenas
- container-fluid: define que o container ocupe toda a largura da tela
- container-{breakpoint}: define o container que se ajusta a largura que você definir

### Grid
O grid é um sistema de 12 colunas que pode ser usado para criar layouts mais complexos.

Uma grid é composta por 3 elementos: container, row(linha) e col(coluna).

Exemplo:
```html
<div class="container">
    <div class="row">
        <div class="col">
            <h1>Coluna 1</h1>
        </div>
        <div class="col">
            <h1>Coluna 2</h1>
        </div>
        <div class="col">
            <h1>Coluna 3</h1>
        </div>
    </div>
</div>
```

Uma row pode ter no máximo 12 colunas. Se você adicionar mais de 12 colunas em uma row, as colunas que não couberem na row irão para a linha de baixo.

#### Tamanho
Para definir o tamanho de uma coluna, basta adicionar a classe .col-{size} ao elemento que será a coluna. Os tamanhos que podem são os numeros de 1 a 12.

Exemplo:
```html
<div class="container">
    <div class="row">
        <div class="col-6">
            <h1>Coluna 1</h1>
        </div>
        <div class="col-3">
            <h1>Coluna 2</h1>
        </div>
        <div class="col-3">
            <h1>Coluna 3</h1>
        </div>
    </div>
</div>
```

Você tambem pode definir o tamanho que uma coluna terá em um determinado breakpoint. Para isso, basta adicionar a classe .col-{breakpoint}-{size} ao elemento que será a coluna.

Exemplo:
```html
<div class="container">
    <div class="row">
        <div class="col-6 col-md-3">
            <h1>Coluna 1</h1>
        </div>
        <div class="col-3 col-md-6">
            <h1>Coluna 2</h1>
        </div>
        <div class="col-3 col-md-3">
            <h1>Coluna 3</h1>
        </div>
    </div>
</div>
```

Ao ultilizar um breakpoint, por exemplo, md, quando a tela for menor que o breakpoint, as colunas irão ocupar toda a largura do container, e ficaram empilhadas uma em cima da outra.

#### Colunas em uma linha
É possivel definir a quantidade de colunas em uma row(linha). Para isso basta adicionar a classe .row-cols-{quantidade} ao elemento que será a row. As quantidades que podem ser usadas são os numeros de 1 a 12.

Exemplo:
```html
<div class="container">
    <div class="row row-cols-1">
        <div class="col">
            <h1>Coluna 1</h1>
        </div>
        <div class="col">
            <h1>Coluna 2</h1>
        </div>
        <div class="col">
            <h1>Coluna 3</h1>
        </div>
    </div>
</div>
```
O seguinte exemplo terá apenas 1 coluna.

Vale lembrar que se uma coluna ocupar o expaço maior que o automatico, as outras colunas irão para a linha de baixo.

Exemplo:
```html
<div class="container">
    <div class="row row-cols-4">
        <div class="col borda">Column</div>
        <div class="col borda">Column</div>
        <div class="col-6 borda">Column</div>
        <div class="col borda">Column</div>
    </div>
</div>
```
No caso acima, em vez de 4 colunas, teremos apenas 3 colunas, pois a coluna 3 ocupa o espaço de 2 colunas.

Tambem é possivel deixar fazer de maneira responsiva. Para isso, basta adicionar a classe .row-cols-{breakpoint}-{quantidade} ao elemento que será a row.

#### Ordem
Para definir a ordem das colunas, basta adicionar a classe .order-{posição} ao elemento que será a coluna. Os tamanhos que podem ser usados são os numeros de 1 a 12.

ATENÇÃO: As colunas afetadas tem que obrigadoriamente possuir a classse .order-{posição}. Por exemplo, se você quiser que a coluna 3 fique na posição 1, você tem que adicionar a classe .order-1 na coluna 3 e a classe .order-2, ou outro maior numero, na coluna 1.

Exemplo:
```html
<div class="container">
    <div class="row">
        <div class="col-6 order-2">
            <h1>Coluna 1</h1>
        </div>
        <div class="col-3 order-3">
            <h1>Coluna 2</h1>
        </div>
        <div class="col-3 order-1">
            <h1>Coluna 3</h1>
        </div>
    </div>
</div>
```

#### Offset
Quando você ultiliza o offset, você está definindo quantas colunas a coluna irá se afastar da esquerda. Para definir o offset de uma coluna, basta adicionar a classe .offset-{size} ao elemento que será a coluna. Os tamanhos que podem ser usados são os numeros de 1 a 12.

Exemplo:
```html
<div class="container">
    <div class="row">
        <div class="col-6 offset-3">
            <h1>Coluna 1</h1>
        </div>
    </div>
</div>
```

Você tambem pode definir o offset que uma coluna terá em um determinado breakpoint. Para isso, basta adicionar a classe .offset-{breakpoint}-{size} ao elemento que será a coluna.

#### Alinhamentos

##### Vertical
Para alinhar as colunas verticalmente, basta adicionar a classe .align-items-{posição} ao elemento que será a row. As posições que podem ser usadas são:

- start: as colunaas começam no topo da row
- center: as colunas ficam no centro da row
- end: as colunas ficam no final da row

Exemplo:
```html
<div class="container">
    <div class="row align-items-center">
        <div class="col-6">
            <h1>Coluna 1</h1>
        </div>
        <div class="col-6">
            <h1>Coluna 2</h1>
        </div>
    </div>
</div>
```

Tambem é possivel alinhar cada coluna individualmente. Para isso, basta adicionar a classe .align-self-{posição} ao elemento que será a coluna.

Exemplo:
```html
<div class="row">
        <div class="col align-self-end">Área 1</div>
        <div class="col align-self-start">Área 2</div>
        <div class="col align-self-center">Área 3</div>
</div>
```

##### Horizontal
Para alinhar as colunas horizontalmente, basta adicionar a classe .justify-content-{posição} ao elemento que será a row. As posições que podem ser usadas são:

- start: as colunas começam a esquerda da row
- center: as colunas ficam no centro da row
- end: as colunas ficam a direita da row
- around: as colunas ficam distribuidas igualmente com espaços iguais entre elas
- between: as colunas ficam distribuidas igualmente com espaços maiores entre elas
- evenly: as colunas ficam distribuidas igualmente com espaços iguais entre elas

Exemplo:
```html
<div class="container">
    <div class="row justify-content-center">
        <div class="col-6">
            <h1>Coluna 1</h1>
        </div>
        <div class="col-6">
            <h1>Coluna 2</h1>
        </div>
    </div>
</div>
```