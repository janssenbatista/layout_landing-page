# 🎧 BOSE Landing Page

Uma landing page moderna e responsiva para produtos BOSE, desenvolvida com HTML5, SCSS e JavaScript. Este projeto apresenta uma interface elegante e interativa para exibir produtos de áudio premium da marca BOSE.

![BOSE Landing Page](https://img.shields.io/badge/BOSE-Landing%20Page-000000?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 🌐 Demo ao Vivo

Acesse a aplicação em funcionamento: [DEMO LINK](https://janssenbatista.github.io/layout_landing-page/)

## 🎨 Design

O design desta landing page foi baseado no protótipo disponível no Figma:

- [Protótipo no Figma](https://www.figma.com/design/DtkQmQ797hk0nI4KfMi2Uq/BOSE-New-Version?node-id=6703-88&p=f&t=illaoycFT45C9bqw-0)

## ✨ Funcionalidades

- ✅ **Design Responsivo**: Totalmente adaptável para desktop, tablet e mobile
- ✅ **Menu Hamburger**: Menu lateral interativo para navegação em dispositivos móveis
- ✅ **Seções Organizadas**:
  - Header com título impactante e ondas sonoras
  - Produtos Recomendados
  - Categorias de produtos
  - Como Comprar (How to Buy)
  - Formulário de Contato
  - Footer com informações da marca
- ✅ **Otimização de Imagens**: Uso de `srcset` para carregamento otimizado em diferentes resoluções
- ✅ **Smooth Scroll**: Navegação suave entre seções
- ✅ **Animações CSS**: Transições e efeitos visuais elegantes

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica e acessível
- **SCSS/Sass**: Pré-processador CSS para estilização modular
- **JavaScript**: Interatividade e funcionalidades dinâmicas
- **Parcel**: Bundler para build e desenvolvimento
- **Cypress**: Framework de testes E2E
- **ESLint**: Linter para garantir qualidade do código JavaScript
- **Stylelint**: Linter para garantir qualidade do código SCSS
- **Prettier**: Formatação automática de código

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter instalado em sua máquina:

- [Node.js](https://nodejs.org/) (versão 14 ou superior)
- [npm](https://www.npmjs.com/) (normalmente vem com o Node.js)
- [Git](https://git-scm.com/)

## 🚀 Como Executar o Projeto

### 1. Clone o repositório

```bash
git clone https://github.com/janssenbatista/layout_landing-page.git
cd layout_landing-page
```

### 2. Instale as dependências

```bash
npm install
```

### 3. Inicie o servidor de desenvolvimento

```bash
npm start
```

A aplicação será aberta automaticamente no seu navegador padrão em `http://localhost:1234`

## 📜 Scripts Disponíveis

| Script                 | Descrição                                         |
| ---------------------- | ------------------------------------------------- |
| `npm start`            | Inicia o servidor de desenvolvimento              |
| `npm run build`        | Cria a versão de produção otimizada               |
| `npm test`             | Executa os linters e testes                       |
| `npm run lint`         | Executa os linters (ESLint, Stylelint e Prettier) |
| `npm run format`       | Formata o código com Prettier                     |
| `npm run style-format` | Formata e corrige arquivos SCSS com Stylelint     |
| `npm run deploy`       | Faz o deploy da aplicação no GitHub Pages         |

## 📁 Estrutura do Projeto

```
layout_landing-page/
├── src/
│   ├── index.html              # Arquivo HTML principal
│   ├── styles/
│   │   ├── main.scss           # Arquivo SCSS principal
│   │   └── blocks/            # Componentes SCSS modulares
│   │       ├── _categories.scss
│   │       ├── _contacts.scss
│   │       ├── _footer.scss
│   │       ├── _header.scss
│   │       ├── _how-to-buy.scss
│   │       ├── _icon.scss
│   │       ├── _menu.scss
│   │       ├── _recommended.scss
│   │       ├── _title.scss
│   │       ├── _top-bar.scss
│   │       └── _variables.scss
│   ├── scripts/
│   │   └── main.js            # JavaScript principal
│   └── images/                # Recursos de imagem
│       └── categories/        # Imagens das categorias
├── cypress/                   # Testes E2E
│   └── integration/
│       └── page.spec.js
├── package.json               # Dependências e scripts
├── cypress.config.js          # Configuração do Cypress
└── README.md                  # Este arquivo
```

## 🎯 Seções da Landing Page

1. **Header**: Apresentação principal com título impactante e logotipo BOSE
2. **Menu**: Menu lateral responsivo com links de navegação
3. **Recommended**: Showcase de produtos recomendados
4. **Categories**: Diferentes categorias de produtos BOSE
5. **How to Buy**: Instruções passo a passo para realizar compras
6. **Contacts**: Formulário de contato para comunicação com clientes
7. **Footer**: Informações adicionais e links úteis

## 🧪 Testes

Para executar os testes:

```bash
# Executar todos os testes (lint + E2E)
npm test

# Apenas testes E2E
npm run test:only
```

## 📦 Build para Produção

Para criar uma versão otimizada para produção:

```bash
npm run build
```

Os arquivos otimizados serão gerados na pasta `dist/`

## 🚀 Deploy

Para fazer deploy no GitHub Pages:

```bash
npm run deploy
```

## 📝 Checklist de Desenvolvimento

Consulte o arquivo [checklist.md](./checklist.md) para verificar todos os requisitos do projeto.

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer um fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona MinhaFeature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abrir um Pull Request

## 📄 Licença

Este projeto está sob a licença GPL-3.0. Veja o arquivo [LICENSE](./LICENSE) para mais detalhes.

## 👤 Autor

**Janssen Batista**

- GitHub: [@janssenbatista](https://github.com/janssenbatista)
- LinkedIn: [Janssen Batista](https://www.linkedin.com/in/janssenbatista)

## 🙏 Agradecimentos

- [Mate Academy](https://mate.academy/) - Plataforma de ensino
- [BOSE](https://www.bose.com/) - Inspiração de design e marca
- Figma Design System - Protótipo base

---

⭐ Se este projeto foi útil para você, considere dar uma estrela no repositório!
