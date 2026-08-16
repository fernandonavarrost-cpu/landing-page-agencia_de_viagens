# Travel&U

Site estático da agência de turismo **Travel&U**, criado para promover pacotes de viagem para a **Noruega** e inspirar os visitantes a conhecer o país.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## Funcionalidades

- Página única com navegação âncora entre seções
- Seção hero com chamada para ação e botão "Ver pacotes"
- Seção "Conheça a Noruega" com destaques sobre paisagens e cultura do país
- Quatro pacotes de viagem (A, B, C e D) com preço e botão "Reservar" que pré-seleciona o pacote no formulário
- Formulário de contato com validação nativa, campo de data de viagem e mensagem de sucesso
- Menu hambúrguer responsivo para dispositivos móveis (JavaScript vanilla)
- Acessibilidade: link "pular para o conteúdo", foco visível e suporte a `prefers-reduced-motion`
- Design responsivo e paleta inspirada na bandeira da Noruega

## Tecnologias

- **HTML5** — estrutura semântica e acessível
- **CSS3** — estilização, layout responsivo e variáveis de tema
- **JavaScript** — menu mobile, validação do formulário e pré-seleção de pacote

## Estrutura do projeto

```
Página da copa/
├── index.html      # Página principal
├── style.css       # Estilos do site
├── img/            # Imagens locais (fiordes, vilas e pacotes)
└── README.md
```

## Site publicado

Disponível em: <https://fernandonavarrost-cpu.github.io/landing-page-agencia_de_viagens/>

O deploy é feito automaticamente via GitHub Actions a cada push na branch `main`.

## Como executar

O projeto é um site estático, sem dependências ou build. Basta abrir o `index.html` no navegador:

1. Baixe ou clone o repositório
2. Dê um duplo clique em `index.html` (ou abra-o pelo navegador)

## Personalização

- **Cores**: edite as variáveis em `:root` no arquivo `style.css` (vermelho `#C8102E` e azul `#00205B`, baseados na bandeira da Noruega)
- **Textos e pacotes**: altere o conteúdo (descrições, preços) diretamente em `index.html`
- **Imagens**: substitua os arquivos da pasta `img/` mantendo os nomes (ou atualize os caminhos no HTML)

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

Copyright (c) 2026 Fernando Navarro.