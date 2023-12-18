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