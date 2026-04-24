# Fundação de Foz do Iguaçu - PR

Site informativo sobre a história da fundação de Foz do Iguaçu, desenvolvido em grupo como projeto escolar. Cada integrante criou sua própria versão estilizada da página, aplicando individualmente os conceitos de HTML5 e CSS3 aprendidos em aula.

---

## Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [Conteúdo Histórico](#-conteúdo-histórico)
- [Páginas do Site](#-páginas-do-site)
- [Personalizações por Integrante](#-personalizações-por-integrante)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Conceitos de HTML e CSS Aplicados](#-conceitos-de-html-e-css-aplicados)
- [Como Visualizar](#-como-visualizar)
- [Integrantes](#-integrantes)

---

## Sobre o Projeto

Este é um projeto escolar em grupo desenvolvido pela turma **2ºBDS**, com o objetivo de apresentar a história da fundação do município de Foz do Iguaçu - PR. O site é composto por uma página principal e quatro versões individuais — uma para cada integrante —, cada uma com estilizações CSS próprias que demonstram o aprendizado individual de cada aluno.

---

## Conteúdo Histórico

A página apresenta a trajetória de Foz do Iguaçu desde seus primórdios até a criação oficial do município, cobrindo os seguintes marcos:

- **6.000 a.C.** — Vestígios da presença humana mais remota na região, identificados por pesquisas arqueológicas da UFPR na área do reservatório de Itaipu
- **1542** — Chegada do espanhol Álvar Nuñes Cabeza de Vaca ao rio Iguaçu, primeiro europeu a atingir as Cataratas
- **1881** — Chegada dos dois primeiros habitantes: o brasileiro Pedro Martins da Silva e o espanhol Manuel Gonzáles
- **1889** — Expedição do Tenente José Joaquim Firmino, que registrou 324 habitantes; fundação da Colônia Militar em 22 de novembro pelo Tenente Antonio Batista da Costa Júnior
- **1897** — Criação da Agência Fiscal; apenas 13 casas registradas na época
- **Início do século XX** — Crescimento para ~2.000 habitantes, com hospedaria, mercearias, quartel e estação telegráfica
- **1910** — A Colônia Militar passa à condição de Vila Iguassu, distrito de Guarapuava
- **1914** — Criação oficial do Município de Vila Iguaçu pela Lei 1383, em 14 de março; posse do primeiro prefeito, Jorge Schimmelpfeng, em 10 de junho
- **1918** — O município passa a se chamar oficialmente **Foz do Iguaçu**

O conteúdo é acompanhado por duas imagens comparativas da cidade: uma fotografia de **1983** (Foz antiga) e uma de **2023** (Foz atual), com créditos às fontes originais.

---

## Páginas do Site

O projeto é composto por **5 páginas HTML** interligadas por uma barra de navegação comum:

| Arquivo | Descrição |
|---|---|
| `index.html` | Página principal do grupo, sem estilização individual |
| `eduardo.html` | Versão do Eduardo — links com efeito hover de destaque |
| `guilherme.html` | Versão do Guilherme — tipografia diferenciada nos parágrafos |
| `maria.html` | Versão da Maria — rodapé com cores personalizadas |
| `vitor.html` | Versão do Vitor — efeito hover de destaque nos parágrafos |

Todas as páginas compartilham o mesmo conteúdo histórico, layout base, header com brasão e navegação, e rodapé — diferenciando-se apenas pelas contribuições CSS individuais.

---

## Personalizações por Integrante

Um dos aspectos mais interessantes do projeto é que cada aluno aplicou ao CSS uma personalização exclusiva em sua versão da página:

### Eduardo (`eduardo.html`) — Classe `.edu`
Os links de navegação ganham um efeito **hover interativo**: ao passar o mouse, o texto fica em maiúsculas (`uppercase`), negrito, aumenta para `30px` e muda para a cor azul-marinho (`navy`), com uma transição suave de **1 segundo**.

### Guilherme (`guilherme.html`) — Classe `.gui`
Os parágrafos do conteúdo histórico utilizam a fonte **Arial/Helvetica** (`font-family`), diferenciando a tipografia do restante do site.

### Maria (`maria.html`) — ID `#maria`
Os textos do rodapé (título "Página construída por:", nome e série/turma) recebem a **cor azul-marinho** (`navy`) via seletor de ID.

### Vitor (`vitor.html`) — Classe `.vitor`
Os parágrafos do texto histórico possuem um efeito **hover de destaque**: ao passar o mouse, o fundo fica roxo (`blueviolet`), o texto muda para branco e fica em negrito — criando uma experiência visual imersiva ao ler o conteúdo.

---

## Estrutura do Projeto

```
Fundacao-de-Foz-do-Iguacu/
│
├── index.html          # Página principal do grupo
├── eduardo.html        # Versão do Eduardo
├── guilherme.html      # Versão do Guilherme
├── maria.html          # Versão da Maria
├── vitor.html          # Versão do Vitor
├── style.css           # Folha de estilos compartilhada (com todas as classes individuais)
│
└── assets/
    └── images/
        ├── brasao.png       # Brasão de Foz do Iguaçu (favicon + header + footer)
        ├── foz-antiga.jpg   # Foto de Foz do Iguaçu em 1983
        └── foz-atual.jpg    # Foto de Foz do Iguaçu em 2023
```

---

## Tecnologias Utilizadas

| Tecnologia | Uso |
|---|---|
| **HTML5** | Estrutura semântica de todas as páginas |
| **CSS3** | Estilização do layout, cores, tipografia e efeitos hover |

Nenhuma dependência externa, framework ou biblioteca é utilizada. O projeto roda diretamente no navegador.

---

## Conceitos de HTML e CSS Aplicados

### HTML

| Tag / Atributo | Uso no Projeto |
|---|---|
| `<!DOCTYPE html>` | Declaração do padrão HTML5 |
| `<meta charset="UTF-8">` | Suporte a caracteres especiais e acentuação |
| `<link rel="shortcut icon">` | Brasão como favicon na aba do navegador |
| `<header>` | Cabeçalho com brasão e navegação |
| `<nav>` + `<ul>` + `<li>` | Menu de navegação entre as páginas |
| `<a href>` | Links de navegação interna e fontes externas |
| `<h1>`, `<h2>` | Hierarquia de títulos (conteúdo e rodapé) |
| `<p>` | Parágrafos do texto histórico |
| `<figure>` + `<figcaption>` | Imagens com crédito de fonte |
| `<img>` com `alt` e `title` | Imagens acessíveis com descrição alternativa |
| `<footer>` | Rodapé com nomes dos integrantes e turma |
| `<hr>` | Separadores visuais entre seções |
| `<div>` | Estrutura de layout para os parágrafos |

### CSS

| Recurso | Uso no Projeto |
|---|---|
| `background-color` | Cor de fundo do `body` (azul claro), `header` e `footer` (cinza escuro) |
| `text-align: center` | Centralização de títulos, imagens e textos do rodapé |
| `display: inline` | Links de navegação dispostos em linha horizontal |
| `border-radius` | Bordas arredondadas nas imagens da cidade |
| `margin` / `padding` | Espaçamentos e margens laterais dos parágrafos |
| `text-decoration: none` | Remoção do sublinhado dos links |
| `:hover` | Efeitos interativos individuais de cada integrante |
| `transition` | Animação suave no efeito hover do Eduardo |
| `font-family` | Tipografia personalizada no texto do Guilherme |
| `color` | Cor de texto personalizada no rodapé da Maria |
| `class` / `id` | Seletores para aplicar estilos individuais por integrante |

---

## Como Visualizar

Por ser um projeto estático em HTML/CSS puro, não requer instalação.

**Opção 1 — Abrir diretamente no navegador:**

1. Clone ou baixe o repositório:
   ```bash
   git clone https://github.com/seu-usuario/Fundacao-de-Foz-do-Iguacu.git
   ```
2. Abra o arquivo `index.html` no seu navegador.
3. Use os links do menu no topo para navegar entre as versões de cada integrante.

**Opção 2 — Live Server (recomendado para desenvolvimento):**

1. Instale a extensão [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) no VS Code.
2. Clique com o botão direito em `index.html` → **"Open with Live Server"**.

> **Atenção:** Mantenha a pasta `assets/` no mesmo diretório dos arquivos HTML para que as imagens e o favicon carreguem corretamente.

---

## Integrantes

Projeto desenvolvido pelos alunos da turma **2ºBDS**:

| Aluno | Página Individual |
|---|---|
| Eduardo Florenciano dos Santos | `eduardo.html` |
| Guilherme Henrique de Almeida | `guilherme.html` |
| Maria Victoria Portillo Villalba | `maria.html` |
| Vitor Alves Kossmann | `vitor.html` |
