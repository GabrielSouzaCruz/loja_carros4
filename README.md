# 🚗 Projeto Loja de Carros 4

Este é um projeto de front-end que simula a página inicial de uma loja de veículos ("AutoMóveis"). O layout foi desenvolvido como um exercício prático de HTML semântico e estilização avançada com CSS.

O objetivo principal era replicar um design específico (visto na `image_ff1ae9.png`), focando no uso de **CSS Grid Layout** para o cabeçalho, menu e o container principal dos carros.

## 🛠️ Tecnologias Utilizadas

  * **HTML5:** Para a estrutura semântica da página.
  * **CSS3:** Para estilização, utilizando:
      * **CSS Grid Layout:** Usado para estruturar o cabeçalho (`.main-header`), o grupo de logo/título (`.logo-title`), o menu de navegação (`.main-nav`) e o container dos anúncios (`.container-carros`).
      * **Flexbox:** Usado dentro de cada card (`.carro-item`) para alinhar a imagem e as informações do veículo.
      * **Media Queries:** Para garantir que o layout seja responsivo e se adapte a telas menores (como celulares).

## 🌟 Principais Seções

1.  **Cabeçalho (`<header>`):**

      * Exibe o logo da marca (Bentley), o título "AutoMóveis" e um menu de navegação.
      * Utiliza `display: grid` para posicionar o grupo logo/título à esquerda e o menu à direita.

2.  **Container de Carros (`.container-carros`):**

      * Uma galeria em grade (`display: grid`) que exibe os veículos à venda.
      * A grade se ajusta automaticamente (`repeat(auto-fit, ...)`), criando novas linhas conforme necessário.

3.  **Cards de Veículos (`.carro-item`):**

      * Cada card combina uma imagem (como `carro-strada.png` ou `carro-gol.png`) com suas informações (modelo, preço, detalhes).
      * Um botão "Fazer proposta" completa o card.

## 📂 Estrutura de Arquivos

```
loja-carros-4/
│
├── image/
│   ├── bentley-logo.png
│   ├── carro-gol.png
│   ├── carro-palio.png
│   └── carro-strada.png
│
├── index.html
└── style.css
```

## 🚀 Como Executar

1.  Clone este repositório (ou baixe os arquivos).
2.  Abra o arquivo `index.html` em qualquer navegador web.
