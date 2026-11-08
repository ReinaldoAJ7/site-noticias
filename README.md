# Site Notícias

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
[![Status](https://img.shields.io/badge/Status-Front-end%20est%C3%A1tico-success)](https://github.com/ReinaldoAJ7/site-noticias)
[![Linguagem](https://img.shields.io/badge/Linguagem-PT--BR-blue)](https://github.com/ReinaldoAJ7/site-noticias)

Projeto de portal de notícias em HTML e CSS, com layout jornalístico, navegação por categorias e destaque visual para destaques, entrevistas, fotos e conteúdo em colunas.

## Índice

- [Sobre o projeto](#sobre-o-projeto)
- [Funcionalidades](#funcionalidades)
- [Tecnologias utilizadas](#tecnologias-utilizadas)
- [Estrutura do projeto](#estrutura-do-projeto)
- [Como executar](#como-executar)
- [Como visualizar o site](#como-visualizar-o-site)
- [Estrutura das páginas](#estrutura-das-páginas)
- [Personalização e manutenção](#personalizacao-e-manutencao)
- [Roadmap](#roadmap)
- [Contribuição](#contribuicao)
- [Licença](#licenca)

## Sobre o projeto

O `site-noticias` é um site institucional de notícias construído com HTML5 e CSS3, inspirado em layouts clássicos de portais jornalísticos. A ideia principal é simular uma página de notícias com:

- cabeçalho com menu de navegação;
- destaque de notícias em diferentes colunas;
- blocos de entrevistas;
- área lateral com notícias recentes;
- formulário de cadastro por e-mail;
- galeria de fotos;
- visual clean e de página de jornal.

Esse tipo de projeto é ideal para praticar:

- estruturação em HTML;
- layout com CSS;
- organização visual de páginas estáticas;
- uso de imagens e seções de conteúdo informativo;
- construção de um front-end sem dependências externas.

## Funcionalidades

- Página inicial com layout em três colunas;
- Menu de navegação principal com categorias de notícias;
- Área de destaques com blocos de conteúdo visual;
- Seção de entrevistas com lista de nomes e links;
- Painel lateral para notícias recentes;
- Formulário de cadastro para newsletter;
- Página dedicada para fotos (`fotos.html`);
- Página de notícias (`noticiasBrasil.html`);
- Design responsivo em foco para telas desktop, com possibilidade de adaptação futura para mobile;
- Uso de imagens locais no diretório `img/`.

## Tecnologias utilizadas

| Tecnologia | Descrição |
| --- | --- |
| HTML5 | Estrutura e semântica das páginas |
| CSS3 | Estilização, layout, cores, fontes, margens e responsividade |
| JavaScript | Não utilizado neste projeto em sua versão atual |
| GitHub Pages / servidor local | Possibilidade de visualização simples via navegador |

### Principais recursos do front-end

- uso de classes e IDs para organização do layout;
- blocos `div` para composição de colunas e seções;
- imagens locais para compor o visual editorial;
- estilos de cards, listas e destaque de conteúdo;
- menu em lista horizontal.

## Estrutura do projeto

```text
site-noticias/
├── css/
│   └── estilo.css
├── img/
│   ├── cidade.jpg
│   ├── doctor.jpg
│   ├── planeta.png
│   ├── taxi.jpg
│   ├── tecnologia.jpg
│   └── ...
├── fotos.html
├── index.html
├── noticiasBrasil.html
├── README.md
└── ...
```

### Descrição dos arquivos principais

- `index.html` — página principal e home do portal.
- `noticiasBrasil.html` — página de notícias do Brasil.
- `fotos.html` — galeria de imagens do site.
- `css/estilo.css` — arquivo central de estilos.
- `img/` — imagens utilizadas para banners, destaques e conteúdo editorial.

## Como executar

Como o projeto é estático, não há necessidade de instalar dependências ou configurar ambiente complexo.

### Opção 1: abrir diretamente no navegador

1. Clone o repositório:

```bash
git clone https://github.com/ReinaldoAJ7/site-noticias.git
```

2. Entre na pasta do projeto:

```bash
cd site-noticias
```

3. Abra o arquivo `index.html` no navegador.

### Opção 2: servir localmente com Python

Caso prefira visualizar em um servidor local:

```bash
cd site-noticias
python -m http.server 8000
```

Em seguida, acesse:

```text
http://localhost:8000
```

## Como visualizar o site

Depois de abrir a página inicial, você poderá navegar pelos elementos principais, como:

- menu principal;
- notícias em destaque;
- seção lateral com conteúdos recentes;
- formulário de cadastro;
- notícias por categoria;
- galeria de fotos.

Se o projeto estiver sendo usado em ambiente local, o fluxo mais simples é:

```text
index.html -> página inicial
noticiasBrasil.html -> notícias
fotos.html -> galeria visual
```

## Estrutura das páginas

### Página inicial (`index.html`)

A home apresenta um layout jornalístico com três áreas principais:

- `#topo` — cabeçalho e menu de navegação;
- `#conteudo` — área central com colunas de conteúdo;
- `#primario` — blocos de entrevistas e newsletter;
- `#secundario` — destaques e matérias em lista;
- `#lateral` — últimas notícias, entrevistas e novidades;
- rodapé com informações de copyright.

### Página de notícias (`noticiasBrasil.html`)

Essa página complementa o portal com foco em notícias do Brasil, mantendo o mesmo padrão visual do projeto. A ideia é manter identidade visual consistente entre as páginas.

### Página de fotos (`fotos.html`)

A página de fotos oferece suporte visual para a publicação de imagens do portal, reforçando a identidade do projeto editorial.

## Personalização e manutenção

Para adaptar o projeto às suas necessidades, você pode:

- trocar textos e manchetes;
- alterar imagens da pasta `img/`;
- ajustar o esquema de cores no `css/estilo.css`;
- incluir novas páginas com o mesmo padrão visual;
- modificar links de navegação no topo;
- inserir novos blocos de destaque.

### Exemplo de customização

Se quiser mudar o título do site, edite a tag `<title>` dentro do `head`:

```html
<title>Planeta Diário - Comprometido com a verdade</title>
```

Para alterar a cor principal do layout, edite o CSS:

```css
body {
  background: #f4f4f4;
  color: #333;
}
```

## Roadmap

Algumas melhorias que podem ser feitas no futuro:

- [ ] tornar o layout responsivo para mobile;
- [ ] criar páginas adicionais para categorias como esportes, tecnologia e economia;
- [ ] adicionar menu dropdown e efeitos interativos;
- [ ] incluir JavaScript para filtros, carrossel e newsletter;
- [ ] melhorar acessibilidade com contraste, semântica e aria-labels;
- [ ] criar uma versão com imagens mais modernas e layout premium.

## Contribuição

Contribuições são bem-vindas.

### Fluxo sugerido

1. Faça um fork do projeto;
2. Crie uma branch para sua feature:

```bash
git checkout -b feature/nova-funcionalidade
```

3. Faça as alterações;
4. Faça commit:

```bash
git commit -m "Adiciona nova funcionalidade"
```

5. Envie para o repositório:

```bash
git push origin feature/nova-funcionalidade
```

6. Abra um pull request.

## Licença

Este projeto não possui uma licença definida no repositório até o momento. Caso queira, você pode adicionar uma licença no GitHub para formalizar uso, distribuição e modificação.

### Sugestões de licença

- `MIT` — simples e amplamente utilizada para projetos open source;
- `GPL` — mais restritiva e orientada a software livre;
- `Apache 2.0` — boa para projetos com foco em código aberto e proteção legal.

## Resumo

O projeto `site-noticias` é um exemplo prático de front-end estático em HTML/CSS com foco em portal de notícias. Ele demonstra como construir uma interface jornalística com colunas, destaques, fotos, listas e blocos de conteúdo visual, além de ser uma excelente base para estudo, evolução e customização.

Se quiser, também posso criar uma versão mais sofisticada deste README com:

- badges de tecnologia mais chamativos;
- seção de screenshots;
- tabela de página por página;
- instruções de deploy no GitHub Pages;
- versão em inglês ou em formato de documentação profissional.

---

Desenvolvido para apresentação e estudo de layout web em HTML/CSS.
