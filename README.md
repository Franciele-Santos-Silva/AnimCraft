# AnimCraft

## Sobre o Projeto

O **AnimCraft** é um carrossel animado de produtos (refrigerantes) desenvolvido com **HTML, CSS e JavaScript puro**.  
O projeto apresenta transições suaves entre sabores (morango, abacate e laranja), com foco em **design interativo e animações**.

## Funcionalidades

✅ Alternar entre slides com **botões de navegação** (→ e ←)  
✅ Animações suaves na transição de elementos (`@keyframes`)  
✅ Uso de **variáveis CSS dinâmicas** (`--background`)  
✅ Estrutura responsiva e leve  

## Tecnologias Utilizadas

| Tecnologia | Descrição |
|-------------|------------|
| **HTML5** | Estrutura base da aplicação |
| **CSS3** | Estilização e animações |
| **JavaScript (ES6)** | Lógica do carrossel e eventos dos botões |

## Estrutura do Projeto

    ```
AnimCraft/
│
├── index.html       # Estrutura principal da página
├── style.css        # Estilos e animações do carrossel
├── js/
│   └── script.js    # Lógica de troca de slides
└── img/
    ├── Morango-refrigerante.png
    ├── Abacate-refrigerante.png
    └── Laranja-refrigerante.png
    ```

## Como Executar o Projeto

1️. Clone o repositório:

    ```bash
     git clone [URL-do-seu-repositório]
    ```

2️. Acesse a pasta do projeto:

    ```bash
    cd AnimCraft
    ```

3️. Abra o arquivo principal no navegador:

    ```bash
    index.html
    ```

Ou clique duas vezes sobre ele para abrir direto.

## Funcionamento

- O **JavaScript** controla a visibilidade dos elementos com a classe `.active`.
- O **CSS** aplica transições suaves e animações usando `@keyframes`.
- A cada clique nos botões **“>”** ou **“<”**, a imagem e o título ativo são trocados dinamicamente.

## Exemplo de Uso

| Fruta | Cor de Fundo | Efeito |
|--------|---------------|--------|
| Morango | Vermelho (#EA3D41) | Entrada suave com fade |
| Abacate | Verde (#2D5643) | Transição lateral |
| Laranja | Laranja (#E7A043) | Troca suave com efeito vertical |

Projeto desenvolvido para fins de aprendizado e prática de **animações front-end** e **interatividade com JavaScript puro**.  
