# 📚 Enciclopédia livre: recriação da Wikipédia com layout moderno

Projeto desenvolvido como **Desafio de Projeto** do módulo de HTML e CSS da trilha Front-End da [DIO](https://www.dio.me/).

O objetivo é treinar a **estrutura de um site**, aplicando conhecimentos de **semântica** e **acessibilidade** ao recriar uma página no estilo da Wikipédia, com um visual mais moderno.

## 🔗 Demonstração

https://destroyerig.github.io/WikipediaModerno-DesafioDio/

## ✨ Funcionalidades e layout

- Layout em **três colunas** no desktop: índice fixo, artigo e infobox (resumo)
- **Responsivo**: no celular e no tablet vira uma coluna só
- **Modo escuro automático**, conforme a preferência do sistema
- Atalho de teclado: a tecla <kbd>/</kbd> leva o foco para o campo de busca
- Rolagem suave entre as seções, respeitando a preferência de reduzir animações

## 🧱 Semântica

- Estrutura da página com `header`, `nav`, `main`, `article`, `section`, `aside` e `footer`
- Conteúdo com `figure` e `figcaption`, `blockquote` com `cite`, `time`, `abbr`, `kbd`, `code` e `details` com `summary`
- Tabelas com `caption`, `thead`, `tbody` e `scope`
- Um único `h1` e títulos em ordem hierárquica

## ♿ Acessibilidade

- Link "Ir para o conteúdo" para navegação pelo teclado
- Campo de busca com `label` e `role="search"`
- `aria-label` em cada `nav` e `aria-current` na página atual do menu
- SVG com `title` e `desc` para leitores de tela
- Foco visível em todos os elementos interativos e contraste de cores adequado

## 📁 Estrutura do projeto

```
.
├── index.html
├── style.css
└── README.md
```

## 🚀 Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/DestroyerIG/WikipediaModerno-DesafioDio.git
   ```
2. Entre na pasta:
   ```bash
   cd WikipediaModerno-DesafioDio
   ```
3. Abra o arquivo `index.html` no navegador.

Não é necessário instalar nada.

## 🛠️ Tecnologias

- HTML5
- CSS3 (Grid, Flexbox, variáveis CSS e media queries)
- JavaScript (apenas o atalho de busca)

## 👤 Autor

**Itallo Gabriel**

- GitHub: [@DestroyerIG](https://github.com/DestroyerIG)
- LinkedIn: [itallogoncalves](https://www.linkedin.com/in/itallogoncalves/)

## 📝 Licença

Projeto desenvolvido para fins educacionais. O texto do artigo é apenas um exemplo.