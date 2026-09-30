# 🌿 Portfólio Maomao — O Diário da Apotecária

Landing Page responsiva inspirada no universo de **O Diário da Apotecária**, desenvolvida como um projeto educacional para praticar HTML5 semântico e CSS3.

A página apresenta um portfólio fictício da personagem **Maomao**, destacando sua trajetória como apotecária, personagens relacionados à sua jornada, uma galeria temática e informações fictícias de contato.

---

## 🎯 Objetivo do projeto

O objetivo do projeto é desenvolver uma Landing Page simples, moderna e responsiva utilizando exclusivamente **HTML5 e CSS3**.

O projeto foi criado para praticar:

- Estruturação de páginas com HTML semântico;
- Organização de conteúdo em seções;
- Hierarquia de títulos;
- Uso de imagens com textos alternativos;
- Flexbox e CSS Grid;
- Responsividade para diferentes tamanhos de tela;
- Organização do CSS em arquivo externo;
- Criação de uma interface visual inspirada em um tema de anime.

---

## 🛠️ Tecnologias utilizadas

- **HTML5**
- **CSS3**
- **Google Fonts**
  - DM Serif Display
  - Poppins

Não foram utilizados:

- JavaScript;
- Frameworks;
- Bibliotecas JavaScript;
- CSS inline;
- Tag `<style>`.

---

## 📁 Estrutura dos arquivos

```text
portfolio-maomao/
│
├── index.html
├── style.css
│
└── README.dm
```

### `index.html`

Contém toda a estrutura e o conteúdo da Landing Page utilizando elementos semânticos do HTML5.

### `style.css`

Contém toda a estilização da página, incluindo:

- Cores;
- Tipografia;
- Espaçamentos;
- Grid;
- Flexbox;
- Efeitos de hover;
- Responsividade;
- Organização visual das seções.

---

## 🖥️ Seções da página

### Header

O cabeçalho apresenta:

- Nome **Maomao**;
- Menu de navegação;
- Links para as principais seções da página.

O menu utiliza links internos para navegar entre as seções.

---

### 🌸 Hero

A seção inicial apresenta:

- Nome da personagem;
- Identificação de *O Diário da Apotecária*;
- Breve apresentação;
- Botão de chamada para ação;
- Imagem relacionada à Maomao.

O botão direciona o usuário para a seção **Sobre**.

---

### 🌿 Sobre

A seção apresenta uma breve descrição de Maomao como apotecária.

O conteúdo aborda:

- Conhecimento sobre medicamentos;
- Ervas;
- Venenos;
- Investigação;
- Capacidade de observação.

Também possui uma imagem relacionada ao universo da apotecaria.

---

### 🏯 Experiência no Palácio

A seção apresenta três cards relacionados à jornada de Maomao:

1. **Apotecária**
2. **Investigadora**
3. **Vida no Palácio**

Cada card possui um título, numeração e uma breve descrição.

---

### 👥 Personagens parceiros

A página apresenta três cards de personagens relacionados à jornada de Maomao:

- **Jinshi**
- **Gyokuyou**
- **Gaoshun**

Cada card contém uma imagem, título e descrição.

---

### 🖼️ Galeria

A galeria apresenta imagens relacionadas ao universo visual da história, incluindo:

- Jardins;
- Palácio;
- Ervas;
- Medicamentos.

As imagens são organizadas utilizando **CSS Grid**, com diferentes tamanhos de cards.

---

### ✉️ Contato

A seção apresenta informações fictícias de contato:

- E-mail;
- LinkedIn;
- GitHub.

O endereço de e-mail utiliza um link `mailto:`.

Os links de LinkedIn e GitHub são apenas endereços fictícios representados por links.

---

### 🌱 Footer

O rodapé apresenta:

- Nome do projeto;
- Mensagem sobre o projeto educacional;
- Tecnologias utilizadas.

---

## 📱 Responsividade

O projeto foi desenvolvido para se adaptar a diferentes tamanhos de tela.

Foram utilizadas **Media Queries** para três situações principais:

### Desktop

A página utiliza:

- Layout em duas colunas no Hero;
- Cards organizados em três colunas;
- Galeria utilizando quatro colunas;
- Espaçamentos maiores.

### Tablet

O layout é adaptado para:

- Reduzir o número de colunas;
- Organizar o Hero verticalmente;
- Ajustar imagens;
- Permitir que o menu ocupe mais de uma linha.

### Celular

Em telas menores:

- O conteúdo passa para uma única coluna;
- Os cards são empilhados;
- A galeria passa para uma coluna;
- Os contatos ficam organizados verticalmente;
- O tamanho das fontes e imagens é reduzido;
- O menu pode ocupar mais de uma linha.

As adaptações são realizadas através de Media Queries no arquivo `style.css`.

---

## ♿ Acessibilidade

Foram utilizados alguns recursos básicos de acessibilidade:

- HTML5 semântico com elementos como:
  - `<header>`
  - `<nav>`
  - `<main>`
  - `<section>`
  - `<article>`
  - `<footer>`
  - `<figure>`
  - `<figcaption>`
  - `<address>`

- Atributo `lang="pt-BR"` no documento;
- Atributos `alt` nas imagens;
- Textos alternativos descritivos para contextualizar as imagens;
- Hierarquia de títulos utilizando `h1`, `h2` e `h3`;
- Atributo `aria-label` na navegação principal;
- `aria-label` nos links fictícios de LinkedIn e GitHub;
- Links de navegação interna para facilitar o acesso às seções.

---

## ▶️ Como executar o projeto

Não é necessário instalar nenhuma dependência ou executar um servidor.

### 1. Clone ou baixe o projeto

Baixe os arquivos do projeto para o computador.

### 2. Mantenha a estrutura de arquivos

Certifique-se de que o arquivo `index.html` e o arquivo `style.css` estejam no mesmo diretório.

Caso utilize imagens locais, mantenha também a pasta `assets`.

### 3. Abra o projeto

Abra o arquivo:

```text
index.html
```

diretamente em um navegador, como:

- Google Chrome;
- Microsoft Edge;
- Mozilla Firefox.

### 4. Visualize a página

A Landing Page será carregada no navegador e poderá ser testada em diferentes tamanhos de tela utilizando as ferramentas de desenvolvedor do navegador.

---

## 🎨 Características visuais

O projeto utiliza uma identidade visual inspirada em elementos tradicionais e naturais presentes no universo de *O Diário da Apotecária*.

A paleta utiliza principalmente:

- Verde escuro;
- Verde claro;
- Vinho;
- Creme;
- Branco;
- Dourado.

A combinação busca criar uma aparência delicada, elegante e organizada.

---

## 📌 Observações

Este é um **projeto educacional e fictício** inspirado em *O Diário da Apotecária*.

As informações de contato apresentadas na página são fictícias.

As imagens utilizadas no projeto devem respeitar as respectivas licenças e condições de uso de suas fontes. Para uma versão final do projeto, recomenda-se manter os créditos quando exigidos pelas licenças das imagens.

---

## 👩‍💻 Projeto

**Portfólio Maomao — O Diário da Apotecária**

Desenvolvido para praticar **HTML5 e CSS3**, com foco em estrutura semântica, organização visual e responsividade.