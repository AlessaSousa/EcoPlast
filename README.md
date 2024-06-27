# Projex Teste
# ECOPLAST - Economia Circular dos Plásticos

## Descrição
O Projeto ECOPLAST tem como objetivo promover a conscientização sobre a economia circular dos plásticos.

## Estrutura em HTML
O projeto é composto por várias seções como:

- **Barra de navegação**: Contém a logo e links de navegação, também possui um botão para caso o usuário deseja ser voluntário do projeto.

- **Imagem de Destaque**: Uma imagem ilustrativa sobre a economia circular

- **Seção de informação**: Explica os princípios da economia circular em geral.

- **Seção de cartões informativos**: Apresenta alguns conceitos de como a economia circular dos plásticos funciona.

- **Depoimentos de voluntários**: Mostra as experiências de diferentes voluntários e seus pontos de vista a cerca do trabalho voluntário.

- **Rodapé**: inclui a logo e ícones de redes sociais.

## CSS
Algumas propriedades feitas em css:

- **Tipografia e Reset**: Utiliza a fonte 'Abel' e aplica reset básico para margens e paddings.

- **Barra de Navegação**: Estilizada com um fundo verde escuro, textos brancos e um layout flexível.

- **Botões**: Botões estilizados com bordas arredondadas e cores personalizadas.

- **Cartões Flipáveis**: Cartões interativos que giram ao passar o mouse, mostrando mais informações no verso.

- **Depoimentos**: Cartões com imagens e descrições dos voluntários, estilizados com margens e paddings apropriados.

- **Rodapé**: Inclui logo e ícones de redes sociais, estilizados para manter um layout consistente.

## Estrutura de pastas
ECOPLAST/
│
├── src/
│ ├── app/
│ │ ├── components/
│ │ │ ├── top-bar/
│ │ │ ├── main-image/
│ │ │ ├── principles/
│ │ │ ├── info-cards/
│ │ │ ├── testimonials/
│ │ │ └── footer/
│ │ ├── services/
│ │ ├── models/
│ │ ├── app.component.html
│ │ ├── app.component.css
│ │ └── app.component.ts
│ ├── assets/
│ ├── environments/
│ ├── index.html
│ └── styles.css
├── angular.json
├── package.json
└── README.md

## Para fazer com que o projeto rode você precisará de alguns requisitos

1. Clone o repositório do github:
    ```sh
     git clone https://github.com/AlessaSousa/EcoPlast.git
    cd ecoplast
    ```
2. instale as dependências:
    ```sh
    npm install
    ```
3. Inicie o servidor local
    ```sh
    ng serve
    ```
    Abra seu navegador e acesse 'http://localhost:4200'.
